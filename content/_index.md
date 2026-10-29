+++
title = "~/arkovyx"
description = "Personal website of arkovyx"
insert_anchor_links = "left"
+++

<style>
    @font-face{
        font-family: "NType82 Mono";
        src: url("fonts/nothingfont/fonts/NType82-Headline.otf") format("opentype");
        font-weight: 900;
        forn-style: normal;
        font-display: swap;
    }

    h1:is(#whoami, #projects, #home) {
        font-family: "NType82 Mono", monospace;
        <!-- letter-spacing: 0.2em; -->
    }

    .crt {
        width: 100% !important;
        max-width: 100% !important;
      }

    .crt pre,
    .crt code {
        width: 100% !important;
    }

      pre mark {
        display: block;
        color: currentcolor;
    }

    pre table td:nth-of-type(1) {
        color: #6b6b6b;
        font-style: italic;
    }
</style>

# ./home

<blockquote>
    <p>IF it works, leave it alone; IF you are me, touch it anyway.</p>
    <footer>— <cite>me</cite></footer>
</blockquote>

{% crt() %}
```
[me@arkovyx ~]$ af
                 _                          USER     me@arkovyx
   __ _ _ __ ___| |__                     󱑢  UPTIME   22 hours, 44 minutes
  / _` | '__/ __| '_ \                    󰥔  TIME     09:49 PM
 | (_| | | | (__| | | |                     OS       Arch Linux
  \__,_|_|  \___|_| |_|                     KERNEL   Linux 7.2.11-arch1-1
  _ _                                     󰮯  PACKAGES 1040
 | (_)_ __  _   ___  __                     TERMINAL foot
 | | | '_ \| | | \ \/ /                     SHELL    zsh
 | | | | | | |_| |>  <                    󰍛  MEMORY   ! 404
 |_|_|_| |_|\__,_/_/\_\                     DISK     ! 404

  ═══════════════════════════════════════════
  ░▒▓█ archlinux █▓▒░
[me@arkovyx ~]$
```
{% end %}

# ./whoami

I am **Junaid**. I go by **arkovyx** online. I am a high school student who got into programming by messing around. I spend most of my time learning Python and exploring Linux deeply. I use Arch Linux (btw) with Hyprland.

Most of my free time goes into the terminal. I read more documentation than fiction. After a small interval of time, i take my setup apart and put it together a little differently. It's not a productive thing - It's just what i do when I'm bored.

- Blog → [```  ```](/blog)
- Nanolog → [```  ```](/nanolog)
- Dotfiles → [``` 󰉋 ```](https://github.com/arkovyx/dotfiles)

---

{% crt() %}
```
[ark@homelab ~/software_stack]$ tree

.
├── [ CORE SYSTEMS ]
│   ├── OS (Desktop) ➜ Arch Linux (btw)
│   ├── OS (Mobile)  ➜ HyperOS 3
│   ├── WM           ➜ Hyprland
│   └── Terminal     ➜ Foot
├── [ PRODUCTIVITY ]
│   ├── Editor       ➜ Neovim
│   ├── Notes        ➜ Obsidian
│   ├── Browser      ➜ Librewolf
│   └── File Manager ➜ lf
└── [ MULTIMEDIA ]
    ├── Video        ➜ MPV
    ├── Music        ➜ Ncmpcpp / Rmptui
    ├── Images       ➜ Nsxiv
    └── Theming      ➜ pywal16

3 directories, 12 files
[ark@homelab ~]$ █
```
{% end %}

---

# ./projects

- [KEYLOCITY](https://arkovyx.github.io/keylocity/): A minimalist typing test with real-time keylocity and accuracy tracking.
- [ARK - II](https://github.com/arkovyx/ark-ii/): A Developer AI Assistant built for Arch Linux.
- [TZEUK](https://github.com/arkovyx/tzeuk/): Custom shell built on Quickshell for arch + hyprland setup.
