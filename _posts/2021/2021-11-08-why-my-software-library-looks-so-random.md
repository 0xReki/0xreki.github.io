---
title: Why my Software Library Looks so Random

tags:
  - Software Recommendations

checker:
  - lt

redirect_from: 
  - /blog/2020/06-06-why-my-software-library-looks-so-random/
  - https://0xreki.de/blog/2020/06-06-why-my-software-library-looks-so-random/

long: true
seo_title_fix: 1
seo_meta_fix: 3

image: /blog/images/2021-11-08-cds.jpg
image_alt: CDs (Symbolic Image)

image_license: Image from pxfuel
image_license_url: https://www.pxfuel.com/en/free-photo-oxgaq
---
People seem to be confused by the software I use — it seems so random.
I have made both good and bad experiences with both closed source and open source software.
To me, practicability is the most important thing to when using software.
So I stick with whatever works best for me.
Also, do remember: this is what works for me.
It doesn't have to work for you.

Isn't that how everyone uses their computer?
<!--more-->

## Operating System

While I prefer Linux to Windows, the recent trend of Microsoft of shipping buggy patches to their Home customers really undermines the image of stability they have been trying to build.
The more problems their feature updates bring, the more inclined I get to move my systems to Linux.
But Linux is not the solution to all my issues.
And it's still not in state to be used for everyone on desktop.
Reasons?
I blame the elitists.

Sure, with web apps, I don't even need native clients for much.
But what if I need some software that doesn't have native Linux clients or web apps?
Well, I use WINE and/or Proton.
That seems to piss off the elitists.
Even just using Steam on Linux seems to piss them off.
“It doesn't count!” or “Make something native yourself!” are things you commonly hear.
Not everyone has the knowledge or time to make something themselves.
If I find something, I'm happy to use it and try to help improve it, but practicability is still more important.

## Games

And for games… well, alternatives are of no interest me, when I want to play with my friends.
Games that run on Linux… well that's a topic for a different video, I mean blog post.
Focus Reki, you're not making YouTube videos… yet.

## Office Stuff

I used to prefer the Microsoft Office Suite over LibreOffice.
But then, Microsoft went the Software-as-a-Service route.
With how often I need to write a document, just having any office suite installed on my computer doesn't make sense.
Sure, I might need a word processor maybe once every two years… and a spreadsheet calculation software like three times a year.

Luckily, I have a friend who hosts a private OnlyOffice instance.
What's OnlyOffice?
Think Google Docs in open source.
Well, I actually use Google Docs, too.
I mean, those spreadsheets I talked about are public!

What about presentations?
I prefer HTML5 slides.

## Audio mixing

Let's talk about audio software next
Some people claim you definitely need a Mac for that.
I strongly disagree.
Sure, Mac was the best for that at some point, but now, the actual audio interface and microphone and knowledge are more important than what base system you use.
And Audacity is great for simple tasks, but if you require more it doesn't quite cut it.
And if Audacity is enough for your needs, you don't need to buy a Mac for it.
I mean, if you prefer Mac, that's your choice that's fine, just don't buy a Mac just to run Audacity.

Ardour might be a real Digital Audio Workstation on Linux, but setting it up and using it is a real pain.
So some years ago, I decided to buy a [REAPER](https://www.reaper.fm){:target="_blank" rel="noopener"} license, and I'm happy I paid for that.
And it runs perfectly fine in Linux with WINE, or natively even supporting Jack Audio Server.

Why consider running REAPER in WINE at all when you can run it natively?
For running VST plugins, of course!
Some VST plugins might have a Linux version, but usually, they don't.
I wanted to write how bad the situation is etc., but it just happens the very first plugin I tried, [Auburn Sounds's Grallion 2](https://www.auburnsounds.com/products/Graillon.html){:target="_blank" rel="noopener"}, had Linux versions in the download.
Granted, REAPER's built-in plugins are good enough, I rarely had the need for plugins anyway, so I don't often look for them.

## Code Editor

I use Visual Studio Code with [VSCode Neovim](https://marketplace.visualstudio.com/items?itemName=asvetliakov.vscode-neovim){:target="_blank" rel="noopener"} extension.
In my opinion, this is the best combination for people that use vim keybindings:
this is the only option I have seen with proper support for undo.
All alternatives I've tried to date, typically set you back half an hour or more if you try to use undo.
And even redo works!

For creative writing, I use the extension [LanguageTool Linter](https://marketplace.visualstudio.com/items?itemName=davidlday.languagetool-linter){:target="_blank" rel="noopener"}, [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint){:target="_blank" rel="noopener"} and [Markdown Fiction Writer](https://marketplace.visualstudio.com/items?itemName=vsc-zoctarine.markdown-fiction-writer){:target="_blank" rel="noopener"}.
I would use [CriticMarkup for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=jloow.vscode-criticmarkup){:target="_blank" rel="noopener"}, but I still have to find collaborators willing to learn Markdown and CriticMarkup.

If you have suggestions or software recommendations, share it in the comments below.
