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

### Friday February 1, 5:30 PM - 8:30 PM

Mozilla Downtown Portland Offices<br>
[1120 NW Couch St #320, Portland, OR 97209](https://goo.gl/maps/BWe5tDpmYU82)

<div><table>
  <col style="width:15%">
  <thead>
    <tr>
      <th>Time</th>
      <th>Session</th>
    </tr>
  </thead>
  <tbody>
  <tr>
    <td>5:30 pm</td>
    <td>Doors open</td>
  </tr>
  <tr>
    <td>5:30 pm</td>
    <td>Doors open</td>
  </tr>
  <tr>
    <td>6:00 pm</td>
    <td>Welcome and Conference Introduction</td>
  </tr>
  <tr>
    <td>6:15 pm</td>
    <td>Lightning talks</td>
  </tr>
  <tr>
    <td>6:45 pm</td>
    <td>Light dinner and networking activities</td>
  </tr>
  <tr>
    <td>7:15 pm</td>
    <td>Lightning talks</td>
  </tr>
  <tr>
    <td>7:45 pm</td>
    <td>Closing</td>
  </tr>
  <tr>
    <td>8:30 pm</td>
    <td>Doors close</td>
  </tr>
  </tbody>
</table></div>

### Saturday February 2, 8:30 AM - 5:00 PM

OHSU Robertson Life Sciences Building<br> 
[2730 SW Moody Ave, Portland, OR 97201](https://goo.gl/maps/yDTHVLd3L6r)

<div><table>
  <col style="width:15%">
  <thead>
    <tr>
      <th>Time</th>
      <th>Session</th>
    </tr>
  </thead>
  <tr>
    <td>8:30 am</td>
    <td>Doors open – Registration</td>
  </tr>
  <tr>
    <td>9:00 am</td>
    <td>Welcome and Conference Introduction</td>
  </tr>
  <tr>
    <td>9:15 am</td>
    <td><b>Morning Keynote</b> (Talk + Q&A)<br>Keynote speaker: Dr. Kadija Ferryman<br>Title: <emph>TBA</emph></td>
  </tr>
  <tr>
    <td>10:00 am</td>
    <td>Coffee + Donuts break</td>
  </tr>
  <tr>
    <td>10:30 am</td>
    <td><b>Open Scholarship Panel</b> (Discussion + Q&A)<br>
            Moderator: Dr. Jeff Spies (TBC)<br>
            Panelists: Dr. David Edwards, TBC, TBC, TBC, TBC<br>
            <hr style="margin:10px">
            <p style="font-size:.85rem">The concept of open scholarship can differ between communities of practice. This panel will explore the variations and intersection of ‘openness’ in the domains of science, education, social justice, and big data. Panelists will share their projects, experiences, and perspectives. The short talks will be followed by a moderated Q&A session in which the audience will have the opportunity to ask questions.</p></td>
  </tr>
  <tr>
    <td>11:45 am</td>
    <td>Lunch (Provided)</td>
  </tr>
  <tr>
    <td>1:00 pm</td>
    <td>
        <b>Afternoon Keynote</b> (Talk + Q&A)<br>
        Keynote Speaker: Dr. Leslie Chan<br>
        Title: TBD</td>
  </tr>
    <tr>
    <td>2:00 pm</td>
    <td><b>Diversity, Equity, and Inclusion Panel</b> (Discussion + Q&A)<br>
        Moderator: TBD<br>
        Panelists: Dr. Letisha Wyatt, TBC, TBC, TBC, TBC<br>
        <hr style="margin:10px">
        <p style="font-size:.85rem">Central to advancing openness is the belief that information should be shared in an equitable and accessible way. As we work together to build an open movement we need to constantly challenge our assumptions and ensure we do not replicate some of the same structures of power and systems of oppression that dominate the current framework of scholarship and education. This panel aims highlight some of the excellent work our local community is already doing and spark a critical discussion around issues of diversity, equity, and inclusions and how we can do better.</p></td>
  </tr>
    <tr>
    <td>3:15 pm</td>
    <td>Coffee break</td>
  </tr>
    <tr>
    <td>3:45 pm</td>
    <td>Open Do-a-thon
    <hr style="margin:10px"><p style="font-size:.85rem">Description: <i>TBA</i></p></td>
  </tr>
    <tr>
    <td>4:45 pm</td>
    <td>Closing remarks</td>
  </tr>
</table></div>

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