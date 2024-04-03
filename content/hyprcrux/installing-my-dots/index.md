---
title: "How To Install My Hyprland Dotfiles"
date: 2024-04-02
draft: false
description: "A concise guide on installing my hyprland dotfiles."
tags: ["Hyprland", "Arch"]
---
<h2> This is a step by step guide on using<br> my dotfiles for Arch Linux/Hyprland</h2>

{{< github repo="xsghetti/dotfiles" >}}

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