---
layout: default
title: TowerBans
---

<div class="container">

  <div style="text-align: center; margin-top: 2rem;">
    <h1>🍔 TowerBans 🍔</h1>
    <p style="font-size: 1.2em; color: #bbb;">
      Transparency and fairness are paramount in our community.
    </p>

    <!-- Links to Rules and Censored Words posts -->
    <div style="margin-top: 1rem;">
      <a href="{{ site.baseurl }}/2025/01/01/Complete-List-Of-Bannable-Rules" style="margin-right: 1.5em; font-weight: bold; color: #f48fb1;">
        🔗 Bannable Rules
      </a>
      <a href="{{ site.baseurl }}/2025/01/01/Complete-List-Of-Censored-Words" style="font-weight: bold; color: #ce93d8;">
        🔗 Censored Words
      </a>
    </div>
  </div>

  <hr />

  <h2 style="margin-top: 2rem; color: #90caf9;">📚 Blog Archive</h2>

  <ul style="list-style: none; padding-left: 0;">
    {% for post in site.posts %}
      <li style="margin-bottom: 1.5em;">
        <a href="{{ site.baseurl }}{{ post.url }}" style="font-size: 1.2em; font-weight: 600; color: #90caf9;">
          {{ post.title }}
        </a><br />
        <small style="color: #888;">{{ post.date | date: "%d %B %Y" }}</small>
      </li>
    {% endfor %}
  </ul>

</div>
