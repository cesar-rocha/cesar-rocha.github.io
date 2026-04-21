---
layout: single
title: "Research Group"
permalink: /group/
header:
  image: /assets/images/vorticity.png
---

Our group studies ocean and climate dynamics across a range of scales, combining theory, observations, and numerical modeling.

## Present Members

{% include group_cards.html members=site.data.group_members.faculty title="Faculty" %}
{% include group_cards.html members=site.data.group_members.postdocs title="Postdocs" %}
{% include group_cards.html members=site.data.group_members.graduate_students title="Graduate Students" %}
{% include group_cards.html members=site.data.group_members.undergrads title="Undergraduate Students" %}

## Alumni

### Graduate Students

<ul class="alumni-list">
{% for person in site.data.group_members.alumni_graduate_students %}
  <li>
    <strong>{{ person.name }}</strong> — {{ person.role }} ({{ person.years }})
    {% if person.current_position %}
      <br><em>Now:</em> {{ person.current_position }}
    {% endif %}
  </li>
{% endfor %}
</ul>

### Undergraduate Students

<ul class="alumni-list">
{% for person in site.data.group_members.alumni_undergrads %}
  <li>
    <strong>{{ person.name }}</strong> — {{ person.role }} ({{ person.years }})
    {% if person.current_position %}
      <br><em>Now:</em> {{ person.current_position }}
    {% endif %}
  </li>
{% endfor %}
</ul>
