---
title: "Neovim?!"
date: 2024-04-06
draft: false
description: "wtf is neovim?!"
tags: ["neovim", "nvim", "IDE"]
---
 So I've finally been persuaded to try out NeoVim, and man am I not disapponited.


 My mate and the developer of *Extremely Elaborate Elegant Calendar* or [EEEC](https://github.com/eeec-cal/eeec) shot me over his config the other day, and within
 minutes I was already sold on neovim. Without knowing much about IDE's I naturally started with VSCode, as it was already preconfigured and plugins were easy to install.

 If you're not familair with [Neovim](https://github.com/neovim/neovim), it is an extremely powerful fork of Vim aimed to simplify maintenance and encourange contributions as well as 
 maximize the extensibility.

 *TLDR*: It's a sick terminal based text editor.

 So after playing around with this new neovim config for a bit, I knew I had to get started on my **own** config.
 There are multiple different ways to install plugins with Neovim, which made it a little challenging to figure out where I wanted to start.

 I started out with [LazyVim](http://www.lazyvim.org/), as I've seen a lot about it before even starting my journey with neovim. It's a very easy install that gives you a base plugins list
 to immediately improve your neovim experience, including a theme. 

 While LazyVim is great for someone just getting started with neovim, I felt it added a little too many plugins a little too
 quickly.


## *Queue lazy.nvim*

So, it took me about 6 hours of deleting my config, and restarting to realize that LazyVim and [lazy.nvim](https://github.com/folke/lazy.nvim) were two very similar, but also
two very different things. For some clarity, LazyVim is a preconfigured neovim setup utilizing the Lazy.nvim package manager.

Once I successfully installed lazy.nvim on a barebones neovim config, I finally felt like I was making some progress.
