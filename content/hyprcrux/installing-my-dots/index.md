---
title: "How To Install My Hyprland Dotfiles"
date: 2024-04-02
draft: false
description: "A concise guide on installing my hyprland dotfiles."
tags: ["Hyprland", "Arch"]
---
<h2> This is a step by step guide on using<br> my dotfiles for Arch Linux/Hyprland</h2>
{{< github repo="xsghetti/dotfiles" >}}

### Why *HyprCrux* you ask?
Well, to keep it as simple as possible if you're not familiar with the term...<br><br>
**Crux** <br>
*/krəks/*<br>
*noun <br>
a particular point of difficulty.
plural noun: cruces; plural noun: cruxes.*

I chose this name for my [Hyprland](https://hyprland.org) configuration because I have always found this realm of technology extremely difficult. As an avid rock climber, the term crux is used for the toughest move or sequence of moves on a climb. As an aspiring developer, I felt the term *Crux* fit in here as well!    

I switched to Linux full time rougly 3 months ago after tinkering for a few months on VM's and using my laptop as a test machine, and finally installing Arch Linux on my PC. I have been fascinated with [r/unixporn](https://reddit.com/r/unixporn/) for quite some time now, and after doing very *minimal* research I saw hyprland and knew I had to get my hands on that software.  




{{< alert >}}
**Warning!** My configs are messy and may not work for you!
{{< /alert >}}


{{< timeline >}}

{{< timelineItem icon="github" header="Clone It!" badge="Step One" subheader="Clone my repository here:" >}}
<ul>
<code>git clone https://github.com/xsghetti/dotfiles</code>
<br>
{{< /timelineItem >}}

{{< timelineItem icon="code" header="Run These Commands" badge="Step Two" >}}
<code>cd ~/dotfiles</code>
<br>
<code>cp -r ~/dotfiles/.config/* ~/.config</code>

{{< /timelineItem >}}


{{< /timeline >}}