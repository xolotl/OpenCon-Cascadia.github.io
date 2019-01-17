---
layout: page
title: OpenCon Cascadia - Speakers
description: Profiles of all speakers
permalink: /speakers/
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---

## Our speakers

<div id="members">
    {% for person in site.speakers %}
    <div class="member">
        <a href="/speakers/{{ person.title | slugify }}">
            <img src="{{ person.image }}" alt="{{ person.name }}">
        </a>
        <ul>
            <a href="/speakers/{{ person.title | slugify }}"><li class="name">{{ person.name }}</li></a>
            <li class="job-title">{{ person.affiliation }}</li>
        </ul>
        <ul class="contact-member">
            {% if person.twitter != null %}
                <li><a class="contact-icon" target="_blank" href="http://twitter.com/{{ person.twitter }}"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
            {% endif %}
            {% if person.github != null %}
                <li><a class="contact-icon" target="_blank" href="http://github.com/{{ person.github }}"><i class="fa fa-github" aria-hidden="true"></i></a></li>
            {% endif %}
            {% if person.orcid != null %}
                <li><a class="contact-icon" target="_blank" href="http://orcid.org/{{ page.orcid }}"><i class="ai ai-orcid" aria-hidden="true"></i></a></li>
            {% endif %} 
        </ul>
    </div>
    {% endfor %}
</div>
