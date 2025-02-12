---
title:  ''
type: markdown
reading_time: false
share: false
---

<!-- Contact Form with Formspree Integration -->
<form action="https://formspree.io/f/xanqbepg" method="POST">
  <h2>Let's get in touch :)</h2>

  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
  </div>

  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
  </div>

  <div class="form-group">
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>

  <div class="form-group">
    <button type="submit">Send Message</button>
  </div>
</form>

<!-- Style for the Contact Form -->
<style>
  /* Contact Form Styling */
  form {
    max-width: 600px;
    margin: 40px auto;
    padding: 20px;
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  h2 {
    font-size: 24px;
    font-weight: bold;
    color: #4a4e69;
    margin-bottom: 20px;
    text-align: center;
  }

  .form-group {
    margin-bottom: 20px;
  }

  .form-group label {
    display: block;
    font-size: 16px;
    color: #4a4e69;
    margin-bottom: 8px;
  }

  .form-group input,
  .form-group textarea {
    width: 100%;
    padding: 10px;
    font-size: 14px;
    color: #4a4e69;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-sizing: border-box;
  }

  .form-group textarea {
    resize: vertical;
  }

  .form-group button {
    display: block;
    margin: 0 auto;
    padding: 10px 20px;
    font-size: 16px;
    color: #ffffff;
    background-color: #4a4e69;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
  }

  .form-group button:hover {
    background-color: #2c3e50;
  }
</style>
