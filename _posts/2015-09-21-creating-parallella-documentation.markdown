---
layout: post
title: "Creating Parallella Documentation"
date: 2015-09-21 11:22:18 -0500
comments: true
categories: [ Education, Parallella ]
---
Technical documentation is always better when it includes screenshots and videos. This article lists some quick ways to create both when working with Parallella.

{% imgcap center /images/elgato_parallella_720.jpg Elgato Game Capture HD60 %}

### Capturing Videos
I tried several software solutions for capturing video. In all cases, they either sputtered or they failed completely. Finally, I found a hardware solution that works: Elgato Game Capture HD60. For roughly $180, you get a smartphone-sized device that sits between the Parallella and the HDMI monitor. HDMI flows from the Parallella, into the Elgato’s HDMI input, out of the Elgato’s HDMI output, and then to the monitor. Anything you see on the screen gets captured by the Elgato Game Capture HD software on your Mac.
<!--more-->
### Scrot for Screenshots
`scrot` is a command line utility for capturing screenshots. The utility comes with Ubuntu by default. If it happens to be missing on your system, you can install `scrot` as follows:

``` bash
$ sudo apt-get install scrot

$

```

`$ scrot - -help` will list the command line options. Here are a few of the frequently use options:

* `$ scrot -d [time in seconds]`. For example, `$ scrot -d 10` will delay taking the screenshot for ten seconds. Use this if you need a few seconds to setup the screen before scrot takes the shot.

*

### scp Secure Copy Program

