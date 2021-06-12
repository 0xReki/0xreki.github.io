---
title: Blog Technology 2020

tags:
  - Software Recommendations

checker:
  - pwa

long: true
---
This is just my current situation.
I tend to replace tools with other tools if they provide me with better user experience.
If you have a suggestions, feel free to reach out.

Most of the stuff I currently write in Google Docs.
That way I can use my phone to write if I'm on the go.
In any case, I have Grammarly set up to catch most errors, though that doesn't always work.
Sometimes it even adds errors! (BTW: Thanks to all the readers that point out errors.)
<!--more-->

[I like using markdown](https://0xreki.de/2019/12-22-what-i-hate-about-wysiwyg/).
In early 2019, I used to use a markdown editor on my mobile with Google Drive but that setup kept losing edits.
Also, Google Drive insisted on renaming my files when it detected certain content which broke the system…

Then, I tried writing on Grammarly itself but that felt too clunky when forcing to their site to cooperate with my mobile.
Losing internet connection also meant lost progress.
Guess when I'm the most productive.
I've also tried editing directly in GitLab.
And even using a Grammarly extension in Visual Studio Code.
The latter work if you manually edit the default configuration as the extension is geared towards technical language.

After I'm done with writing I copy it over to my GitLab repository which I use with Visual Studio Code.
To help me with organizing I add metadata as YAML frontmatter and have it rendered and hosted by Netlify.
To improve performance I let Cloudflare take care of it.
All those things are on free accounts.

I used to have GitHub Pages render and host the page but unfortunately GitHub Pages is very restrictive with the plugins that you can use at all.
I wanted to have autolinking to the glossary and using a regex plugin is the only way to make it efficient.
I tried it without the regex plugin.
And the pages took like 30 minutes to render.
With the regex plugin it's only 2 minutes.

Another reason is there's no real 3xx redirects on GitHub Pages only meta redirects which make the page quite inaccessible to search engines.
Netlify lets me use plugins.
At the same time, I changed to GitLab because it has issue branches.
It's a very basic feature and GitHub just doesn't care about implementing it.

That's all about the technology that I use with the page.
Next time I think I should tell you about the adventures with getting the chapters out to social media…
I'm still looking for suitable tools.
