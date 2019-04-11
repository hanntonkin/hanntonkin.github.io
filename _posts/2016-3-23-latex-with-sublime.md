---
layout: post
title: "Latex with Sublime in Mac"
location: Seoul, Korea
excerpt: Simple guide on edit/build latex with sublime.
update_date: 2016-3-23
redirect_from: /2016/3/23/latex-with-sublime/
readlater: true
tags:
- Latex
- Mac
- HOWTO
thumbnail_path: blog/Sublime_Text.png
---

LaTex is a popular markup language for writing scientific documents. Sublime Text is a simple, yet, powerful text editor which I love. In this note, I share my setup for using Latex with Sublime Text.

**Installation**

* Install [MacTeX](https://tug.org/mactex/).
* Install [Sublime Text](http://www.sublimetext.com/3).
* Install [Package Control](https://packagecontrol.io/installation) in Sublime.
* Install [LaTeX TOOLS]() using Package Control:
1) "Command+Shift+P" to open Command Pallet
2) Type "Install package" and find "LaTeX Tools".


* Install Inverse Search with [Skim pdf viewer](http://skim-app.sourceforge.net). In Skim > Preferences > Sync:
1) Uncheck "Check for file changes"
2) Preset to "Sublime text" (/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl for ST3)

* Separate temporary files: set "output_directory" option with the value <<cache>>

