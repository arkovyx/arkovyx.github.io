+++
title = "~/arkovyx"
description = "Personal website of arkovyx"
insert_anchor_links = "left"
[extra]
no_header = true
+++

<!-- ========== IMAGE WITH CRT EFFECT ========== -->
<div id="logo-wrapper" class="crt">
  <pre>
    <img id="logo" class="transparent no-hover" src="1.jpg" alt="arkovyx logo">
  </pre>
</div>

<style>
  /* ============================================================
     IMAGE CRT EFFECT – ROUNDED, STATIC, NO HOVER INTERACTION
     ============================================================ */

  /* Wrapper – clips scanlines to rounded shape */
  #logo-wrapper.crt {
    display: inline-block;
    border-radius: 12px;
    overflow: hidden;
    background: transparent !important;
    border: none !important;
  }

  /* Pre inside wrapper – clean, no extra styles */
  #logo-wrapper.crt pre {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px;
    margin: 0;
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
  }

  /* The image itself */
  #logo {
    width: 100%;
    max-width: 100%;
    height: auto;
    display: block;
    border-radius: 12px;
    filter: brightness(0.9) contrast(1.1) saturate(1.2);
    box-shadow: 0 0 30px rgba(201, 169, 110, 0.3), 0 0 60px rgba(201, 169, 110, 0.1);
    image-rendering: pixelated;
    border: 2px solid rgba(201, 169, 110, 0.4);
    transform: none !important;
    transition: none !important;
    cursor: default !important;
  }

  /* Kill ALL hover effects – brightness, shadow, scale, everything */
  #logo.no-hover,
  #logo.no-hover:hover {
    filter: brightness(0.9) contrast(1.1) saturate(1.2) !important;
    box-shadow: 0 0 30px rgba(201, 169, 110, 0.3), 0 0 60px rgba(201, 169, 110, 0.1) !important;
    transform: none !important;
    transition: none !important;
    opacity: 1 !important;
    cursor: default !important;
    background-color: transparent !important;
    mix-blend-mode: normal !important;
    border-radius: 12px !important;
    -webkit-filter: brightness(0.9) contrast(1.1) saturate(1.2) !important;
  }

  /* Wrapper hover – kill anything from theme */
  #logo-wrapper:hover {
    transform: none !important;
    opacity: 1 !important;
  }

  /* ============================================================
     SOFTWARE STACK CRT – UNTOUCHED, KEEP AS IS
     ============================================================ */

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

<!-- ============================================================
     WHOAMI SECTION
     ============================================================ -->

# ./whoami

I am **Junaid**. I go by **arkovyx** online. I am a high school student who got into programming by messing around. I spend most of my time learning Python and exploring Linux deeply. I use Arch Linux (btw) with Hyprland.

> - You can read my blogs [here](/blog).
> - You can read my nanologs [here](/nanolog).
> - My **dotfiles** are available on this [git repo](https://github.com/arkovyx/dotfiles).

---

<!-- ============================================================
     SOFTWARE STACK (CRT MACRO) – GREEN HACKER EFFECT
     ============================================================ -->

{% crt() %}
[ark@homelab ~]$ cat software_stack.txt

[ CORE SYSTEMS ]
OS (Desktop)  ➜  Arch Linux (btw)
OS (Mobile)   ➜  HyperOS 3
WM            ➜  Hyprland
Terminal      ➜  Foot

[ PRODUCTIVITY ]
Editor        ➜  Neovim
Notes         ➜  Obsidian
Browser       ➜  Librewolf
File Manager  ➜  lf

[ MULTIMEDIA ]
Video         ➜  MPV
Music         ➜  Ncmpcpp / Rmptui
Images        ➜  Nsxiv
Theming       ➜  pywal16
{% end %}

---

<!-- ============================================================
     PROJECTS
     ============================================================ -->

# ./projects

- [KEYLOCITY](https://arkovyx.github.io/keylocity/): A minimalist typing test with real-time keylocity and accuracy tracking.
