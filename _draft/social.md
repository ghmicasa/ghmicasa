---
title: Social
description: Connect with me and explore my music taste.
---

<section class="social-page">
  <div class="music-section">
    <h3>Music</h3>
    <p>
      Dive into my favorite tunes and discover the sounds that inspire me. Check out my handpicked Spotify playlist below.
    </p>
    {% include spotifyplaylist.html %}
  </div>

  <div class="personal-note">
    <p>
     I also enjoy reading. Feel free to explore my blog for my thoughts.
    </p>
  </div>
  {% include share-buttons.html %}
</section>

<style>
  .social-page {
    max-width: 800px;
    margin: 0 auto;
    padding: 2px; /* reduced padding */
  }

  .music-section,
  .personal-note {
    margin-bottom: 2px; /* reduced margin */
  }

  .personal-note p {
    margin-top: 10px; /* reduced margin */
  }
</style>