---
layout: default
title: Contact
---

If you want to contact us to find out more about our junior section then please complete the form and we will reply as soon as we can.

<form class="contact" method="POST" action="http://formspree.io/info.2011@calnecomets.co.uk">
  <input class="sender" type="text" placeholder="Your name" name="name" required="required">
  <input class="email" type="email" placeholder="Your email" name="_replyto" required="required">
  <textarea class="message" placeholder="Your message" name="body" required="required"></textarea>
  <input id="send-button" type="submit" value="Send">
  <input type="hidden" name="_subject" value="Junior volleyball contact request" >
  <input type="hidden" name="_next" value="{{ site.url }}">
  <input type="hidden" name="_gotcha" >
</form>
