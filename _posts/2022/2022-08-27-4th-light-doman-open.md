---
title: "来冬 の 麻雀 (Mahjong of Light) — 4th Light Doman Open"
long: true

tags:
  - Riichi Mahjong
  - Doman Mahjong Tournament

permalink: /doman/2022-09-4th-light-doman-open/

image: /blog/images/2021-09-throne.jpg
image_alt: The Mahjong Throne

seo_title_fix: 3

redirect_from:
  - /doman/

start_date: 2022-09-23
end_date: 2022-09-25
registration_url: https://docs.google.com/forms/d/e/1FAIpQLScU0qWowtdQhK66iMx39eQVR2xIxk48u7lDY81BRsTt4xOCyg/viewform?usp=sf_link
registration_date: 2021-09-18
sheet_url: https://docs.google.com/spreadsheets/d/e/2PACX-1vSxtNlGlzXMLAkqgO_Z7OU_j5OXTG4kBwLmiP5VYvnbzTL0h_VaWJaHUe2h8pP0wnpELBDGM_KdrDa2/pubhtml

excerpt: |
  It's time for another Light Doman Open!
  This is the sixth Doman Mahjong Tournament on Light, feel free to make an alt character on Light, or Chaos, to join.
  This will be the first tournament after Final Fantasy XIV adds Data Centre Travel, let's see how well it works for us.
  And since I need some image I can connect to this tournament, I dug out some bad pun: 来冬 の 麻雀, raitou no maajan.
  来冬 means next winter.
  You know where this is going: Riichi is coming.
---
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SportsEvent",
  "name": "{{ page.title }}",
  "url": "{{ page.url }}",
  "sport": "Riichi Mahjong",
  "startDate": "{{ page.start_date }}",
  "endDate": "{{ page.end_date }}",
  "location": {
    "@type": "VirtualLocation",
    "name": "Final Fantasy XIV Online",
    "disambiguatingDescription": "Server Odin, Datacenter Light",
    "url": "https://eu.finalfantasyxiv.com/"
  },
  "image": "{{ page.image | absolute_url }}",
  "description": "{{ page.excerpt }}.",
  "eventStatus": "https://schema.org/EventScheduled",
  "eventAttendanceMode": "https://schema.org/OnlineEventAttendanceMode",
  "isAccessibleForFree": true,
  "organizer": {
    "@type": "Person",
    "url": "https://reki.wtf/about-me/",
    "name": "quốc Thái “0xReki” Chung"
  },
  "potentialAction": {
    "@type": "JoinAction",
    "url": "{{ page.registration_url }}",
    "name": "Registration Form",
    "event": { "id": "{{ page.url }}" },
    "endTime": "{{ page.registration_date }}"
  }
}
</script>

<picture>
  <source srcset="{{ '/blog/images/xs/2021-09-throne.avif' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/avif">
  <source srcset="{{ '/blog/images/xs/2021-09-throne.webp' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/webp">
  <source srcset="{{ '/blog/images/xs/2021-09-throne.png' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/jpeg">
  <source srcset="{{ '/blog/images/2021-09-throne.avif' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/avif">
  <source srcset="{{ '/blog/images/2021-09-throne.webp' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/webp">
  <source srcset="{{ '/blog/images/2021-09-throne.png' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/png">
  <img loading="lazy" class="my-2" src="{{ '/blog/images/2021-09-throne.webp' | prepend: site.static_url | absolute_url }}" alt="The Mahjong Throne" title="The Mahjong Throne">
  <figcaption class="text-center">The Mahjong Throne</figcaption>
</picture>

{:.mt-4}
It's time for another Light Doman Open!
This is the eighth Doman Mahjong Tournament on Light, feel free to make an alt character on Light, or Chaos, to join.
This will be the first tournament after Final Fantasy XIV adds Data Centre Travel,
let's see how well it works for us.
And since I need some image I can connect to this tournament, I dug out some bad pun: 来冬 の 麻雀, raito no maajan.
来冬 means next winter.
You know where this is going: Riichi is coming.

As always, this is a player event: it is not affiliated with FFXIV, SquareEnix etc.

## Schedule

**Deadline for Registration**: {{ page.registration_date }}

**Games**: {{ page.start_date }} to {{ page.end_date }}

## Prizes

TBA

{% comment %}
1. 1 Item or Item Set from the [FFXIV Online Store](https://store.finalfantasyxiv.com/ffxivstore){:target="_blank" rel="noopener"} of up to 20 EUR
2. 1 Item or Item Set from the [FFXIV Online Store](https://store.finalfantasyxiv.com/ffxivstore){:target="_blank" rel="noopener"} of up to 15 EUR
3. 1 Item or Item Set from the [FFXIV Online Store](https://store.finalfantasyxiv.com/ffxivstore){:target="_blank" rel="noopener"} of up to 10 EUR
{% endcomment %}

The spreadsheet includes space for private games.
After the finalization of the timetable, feel free to challenge some players for a game to fill the time.
There will be second ranking for those, which also include the scores for games someone subbed in.
{% comment %}
I'm giving an extra prize for the top average score: 1 Item or Item Set from the [FFXIV Online Store](https://store.finalfantasyxiv.com/ffxivstore){:target="_blank" rel="noopener"} of up to 5 EUR.
{% endcomment %}

Note: Prizes can't be received on any trial accounts.

## Sponsors

A big thanks to the sponsors! If you want to sponsor, feel free to send it to [my PayPal](https://paypal.me/0xReki).


## General Information

**How to Register**: {% if page.registration_url %}fill out the
[Registration Form]({{ page.registration_url }}){:target="_blank" rel="noopener"}{% else %}registration closed{% endif %}

**Registered Players, Seating etc.**: {% if page.sheet_url %} see the
[Tournament Spreadsheet]({{ page.sheet_url }}){:target="_blank" rel="noopener"}, times are all UTC (a.k.a. Server Time) {% else %}not available{% endif %}

**Where**: Final Fantasy XIV Online, Data Centre Light, preferably at the Mahjong Tables on Server Odin. Feel free to join the [Mahjong of Light Discord](https://discord.gg/nUSfJ2Q){:target="_blank" rel="noopener"}

## Format

6+ Hanchan Round-Robin'ish.
As before, it depends on how many people attend.

Since I'm trying to accommodate players from all over the globe, the games don't have necessarily to be in one single block each day.
My current plan is to have 2 games per player each day.
Having more slots just helps a lot with not playing the same people each time.

All games will be played in Final Fantasy XIV Online as friendly matches “Full Game Four-player Mahjong (Kuitan Enabled)” on Data Centre Light.
Don't be confused, what Doman Mahjong considers a “Full Game” is just a hanchan, it's *not* an iichan.
After the game, since FFXIV doesn't have logs and spectator mode (yet! Yoshi-P, please add one for us!) the result should be screenshotted and sent to the organizer.

## Rules

I want everyone to have a good time, so please show good sportsmanship.
In case of bad conduct, I will take the liberty to disqualify any offending players.
Should any problems arise, even during the tournament, please don't hesitate to contact me.

### Riichi Rules

Most of these are the result of playing in Final Fantasy XIV Online.

- three red fives (aka ari)
- players **start on 25,000 points** and return 25,000
- placement bonuses are +15/+5/-5/-15
- hanchan **ends** if a player falls **below zero points** (tobi)
- South 4 Round also ends when dealership doesn't pass (agariyame)
- open tanyao is allowed (kuitan ari)
- 13 han and above is a kazoe yakuman
- cumulative single yakuman
- double ron allowed, no head bump
- abortive draws for
  - 9 unique terminals/honours in starting hand (kyuushuu kyuuhai) [^advanced-doman-rules]
  - same wind tile as the first 4 discards (suufonsu renda) [^advanced-doman-rules]
  - 4 kan not from the same person (suukaikan) and [^advanced-doman-rules]
  - triple ron (sancha hou) [^advanced-doman-rules]
- **no abortive draw** for 4 riichi (suucha riichi)
- mangan at draw (nagashi mangan) possible [^special-yaku]

If a player is late by more than ten minutes, they are replaced by a substitute player for the hanchan.

### On Missed Games and Substituted Players

Substitute players are scored normally and then not included in the ranking. The
player missing the hanchan doesn't get any points and will have a 30 points
penalty.

## Final Fantasy XIV Online

All games are being played in [Final Fantasy XIV Online](https://www.finalfantasyxiv.com/).
To play, a trial account is sufficient.
You only need to [unlock the Gold Saucer](https://ffxiv.consolegameswiki.com/wiki/It_Could_Happen_to_You).
Note, if you're not new to Mahjong, it's recommended to change the display from actual dora (setting: doman mahjong) to dora indicator (setting: traditional).
If your character is not on world Odin on Datacenter Light, you can use the [World Visit System](https://eu.finalfantasyxiv.com/lodestone/playguide/contentsguide/worldvisit/) or [Data Center Travel System](https://eu.finalfantasyxiv.com/lodestone/playguide/contentsguide/datacentertravel/) to be on Odin for the tournament.
Your homeworld still has to be on an EU server, though.

<picture>
  <source srcset="{{ '/blog/images/xs/2022-02-doman-mahjong-settings.avif' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/avif">
  <source srcset="{{ '/blog/images/xs/2022-02-doman-mahjong-settings.webp' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/webp">
  <source srcset="{{ '/blog/images/xs/2022-02-doman-mahjong-settings.jpg' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/jpeg">
  <source srcset="{{ '/blog/images/2022-02-doman-mahjong-settings.avif' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/avif">
  <source srcset="{{ '/blog/images/2022-02-doman-mahjong-settings.webp' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/webp">
  <source srcset="{{ '/blog/images/2022-02-doman-mahjong-settings.jpg' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/jpeg">
  <img loading="lazy" class="my-2" src="{{ '/blog/images/2022-02-doman-mahjong-settings.webp' | prepend: site.static_url | absolute_url }}" alt="Doman Mahjong Settings" title="Doman Mahjong Settings">
</picture>

## References

[^advanced-doman-rules]: [Doman Mahjong — Advanced Rules](https://na.finalfantasyxiv.com/lodestone/playguide/contentsguide/goldsaucer/doman-mahjong/special_rule/)
[^special-yaku]: [Doman Mahjong — Special Yaku](https://na.finalfantasyxiv.com/lodestone/playguide/contentsguide/goldsaucer/doman-mahjong/yaku_list/#anchor_005)
