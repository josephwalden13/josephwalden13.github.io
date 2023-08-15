---
layout: page
title: Tweak Installer
permalink: /projects/tweak-installer/
icon: fas fa-code
order: 2
---

> I do not accept responsibility for any damage that may be caused by this tool. Use at your own risk
{: .prompt-danger }

[Github](https://github.com/josephwalden13/tweak-installer)

Tweak Installer is an open source tool, written in C#, to install debian packages to a jailbroken iOS device via SSH. It can be used as an alternative to Cydia / Installer and other package managers but it is not a replacement. When electra11.1.2 was first released no iOS package manager was compatible with iOS 11 so I created this tool to automate the process of installing deb files. 

When copying files which already exist on the device the tool with give you the option to create a backup which can be restored when removing the package. This prevents issues arising from packages overwriting system files.

> More details coming soon
{: .prompt-info }