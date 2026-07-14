<div align="center">

# 💎 Pyrope

**A warm, dark, jewel-toned colorscheme built for long sessions and Deutan eyes.**

*Named after the deep red garnet — the jewel of fire.*

![License](https://img.shields.io/badge/license-MIT-a8c155?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0.0-d4893f?style=flat-square)
![Maintained](https://img.shields.io/badge/maintained-yes-c33d5e?style=flat-square)

</div>

---

## The Problem

Most colorschemes are built around a hypothetical average eye, then shipped unchanged to everyone. Gruvbox, Nord, Catppuccin, Solarized — all well-made, all tuned around trichromatic perception as the default. None of them were wrong on their own terms. They were just never going to feel right for a Deutan eye, because the thing that makes them *feel* balanced — the relationship between red and green — is the one relationship a Deutan eye can't fully receive.

Pyrope fixes this at the source, not by strapping corrections on top of an existing scheme, but by designing every color decision from the ground up around one specific set of eyes and one specific set of requirements: **warm, not cold. Grounded, not neon. Professional, not cute. Consistent across every tool you use.**

---

## Design Pillars

| Pillar | What it means in practice |
|--------|--------------------------|
| 🎯 **Deutan-aware** | No red-green meaning pairs. Status colors split by brightness and hue axis, not just hue alone |
| 🔥 **Warm dark** | Near-black base with a minimal warm tint — deep without being muddy or brown-heavy |
| 💎 **Jewel-toned** | Saturated, grounded accent palette — vibrant without being neon or pastel |
| 🔒 **Singular accent** | One primary identity color used consistently everywhere, never diluted by secondary "also accents" |
| ⚖️ **Brightness as backup** | Every meaningful color pair also differs in lightness — readable even on bad monitors |
| 🔁 **One palette, every tool** | Same hex, same role — terminal, KDE, Anki, editor, browser — never repurposed per context |

---

## Palette

### Backgrounds

> Darkness does the work. Warmth stays subtle — saturation was the cause of "muddy", not warmth itself.

| Swatch | Name | Hex | RGB | Role |
|--------|------|-----|-----|------|
| ![#171513](https://placehold.co/16x16/171513/171513.png) | **Base** | `#171513` | 23, 21, 19 | Primary background — editor, terminal, view areas |
| ![#1e1b19](https://placehold.co/16x16/1e1b19/1e1b19.png) | **Surface** | `#1e1b19` | 30, 27, 25 | Window chrome, panels, sidebars |
| ![#282420](https://placehold.co/16x16/282420/282420.png) | **Elevated** | `#282420` | 40, 36, 32 | Buttons, inputs, raised cards |
| ![#3a3430](https://placehold.co/16x16/3a3430/3a3430.png) | **Border** | `#3a3430` | 58, 52, 48 | Dividers, borders, separators |

---

### Foreground

> Slightly desaturated, warm-tinted off-white — high contrast without the glare of pure white on near-black.

| Swatch | Name | Hex | RGB | Role |
|--------|------|-----|-----|------|
| ![#f0e9dd](https://placehold.co/16x16/f0e9dd/f0e9dd.png) | **Bright** | `#f0e9dd` | 240, 233, 221 | Active states, emphasis, selected text |
| ![#e6ddd0](https://placehold.co/16x16/e6ddd0/e6ddd0.png) | **Primary** | `#e6ddd0` | 230, 221, 208 | Main text — all body copy, code |
| ![#9c9186](https://placehold.co/16x16/9c9186/9c9186.png) | **Muted** | `#9c9186` | 156, 145, 134 | Comments, metadata, placeholders |
| ![#6b625a](https://placehold.co/16x16/6b625a/6b625a.png) | **Faint** | `#6b625a` | 107, 98, 90 | Disabled text, de-emphasized UI |

---

### Accent

> The identity of this scheme. Used for links, focus rings, selection backgrounds, and active states everywhere.

| Swatch | Name | Hex | RGB | Notes |
|--------|------|-----|-----|-------|
| ![#a8c155](https://placehold.co/16x16/a8c155/a8c155.png) | **Pear Green** | `#a8c155` | 168, 193, 85 | Primary accent — singular, never substituted |

**Why this green specifically:** Cool greens (mint, seafoam) carry a dominant blue component that reads as blue to a Deutan eye whose blue cone runs at 100%. Pear green is warm-leaning — it drives its brightness through its red component and raw luminance, so it reads as a warm gold-olive instead of triggering the blue channel. To a full-color eye it reads as clean spring green. Both are true at once. Blue-channel share of total RGB: ~19% — well under the 20% threshold that defines a safe, non-blue-reading color for this palette.

---

### Status Colors

> Meaning-bearing. Each pair differs in both hue family *and* brightness — belt and suspenders.

| Swatch | Name | Hex | RGB | Role | Why |
|--------|------|-----|-----|------|-----|
| ![#5683c4](https://placehold.co/16x16/5683c4/5683c4.png) | **Sapphire** | `#5683c4` | 86, 131, 196 | ✅ Success / Positive | The one place blue is allowed. Blue cone at 100% means this signal is unmissable. Kept deliberately rare so it stays meaningful. |
| ![#d4893f](https://placehold.co/16x16/d4893f/d4893f.png) | **Amber** | `#d4893f` | 212, 137, 63 | ⚠️ Warning / Neutral | High brightness, zero blue content, clear separation from both error and success in hue and lightness. |
| ![#c33d5e](https://placehold.co/16x16/c33d5e/c33d5e.png) | **Crimson** | `#c33d5e` | 195, 61, 94 | ❌ Error / Negative | Red with enough magenta to stay visually distinct from amber. Never paired against green for meaning. |
| ![#d1a83e](https://placehold.co/16x16/d1a83e/d1a83e.png) | **Gold** | `#d1a83e` | 209, 168, 62 | 🔗 Visited / Secondary | Distinct from amber in warmth and hue, used for visited links and secondary indicators so the three primary status colors stay uncrowded. |

---

### Jewel Tones

> Decorative palette. Used for syntax variety, UI flourishes, and anywhere color is needed without carrying meaning. Not interchangeable with status colors.

| Swatch | Name | Hex | RGB | Personality | Caution |
|--------|------|-----|-----|------------|---------|
| ![#b5475c](https://placehold.co/16x16/b5475c/b5475c.png) | **Garnet** | `#b5475c` | 181, 71, 92 | Deep red, anchoring, grounded | Safe — low blue channel. Use for nested links on selection backgrounds, strings, tags. |
| ![#b04f86](https://placehold.co/16x16/b04f86/b04f86.png) | **Rosewood** | `#b04f86` | 176, 79, 134 | Magenta-adjacent, rich | Use sparingly — medium blue component. Decorative only, never meaning-bearing. |
| ![#d1a83e](https://placehold.co/16x16/d1a83e/d1a83e.png) | **Gold** | `#d1a83e` | 209, 168, 62 | Warm, prestigious, distinct | Also lives in the status palette as visited/secondary — don't add extra meaning on top. |
| ![#3f93a0](https://placehold.co/16x16/3f93a0/3f93a0.png) | **Lagoon** | `#3f93a0` | 63, 147, 160 | Cyan, cool, aquatic | ⚠️ High blue content (~39%) — decorative only. Will read blue-dominant. |
| ![#4f9c87](https://placehold.co/16x16/4f9c87/4f9c87.png) | **Verdant** | `#4f9c87` | 79, 156, 135 | Teal-green, earthy | ⚠️ Medium-high blue (~33%) — same caution as Lagoon, use sparingly. |

---

## Terminal — ANSI 16

> The most important practical fix: ANSI slot 2 (green) is the actual Pear accent, not a teal substitute. `git diff` becomes Garnet vs. Pear — separated by hue family *and* brightness. No more guessing which side of a diff is which.

| # | Swatch | Name | Hex | | # | Swatch | Name | Hex |
|---|--------|------|-----|-|---|--------|------|-----|
| 0 | ![#171513](https://placehold.co/14x14/171513/171513.png) | Black | `#171513` | | 8 | ![#3a3430](https://placehold.co/14x14/3a3430/3a3430.png) | Bright Black | `#3a3430` |
| 1 | ![#b5475c](https://placehold.co/14x14/b5475c/b5475c.png) | Red | `#b5475c` | | 9 | ![#cf6478](https://placehold.co/14x14/cf6478/cf6478.png) | Bright Red | `#cf6478` |
| 2 | ![#a8c155](https://placehold.co/14x14/a8c155/a8c155.png) | Green | `#a8c155` | | 10 | ![#c3d978](https://placehold.co/14x14/c3d978/c3d978.png) | Bright Green | `#c3d978` |
| 3 | ![#d1a83e](https://placehold.co/14x14/d1a83e/d1a83e.png) | Yellow | `#d1a83e` | | 11 | ![#e0bc5a](https://placehold.co/14x14/e0bc5a/e0bc5a.png) | Bright Yellow | `#e0bc5a` |
| 4 | ![#5683c4](https://placehold.co/14x14/5683c4/5683c4.png) | Blue | `#5683c4` | | 12 | ![#6f9bdb](https://placehold.co/14x14/6f9bdb/6f9bdb.png) | Bright Blue | `#6f9bdb` |
| 5 | ![#b04f86](https://placehold.co/14x14/b04f86/b04f86.png) | Magenta | `#b04f86` | | 13 | ![#c570a0](https://placehold.co/14x14/c570a0/c570a0.png) | Bright Magenta | `#c570a0` |
| 6 | ![#3f93a0](https://placehold.co/14x14/3f93a0/3f93a0.png) | Cyan | `#3f93a0` | | 14 | ![#56aab8](https://placehold.co/14x14/56aab8/56aab8.png) | Bright Cyan | `#56aab8` |
| 7 | ![#c9bfb2](https://placehold.co/14x14/c9bfb2/c9bfb2.png) | White | `#c9bfb2` | | 15 | ![#f0e9dd](https://placehold.co/14x14/f0e9dd/f0e9dd.png) | Bright White | `#f0e9dd` |

---

## Ports

| Tool | Status | File |
|------|--------|------|
| KDE Plasma / Breeze | ✅ Available | `ports/kde/NirvikJewel.colors` |
| Konsole | 🚧 In progress | — |
| Kitty | 🚧 In progress | — |
| Alacritty | 🚧 In progress | — |
| WezTerm | 📋 Planned | — |
| VS Code | 📋 Planned | — |
| Neovim | 📋 Planned | — |
| Zed | 📋 Planned | — |
| Kate | 📋 Planned | — |
| Anki | 📋 Planned | — |
| Zsh Syntax Highlighting | 📋 Planned | — |
| GTK | 📋 Planned | — |

---

## Installation

### KDE Plasma

```bash
cp ports/kde/NirvikJewel.colors ~/.local/share/color-schemes/
```

Then: **System Settings → Appearance → Colors → Pyrope Jewel Dark**

---

## Night Color / Redshift Settings

Pyrope is tuned for use with conservative night-shift settings. Aggressive warm-shifting (3000–3500K, the typical default) suppresses blue — which is counterproductive for a Deutan eye whose blue cone is the single most reliable hue channel.

| Setting | Value | Reason |
|---------|-------|--------|
| Day temperature | `6500K` | Neutral — full palette accuracy, no shift |
| Night temperature | `4800–5000K` | Reduces blue light for sleep hygiene without gutting the one cue that works best |
| During color-critical work | Toggle off | Terminal diffs, Anki reviews, git — use full color when it matters |

---

## Consistency Rules

These are non-negotiable if you're extending the scheme, porting it to a new tool, or contributing a port.

1. **Same hex, same role, every tool.** Sapphire is success in KDE, the terminal, Anki, and everywhere else. It is never repurposed as a decorative color in any port.

2. **The accent is singular.** Pear Green (`#a8c155`) is the identity color of Pyrope. Never substitute a different green because it "looks better" in one specific context.

3. **Never introduce a red-green meaning pair.** Not directly, not indirectly. If two states differ primarily in being more red vs. more green without a corresponding brightness difference, that's a violation.

4. **Blue-fraction test for any new color.** Before any new color enters the palette: calculate its blue channel as a share of total RGB (`B / (R+G+B)`). Under ~20% — generally safe. Over ~35% — do not use as anything meaning-bearing, and flag it in the decorative palette with a caution note.

5. **Brightness is always the backup channel.** Every pair of colors that need to be distinguishable from each other must also differ in relative lightness. Hue difference alone is never sufficient.

6. **Backgrounds step in one direction only.** Base → Surface → Elevated → Border, always in that order of increasing brightness. Never reorder, never substitute, never add a fifth step without updating all ports.

7. **Taste overrides theory.** A technically "safe" color that looks wrong on sight is still wrong for this scheme. Pyrope optimizes for correctness *and* for actually wanting to look at it for eight hours a day — neither goal is allowed to override the other.

---

## What Was Tried and Rejected

Documented here so the same paths don't get re-explored.

| Color | Reason rejected |
|-------|----------------|
| **Sapphire as primary accent** | Technically the "loudest" perceptual channel, but blue as a dominant aesthetic was flatly disliked. Safety doesn't override taste. |
| **Amethyst / purple** | Reads as blue in practice. ~40% blue-channel share gets amplified by a maxed-out blue cone to the point the purple reads as a cool blue, not a warm purple. |
| **Terracotta / red-orange** | No perceptual issue — just disliked on sight. That's sufficient reason. |
| **Cool mint / seafoam green** | Green + blue mix where the green component contributes nothing to a zero-green-cone eye. Collapses perceptually into the same problem as amethyst, approached from the other side. |
| **Gruvbox bg style (warm, saturated dark)** | The "muddy" problem: brown gets warm enough and saturated enough relative to its darkness that it starts reading as dirty rather than rich. Solution was to separate darkness from saturation. |

---

## Philosophy — The Short Version

Pyrope exists because "try another scheme" was always going to fail. The failure wasn't taste or pickiness — it was a structural mismatch between how existing schemes build visual hierarchy and how Deutan eyes receive color. Every other scheme uses red-vs-green as a meaning axis, and a green cone at 0% means that axis is simply unavailable.

The fix is to build hierarchy on axes that *are* available: **brightness**, **warm vs. cool hue families**, and the **blue channel used sparingly as a reserved signal** rather than ambient noise.

Green is here — it's just been built from a different direction.

---

## License

MIT — use it, port it, fork it.

---

<div align="center">

*Pyrope — because a garnet looks black until the light hits it right.*

</div>
