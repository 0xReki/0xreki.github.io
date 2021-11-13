---
title: Blog Technology 2021

tags:
  - Software Recommendations

redirect_from:
  - /2020/05-22-blog-technology-2020
  - /2020/05/22/blog-technology-2020

image: /blog/images/2021-06-23-gears.jpg
image_alt: Gears (Symbolic Picture)
image_license: CC-0

checker:
  - lt
  - pwa

long: true
audio:
  date: 2021-06-28
---
This is just what I currently use; I tend to replace tools with other tools if they provide me with better user experience.
If you have suggestions, [feel free to reach out](/contact/).

I used to write most of the stuff in Google Docs.
I only did that, so I could use my phone to write when I was on the go.
Writing on the phone is something I've given up on, so now I mostly write on my computer.
<!--more-->

<picture>
  <source srcset="{{ '/blog/images/xs/2021-06-23-gears.avif' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/avif">
  <source srcset="{{ '/blog/images/xs/2021-06-23-gears.webp' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/webp">
  <source srcset="{{ '/blog/images/xs/2021-06-23-gears.jpg' | prepend: site.static_url | absolute_url }}" media="(max-width: 575.96px)" type="image/jpeg">
  <source srcset="{{ '/blog/images/2021-06-23-gears.avif' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/avif">
  <source srcset="{{ '/blog/images/2021-06-23-gears.webp' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/webp">
  <source srcset="{{ '/blog/images/2021-06-23-gears.jpg' | prepend: site.static_url | absolute_url }}" media="(min-width: 576px)" type="image/jpeg">
  <img loading="lazy" class="my-2" src="{{ '/blog/images/2021-06-23-gears.webp' | prepend: site.static_url | absolute_url }}" alt="{{ page.image_alt }}" title="{{ page.image_alt }}">
</picture>

## Visual Studio Code and its Extensions

My editor of choice is Visual Studio Code and use all kinds of extensions.
The one that made the biggest difference this year is [LanguageTool Linter](https://marketplace.visualstudio.com/items?itemName=davidlday.languagetool-linter){:target="_blank" rel="noopener"}.
For all the natural language extensions I've used so far, this is the most configurable one.
If you bother to install a local version of the tool, you can even run it while you are offline.

There's also [VSCode Neovim](https://github.com/asvetliakov/vscode-neovim){:target="_blank" rel="noopener"}.
But VIM is just my personal preference, and I don't like missionaries from either side.
Just use whatever you feel is best for you.

## Jekyll, its Plugins and what my Theme uses

[I like using markdown](https://reki.wtf/blog/2019/12-22-what-i-hate-about-wysiwyg/) and luckily, that's what [Jekyll](https://jekyllrb.com/){:target="_blank" rel="noopener"} takes to build this website.
In the beginning, I used GitHub Pages to build and host, but as the site got bigger and I wanted some more custom code, and more plugins, it quickly fell out of what GitHub Pages supports.
Now I have [Netlify](https://www.netlify.com/){:target="_blank" rel="noopener"} build and host the site, it's more flexible.
I can just push source files and don't need to push rendered files into the repository.

Why did I need more plugins anyway?
When I first I wanted to have automatic linking key terms to the respective glossary and using a regex plugin is the only way to make it efficient.
I tried it without the regex plugin and the pages took like 30 minutes to render.
With the regex plugin it's only 2 minutes.

Over time, I just wanted some more custom code, so I ended up making my own plugins.

Currently, the Jekyll Plugins I use are:

- jekyll-last-modified-at
- jekyll-regex-replace
- jekyll-include-cache
- jekyll-liquify
- [jekyll-criticmarkup](https://gitlab.com/0xReki/jekyll-criticmarkup){:target="_blank" rel="noopener"}
- [jekyll-wns](https://gitlab.com/0xReki/jekyll-wns){:target="_blank" rel="noopener"}

While not technically a Jekyll Plugin, my theme uses [Hagsten/Talkify](https://github.com/Hagsten/Talkify){:target="_blank" rel="noopener"} for the Text-To-Speech function.
I don't use their fancy voices, their free limits are too restrictive.
Instead, I just use the browser provided ones.
Sadly, that means Firefox has the worst selection of Text-to-Speech voices.
It still works, but the AI voices that Edge and Chrome provide are much more superior.

Speaking of my theme, when I preview my site, all of the content is displayed in an editable container.
All that container does is make it possible for [ProWritingAid](https://prowritingaid.com/?afid=9599){:target="_blank" rel="noopener"} to go over the chapter and point out anything it finds.
It still have to edit it in Visual Studio Code, but it's the easiest solution for me.
Plus, this should also work for Grammarly, should you prefer that.

## GitLab

As of last year, I have my code mainly on GitLab.
Why? It has issue branches.
It's a very basic feature, and GitHub just doesn't care about implementing it.
Yes, there's some custom action you can configure to make something like that, but it's clunky — you have to do that for every single repository.
Plus, I'm not comfortable with their freemium model.

## Command-Line Tools

I shouldn't forget to mention [markdowny](https://www.npmjs.com/package/markdowny){:target="_blank" rel="noopener"}.
When I started out I had like 5 lines of front matter in my files.
Since then, I had to add more to do things like navigation, SEO etc.
There were times, where 40 lines of front matter for each file was normal.
Granted I managed to automate them where possible, but it's still 20 lines per files wherever it's needed.
All that would be a real pain to manage and check, if I didn't have a tool that goes with it.
npm keeps screaming its dependencies are outdated, but my node JS is not good enough for me to try and fix that.

For now, I'm not putting out eBooks versions, but I still have my pipeline somewhere.
I use [pandoc](https://pandoc.org/){:target="_blank" rel="noopener"} for creating ePUB versions.
And then, I use [Calibre](https://calibre-ebook.com/){:target="_blank" rel="noopener"} to convert my ePUB to PDF.
In 90% of all cases, this works without further intervention.
In the other 10% of the cases, I just tweak the code until it works.

That's all about the technology that I use with the page.
Next time I think I should tell you about the adventures with getting the chapters out to social media…
I'm still looking for suitable tools.
