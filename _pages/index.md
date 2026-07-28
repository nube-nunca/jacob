---
layout: default
permalink: /
title: Jacob Charles
---

<section class="home-hero">

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

</section>


<section class="home-reel">

  <div class="home-reel-header">
    <div>
      <p class="home-section-number">01</p>
      <h2>Selected Reel</h2>
    </div>

    <p>
      A short selection of documentary, commercial,
      and social-first moving-image work.
    </p>
  </div>

  <div class="home-reel-frame">
    <video
      autoplay
      muted
      loop
      playsinline
      preload="metadata"
      poster="{{ '/photoassets/featured/home-reel-poster.jpg' | relative_url }}"
    >
      <source
        src="{{ '/photoassets/featured/home-reel-loop.mp4' | relative_url }}"
        type="video/mp4"
      >
    </video>

    <div class="home-reel-label">
      <span>Selected Reel</span>
      <span>00:08 Loop</span>
    </div>
  </div>

</section>


<section class="home-work">

  <a href="{{ '/photo/' | relative_url }}" class="home-work-item">
    <p class="home-section-number">02</p>

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
    <p class="home-section-number">03</p>

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
    <p class="home-section-number">04</p>

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

  <a href="{{ '/contact/' | relative_url }}">
    Let’s make something memorable.
  </a>

</section>
