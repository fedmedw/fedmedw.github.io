---
layout: default
---

# Talks

{% for person in site.workshop.talks %}
<div class="speaker">
<a href='#'>
    <img src="{{ person.pic }}"/>
    <div class="details">
        <span class="name">{{ person.name }}<br>{{ person.surname }}</span>
        <span class="affiliation">{{ person.affiliation }}</span>
        <span class="title">Title of the talk: {{ person.title }}</span>
    </div>
</a>
</div>
{% endfor %}
