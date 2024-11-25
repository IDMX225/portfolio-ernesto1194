---
layout: base.njk
title: Contact
---

<style>
  form {
    background-color: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    padding: 2em;
    max-width: 600px;
    margin: 0 auto;
    font-family: 'Roboto', sans-serif;
    color: #333;
  }

  h2 {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.75rem;
    font-weight: 700;
    color: #5e7b90;
    margin-bottom: 1.5em;
    text-align: center; 
  }

  form label {
    display: block;
    font-weight: 600;
    margin-bottom: 0.5em;
    color: #5e7b90;
  }

  form input,
  form textarea {
    width: 100%;
    padding: 0.75em;
    margin-bottom: 1.5em;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
    font-family: inherit;
    transition: border-color 0.3s ease;
  }

  form input:focus,
  form textarea:focus {
    border-color: #5e7b90;
    outline: none;
  }

  form textarea {
    height: 150px;
    resize: vertical;
  }

  form button[type="submit"] {
    font-size: 1rem;
    padding: 1em 2em;
    background-color: #5e7b90;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    width: 100%;
  }

  form button[type="submit"]:hover,
  form button[type="submit"]:focus {
    background-color: #4d6d7b;
  }

  @media (min-width: 768px) {
    form {
      padding: 2.5em;
    }
  }
</style>

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

