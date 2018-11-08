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

## Keynotes

We are ecstatic to announce our two keynote speakers:
[Dr. Kadija Ferryman](https://datasociety.net/people/ferryman-kadija/) and [Dr. Leslie Chan!](http://www.utsc.utoronto.ca/~chan/)
<span class="image left"><img src="{{ "/images/kadija-ferryman-headshot.jpg" | absolute_url }}" alt="" /></span>
<p>Dr. Kadija Ferryman is a cultural anthropologist who studies health risk as a social, cultural, and ethical phenomenon. Specifically, her research examines the impacts of health risk prediction through information technologies such as genomics, digital medical records, and artificial intelligence on marginalized groups. She is currently a Postdoctoral Scholar at the Data & Society Research Institute in New York and leads the Fairness in Precision Medicine research study, which examines the potential for bias and discrimination in predictive precision medicine. She is a Mozilla Open Science Fellow and will be conducting an ethnography examining the origins of the open health movement and the history of electronic health records during the fellowship.</p>
<span class="image left"><img src="{{ "/images/leslie-chan-headshot.png" | absolute_url }}" alt="" /></span>
<p>Leslie is an Associate Professor and Associate Director of the Centre for Critical Development Studies at the University of Toronto Scarborough. An early practitioner of the Web for scholarly and educational exchange, Leslie has been particularly interested in the role of “openness” in the design of knowledge infrastructure, and the implications on the production and flow of knowledge and their impact on local and international development. As one of the original signatories of the Budapest Open Access Initiative, Leslie has been active in the experimentation and implementation of scholarly communication initiatives of varying scales around the world. Director of Bioline International, an international collaborative open access platform, Leslie is a long time advocate for knowledge equity and inclusive development.  Leslie has served as advisor to numerous projects and organizations, including the Canadian Research Knowledge Network, the American Anthropological Association, the International Development Research Centre, UNESCO, the Open Society Foundation, the Directory of Open Access Journal, more recently the San Francisco Declaration on Research Assessment (DORA). Leslie is the principal investigator for the Open and Collaborative Science in Development Network (OCSDNet), funded by IDRC in Canada and DFID in the UK, and the PI of the Knowledge G.A.P project.</p>

## Organizing Committee

<div id="members">
    {% for person in site.data.members %}
    <div class="member">
        <img src="{{ person.image }}" alt="{{ person.name }}">
        <ul>
            <li class="name">{{ person.name }}</li>
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

### Gold Sponsor: $2500+
- Exclusive sponsorship of lunch with signage
- 10-minute speaking opportunity
- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

### Silver Sponsor: $1500-2499
- Exclusive sponsorship of a coffee break with signage
- 5-minute speaking opportunity
- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

### Bronze Sponsor: $500-1499
- Logo on our website, fliers, and promotional material
- Recognition during conference opening remarks

Interested in becoming a sponsor? Please email us at [openconcascadia@gmail.com](mailto:openconcascadia@gmail.com)!

