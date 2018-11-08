---
layout: page
title: About OpenCon Cascadia
description: About us.
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---

## What is OpenCon Cascadia?

> It is the mission of OpenCon Cascadia to build an inclusive, collaborative community, spanning all disciplines, domains, and research communities, by flattening hierarchical structures to provide a more open and equitable place for individuals to thrive. This Pacific Northwest community aims to support and foster mentorship, innovative solutions, collective projects, and energizing conversations on all things open, with a focus on building up young or new professionals.

<span class="image left"><img src="{{ "/images/OCClogo.png" | absolute_url }}" alt="" /></span>

We believe that everyone has the right to access research and scholarship. We're convening OpenCon Cascadia to provide support to communities and projects with the goal of making scholarship more open, inclusive, and accessible. Are you involved in a project with a goal of improving research, academic culture, or public access to scholarly work? Are you pushing for open research at your institution or organization? Are you involved in a project that seeks to make research more accessible through citizen science or DIY science?
Join us at OpenCon Cascadia to share stories, discuss challenges, and connect with regional colleagues in a fun and welcoming environment. We'll discuss issues facing research and scholarship today and work on strategy and communication docs for our projects.

## Sponsors

Help make OpenCon Cascadia great! We are looking for sponsors to keep our event *low cost to attend* and to fund:<br>
Lunch - Coffee breaks - Childcare - AV Support - First-rate speakers - Free tickets

#### Gold Sponsor: $2500+

- Exclusive sponsorship of lunch with signage
- 10-minute speaking opportunity
- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

#### Silver Sponsor: $1500-2499

- Exclusive sponsorship of a coffee break with signage
- 5-minute speaking opportunity
- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

#### Bronze Sponsor: $500-1499

- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

Interested in becoming a sponsor? Please email us at [openconcascadia@gmail.com](mailto:openconcascadia@gmail.com)!

## Organizing Committee

<div id="members">
    {% for person in site.data.members %}
    <div class="member">
        <a href="/team/{{ person.name | slugify }}" style="border: 0;">
            <img src="{{ person.image }}" alt="{{ person.name }}">
        </a>
        <ul>
            <a href="/team/{{ person.name | slugify }}"><li class="name">{{ person.name }}</li></a>
            <li class="job-title">{{ person.affiliation }}</li>
        </ul>
        <ul class="contact-member">
            {% if person.twitter != null %}
                <li><a class="contact-icon" target="_blank" href="http://twitter.com/{{ person.twitter }}"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
            {% endif %}
            {% if person.github != null %}
                <li><a class="contact-icon" target="_blank" href="http://github.com/{{ person.github }}"><i class="fa fa-github" aria-hidden="true"></i></a></li>
            {% endif %}
        </ul>
    </div>
    {% endfor %}
</div>