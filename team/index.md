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
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/alt-header.jpg" dark=true %}

{% include section.html %}

{% capture content %}

# {% include icon.html icon="fa-solid fa-users" %}Lab Alumni

{% capture text %}
Mr Michael Spencer (Research Technician; 2021-2023)
Mr Benjamin H.K. Allouis (MSc Student; 2022-2023)
Ms Rebecca Lavery (MSc Student; 2021-2022)
Ms Chiara Pillen (RMS summer scholar; 2021)
Dr Miriam Hurley (PhD researcher; 2016-2020)
Dr Lucia Pedicini (PhD researcher; 2016-2019)
Dr Katarina Miteva (PhD researcher; 2016-2020)
Dr Ashley Rowley (PhD researcher; 2018-2021)
Dr Kaarjel Narayanasamy (Postdoctoral Research Assistant; 2017-2019)
Dr Ruth Norman (Postdoctoral Research Associate; supervised with PI A/Prof Sarah Calaghan; 2016-2019)
Dr Kathleen Wright (Senior Technician; 2016-2018)
Tim Munsey (Senior Technician; 2018-2020)
{% endcapture %}

{% endcapture content %}




