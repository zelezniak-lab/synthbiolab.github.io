---
title: Team
nav:
  order: 3
  tooltip: About our team
---

## {% include icon.html icon="fa-solid fa-users" %}Team

Our success is deeply rooted in the contributions of team members, whose dedication, insights, and innovations continue to inspire and propel our research forward. We are an interdisciplinary team working collaboratively on computational and experimental problems. We are highly engaged in collaborative work and believe in 1+1=5. We nurture an environment where team members are treated equally and respect and admire our differences. Our team includes postdocs, PhD students and students at all stages of their careers interested in the intersection of computational, engineering and biological sciences.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ^(?!a_.*?)" %}

## {% include icon.html icon="fa-solid fa-users" %}Alumni

Invaluable contributions of our alumni have been instrumental in shaping our lab's culture and research. We are grateful for their dedication and wish them all the best in their future endeavours.

{% include section.html %}

{% include list.html data="members" component="portrait" style="small" filters="role: ^a_.*?" %}


## {% include icon.html icon="fa-solid fa-sack-dollar" %}Funding

Our work is made possible by generous funding from these organizations.

{% capture content %}

{% include figure.html image="images/ukri-bbsrc-square-logo.png" link="https://www.ukri.org/councils/bbsrc/" %}
{% include figure.html image="images/kaw.png" link="https://kaw.wallenberg.org/en"%}
{% include figure.html image="images/formas.jpg" link="https://formas.se/" %}
{% include figure.html image="images/vr.png"  link="https://www.vr.se/" %}
{% include figure.html image="images/ms_logo_cam.gif" link="https://www.microsoft.com/en-us/research/" %}
{% include figure.html image="images/scilifelab.png" link="https://www.scilifelab.se/" %}
{% include figure.html image="images/mjj.png" link="https://mjjfondas.lt/en/main-page/" tooltip="Marius Jakulis Jason Foundation" %}
{% endcapture %}

{% include grid.html style="square" content=content %}
