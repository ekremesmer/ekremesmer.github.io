---
permalink: /
#title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a postdoctoral researcher at the University of Kansas, working with Ian Crossfield's ExoLab group. I study planets in binary and multiple star systems: how they can be detected, whether their orbits are stable, and how stellar multiplicity shapes the wider planet population. My work combines eclipse-timing, transit, and radial-velocity observations with dynamical modeling and population statistics, and currently includes occurrence-rate estimates for Earth-like planets.

Before joining KU, I was a McDonnell Center Postdoctoral Fellow at Washington University in St. Louis, and I received my PhD from Ankara University. I also enjoy [teaching](/teaching/) and public [outreach](/outreach/), from university courses to Astronomy on Tap.

More on my current and past projects is on the [Research](/research/) page.

## Recent Publications

{% assign recent = site.publications | sort: "date" | reverse %}
{% for post in recent limit: 4 -%}
- {{ post.title }}. *{{ post.venue }}* ({{ post.year }}). [[Details]]({{ post.url }})
{% endfor %}

See the full list on the [Publications](/publications/) page.

