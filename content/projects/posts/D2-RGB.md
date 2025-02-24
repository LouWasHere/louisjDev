+++
title = "Destiny 2 RGB Sync"
date = "2025-02-24"
author = "Louis"
description = "I wanted to sync my computer's RGB system to my equipped subclass in Destiny 2 using [Bungie](bungie.net)'s API. The repository as well as compiled releases for this project can be found [here](https://github.com/LouWasHere/D2-RGB-Tool)."
+++

### D2RGB (Destiny 2 RGB Sync)
- This was a project I worked on in my spare time whilst on my Placement Year. I wanted to sync my computer's RGB system to my equipped subclass in Destiny 2 using [Bungie](bungie.net)'s API. 

- The original plan was to use my motherboard's RGB drivers but after finding out Gigabyte haven't bothered to document or update their software I decided to use [OpenRGB](openrgb.org) and their local server API that can hook into Python.

- The project was good practice at untangling APIs and making the right requests as well as managing when I query and indexing complex data structures (thanks, Bungie).

- I then compiled the project with PyInstaller for distribution (to anyone who uses OpenRGB at least...)

The repository as well as compiled releases for this project can be found [here](https://github.com/LouWasHere/D2-RGB-Tool).