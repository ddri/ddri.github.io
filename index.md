---
layout: default
title: Home
---

# Quantum Computing Timeline

{% for item in site.data.timeline %}
<div class="timeline-item {% cycle 'left', 'right' %}">
    <div class="content">
        <h2>{{ item.year }}</h2>
        <p>{{ item.event }}</p>
    </div>
</div>
{% endfor %}