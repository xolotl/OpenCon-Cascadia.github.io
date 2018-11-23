---
layout: page
title: Conference Program
description: Conference Program
permalink: /program/
sitemap:
    priority: 0.7
    lastmod: 2018-11-07
    changefreq: weekly
---

# Program

Stay tuned for more information!

## Keynote Speakers

<div>
    {% for person in site.speakers %}
        <div class="row keynotes">  
            <div class="image 4u 4u(medium) 6u(small) -3u(small)">
                <img src="{{ person.image }}" alt="{{ person.name }}"/>
            </div>
            <div class="text 8u 8u(medium) 12u(small)">
                <h3>
                    {{ person.name }}
                    <a class="contact-icon" target="_blank" href="http://twitter.com/{{ person.twitter }}"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                </h3>
                <h5>{{ person.affiliation }}</h5>
                {{ person.content }}
            </div>
        </div>
        <p></p>
        <div class="row">
            <div class="text 12u">
                
            </div>   
        </div>
    {% endfor %}
</div>

### Schedule

_TBD_
