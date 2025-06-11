---
layout: single
title: Contact
permalink: /contact/
---

<link rel="stylesheet" href="/assets/style.css">  box-shadow: 0 2px 12px rgba(80,80,125,0.18);
  transition: background 0.16s;
  margin-top: 0.3em;
}
.contact-form-black button:hover {
  background: linear-gradient(90deg,var(--primary-dark) 0%,var(--primary) 100%);
}

.direct-email {
  text-align: center;
  margin-top: 1.6em;
  font-size: 1em;
  color: var(--text-muted);
}
.direct-email a {
  color: var(--primary);
  text-decoration: underline;
  word-break: break-all;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 2.3em;
  margin-top: 2.3em;
}
.social-links a {
  color: var(--primary);
  text-decoration: none;
  font-size: 2em;
  transition: color 0.2s;
}
.social-links a:hover {
  color: var(--primary-dark);
}

@media (max-width: 600px) {
  .contact-form-black {
    padding: 1.1em 0.5em 1.5em 0.5em;
  }
  .social-links {
    gap: 1.2em;
  }
  .contact-form-black h2 {
    font-size: 1.15em;
  }
}
</style>

<div class="contact-form-black">
  <h2>Contact Me</h2>
  <div style="text-align:center; color:var(--text-muted); font-size:1.06em; margin-bottom:2.2rem;">
    Let's connect! Fill out the form or use the links below.<br>
    <span style="font-size:0.96em;">
      Also available on 
      <a href="https://www.linkedin.com/in/capwell-murimi/" target="_blank" rel="noopener" style="color:var(--primary);">LinkedIn</a>
      and 
      <a href="https://github.com/capwell-murimi" target="_blank" rel="noopener" style="color:var(--primary);">GitHub</a>.
    </span>
  </div>
  <form class="contact-form-fields" action="https://formspree.io/f/mvgrkjlz" method="POST">
    <div class="floating-label">
      <input type="text" id="name" name="name" required placeholder=" " autocomplete="name">
      <label for="name">Name</label>
    </div>
    <div class="floating-label">
      <input type="email" id="email" name="email" required placeholder=" " autocomplete="email">
      <label for="email">Email</label>
    </div>
    <div class="floating-label">
      <textarea id="message" name="message" rows="5" required placeholder=" "></textarea>
      <label for="message">Message</label>
    </div>
    <button type="submit">Send Message</button>
  </form>

  <div class="direct-email">
    Or email me directly at<br>
    <a href="mailto:capwellmurimi@gmail.com">capwellmurimi@gmail.com</a>
  </div>

  <div class="social-links">
    <a href="https://www.linkedin.com/in/capwell-murimi/" title="LinkedIn" target="_blank" rel="noopener">
      <svg width="1.3em" height="1.3em" viewBox="0 0 24 24" fill="currentColor"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.761 0 5-2.239 5-5v-14c0-2.761-2.239-5-5-5zm-11 19h-3v-10h3v10zm-1.5-11.268c-.966 0-1.75-.783-1.75-1.75s.784-1.75 1.75-1.75 1.75.784 1.75 1.75-.784 1.75-1.75 1.75zm13.5 11.268h-3v-5.604c0-1.337-.025-3.061-1.867-3.061-1.868 0-2.154 1.459-2.154 2.968v5.697h-3v-10h2.881v1.367h.041c.401-.762 1.381-1.566 2.841-1.566 3.039 0 3.6 2.001 3.6 4.601v5.598z"/></svg>
    </a>
    <a href="https://github.com/capwell-murimi" title="GitHub" target="_blank" rel="noopener">
      <svg width="1.3em" height="1.3em" viewBox="0 0 24 24" fill="currentColor"><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577v-2.234c-3.338.724-4.033-1.415-4.033-1.415-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.084-.729.084-.729 1.205.084 1.84 1.236 1.84 1.236 1.07 1.834 2.809 1.304 3.495.997.108-.775.418-1.305.762-1.605-2.665-.306-5.466-1.334-5.466-5.931 0-1.311.469-2.382 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23a11.48 11.48 0 013.003-.404c1.018.005 2.045.138 3.003.404 2.291-1.553 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.839 1.235 1.91 1.235 3.221 0 4.609-2.803 5.624-5.475 5.921.43.372.823 1.102.823 2.222v3.293c0 .322.218.694.825.576C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>
    </a>
  </div>
</div>
