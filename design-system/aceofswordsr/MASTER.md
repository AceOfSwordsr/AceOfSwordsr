# AceOFSwordsr — Design System & Visual Intelligence
*Theme: Ace of Swords (Minor Arcana I) ・ Element Air ・ Intellectual Victory*
*Reference: https://www.astrolink.com/en/tarot/suit/swords/ace-of-swords*

---

## 🗡️ Mythos & Archetype

The **Ace of Swords** represents the pure **Element of Air** — the intellect, rationality, mental clarity, and the power of thought as the source of all action. In the Rider-Waite-Smith canon, a divine hand emerges from the celestial clouds, wielding an upright double-edged steel blade. Atop the blade rests a golden crown draped with olive and laurel branches — the **Crown of Victory**. Beneath stretches an arid, cold mountain range, symbolizing that true engineering requires **more reason and less emotion**.

> *"The Ace of Swords indicates that you can perceive things more clearly, that your mind is sharper... It carries with it the power of truth, seeing the light in a situation, restoring balance. A time to act with more reason and less emotion."* — Astrolink

---

## 🎨 Color Palette & Tokens (Air, Steel & Victory)

| Role | Color Name | Hex | CSS Token | Archetypal Symbolism |
|:---|:---|:---|:---|:---|
| **Background** | Arid Peak Void | `#06080e` | `--bg-void` | The cold mountain night under the high sky |
| **Surface** | Cloud Layer | `#0c101a` | `--bg-surface` | The dense mist from which the hand emerges |
| **Card Surface** | Slate Hearth | `rgba(14, 18, 28, 0.8)` | `--bg-card` | Low-reflection dark steel base |
| **Primary Accent** | Element Air / Ozone | `#38bdf8` | `--color-air` | Pure intellect, breath, atmospheric wind |
| **Secondary Accent**| Laurel of Victory | `#00f59b` | `--color-laurel`| The laurel branches signifying triumphant delivery |
| **Blade Edge** | Honed Steel | `#f8fafc` | `--color-steel` | Razor-sharp double-edged truth |
| **Crown Gold** | Celestial Crown | `#f59e0b` | `--color-crown`| The crown atop the blade representing mastery |
| **Muted Text** | Cold Granite | `#94a3b8` | `--text-muted` | Balanced, impartial commentary |
| **Border Tone** | Frost Wire | `rgba(56, 189, 248, 0.14)` | `--border-ice` | Subtle crystalline perimeter lines |

---

## 🖋️ Typography Hierarchy

* **Display / Brand**: `Archivo` (weight 700/800) — authoritative, architectural, cold, uncompromising.
* **Body / Prose**: `Space Grotesk` (weight 400/500/600) — rational, geometric, highly readable, balanced.
* **Terminal / Code**: `JetBrains Mono` (weight 400/500) — precise monospace for technical metrics, routes, and tokens.

---

## ⚡ Interaction & Polish Axioms

1. **Air Element Ambient Motion**: Subtle drifting gradient mesh mimicking high-altitude wind currents (`prefers-reduced-motion` respected).
2. **Sharp Geometry**: Razor-fine borders (`1px solid rgba(56, 189, 248, 0.18)`), minimal border-radii (`6px` to `12px`), crisp shadow cutoffs.
3. **No Decorative Slop**: Every element serves an intellectual purpose. No frivolous emojis as icons; use geometric SVGs.
4. **Instant State Feedback**: Interactive elements respond in $<180\text{ms}$ with smooth transition curves. Focus rings are luminous and high-contrast.
