---
title: About Me!
nav:
  order: 5
  tooltip: Background, CV, and contact info
---

# {% include icon.html icon="fa-regular fa-file-text" %}About

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="pws5408@psu.edu"
  link="pws5408@psu.edu"
%}
{%
  include button.html
  type=""
  text="(925) 998-7090"
  link="+1-925-998-7090"
%}
{%
  include button.html
  type=""
  text="CV Oct 2024"
  tooltip="PDF of my latest CV"
  link="https://drive.google.com/file/d/1uKrZLKjltUknVyT70Fv1MgpBTC_8Jfjv/view?usp=sharing"
%}
{%
  include button.html
  type=""
  text="Burghardt Lab"
  tooltip="Lab Website of PI #1"
  link="https://lianaburghardtlab.com/"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/patlianasoy.jpg"
  caption="The only thing better than being in the field... "
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/patbike.jpg"
  caption="... is the bike ride to get there."
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
