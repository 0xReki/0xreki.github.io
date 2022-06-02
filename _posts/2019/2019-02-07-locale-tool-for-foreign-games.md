---
title: Locale Tool for Foreign Games

tags:
  - Tools
  - Locale
  - Windows

checker: 
  - pwa

long: true
---

I have old Windows games running.
Some games, especially foreign ones, require the correct locale set to be even installed and run.
What's a locale?<!--more-->
It's the localization settings of your computer: lots of things under the hood you usually don't think about.
Whether you use metric or imperial units, what the dimensions of your default printing paper is, where the month is in the short date representation, is it comma or point as decimal separator, or which symbol is used as the directory separator: `\` or `¥`.

Current software should work regardless of the locale settings, but that would require good code.
So software can still show random behaviour if the local is not set as the coder expected.

Problem is, to change your current locale on Windows, you need to reboot any time you change it.
And with Windows currently needing up to 10 minutes to reboot for no apparent reason, I thought there should be a much better solution to this.

After spending some time googling, I found [xupefei/Locale-Emulator](https://github.com/xupefei/Locale-Emulator){:target="_blank" rel="noopener"}<!--_-->.
It's perfect: this tool even remembers what application I installed with what locale.
And even if I need to change it, I can do that in the context menu.
