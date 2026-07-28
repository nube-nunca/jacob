---
layout: default
permalink: /contact/
title: Contact
---

<section class="contact-page">

  <div class="contact-intro">
    <p class="contact-kicker">Get in touch</p>

    <h1>
      Let’s make<br>
      something memorable.
    </h1>

    <div class="contact-intro-meta">
      <p>
        Available for photography, film,
        editorial, and commissioned content.
      </p>

      <p>
        Based in Iowa City &amp; Upstate New York.<br>
        Available worldwide.
      </p>
    </div>
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
        onsubmit="submitted=true;">

        <div class="contact-name-row">
          <div class="contact-field">
            <label for="firstname">First name</label>
            <input
              type="text"
              id="firstname"
              name="entry.625646384"
              placeholder="Jacob"
              required>
          </div>

          <div class="contact-field">
            <label for="lastname">Last name</label>
            <input
              type="text"
              id="lastname"
              name="entry.1744308571"
              placeholder="Charles"
              required>
          </div>
        </div>

        <div class="contact-field">
          <label for="email">Email</label>
          <input
            type="email"
            id="email"
            name="entry.362250930"
            placeholder="you@example.com"
            required>
        </div>

        <div class="contact-field">
          <label for="subject">Project type</label>
          <input
            type="text"
            id="subject"
            name="entry.579498837"
            placeholder="Documentary, portrait, campaign, event..."
            required>
        </div>

        <div class="contact-form-split">
          <div class="contact-field">
            <label for="eventdate">Project date</label>
            <input
              type="text"
              id="eventdate"
              name="entry.1245624429"
              placeholder="Optional">
          </div>

          <div class="contact-field">
            <label for="location">Location</label>
            <input
              type="text"
              id="location"
              name="entry.18748500"
              placeholder="Optional">
          </div>
        </div>

        <div class="contact-field">
          <label for="message">Tell me about the project</label>
          <textarea
            id="message"
            name="entry.709681169"
            rows="3"
            placeholder="Scope, timeline, deliverables, and anything else worth knowing."
            required></textarea>
        </div>

        <button type="submit" class="contact-submit">
          <span>Send inquiry</span>
          <span aria-hidden="true">↗</span>
        </button>

        <div id="formSubmissionText" class="hidden form-submission-text">
          <p>Please allow up to 2 business days for a reply. Thank you.</p>
        </div>

      </form>

      <iframe
        name="hidden_iframe"
        id="hidden_iframe"
        style="display:none;"
        onload="if(submitted) {}">
      </iframe>

    </section>


    <aside class="contact-visual">

      <div class="contact-image-frame">
        <img
          src="{{ '/photoassets/featured/contact-cover.jpg' | relative_url }}"
          alt="Selected photography by Jacob Charles">
      </div>

      <div class="contact-visual-caption">
        <span>Iowa City · Upstate New York</span>
        <span>Available worldwide</span>
      </div>

    </aside>

  </div>

</section>


<script src="https://code.jquery.com/jquery-3.6.3.min.js"></script>
<script>var submitted = false;</script>

<script>
  $('#gform').on('submit', function () {
    $('#gform').fadeOut(500, function () {
      $(this)
        .html('<p class="contact-success">Sent. Please allow up to 2 business days for a reply.</p>')
        .fadeIn(500);
    });
  });
</script>
