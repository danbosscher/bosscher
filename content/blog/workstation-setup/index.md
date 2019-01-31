---
title: Workstation setup
date: '2019-01-30T15:30:00'
---

After any fresh OS installation, you'll spend some time resetting preferences, installing your applications, etc.
These are some scripts that'll automate some of that work. They're using two popular open source projects.
- [Boxstarter](http://boxstarter.org)
- [Chocolatey](http://chocolatey.org)

On a new installation of Windows 10, I use my own fork of Microsoft's [dev box scripts](https://github.com/Microsoft/windows-dev-box-setup-scripts).
You can find mine [here on Github](https://github.com/danbosscher/windows-dev-box-setup-scripts).

It'll automatically install [Chocolately](https://chocolatey.org), download and installs your preferred packages, and set a few personal preferences.
Please ensure to read through the Powershell scripts before running them, as it'll detail what's getting installed.