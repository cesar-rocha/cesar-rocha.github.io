---
layout: single
title: "Research Group"
permalink: /group/
header:
  image: /assets/images/vorticity.png
---

My research group investigates fundamental questions in physical oceanography and geophysical fluid dynamics through a combination of theory, observations, and a hierarchy of numerical models. Current research topics include submesoscale physics; internal waves; compact mesoscale eddies; volume, heat, and freshwater transports associated with the AMOC; and the intermediate circulation of the Southwest Atlantic.  

## Present Members

{% include group_cards.html members=site.data.group_members.faculty title="Principal Investigator" %}
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
