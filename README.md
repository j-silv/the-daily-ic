# The Daily ~~Bugle~~ IC

>J. JONAH JAMESON : [about Peter's pictures of Spider-Man] They're crap. Crap, crap, megacrap. I'll give you two hundred bucks for all of 'em.

-Spider-Man (2002)

# Description
A script that checks the internet for integrated circuit (IC) die shots, randomly picks one, then sets the user's desktop background to it. Additionally, an info box pops up which provides some information about the IC. Here is an example output:

![alt text](https://github.com/j-silv/the-daily-ic/blob/master/example_output.png?raw=true)

# Prerequisites
The following utilities are used:

- wget
- grep
- cut
- date
- sort
- head
- tail
- xmessage

# Image sources

### Currently sourcing die images from:
- https://zeptobars.com/en/

# How-To
Simply copy or download the shell script, set it to be executable, then (optionally) add it as an Ubuntu (or other distro) start-up application.

# Modification
Feel free to play around with how the script works. For example, you can change the download location for the IC image, the info message, what sort of background image formatting you'd like, etc. This script was developed for Ubuntu 20.04, but can easily be modified to fit your distro (for example, changing the command that sets the user's background).

# Debugging
The `-xv` option can be added to the standard shebang to help debug script execution:

```#!/bin/bash -xv```

Alternatively, this script can be executed with the `-xv` option:

```bash -xv getdailyic```

# To-Do

### Source other die images from :
- https://siliconpr0n.org/map/
- https://siliconpr0n.org/archive/doku.php?id=collection
- https://micro.magnet.fsu.edu/chipshots/index.html (**licensing issues??**)
- http://www.visual6502.org/ (chip list page is broken...)
- http://diephotos.blogspot.com/
- https://www.cpu-world.com/info/die_pictures.html
- http://www.siliconzoo.org/index.html
- http://www.righto.com/search?q=die+photo
- https://www.reddit.com/r/ReSilicon/
- https://www.instagram.com/evilmonkeyzdesignz/
- https://www.instagram.com/siliconinsider/

# Contributing
Feel free!

# Acknowledgements
- zeptobars.com

