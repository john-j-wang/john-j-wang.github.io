---
layout: default
title: Contact Me
permalink: /contact-me/
---

<section>
    <h2>{{ page.title }}</h2>
    <p>I would love to hear from you! Please fill out this form, and I will get in touch with you shortly.</p>

    <form action="https://formspree.io/f/yourformid" method="POST">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="_replyto" required><br><br>

        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br><br>

        <input type="submit" value="Send">
    </form>
</section>
