# Awesome-Terminal-Emulator

## Top Terminal Emulator Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on GPU-Accelerated Rendering, Multiplexing & Cross-Platform Shells*  

**Last updated: October 2026**



This repository tracks notable **commercial terminal emulators** and **open-source projects** that provide fast, feature-rich command-line interfaces — from GPU-accelerated terminals to cross-platform multiplexers and remote access tools.



**Examples** include Windows Terminal, iTerm2, Alacritty, Kitty, Hyper, ConEmu, PuTTY, MobaXterm, Warp, and WezTerm (the category leaders).



**Open-source emphasis**: Terminal emulators are one of the strongest open-source domains. **Alacritty**, **Kitty**, **WezTerm**, **Windows Terminal**, and **Ghostty** collectively deliver GPU-accelerated performance with zero licensing costs, while **tmux** and **Zellij** provide terminal multiplexing. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[iTerm2](https://iterm2.com/)**  

  macOS-only terminal emulator with split panes, search, autocomplete, and extensive customization. **Free and open-source** (GPL-2.0) but closely tied to macOS ecosystem. **The de facto macOS terminal** for developers .



- **[MobaXterm](https://mobaxterm.mobatek.net/)**  

  Windows terminal with built-in X server, SSH client, SFTP browser, and remote desktop tools. **Free tier available** with limited sessions; Professional edition for unlimited use. **The Swiss Army knife of Windows remote access** .



- **[Warp](https://www.warp.dev/)**  

  Modern terminal with AI-powered command suggestions, blocks-based output, and collaborative features. **Free tier available**; paid for teams. **The most AI-forward commercial terminal** — closed source.



- **[PuTTY](https://www.putty.org/)**  

  Legendary Windows SSH client with terminal emulation. **Open-source** (MIT) but development has slowed significantly. **Historically the standard Windows SSH client** — still widely deployed .



## Open-Source GitHub Projects



- **[Windows Terminal](https://github.com/microsoft/terminal)**  

  **Microsoft's modern terminal for Windows**, MIT licensed with 100,000+ GitHub stars . **GPU-accelerated rendering** via DirectWrite/DirectX, tabs, panes, and full Unicode/emoji support . Integrates with PowerShell, WSL, SSH, and Azure Cloud Shell . **The default terminal for Windows 11** — completely replaced the legacy console host . Highly customizable with JSON profiles and themes .



- **[Alacritty](https://github.com/alacritty/alacritty)**  

  **The original GPU-accelerated terminal emulator**, Apache-2.0 licensed with 60,000+ GitHub stars . **Focuses exclusively on performance** — no tabs, no splits, no scrollback by design . **Relies on tmux or a window manager for multiplexing** . **The fastest terminal available** with minimal resource usage . Cross-platform (Linux, macOS, Windows, BSD) . **The reference implementation for GPU-accelerated terminals** — inspired Kitty, WezTerm, and Ghostty .



- **[Kitty](https://github.com/kovidgoyal/kitty)**  

  **GPU-accelerated terminal with batteries included**, GPL-3.0 licensed with 30,000+ GitHub stars . **Tabs, splits, layouts, and sessions built in** — no external multiplexer needed . Features **kittens** (extensible Python scripts for terminal features), **remote control via kitty socket**, **hyperlinks, images, and Unicode support** . **The most feature-complete GPU terminal** — creator Kovid Goyal also developed Calibre . macOS, Linux, and BSD only.



- **[WezTerm](https://github.com/wezterm/wezterm)**  

  **GPU-accelerated terminal emulator and multiplexer**, MIT licensed with 20,000+ GitHub stars . **Built in Rust with Lua configuration** — fully scriptable . **Cross-platform** (Linux, macOS, Windows, FreeBSD, NetBSD, OpenBSD) . Features **tab and pane multiplexing**, **SSH/TLS remote domains**, **ligature support**, and **built-in image protocol** . **The most configurable terminal** — Lua scripting enables deep customization . **The best choice for cross-platform consistency** .



- **[Ghostty](https://github.com/ghostty-org/ghostty)**  

  **Fast, feature-rich, cross-platform terminal emulator** by Mitchell Hashimoto (HashiCorp co-founder), MIT licensed with 25,000+ GitHub stars . **Native GUI on every platform** — GTK on Linux, AppKit on macOS, Win32 on Windows (alpha) . **GPU-accelerated with platform-native rendering** — no Electron, no web tech . **The most promising new terminal** — focuses on speed, correctness, and native experience . **Not yet 1.0** but already production-quality on macOS and Linux .



- **[Hyper](https://github.com/vercel/hyper)**  

  **Electron-based terminal** built with web technologies, MIT licensed with 45,000+ GitHub stars . **Extensible via npm packages** — plugins for themes, notifications, and more . **The most customizable terminal for JavaScript developers** . **Trade-off**: Electron overhead means higher memory usage and slower startup than native alternatives .



- **[Tabby](https://github.com/Eugeny/tabby)**  

  **Modern terminal emulator with SSH, serial, and Telnet support**, MIT licensed with 60,000+ GitHub stars . **Cross-platform** with integrated SSH client, port forwarding, and SFTP . **The best open-source alternative to MobaXterm** — built with Electron and TypeScript . **Best for Windows users needing remote access tools in one app** .



- **[ConEmu](https://github.com/Maximus5/ConEmu)**  

  **Windows terminal emulator with tabs, splits, and extensive customization**, BSD-3-Clause licensed . **The predecessor to Windows Terminal** — still actively used for legacy Windows workflows . **Best for Windows users needing a mature, feature-rich terminal** with task automation .



- **[Terminator](https://github.com/gnome-terminator/terminator)**  

  **Linux terminal with multiple resizable panes in a grid**, GPL-2.0 licensed . **Split panes and tabs** with drag-and-drop reordering . **The classic Linux multiplexing terminal** — popular in DevOps workflows .



- **[Tilix](https://github.com/gnunn1/tilix)**  

  **GTK3 terminal for Linux with tiling and split panes**, MPL-2.0 licensed . **Quake mode** for drop-down terminal access . **Best for GNOME users** wanting tiling without tmux .



- **[Guake](https://github.com/Guake/guake)**  

  **Drop-down terminal for GNOME**, GPL-2.0 licensed . **Quake-style overlay** accessible with a single hotkey . **Best for quick command access** without leaving your current application .



- **[QTerminal](https://github.com/lxqt/qterminal)**  

  **Lightweight Qt-based terminal emulator**, GPL-2.0 licensed . **The default terminal for LXQt** — fast and minimal . **Best for low-resource Linux systems** .



- **[Termux](https://github.com/termux/termux-app)**  

  **Android terminal emulator and Linux environment**, GPL-3.0 licensed with 35,000+ GitHub stars . **Full package management via apt** — runs Python, Node.js, Git, and more on Android . **The most capable mobile terminal** — turns Android into a portable development environment . **Not available on Google Play due to API restrictions** — install from F-Droid or GitHub .



### The Multiplexers



Terminal multiplexers are essential companions to minimalist terminals like Alacritty:



- **[tmux](https://github.com/tmux/tmux)**  

  **The standard terminal multiplexer**, ISC licensed with 35,000+ GitHub stars . **Sessions, windows, and panes** with detach/reattach persistence . **The most widely used multiplexer** — essential for remote work and long-running processes .



- **[Zellij](https://github.com/zellij-org/zellij)**  

  **Modern terminal workspace and multiplexer**, MIT licensed with 20,000+ GitHub stars . **Built-in layouts, plugins, and floating panes** with discoverable keybindings . **The user-friendly tmux alternative** — better defaults and status bar .



- **[GNU Screen](https://www.gnu.org/software/screen/)**  

  **The original terminal multiplexer**, GPL-3.0 licensed . **Sessions and detach/reattach** — simpler than tmux . **Still useful on legacy systems** where tmux isn't installed .



- **[abduco](https://github.com/martanne/abduco)**  

  **Session management with minimal dependencies**, ISC licensed . **The simplest detach/reattach tool** — pairs with dvtm for panes .



- **[dvtm](https://github.com/martanne/dvtm)**  

  **Dynamic virtual terminal manager**, MIT licensed . **Tiling window management for terminals** — pairs with abduco for sessions .



### Additional Strong Open-Source Options



- **GNOME Terminal** — Default terminal for GNOME with tabs, profiles, and transparency .

- **Konsole** — KDE's terminal emulator with tabs, splits, and bookmarks .

- **XFCE Terminal** — Lightweight terminal for XFCE desktop .

- **Terminology** — Enlightenment's terminal with unique visual features .

- **st** — Simple terminal from suckless, minimal and fast .

- **Extraterm** — Terminal with GUI features like image display and command output editing .

- **Rio** — Web-based terminal emulator built with Rust and WebAssembly .

- **Wave Terminal** — Modern terminal with graphical widgets and AI features .



**Frameworks for building custom terminal solutions**: Choose based on platform and workflow. **Windows Terminal** for Windows-native GPU acceleration and WSL integration . **Alacritty** for maximum performance with external multiplexing . **Kitty** for built-in tabs, splits, and Python extensibility . **WezTerm** for cross-platform consistency with Lua scripting . **Ghostty** for native GUI performance on macOS and Linux . **Tabby** for integrated SSH/SFTP on Windows . **Termux** for Android-based development . Pair minimalist terminals with **tmux** or **Zellij** for multiplexing . Note that true commercial terminals like Warp offer AI features and collaboration, but open-source alternatives match their performance and exceed their configurability .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Terminal emulators handle shell sessions, SSH keys, and potentially sensitive command history. **Review security settings** — some terminals store scrollback to disk, log sessions, or transmit data for AI features .

- **GPU-accelerated terminals require compatible graphics drivers** — Alacritty, Kitty, WezTerm, and Ghostty need OpenGL 3.3+ or Metal/Vulkan support .

- **Electron-based terminals (Hyper, Tabby) use more memory** than native alternatives — typically 100-200 MB vs. 20-50 MB for Alacritty or Kitty .

- **Warp and MobaXterm are not fully open source** — Warp's client is closed, MobaXterm's free tier has session limits .

- The open-source ecosystem provides strong performance, multiplexing, and cross-platform foundations, but **AI features, team collaboration, and managed remote access** remain primarily commercial offerings.



---



**Made for developers, system administrators, and command-line enthusiasts.**

Let's make terminal emulators more open, transparent, and performant.
