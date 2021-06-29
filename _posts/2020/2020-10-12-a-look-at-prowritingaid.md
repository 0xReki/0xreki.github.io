---
title: A Look At ProWritingAid

tags:
  - Creative Writing
  - Grammar Checking
  - Spell Checking
  - Review

image: /blog/images/2020-10-12-prowritingaid-logo.webp

checker:
  - pwa

long: true
---
No, this isn't a mahjong client.
It's not old software, either.
But I do have a third hobby, aside from Riichi Mahjong and Final Fantasy XIV.
And it's Creative Writing.
If you haven't seen it yet, I write a Web Novel called [Crystal Down](/crystaldown/){:target="_blank" ref="noopener"}.
While I do have volunteers and commenters that help me with spelling and grammar, running it through a tool beforehand is just good practice.
Until now, I've been using Grammarly Free, and it leaves a lot of things to be desired…
So much so, I don't even care about their Premium because it doesn't seem to offer anything I need.
<!--more-->

I have a tech background.
That makes me have requirements to software other people might not even consider.
I know can't have everything, but I'm at least allowed to nicely ask, am I not?
Let's start with what I want.
I use Linux as my preferred operating system and [Jekyll](https://jekyllrb.com/){:target="_blank" ref="noopener"} as static site generator.
If there is installable software, Linux support would be very nice.
I've more or less given up on that front, so I can live with just the software running in WINE.

For Jekyll, I write in Markdown, so the software should parse it or at least correctly ignore Markdown.
For plus points, it even ignores the front matter.
That way I can just open my files and edit without needing to copy and paste text to another software and fixing the Markdown.
There's nothing on this front, so this is also just a nice thing to wish for.

I'm writing a Novel, so options for more natural speech and other colloquial styles would be very useful.
So I get the 7-day free trial of [ProWritingAid](https://prowritingaid.com/?afid=9599){:target="_blank" rel="sponsored" ref="noopener"} and start testing it.

![ProWritingAid]({{ "/blog/images/2020-10-12-prowritingaid-logo.webp" | prepend: site.static_url | absolute_url }}){:loading="lazy"}

## A Look at the Technical Matters

First, some technical tests.
The [ProWritingAid Web Editor](https://prowritingaid.com/en/Analysis/WebEditor/Go?afid=9599){:target="_blank" rel="sponsored" ref="noopener"} doesn't have any options to style your text while writing.
It feels somewhat strange after using Grammarly's Web App.
The Apps has a lot of proofing tools and options.
It's always good to see options for other English variants than UK and US.
If you're going to use it, you'd need to put in the styles or Markdown after you're done checking it.
Or just like me, use one of the other ProWritingAid Apps.

Let's continue to [ProWritingAid Desktop App](https://prowritingaid.com/en/App/Desktop?afid=9599){:target="_blank" rel="sponsored" ref="noopener"}.
It caught my eye because it claims to have support for Scrivener projects, Rich Text, Microsoft Word, Open Office, and Markdown documents.
Markdown! That's exactly what I need!
It doesn't have a Linux version, and the Windows version doesn't run in WINE, I tried.
Maybe I'll have more luck with the MacOS version and darling, but that'll have to wait for later.

![ProWritingAid DesktopApp]({{ "/blog/images/2020-10-12-prowritingaid-desktop.webp" | prepend: site.static_url | absolute_url }}){:loading="lazy"}

So for testing, I run it on a Windows machine.
The software looks much like the Web App, but the options are in the native menu bar, making them much easier to access.
There's also a word counter at the native status bar.
They said Markdown so I that's the first thing I load into the software.
I see I can even open a whole folder.
That would make things a lot easier if my dream features work.
Well… it just loads the file as plaintext.
It treats any Markdown it encounters as interpunction and gives me interpunction mistakes.
Sadly, I can't even properly disable that rule.
And it doesn't ignore the front matter!
Just as I get my hopes up, a big letdown…
But those were just nice to have things.

Next, we have [ProWritingAid Chrome Extension](https://prowritingaid.com/en/App/ChromeExtension?afid=9599){:target="_blank" rel="sponsored" ref="noopener"}.
Extensions for other browsers exist, too. But I'm using a chromium-based browser.
And it works! So far with every editable box I had around the extension found it and did its checks.

So I did some workaround for my setup.
I have a local testing environment anyway, so I set it up so the chapter area is editable when I'm in development mode.
And it works! Last time I tried with Grammarly, it didn't even want to look at it.
Yes, I'm still copying the corrections to my editor.
But this is only one-way now. That's an improvement over having to copy it into Google Docs, fixing it up, and copying it back.

All following tests, I did with the extension.

## A Look at the Proofing Options

Let's start with the thing I immediately noticed:
I'm thrilled to see the extension catches all wrong closing and opening quotes.
Yes, smart quotes can be nice.
But they can go horribly wrong, so I prefer manual “curly” quotes.

With term that look similar to existing people and things, it suggests you might have mixed up the spelling.
I didn't know there was a John Wentworth.
And no, the character I made is in no relation to the other guy!
I was just pulling out names from a list of Forenames and Surnames…
Disabling the rules about the mixup adds the name you use to your personal dictionary.
I'd like to add the names of all my characters and terms to that.
But trying to add them manually, the website doesn't let me enter anything with spaces, only single words.

Unlike their competitor, it's nice to see the writing styles changes the suggestions you get for your text.
With hints to encourage “show don't tell”, the `General` style is aimed at Creative Writing.
I'm also thrilled about the option in the `Script` style to disable the suggestions about the use of passive.
They have even more styles I'm not getting into.
[ProWritingAid has a nice blog post about their Writing Styles.](https://prowritingaid.com/art/1294/get-custom-writing-style-suggestions-with-prowritingaid.aspx?afid=9599){:target="_blank" rel="sponsored" ref="noopener"}

While we're at styles, I'd like to request a feature that checks speech with the `Script` style.
I mean it properly detects quotation marks.
I know I'm asking a lot.

## Summary

It didn't give me the Markdown support I hoped for, but it's still good to use for creative writing.
While my dream features will are still far away, I'll be using ProWritingAid for now.
I'm not even through my free trial yet, and I'm already preferring ProWritingAid over Grammarly.
Well, if I have the money for it, that is.
20 bucks is quite a lot of money for someone that writes for a hobby.
