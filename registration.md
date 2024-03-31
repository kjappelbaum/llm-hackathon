---
title: Hackathon registration
menu_title: Registration
menu_icon: clipboard-check
event_status:
 - soon
---

{:.lead}
Participation is FREE. 
We can't wait to see what you build!
{% if site.registration_status
== "soon" or site.registration_status == "demo" %}Registration opens on
{{ site.registration_opens_date }}.{% endif %} The closing date for applications
is {{ site.registration_closes_date }}.



{% if site.registration_status == "soon" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration opens soon</a>
{% endif %}
{% if site.registration_status == "open" or site.registration_status == "demo" %}
  [Register now](https://www.eventbrite.com/e/llm-hackathon-for-applications-in-materials-and-chemistry-tickets-868303598437){:.btn target="_blank"}
{% endif %}
{% if site.registration_status == "closed" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration has closed</a>
{% endif %}

The closing date for applications is {{ site.registration_closes_date }}.
<div>
The hackathon is open to everyone, regardless of experience. 
Prior coding experience is not required, you can already do a lot by prompting models in interesting ways, or by compiling benchmark datasets.

During the hackathon, the organizers will be available to support you. 
After the hackathon, if you choose to, and you meet the guidelines, you can contribute to the scholarly article.
</div>


