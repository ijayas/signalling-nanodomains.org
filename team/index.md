---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/alt-header.jpg" dark=true %}

# {% include icon.html icon="fa-solid fa-users" %}Lab Alumni

{% capture text %}
Mr Michael Spencer (Research Technician)
Mr Benjamin H.K. Allouis (MSc Student)
Ms Rebecca Lavery (MSc Student)
Ms Chiara Pillen (RMS summer scholar)
Dr Miriam Hurley (PhD researcher)
Dr Lucia Pedicini (PhD researcher)
Dr Katarina Miteva (PhD researcher)
Dr Ashley Rowley (PhD researcher)
Dr Kaarjel Narayanasamy (Postdoctoral Research Assistant)
Dr Ruth Norman (Postdoctoral Research Associate; supervised with PI A/Prof Sarah Calaghan)
Dr Sabine Lotteu (Postdoctoral Research Associate; supervised with PI A/Prof Sarah Calaghan)
Dr Kathleen Wright (Senior Technician)
Tim Munsey (Senior Technician)
{% endcapture %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/izzy.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
