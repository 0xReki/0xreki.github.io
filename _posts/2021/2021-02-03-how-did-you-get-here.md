---
title: "How did you get here?"
---
While you're here, would you tell me how you found this page?

{% if site.data.polls %}
{% assign votes = site.data.polls.referral %}
{% assign total = votes | size %}
{% assign facebook = votes | where: 'referrer', 'facebook' | size %}
{% assign google = votes | where: 'referrer', 'google' | size %}
{% assign twitter = votes | where: 'referrer', 'twitter' | size %}
{% assign scribblehub = votes | where: 'referrer', 'scribblehub' | size %}
{% assign other = votes | where: 'referrer', 'other' | size %}
{% endif %}

{% if votes %}
| Results | |
| ---- | ----- |
| Facebook    | <meter min="0" max="{{ total }}" value="{{ facebook }}" style="width:20em">{{ facebook }}/{{ total }}</meter> |
| Google      | <meter min="0" max="{{ total }}" value="{{ google }}" style="width:20em">{{ google }}/{{ total }}</meter> |
| Twitter     | <meter min="0" max="{{ total }}" value="{{ twitter }}" style="width:20em">{{ twitter }}/{{ total }}</meter> |
| ScribbleHub  | <meter min="0" max="{{ total }}" value="{{ scribblehub }}" style="width:20em">{{ scribblehub }}/{{ total }}</meter> |
| other       | <meter min="0" max="{{ total }}" value="{{ other }}" style="width:20em">{{ other }}/{{ total }}</meter> |
{% endif %}

<!--more-->
