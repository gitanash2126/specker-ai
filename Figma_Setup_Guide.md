# Specker.ai – Complete Figma Structure & Hand-off Guide

If the hiring team asked you to share a Figma link, follow this exact structure. This is the gold standard used by Senior Product Designers at top tech companies.

---

## 📁 Recommended Figma File Page Structure

```
Specker.ai – Product Design Assignment
├── 📄 01. Cover & Executive Summary
├── 📄 02. Current App Audit & UX Teardown
├── 📄 03. Information Architecture & Wireframes
├── 📄 04. High-Fidelity UI (Dark & Light Mode)
├── 📄 05. Voice Call & Scorecard Flow
├── 📄 06. Edge Cases & System States
└── 📄 07. Design System & Components
```

---

## 📄 Page 1: Cover & Executive Summary

- **Frame Size:** 1920 × 1080 (16:9 Presentation Slide)
- **Elements:**
  - Project Title: `Specker.ai Home Screen Redesign & App Audit`
  - Subtitle: `Transforming Speaking Anxiety into Daily Fluency Habits`
  - Metadata: `Role: Product Designer | Duration: 3 Days | Platform: iOS / Android`
  - Hero Thumbnail: Place `assets/specker_home_dark_redesign.jpg` with a soft drop shadow (`X: 0, Y: 20, Blur: 40, Spread: -10, Color: #000000 40%`).

---

## 📄 Page 2: Current App Audit & UX Teardown

- **Frame Size:** 1920 × 1080 (or auto-height board)
- **Layout:**
  - Place the current app screenshots (`app_screenshots/screen1.png` to `screen4.png`).
  - Add red-line annotation callout pills (`#EF4444` background, white text) pointing to key UX issues:
    1. `Lack of dominant Hero CTA (Decision Paralysis)`
    2. `No topic preview or conversation scaffolding before call`
    3. `Missing daily speaking streak & habit goal on home screen`
    4. `Post-call scorecard is a dead-end with no 1-tap micro-drill`
    5. `Inconsistent dark surface contrast (< 3:1 WCAG failure)`

---

## 📄 Page 3: Information Architecture & Wireframes

- **Low-Fidelity Wireframe Frame:** iPhone 16 Pro (393 × 852 px)
- **Layout Blocks:**
  1. `[Header]` Profile avatar, Streak Pill (`🔥 7 Days`), CEFR Level (`B2`)
  2. `[Hero Card]` Stella AI Voice Hub with Topic of the Day and Primary Call CTA
  3. `[Habit Strip]` Circular progress ring for 12-min daily speaking goal
  4. `[Scenario Hub]` Filter chips (Career, Workplace, IELTS) + Horizontal cards
  5. `[Scorecard Snapshot]` Latest session score (85) + 1-tap IPA audio drill
  6. `[Quick Warmup]` 60-second low-stakes pronunciation exercise
  7. `[Bottom Nav]` 4 tabs with central elevated Quick-Speak FAB

---

## 📄 Page 4: High-Fidelity UI (Dark & Light Mode)

- **Frame Size:** 393 × 852 px (iPhone 16 Pro)
- Place `assets/specker_home_dark_redesign.jpg` (Stella Midnight Theme) side-by-side with `assets/specker_home_light_redesign.jpg` (Nordic Clean Theme).
- Add design token annotations:
  - Radius: `24px` for large cards, `16px` for scenario cards, `12px` for chips, `9999px` for pills.
  - Padding: `20px` horizontal screen padding, `16px` vertical gaps between sections.

---

## 📄 Page 5: Voice Call & Scorecard Flow

- Place `assets/specker_call_scorecard_flow.jpg` showing:
  - Screen 1: Active Calling State with Stella (Live equalizer, "Live Whisper" coaching prompt, 125 WPM pacing indicator).
  - Screen 2: Post-Call Scorecard (Fluency Band 88/100, Pronunciation 84%, Grammar 92%, and 'Particularly' pronunciation drill).

---

## 📄 Page 6: Edge Cases & System States

Create a frame with 4 state cards:

1. **Zero-State (New User - Day 0):** Hero card says _"Meet Stella: Take your 3-minute diagnostic call"_ with zero streak.
2. **At-Risk User (Missed Streak):** Friendly recovery banner _"Freeze used! Complete 5 mins today to repair streak."_
3. **Zero Minutes / Free Tier Limit:** Subtle upgrade banner _"You've completed your 30 free minutes this week. Unlock Unlimited Stella with Pro."_
4. **Offline / Mic Permission Denied:** System toast explaining _"Specker requires microphone access to hear your voice."_

---

## 📄 Page 7: Design System & Tokens

- **Colors:**
  - Primary Brand: `#6366F1` (Indigo 500)
  - Secondary Brand: `#7C3AED` (Purple 600)
  - Dark Canvas: `#0B0D17` (Midnight Base)
  - Dark Surface: `#141829` (Card Surface)
  - Dark Border: `#232946` (Subtle Card Border)
  - Light Canvas: `#F8FAFC` (Slate 50)
  - Accent Success: `#10B981` (Emerald 500)
  - Accent Warning: `#F59E0B` (Amber 500)
- **Typography (Inter or SF Pro Display):**
  - `Display`: 24px Bold / Line-height: 32px
  - `Title`: 18px Bold / Line-height: 24px
  - `Body Bold`: 14px SemiBold / Line-height: 20px
  - `Body Regular`: 13px Regular / Line-height: 18px
  - `Caption / Micro`: 10px Bold Uppercase / Line-height: 14px / Tracking: +0.05em
