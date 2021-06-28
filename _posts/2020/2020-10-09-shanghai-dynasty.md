---
title: "Good Game: “Shanghai: Dynasty”"

tags:
  - Games
  - Riichi Mahjong
  - Chinese Mahjong
  - American Mahjong
  - WINE Is Not an Emulator
  - Good Game

image: /blog/images/2020-10-09-title-screen.webp

checker:
  - pwa
  - lt

long: true
---
I have written about old software before.
I have written about Mahjong before.
But I haven't done both at the same time!
Let's talk about “Shanghai: Dynasty”.
<!--more-->

![Shanghai: Dynasty Title Screen]({{ "/blog/images/2020-10-09-title-screen.webp" | prepend: site.static_url | absolute_url }})

Shanghai: Dynasty was written by Quicksilver Software.
It was published by Activision in 1997 for Windows 95 and macOS 7.
Sadly, it errors out on current Windows.
So I've tried VM with Windows 98 and XP before, and the game still crashes the audio in the VM.
But I know it runs flawlessly on Linux using WINE!

The game uses red book audio for its soundtrack, so better have a real CD drive.
Or use a proper image with proper tools.
Anyway, we need on Linux we need `libcdparanoia` (and its 32-bit equivalent) for this to work.
This also lets the game do its CD check.
Even though the game is only checking for something the label DYNASTY.
It can also be a partition.
If you're using an ISO like I do, I mean who has optical drives these days, you have to point the d:: link to the ISO for this to work.
Also, the internet archive has [Shanghai: Dynasty for Download](https://archive.org/details/shanghai-dynasty), including soundtrack.

Depending on your OS, you might run into some DLL install error.
Just ignore that and click OK, it just means you run it on something not Windows 95 and have a newer version of it already.

I also apply the [Shanghai: Dynasty Patch 1.21](https://www.patches-scrolls.de/patch/3667/7/30672) to the base game.
Why? The patch adds Riichi Mahjong to the game!

After starting the game itself, we're greeted by a now tiny 640x480 window.
There's no option for resizing the window.
We have 4 options to choose from: Shanghai, Kids, Mahjong and Multiplayer.

Multiplayer sounds nice, doesn't it?
But its servers are long gone, and the client uses Java 1.1.
That's 16-bit software and therefore won't even run on newer 64-bit Windows.

Shanghai and Kids is the typical Mahjong Solitaire Game with lots of options: shapes, tile sets etc.
Kids just gives you a friend kid voice to help you with playing.
Shanghai just gives you annoying beeps whenever you do a mistake.

But we're here for the real Mahjong! Shanghai: Dynasty has 3 types: Chinese, Western and Japanese.
I know nothing about Chinese Mahjong and American Mahjong, so I can't tell you anything about how well the Chinese and Western option emulate how people actually play.
But the game gives you a lot of options.
Let's dive into Japanese Mahjong!

In 1997, 640x480 was a standard everyone had. So you don't have much of screen real estate to work with.
So the dora indicators are all in the centre.
Riichi sticks go on the discards.

The default settings on the game are… not so good.
The buttons have 3 options: Chinese, Western and Japanese.
So the default is Chinese: pung, kong and chow.
Setting it to English make the buttons say: trip for triple, quad and sequ for sequence.
Of course, setting it to Japanese makes them say: pon, kan and chi.
Turning off western numbers also make haku blank again.
Now we feel right at home. It somewhat reminds me of ron2.

Setting the label doesn't change the voices.
The players get a random voice which could be Chinese, Japanese or English.
The English calls are definitely… unfamiliar.
One of the voices wins by saying, “I'm out.”

Yes, Riichi Mahjong feels every tacked on. Granted, it is. It was added in a patch.
Whenever you get uradora, you can only see them mark gold in the hand.
You won't see the uradora indicators.

![Winning with 2 Dora]({{ "/blog/images/2020-10-09-whats-my-ura-1.webp" | prepend: site.static_url | absolute_url }})

![You see 1 dora indicator, but no ura indicator]({{ "/blog/images/2020-10-09-whats-my-ura-2.webp" | prepend: site.static_url | absolute_url }})

But then there are… the bugs? Misinterpretation of the rules?
The more you play, the more you notice them.
Like you can kan after you call, you shouldn't be able to do that.

Just when I was about to finish up my screenshot collection for this post, I stumbled across something else: a wild 4 Winds Abortion appears where it shouldn't.

![A Wild Suufon Appears!]({{ "/blog/images/2020-10-09-a-wild-suufon-appears.webp" | prepend: site.static_url | absolute_url }})

I like the sound and visual effects of the calls.
I think it's one of the reasons I like revisiting this software.
Calling manzu gives you rattling through paper money.
Calling pinzu gives you some balls floating around.
Calling souzu gives you growing bamboo.
Calling dragons gives you… dragons.
And calling winds gives you… wind.
Very hard to describe in words.

Yes, it's the animations they used for Mahjong Solitaire, but it gives this software its special flair.
Maybe it's just my nostalgia.
After all, this was my entry drug into the world of Mahjong.
