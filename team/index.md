---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>Team

Our lab fosters multi-disciplinary and collaborative research. It is so much more fun and rewarding to do research in diverse teams with diverse expertises! As a result, our team embeds a group of highly engaged researchers from various research groups with a broad range of equally-cherised skills.

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" style="small" %}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/NWO.png"
  link1="https://www.nwo.nl/en/researchprogrammes/nwo-talent-programme"
  tooltip1="VENI young talent award"

  image2="images/lumc.png"
  link2="https://www.lumc.nl/?setlanguage=English&setcountry=en"
  tooltip2="Leiden University Medical Center"

  image3="images/healthholland.png"
  link3="https://www.health-holland.com"
  tooltip3="Health~Holland"
%}
