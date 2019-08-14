---
layout: post
title: Hate the 3D, glass dock of Mac OS - this one liner will solve that for you.
date: '2012-04-03T16:01:00-04:00'
tags:
- macos
- lion
- dock
- apple
- macosx
- snowleopard
- tweaks
- leopard
tumblr_url: https://b.sricola.com/post/20432326807/hate-the-3d-glass-dock-of-mac-os-this-one-liner
---
Would you rather look at this …&nbsp;

![2D Mac OS Dock](http://f.cl.ly/items/1N2g0g1j0l3v3d3G3c0E/Screen%20Shot%202012-04-03%20at%206.56.01%20PM.png)

or …&nbsp;

![3D Dock](http://f.cl.ly/items/1G0F3i2Y0S1D3Q3J0I3W/Screen%20Shot%202012-04-03%20at%206.56.51%20PM.png)

when it comes to looking at your dock?&nbsp;

If you are anything like me, you probably hate the 3Dimensional, glossy dock that Mac OS ships with. Fortunately, the former version is still available using this one liner.

Open Applications-\>Terminal.app and paste in this line, and hit enter.

`defaults write com.apple.dock no-glass -boolean YES; killall Dock`

To revert back to the ugly 3Dimented, glossy dock, merely paste the following line, followed by, you guessed it, enter

`defaults write com.apple.dock no-glass -boolean NO; killall Dock`

