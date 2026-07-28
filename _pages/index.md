---
layout: default
permalink: /
title: Jacob Charles
---

<section class="home-hero home-hero-video">

  <video
    class="home-hero-background"
    autoplay
    muted
    loop
    playsinline
    preload="metadata"
    poster="{{ '/photoassets/featured/home-hero-poster.jpg' | relative_url }}"
  >
    <source
      src="{{ '/photoassets/featured/home-hero-loop.mp4' | relative_url }}"
      type="video/mp4"
    >
  </video>

  <div class="home-hero-overlay"></div>

  <div class="home-hero-content">
    <p class="home-kicker">
      Photographer · Filmmaker · Content Creator
    </p>

    <h1>
      Creating stories<br>
      people remember.
    </h1>

    <div class="home-hero-details">
      <p>
        Photography · Film · Social Content
      </p>

      <p>
        Based in Iowa City &amp; Upstate New York.<br>
        Available worldwide.
      </p>
    </div>
  </div>

</section>


<section class="home-work">

  <a href="{{ '/photo/' | relative_url }}" class="home-work-item">
    <p class="home-section-number">01</p>

    <div class="home-work-title">
      <h2>Photo</h2>
      <span aria-hidden="true">↗</span>
    </div>

    <p>
      Portraiture, documentary photography,
      events, and visual storytelling.
    </p>
  </a>


  <a href="{{ '/video/' | relative_url }}" class="home-work-item">
    <p class="home-section-number">02</p>

    <div class="home-work-title">
      <h2>Video</h2>
      <span aria-hidden="true">↗</span>
    </div>

    <p>
      Documentary, music video,
      narrative, and commercial work.
    </p>
  </a>


  <a href="{{ '/content/' | relative_url }}" class="home-work-item">
    <p class="home-section-number">03</p>

    <div class="home-work-title">
      <h2>Content</h2>
      <span aria-hidden="true">↗</span>
    </div>

    <p>
      Photography, short-form video,
      interviews, and university campaigns.
    </p>
  </a>

</section>


<section class="home-contact">

  <p class="home-kicker">
    Available for commissions and collaborations
  </p>

  <a href="{{ '/contact/' | relative_url }}" class="home-contact-link">
    <span class="home-contact-text">
      Let’s make something memorable.
    </span>

    <span class="home-contact-arrow" aria-hidden="true">
      ↗
    </span>
  </a>

</section>
