---
layout: page
title: About OpenCon Cascadia
description: About us.
permalink: /about/
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

## Organizing Committee

<div id="members">
    {% for person in site.team %}
    <div class="member">
        <a href="/team/{{ person.title | slugify }}">
            <img src="{{ person.image }}" alt="{{ person.name }}">
        </a>
        <ul>
            <a href="/team/{{ person.title | slugify }}"><li class="name">{{ person.name }}</li></a>
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

## Sponsors

Help make OpenCon Cascadia great! We are looking for sponsors to keep our event *low cost to attend* and to fund:<br>
Lunch - Coffee breaks - Childcare - AV Support - First-rate speakers - Free tickets

Interested in becoming a sponsor? Please email us at [openconcascadia@gmail.com](mailto:openconcascadia@gmail.com)!

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

<div id="sponsors">
<center>
    <div class="sponsor">
        <div class="logo">
            <a href ="https://www.mozilla.org/en-US/" target = "_blank">
                <img src="/images/mozilla_logo.png" alt="Mozilla" />
            </a>
        </div>
        <!-- <ul>
            <a href="https://www.mozilla.org/en-US/" target = "_blank"><li class="name">Mozilla</li></a>
        </ul> -->
    </div>
    <div class="sponsor">
        <div class="logo">
            <a href="https://library.pdx.edu/" target = "_blank">
                <img src="/images/psu_logo.png" alt="Portland State University" />
            </a>
        </div>
        <!-- <ul>
            <a href="https://library.pdx.edu/" target = "_blank"><li class="name">Portland State University Library</li></a>
        </ul> -->
    </div>
    <div class="sponsor">
        <div class="logo">
            <a href="https://library.uoregon.edu/" target = "_blank">
                <img src="/images/UofO_logo.png" alt="University of Oregon" />
            </a>
        </div>
        <!-- <ul>
            <a href="https://library.uoregon.edu/" target = "_blank"><li class="name">University of Oregon Library</li></a>
        </ul> -->
    </div>
     <div class="sponsor">
        <div class="logo">
            <a href ="https://www.ohsu.edu/library" target = "_blank">
                <img src="/images/OHSU-RGB-4C-POS.png" alt="OHSU Library" />
            </a>
        </div>
        <!-- <ul>
            <a href="https://www.ohsu.edu/library" target = "_blank"><li class="name">OHSU Library</li></a>
        </ul> -->
    </div>
</center>
</div>

#### Bronze Sponsor: $500-1499

- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

<div id="sponsors">
<center>
    <div class="sponsor">
        <div class="logo">
        <a href="https://library.whitman.edu/" target = "_blank">
            <img src="/images/whitman_logo.JPG" alt="Whitman University" />
        </a>
        </div>
        <!-- <ul>
            <a href="https://library.whitman.edu/" target = "_blank"><li class="name">Whitman University Penrose Library</li></a>
        </ul> -->
    </div>
    <div class="sponsor">
        <div class="logo">
            <a href="https://library.reed.edu/" target = "_blank">
                <img src="/images/reed_logo.png" alt="Reed College" />
            </a>
        </div>
        <!-- <ul>
            <a href="https://library.reed.edu/" target = "_blank"><li class="name">Reed College Library</li></a>
        </ul> -->
    </div>
    <div class="sponsor">
        <div class="logo">
        <a href="https://college.lclark.edu/library/" target = "_blank">
            <img src="/images/lewis_clark_logo.png" alt="Lewis and Clark" />
        </a>
        </div>
        <!-- <ul>
            <a href="https://college.lclark.edu/library/" target = "_blank"><li class="name">Lewis and Clark Library</li></a>
        </ul> -->
    </div>
    <div class="sponsor">
        <div class="logo">
        <a href="https://library.willamette.edu/" target = "_blank">
            <img src="/images/willamette_logo.png" alt="willamette University" />
        </a>
        </div>
        <!-- <ul>
            <a href="https://library.willamette.edu/" target = "_blank"><li class="name">Willamette University Library</li></a>
        </ul> -->
    </div>
    <div class="sponsor">
        <div class="logo">
        <a href="https://www.ohsu.edu/xd/education/student-services/student-life/ohsu-student-council/" target = "_blank">
            <img src="/images/all_hill_logo.png" alt="All-Hill OHSU" />
        </a>
        </div>
        <!-- <ul>
            <a href="https://www.ohsu.edu/xd/education/student-services/student-life/ohsu-student-council/" target = "_blank"><li class="name">OHSU All Hill Student Council</li></a>
        </ul> -->
    </div>
</center>
</div>
