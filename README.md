
# 👋 Hi There!

My name is Xavier Chanthavong, and I'm a Software Engineer at Atsign.
I have a deep passion for learning, and I'm constantly improving my ability to write effective software.

I'm also a big of fan open-source software and love to use open-source software whenever possible.
I'm truly proud to say that Atsign is an open-source company, and you can check out the platform & tools we are building over at [atsign-foundation](https://github.com/atsign-foundation)!

I'm building an open-source tool called [NoPorts](https://noports.com), you can check out the code [here](https://github.com/atsign-foundation/noports). I use it all the time to do remote development and access my homelab without opening attack surface to my home network.

## 📈 Github Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=xavierchanth&show_icons=true&hide_title=true&hide_border=true&line_height=29&hide=stars&theme=default)
![GitHub Streak](https://streak-stats.demolab.com?user=xavierchanth&hide_border=true)

<!-- Disabled language stats, it's not reflective of my actual work & experience -->
<!-- ![](https://github-readme-stats.vercel.app/api/top-langs?username=xavierchanth&show_icons=true&hide_title=true&layout=compact&hide_border=true&langs_count=8&count_private=true&hide=html,dockerfile&bg_color=00000000) -->


## 🛠️ My Tools

My workflow is primarily keyboard based and [open-source](https://github.com/xavierchanth/dotfiles)!

### Core

[![](https://img.shields.io/badge/Terminal_Emulator-Ghostty-Informational?style=for-the-badge&color=blue&logo=ghostty)](https://ghostty.org)
[![](https://img.shields.io/badge/Multiplexer-tmux-Informational?style=for-the-badge&color=blue&logo=tmux)](https://github.com/tmux/tmux/wiki)
[![](https://img.shields.io/badge/Shell-zsh-Informational?style=for-the-badge&color=blue&logo=zsh)](https://zsh-manual.netlify.app)
[![](https://img.shields.io/badge/Editor-Neovim-Informational?style=for-the-badge&color=blue&logo=neovim)](https://neovim.io)


My core workflow tools are based around zsh and tmux, with neovim as my editor of choice. I've made a number of enhancements which can be found in my configuration, most notably:

- Running tmux server headlessly outside of any Linux sessions so that it can be shared across sessions, and survives session logouts.
- Per-session zsh history in tmux, which is created from main history at the start of a session and gets merged into the main history at the end of a session.
- A whole bunch of keybinds for managing tmux nicer, and mapping of `hyper+<key>` to a bunch of tmux commands in ghostty, (My CAPS key is always bound to escape on tap, hyper on hold).

### Homelab

[![](https://img.shields.io/badge/Cluster-Proxmox-Informational?style=for-the-badge&color=blue&logo=proxmox)](https://www.proxmox.com/en/)
[![](https://img.shields.io/badge/Cluster_Hardware-3x_Beelink_SER5_AMD_5800H_64Gb-Informational?style=for-the-badge&color=blue&logo=proxmox)]([https://www.proxmox.com/en/](https://www.bee-link.com/))  
[![](https://img.shields.io/badge/NFS-TrueNAS-Informational?style=for-the-badge&color=blue&logo=truenas)](https://www.truenas.com)
[![](https://img.shields.io/badge/Router-Gli.Net_Flint_2-Informational?style=for-the-badge&color=blue&logo=openwrt)](https://www.gl-inet.com/products/gl-mt6000/)
![](https://img.shields.io/badge/Standalone-Apple_Mac_Mini_M4-Informational?style=for-the-badge&color=blue&logo=apple)

My homelab runs a three node mini-pc cluster, the Flint 2 manages VLANs and I have a dedicated VLAN for ceph. I use a semi-managed switch with port base VLAN assignment so that I can have a dedicated NIC for ceph on each mini PC, and control the traffic for it independently from the rest of my network. The Mac Mini serves as my access to Mac, as I've given away my Macbook Pro. I was tired of MacOS enshittification, and kanata uses 3rd-party drivers that have to be manually installed, so that meant every MacOS update would break my workflow until I manually update the drivers. VNC from Remmina gets the job done of getting me access to my Mac Mini when I need to do MacOS/iOS development, or SSH if I'm developing non-GUI software. Same kind of story for Windows development, but I tend to use my gaming PC nowadays, Windows performance in Proxmox tends to be super slow, even when throwing a ton of resources at it (well, Windows in general is just slow, it's just slower when virtualized, even with virtio drivers). When I'm away from home, I use NoPorts to get access to everything behind this router. I've used this to reach my homelab in the backseat of a car, and even from the other side of the planet.

### Personal Computer

#### Hardware

[![](https://img.shields.io/badge/Laptop-Framework_13_Ryzen_AI_9-Informational?style=for-the-badge&color=blue&logo=framework)](https://frame.work)
[![](https://img.shields.io/badge/Keyboard-ZSA_Voyager-Informational?style=for-the-badge&color=blue)](https://www.zsa.io/voyager)
[![](https://img.shields.io/badge/Pointer-Apple_Magic_Trackpad-Informational?style=for-the-badge&color=blue&logo=apple)](https://www.apple.com/shop/product/MXKA3AM/A/magic-trackpad-usb%E2%80%91c-black-multi-touch-surface)

A single USB C cable with a cheap "Mag safe" adapter is all it takes to hook my Laptop up to my desk. On my desk lives the ZSA Voyager - a split ortholinear keyboard, with an Apple magic trackpad between each side. When I first got the Voyager, I would spend 20-40 minutes typing on it each morning and afternoon until I got reasonably close to my normal speed. It was worth learning, typing on this thing feels way smoother than a staggered layout, and I touch-type with far less mistakes.

#### Software

[![](https://img.shields.io/badge/OS-Arch-Informational?style=for-the-badge&color=blue&logo=archlinux)](https://wiki.archlinux.org/title/Main_page)
[![](https://img.shields.io/badge/Window_Manager-Sway-Informational?style=for-the-badge&color=blue)](https://swaywm.org/)
[![](https://img.shields.io/badge/Status_Bar-Waybar-Informational?style=for-the-badge&color=blue)](https://github.com/Alexays/Waybar)
[![](https://img.shields.io/badge/Launcher-Wofi-Informational?style=for-the-badge&color=blue)](https://github.com/SimplyCEO/wofi)

Super plain setup, as simple as it gets. Tmux is almost enough to be my OS. Sway is pretty much a launcher for terminal windows, my browser, zoom, spotify, and remmina. My Waybar has three hide-away modules which contain app tray icons, system usage stats, and controls (like wifi, bluetooth, volume).

### Languages & Frameworks

I have used a number of languages and I consider myself proficient at learning language idioms quickly. This list is ordered by current proficiency (last updated 2025-06-26):

| Language | Framework(s) |
| - | - |
| ![](https://img.shields.io/badge/Dart-Informational?style=for-the-badge&color=gray&logoColor=white&logo=dart) | ![](https://img.shields.io/badge/Flutter-Informational?style=for-the-badge&color=gray&logoColor=white&logo=flutter) |
| ![](https://img.shields.io/badge/Shell-Informational?style=for-the-badge&color=gray) | ![](https://img.shields.io/badge/Bash-Informational?style=for-the-badge&color=gray&logoColor=white&logo=gnubash) ![](https://img.shields.io/badge/Zsh-Informational?style=for-the-badge&color=gray&logoColor=white&logo=zsh) ![](https://img.shields.io/badge/POSIX-Informational?style=for-the-badge&color=gray) |
| ![](https://img.shields.io/badge/Lua-Informational?style=for-the-badge&color=gray&logoColor=white&logo=lua) | |
| ![](https://img.shields.io/badge/C99-Informational?style=for-the-badge&color=gray&logoColor=white&logo=c) | |
| ![](https://img.shields.io/badge/Go-Informational?style=for-the-badge&color=gray&logoColor=white&logo=go) | ![](https://img.shields.io/badge/Wish-Informational?style=for-the-badge&color=gray) ![](https://img.shields.io/badge/BubbleTea-Informational?style=for-the-badge&color=gray) |
| ![](https://img.shields.io/badge/Python-Informational?style=for-the-badge&color=gray&logoColor=white&logo=python) | |
| ![](https://img.shields.io/badge/JavaScript-Informational?style=for-the-badge&color=gray&logoColor=white&logo=node.js) | ![](https://img.shields.io/badge/React-Informational?style=for-the-badge&color=gray&logoColor=white&logo=react) ![](https://img.shields.io/badge/Svelte-Informational?style=for-the-badge&color=gray&logoColor=white&logo=svelte) |
| ![](https://img.shields.io/badge/C++-Informational?style=for-the-badge&color=gray&logoColor=white&logo=cplusplus) | |
| ![](https://img.shields.io/badge/C%23-Informational?style=for-the-badge&color=gray) | |
| ![](https://img.shields.io/badge/Java-Informational?style=for-the-badge&color=gray) | |
| ![](https://img.shields.io/badge/Zig-Informational?style=for-the-badge&color=gray&logoColor=white&logo=zig) | |
| ![](https://img.shields.io/badge/Rust-Informational?style=for-the-badge&color=gray&logoColor=white&logo=rust) | |
| ![](https://img.shields.io/badge/Kotlin-Informational?style=for-the-badge&color=gray&logoColor=white&logo=kotlin) | |
