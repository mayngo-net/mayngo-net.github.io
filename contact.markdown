---
layout: page
title: Contact
permalink: /contact
order: 400
---

<form target="_blank" action="https://formsubmit.co/{{ site.email }}" method="POST">

<label for="name">Your Name</label>
<input type="text" id="name" name="name" required>

<label for="email">Your e-mail</label>
<input type="email" id="email" name="email">

<label for="message">Your Message</label>
<textarea id="message" name="message" rows="7" required></textarea>

<button type="submit">Submit</button>
</form>
