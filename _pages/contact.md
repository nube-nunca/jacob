---
layout: default
permalink: /contact/
title: Contact
---

<section class="contact-page">

  <div class="contact-page-heading">
    <p class="contact-kicker">Inquiries</p>
    <h1>Ready when you are.</h1>
  </div>

  <div class="contact-layout">

    <section class="contact-form-column">

      <form
        class="contact-form"
        name="gform"
        id="gform"
        method="POST"
        action="https://docs.google.com/forms/d/e/1FAIpQLSdZ7-C23kYCopL0N3l88v7k3ixYfp9H8GO4cQNvMw8jfrn9zg/formResponse"
        target="hidden_iframe"
        onsubmit="submitted = true;"
      >

        <div class="contact-name-row">

          <div class="contact-field">
            <label for="firstname">First name</label>
            <input
              type="text"
              id="firstname"
              name="entry.625646384"
              placeholder="First name"
              autocomplete="given-name"
              required
            >
          </div>

          <div class="contact-field">
            <label for="lastname">Last name</label>
            <input
              type="text"
              id="lastname"
              name="entry.1744308571"
              placeholder="Last name"
              autocomplete="family-name"
              required
            >
          </div>

        </div>

        <div class="contact-field">
          <label for="email">Email</label>
          <input
            type="email"
            id="email"
            name="entry.362250930"
            placeholder="you@example.com"
            autocomplete="email"
            required
          >
        </div>

        <div class="contact-field">
          <label for="subject">What are you inquiring about?</label>
          <input
            type="text"
            id="subject"
            name="entry.579498837"
            placeholder="service types on the right"
            required
          >
        </div>

        <div class="contact-form-split">

          <div class="contact-field">
            <label for="eventdate">Project date</label>
            <input
              type="text"
              id="eventdate"
              name="entry.1245624429"
              placeholder="(Optional)"
            >
          </div>

          <div class="contact-field">
            <label for="location">Location</label>
            <input
              type="text"
              id="location"
              name="entry.18748500"
              placeholder="(Optional)"
              autocomplete="address-level2"
            >
          </div>

        </div>

        <div class="contact-field">
          <label for="message">Do you want to add more details?</label>
          <textarea
            id="message"
            name="entry.709681169"
            rows="3"
            placeholder="Scope, timeline, deliverables, and anything else worth knowing."
            required
          ></textarea>
        </div>

        <button type="submit" class="contact-submit">
          <span>Send inquiry</span>
          <span aria-hidden="true">↗</span>
        </button>
        
      </form>

      <iframe
        name="hidden_iframe"
        id="hidden_iframe"
        title="Hidden form submission target"
        style="display: none;"
      ></iframe>

    </section>


    <aside class="contact-info">

      <section class="contact-info-block contact-services-block">
        <p class="contact-info-label">Services</p>

        <div class="contact-service-group">
          <span class="contact-service-number">01</span>

 <div class="contact-service-content">
  <h2>Photography</h2>

  <ul class="contact-service-list">
    <li>Portraits</li>
    <li>Couples & Families</li>
    <li>Senior Portraits</li>
    <li>Professional Headshots</li>
    <li>Events</li>
    <li>Commercial</li>
    <li>Real Estate</li>
    <li>Passport Photos</li>
  </ul>
</div>
        </div>

        <div class="contact-service-group">
          <span class="contact-service-number">02</span>

<div class="contact-service-content">
  <h2>Video</h2>

  <ul class="contact-service-list">
    <li>Documentary</li>
    <li>Interviews</li>
    <li>Events</li>
    <li>Commercial</li>
    <li>Music Videos</li>
  </ul>
</div>
        </div>

        <div class="contact-service-group">
          <span class="contact-service-number">03</span>

<div class="contact-service-content">
  <h2>Content</h2>

  <ul class="contact-service-list">
    <li>Social Media</li>
    <li>University Communications</li>
    <li>Brand Campaigns</li>
    <li>Short-form Content</li>
  </ul>
</div>
        </div>
      </section>


      <section class="contact-info-block">
        <p class="contact-info-label">Working with</p>

        <p class="contact-info-copy">
          Individuals · Families · Businesses · Universities ·
          Nonprofits · Organizations · Creative agencies
        </p>
      </section>


      <section class="contact-info-block">
        <p class="contact-info-label">Based in</p>

        <p class="contact-info-copy">
          Iowa City · Upstate New York<br>
          Available for travel and remote collaboration
        </p>
      </section>

    </aside>

  </div>

</section>


<script src="https://code.jquery.com/jquery-3.6.3.min.js"></script>

<script>
  let submitted = false;

  $("#gform").on("submit", function () {
    const $form = $(this);

    $form.fadeOut(450, function () {
      $form
        .html(
          '<div class="contact-success">' +
            '<p class="contact-success-heading">Inquiry sent.</p>' +
            '<p>Sent! I'll get back you soon. Please allow up to 2 business days for a reply.</p>' +
          '</div>'
        )
        .fadeIn(450);
    });
  });
</script>
