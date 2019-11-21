---
layout: page
title : About
permalink: /00about/
---

Soon

aa

      <div class="footer-col footer-col-2 footer-content">
        <ul class="social-media-list">
          {% if site.github_username %}
          <li>
            {% include icon-github.html username=site.github_username %}
          </li>
          {% endif %}

          {% if site.twitter_username %}
          <li>
            {% include icon-twitter.html username=site.twitter_username %}
          </li>
          {% endif %}
        </ul>
      </div>

      <div class="footer-col footer-col-3 site-description">
        <p>{{ site.description }}</p>
      </div>
