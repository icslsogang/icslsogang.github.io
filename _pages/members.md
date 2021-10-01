---
layout: page
permalink: /members/
title: Current Members
subtitle: Intelligent Connected Systems Laboratory
---

### Professor

<ul>
{% for member in site.data.members %}
  {% if member.identification == "prof" %}
  <li>
    {{ member.name }}
    {% if member.social-network-links.github %}
    <a class="fa" href="https://github.com/{{ member.social-network-links.github }}">
      <i class="fab fa-github" title="Github"></i>
    </a>
    {% endif %}
    {% if member.social-network-links.email %}
    <a class="fa" href="mailto:{{ member.social-network-links.email }}">
      <i class="fas fa-envelope" title="E-Mail"></i>
    </a>
    {% endif %}
  </li>
  {% endif %}
{% endfor %}
</ul>

---

### M.S. Students

<ul>
{% for member in site.data.members %}
  {% if member.identification == "ms" %}
  <li>
    {{ member.name }}
    {% if member.social-network-links.github %}
    <a class="fa" href="https://github.com/{{ member.social-network-links.github }}">
      <i class="fab fa-github" title="Github"></i>
    </a>
    {% endif %}
    {% if member.social-network-links.email %}
    <a class="fa" href="mailto:{{ member.social-network-links.email }}">
      <i class="fas fa-envelope" title="E-Mail"></i>
    </a>
    {% endif %}
  </li>
  {% endif %}
{% endfor %}
</ul>

---

### Undergraduate Interns

<ul>
{% for member in site.data.members %}
  {% if member.identification == "ug" %}
  <li>
    {{ member.name }}
    {% if member.social-network-links.github %}
    <a class="fa" href="https://github.com/{{ member.social-network-links.github }}">
      <i class="fab fa-github" title="Github"></i>
    </a>
    {% endif %}
    {% if member.social-network-links.email %}
    <a class="fa" href="mailto:{{ member.social-network-links.email }}">
      <i class="fas fa-envelope" title="E-Mail"></i>
    </a>
    {% endif %}
  </li>
  {% endif %}
{% endfor %}
</ul>