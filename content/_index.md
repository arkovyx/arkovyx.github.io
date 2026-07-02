+++
title = "~/arkovyx"
description = "Personal website of arkovyx"
insert_anchor_links = "left"
[extra]
no_header = true
+++

<img id="logo" class="transparent" src="image.jpg" alt="arkovyx logo">

<style>
  #logo {
    width: min(calc(var(--content-width) / 2), 100%);
    border-radius: 50%;
    filter: brightness(0.9) contrast(1.1) saturate(1.2);
    box-shadow: 0 0 30px rgba(201, 169, 110, 0.3), 0 0 60px rgba(201, 169, 110, 0.1);
    transition: all 0.5s ease;
  }

  #logo:hover {
    transform: scale(1.05);
    filter: brightness(1.1) contrast(1.15) saturate(1.3);
    box-shadow: 0 0 40px rgba(201, 169, 110, 0.5), 0 0 80px rgba(201, 169, 110, 0.2);
  }

  .crt {
    width: 100% !important;
    max-width: 100% !important;
  }

  .crt pre, .crt code {
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

---

# ./whoami

I am **Junaid**. I go by **arkovyx** online. I am a high school student who got into programming by messing around. I spend most of my time learning Python and exploring Linux deeply. I use Arch Linux (btw) with Hyprland.

>- You can read my blogs [here](/blog).
>- You can read my nanologs [here](/nanolog).
>- My **dotfiles** are available on this [git repo](https://github.com/arkovyx/dotfiles).

---

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

# ./projects

[KEYLOCITY](https://arkovyx.github.io/keylocity): A minimalist typing test with real-time keylocity and accuracy tracking.
