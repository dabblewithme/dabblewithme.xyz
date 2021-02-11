---
title: "Some issues with my BigTreeTech TFT35 E3 v3.0 touch display"
date: 2021-02-11T12:56:02+02:00
slug: "some-issues-with-my-bigtreetech-tft35-e3-v30-touch-display"
description: "Well here it comes. Some list of issues that I have at the moment with my TFT35 E3 v3.0 touch display. I will update this post or make a new post if I get some of them fixed."
keywords: ["3D printer", "BigTreeTech", "TFT35"]
draft: false
tags: ["3D printer", "BigTreeTech", "TFT35"]
math: false
toc: true
---

Well here it comes. Some list of issues that I have at the moment with my TFT35 E3 v3.0 touch display. I will update this post or make a new post if I get some of them fixed.

## M600 / Filament change

I tried multicolor printing with filament change middle of the print. I used PrusaSlicer to do M600 (filament change) command on specific layer. It worked just fine with the stock display that my Ender 3 Pro had.

Problem was that I got the filament changed but when tried to continue the print it gives prompt with OK on it and it just purges more filamant. Messing with scroll wheel button and touch screen did something and I got the print to continue but the filament was pulled away from the nozzle when trying to continue the print.

It should give more useful selections. The problem exists on the touch mode. I have not yet tried the Marlin emulator.

## Octoprint lag

Other problem is with Octoprint. It somehow is lagging the printer when using Octoprint and touch mode. There might be solution to mess with Marlin and SERIAL_PORT settings. I have not yet tried that.

At this time I'm printing through USB stick and touch mode. 

## Random mentions

BabyStepping works ok with the touch mode but it could be a bit clearer. I misunderstood the display and got a bit too low and scratched my bed. After that I used the Marlin mode to do my babystepping.

Changing to Marlin mode would probably fix my issues but main reason why I got the display was the touch mode and "pretty" UI. 

Also I need to try newer firmware. At this time I have couple of weeks old firmware inside it.

**If you happen to have any tips/tricks, please let me know!**