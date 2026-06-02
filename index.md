---
layout: default
title: "Davide Talon | Homepage"
#description: "Personal academic website for Your Name."
author_name: "Davide Talon"
position: "Postdoctoral Researcher in Computer Vision"
institution: "Fondazione Bruno Kessler, Trento, Italy"
email: "dtalon AT fbk DOT eu"
profile_image: "assets/images/profile.jpg"
scholar: https://scholar.google.com/citations?user=IiMwp7EAAAAJ&hl=en
x: https://x.com/davidetalon94
linkedin: https://www.linkedin.com/in/davidetalon/
github: https://github.com/davidetalon
cv: ./assets/files/cv.pdf
---

<section class="hero" aria-label="Profile">
  <img class="portrait" src="{{ page.profile_image }}" alt="{{ page.profile_alt }}">
  <div class="hero-copy">
    <h1>{{ page.author_name }}</h1>
    <p class="role">{{ page.position }}</p>
    <p class="institution">{{ page.institution }}</p>
    <p class="contact"><a href="mailto:{{ page.email }}">{{ page.email }}</a></p>
    <div class="quick-links" aria-label="Profile links">
      <a href="{{ page.cv }}" rel="noopener">CV</a>
      <a href="{{ page.scholar }}">Scholar</a>
      <a href="{{ page.linkedin }}">Linkedin</a>
      <a href="{{ page.github }}">Github</a>
      <a href="{{ page.x }}">X</a>
    </div>
  </div>
</section>

<section class="content-section bio" id="about">
{% capture about_content %}{% include content/about.md %}{% endcapture %}
{{ about_content | markdownify }}
</section>

<section class="content-section" id="news">
{% capture news_content %}{% include content/news.md %}{% endcapture %}
{{ news_content | markdownify }}
</section>

<section class="content-section" id="publications">
{% capture publications_content %}{% include content/publications.md %}{% endcapture %}
{{ publications_content | markdownify }}
</section>

<section class="content-section" id="teaching">
{% capture teaching_content %}{% include content/teaching-service.md %}{% endcapture %}
{{ teaching_content | markdownify }}
</section>

<section class="content-section" id="more">
{% capture more_content %}{% include content/more.md %}{% endcapture %}
{{ more_content | markdownify }}
</section>
