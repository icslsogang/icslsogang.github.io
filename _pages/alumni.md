---
layout: page
permalink: /alumni/
title: "Alumni" 
subtitle: Intelligent Connected Systems Laboratory
---

### Former Graduate Students

<ul>
{% for member in site.data.alumni %}
  <li>
    <div>
        {{ member.name }} 
        {{ member.identification }}
        {% if member.univ %}
        {{ member.univ}}
        {% endif %}
        {{ member.grad-year }}
        {% if member.current %}
        (@{{ member.current }})
        {% endif %}
    </div>
  </li>
{% endfor %}
</ul>
