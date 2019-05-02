---
title: Dev box setup
date: '2019-01-31T15:30:00'
---

After any fresh OS installation, you'll spend some time resetting preferences, installing your applications, etc.
These are some scripts that'll automate some of that work.

I use my own fork of Microsoft's [dev box scripts](https://github.com/Microsoft/windows-dev-box-setup-scripts).
You can find mine [here on Github](https://github.com/danbosscher/windows-dev-box-setup-scripts).

They're using two popular open source projects, [Boxstarter](http://boxstarter.org) and [Chocolatey](http://chocolatey.org).

It'll automatically install Chocolately, install your preferred software, and set a few personal preferences.
Please ensure to read through the 'home.ps1' or 'work.ps1' Powershell scripts before running them, as it'll detail what's getting installed.
