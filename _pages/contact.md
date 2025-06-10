---
layout: single
title: Contact
permalink: /contact/
---

<style>
.contact-container {
  max-width: 500px;
  margin: 2rem auto;
  background: #ffffffcc;
  border-radius: 18px;
  box-shadow: 0 6px 32px rgba(0,0,0,0.12);
  padding: 2.5rem 2rem 2rem 2rem;
  font-family: 'Segoe UI', 'Roboto', 'Arial', sans-serif;
}
.contact-container h1 {
  text-align: center;
  margin-bottom: 1.5rem;
  font-weight: 600;
  color: #22223b;
}
.contact-form label {
  display: block;
  margin-bottom: 0.3rem;
  color: #4a4e69;
  font-weight: 500;
}
.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 0.7rem;
  margin-bottom: 1.2rem;
  border: 1px solid #a0aec0;
  border-radius: 8px;
  background: #f7f7fa;
  font-size: 1rem;
  transition: border-color 0.2s;
}
.contact-form input:focus,
.contact-form textarea:focus {
  border-color: #5e60ce;
  outline: none;
}
.contact-form button {
  width: 100%;
  background: linear-gradient(90deg,#5e60ce 0%, #4361ee 100%);
  color: #fff;
  border: none;
  padding: 0.85rem 0;
  border-radius: 8px;
  font-size: 1.1rem;
  font-weight: 600;
  cursor: pointer;
  transition: background 0.2s;
}
.contact-form button:hover {
  background: linear-gradient(90deg,#4361ee 0%, #5e60ce 100%);
}
.social-links {
  text-align: center;
  margin-top: 2rem;
}
.social-links a {
  display: inline-block;
  margin: 0 1.2rem;
  color: #4361ee;
  font-size: 1.8rem;
  transition: color 0.2s;
  text-decoration: none;
}
.social-links a:hover {
  color: #22223b;
}
@media (max-width: 600px) {
  .contact-container { padding: 1.2rem 0.5rem 1.5rem 0.5rem; }
}
</style>

<div class="contact-container">
  <h1>Contact Me</h1>
  <form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <button type="submit">Send Message</button>
  </form>

  <div style="text-align:center; margin-top:1.2rem;">
    <span style="color:#555; font-size:0.95rem;">
      Or email me directly at
      <a href="mailto:your@email.com" style="color:#5e60ce; text-decoration:underline;">your@email.com</a>
    </span>
  </div>

  <div class="social-links">
    <a href="https://www.linkedin.com/in/your-linkedin/" title="LinkedIn" target="_blank" rel="noopener">
      <svg width="1.5em" height="1.5em" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:middle;">
        <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.761 0 5-2.239 5-5v-14c0-2.761-2.239-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.268c-.966 0-1.75-.783-1.75-1.75s.784-1.75 1.75-1.75 1.75.784 1.75 1.75-.784 1.75-1.75 1.75zm13.5 11.268h-3v-5.604c0-1.337-.025-3.061-1.867-3.061-1.868 0-2.154 1.459-2.154 2.968v5.697h-3v-10h2.881v1.367h.041c.401-.762 1.381-1.566 2.841-1.566 3.039 0 3.6 2.001 3.6 4.601v5.598z"/>
      </svg>
    </a>
    <a href="https://github.com/your-github" title="GitHub" target="_blank" rel="noopener">
      <svg width="1.5em" height="1.5em" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:middle;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577v-2.234c-3.338.724-4.033-1.415-4.033-1.415-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.084-.729.084-.729 1.205.084 1.84 1.236 1.84 1.236 1.07 1.834 2.809 1.304 3.495.997.108-.775.418-1.305.762-1.605-2.665-.306-5.466-1.334-5.466-5.931 0-1.311.469-2.382 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23a11.48 11.48 0 013.003-.404c1.018.005 2.045.138 3.003.404 2.291-1.553 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.839 1.235 1.91 1.235 3.221 0 4.609-2.803 5.624-5.475 5.921.43.372.823 1.102.823 2.222v3.293c0 .322.218.694.825.576C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
    </a>
  </div>
</div>
