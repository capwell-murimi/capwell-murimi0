---
layout: home
permalink: /blog/
title: Blog
author_profile: true
---

<style>
.hashnode-blogs {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2em;
  margin: 2em 0;
}
.hashnode-blog-card {
  background: #181818;
  color: #f2f2f2;
  border-radius: 18px;
  box-shadow: 0 2px 12px #222;
  padding: 1.5em 1.4em 1.4em 1.4em;
  transition: transform 0.25s cubic-bezier(.4,2,.6,.8), box-shadow 0.25s;
  display: flex;
  flex-direction: column;
}
.hashnode-blog-card:hover {
  transform: scale(1.045) rotate(-1deg);
  box-shadow: 0 8px 28px #0af6ff44;
}
.hashnode-blog-title {
  font-size: 1.25em;
  font-weight: bold;
  color: #36a7ff;
  margin-bottom: 0.45em;
  text-decoration: none;
}
.hashnode-blog-desc {
  color: #e0e0e0;
  margin-bottom: 1em;
}
.hashnode-blog-date {
  font-size: 0.95em;
  color: #b0e0ff;
  margin-bottom: 0.7em;
}
</style>

# My Hashnode Blogs

<div id="hashnode-blogs" class="hashnode-blogs">
  <p>Loading latest posts…</p>
</div>

<script>
const HASHNODE_USERNAME = "capwell"; // Replace with your username if needed

async function fetchHashnodeBlogs(username) {
  // GraphQL query for Hashnode v2 API
  const query = `
    query {
      publication(host: "${username}.hashnode.dev") {
        posts(first: 12) {
          edges {
            node {
              title
              brief
              slug
              publishedAt
              coverImage {
                url
              }
            }
          }
        }
      }
    }
  `;
  const res = await fetch("https://gql.hashnode.com/", {
    method: "POST",
    headers: { "Content-Type": "application/json" },
    body: JSON.stringify({ query })
  });
  const data = await res.json();
  return data.data.publication.posts.edges.map(e => e.node);
}

function renderHashnodeBlogs(posts) {
  const container = document.getElementById("hashnode-blogs");
  if (!posts.length) {
    container.innerHTML = "<p>No blog posts found.</p>";
    return;
  }
  container.innerHTML = posts.map(post => `
    <div class="hashnode-blog-card">
      ${post.coverImage && post.coverImage.url ? `<img src="${post.coverImage.url}" style="width:100%;border-radius:12px 12px 0 0;margin-bottom:1em;object-fit:cover;max-height:160px;">` : ""}
      <a href="https://${HASHNODE_USERNAME}.hashnode.dev/${post.slug}" class="hashnode-blog-title" target="_blank">${post.title}</a>
      <div class="hashnode-blog-date">${new Date(post.publishedAt).toLocaleDateString()}</div>
      <div class="hashnode-blog-desc">${post.brief}</div>
    </div>
  `).join("");
}

fetchHashnodeBlogs(HASHNODE_USERNAME)
  .then(renderHashnodeBlogs)
  .catch(() => {
    document.getElementById("hashnode-blogs").innerHTML = "<p>Failed to load posts.</p>";
  });
</script>
