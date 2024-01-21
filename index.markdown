---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
---

![serene mountain lake](assets/mountain_lake.jpg)

<center>Dr. Kidder has retired from his practice as of January 2023. This website is for medical record requests only. Use the form below to send a request. Please include a good contact phone number.</center>

 

  <section class="get-in-touch">
   <h1 class="title">Contact Form</h1>
   <form class="contact-form row" action="mailto:{{ site.email }}" method="get" enctype="text/plain">
      <div class="form-field col x-50">
         <input id="name" class="input-text js-input" type="text" required>
         <label class="label" for="name">Name</label>
      </div>
      <div class="form-field col x-50">
         <input id="email" class="input-text js-input" type="email" required>
         <label class="label" for="email">E-mail</label>
      </div>
      <div class="form-field col x-100">
         <input id="message" class="input-text js-input" type="text" required>
         <label class="label" for="message">Message</label>
      </div>
      <div class="form-field col x-100 align-center">
         <input class="submit-btn" type="submit" value="Send">
      </div>
   </form>
</section>

<script type="text/javascript" src="assets/js/jquery.min.js" ></script>
<script type="text/javascript" src="assets/js/custom.js"></script>