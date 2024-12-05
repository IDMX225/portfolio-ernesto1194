---
layout: base.njk
title: Contact
---

<h2>Contact Us</h2>

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label for="name">Your Name:</label>
    <input type="text" id="name" name="name" required />
  </p>
  <p>
    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email" required />
  </p>
  <p>
    <label for="message">Message:</label>
    <textarea id="message" name="message" required></textarea>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

