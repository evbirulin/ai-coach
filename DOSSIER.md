# Athlete Training Dossier & Performance Roadmap

**Dossier Version:** v1.1.1  
**Protocol Compatibility:** Section 11 v11.6+  
**Date:** [YYYY-MM-DD]  
**Primary Source Systems:** Intervals.icu | [Other platforms]

This document serves as a reference template for endurance athletes using the deterministic AI-coaching framework defined in Section 11.

---

## Quick Start

1. Fill in your athlete profile (Section 1)
2. Document your equipment (Section 2)
3. Define your training schedule and goals (Section 3)
4. Enter your current performance metrics (Section 4)
5. Set up your nutrition/fueling protocol (Section 5)
6. Link this dossier to your JSON data mirror (see Section 11 for protocol)

---

## 1. Athlete Overview

### Athlete Profile

| Field | Value |
|-------|-------|
| Name | Evan |
| Age | 14 |
| Height | 162 |
| Current Weight | 49 |
| Location | Sydney, Australia |

**Weigh-in Protocol:** Once weekly, Tuesday morning, during gym

### Sport Focus

| Type | Description |
|------|-------------|
| Primary | Triathlon, specifically Ironman and 70.3 distances |
| Secondary | Cycling, endurance |

**Current Phase:** Building a strong base for long-term goals
**Training Style:** ~15 hours per week, highly flexible with fatigue and exertion

---

## 2. Equipment & Environment

### Indoor Training Setup

| Component | Details |
|-----------|---------|
| Trainer/Bike | Reid Falco |
| Platform | Wattbike |
| Cooling | Fans, AC |
| Sensors | Pixel Watch 3, Power, Cadence |
| Pedals | Flat |

### Outdoor Setup

| Component | Details |
|-----------|---------|
| Bike | Reid Falco, Size S |
| Power Meter | None |
| Head Unit | Pixel Watch 3 |
| HRM | Pixel Watch 3 |

### Other Modalities

| Modality | Equipment | Purpose |
|----------|-----------|---------|
| Swimming | Swimming goggles, swimming cap | Triathlon, recovery |
| Running | Altra Lone Peak 9+, Pixel Watch 3, treadmill | Triathlon |
| Strength/Plyometrics | Full gym | Helping triathlon training |

### Environment

| Factor | Details |
|--------|---------|
| Indoor | Indoor bike at gym, treadmill, or just gym |
| Outdoor | Fairly hilly |
| Calibration | None |

---

## 3. Training Schedule & Framework

### Weekly Volume Target

**Baseline:** 15 hours/week (± 7 hours)  
**Peak phases:** Up to 15 hours (requires RI ≥ 0.8, HRV within 10%)

### Normal Weekly Schedule

| Day | Primary Session | Duration | Secondary |
|-----|-----------------|----------|-----------|
| Sunday | Long, easy outdoor run | ~2 hours | None |
| Monday | Pool swim, for technique | ~1 hour | None |
| Tuesday | Easy treadmill run | ~1 hour | None |
| Wednesday | Sweet spot intervals, on indoor bike | ~1 hour | Gym/plyometrics |
| Thursday | Intervals, tempo, hill repeat, easy treadmill run (cycling through each one every week) | ~1 hour | None |
| Friday | None | None | None |
| Saturday | Long, easy outdoor bike | ~2-3 hours | Short, easy brick run after |

### Session Details

| Session Type | Target Power/HR | Duration | Purpose |
|--------------|-----------------|----------|---------|
| VO₂Max | 95-108w |
| Endurance | 50-67w | ~2-3 hours |
| Sweetspot | 75-87w | Optimal training |
| Long Ride | 50-67w | ~2-3 hours |
| Recovery | 1-49w | Recovery |

### Recovery Protocol

**Recovery Triggers (Auto-Deload):**
- HRV ↓ > 20% → Z1/No training
- RHR ↑ ≥ 5 bpm → Z1/No training
- Feel ≥ 4 → Z1/No training
- Two+ triggers → Z1/No training

**Feel Scale:**
| Score | Meaning |
|-------|---------|
| 1 | Excellent (fully recovered) |
| 2 | Good (normal fatigue) |
| 3 | Moderate (manageable tiredness) |
| 4 | Fatigued (reduced readiness, deload trigger) |
| 5 | Exhausted (complete rest required) |

---

## 4. Performance Metrics

### Current Power Zones

| Zone | % of FTP | Power (W) | Notes |
|------|----------|-----------|-------|
| Z1 | 0–55% | 1-49w | Active Recovery |
| Z2 | 56–75% | 50-67w | Endurance (Base) |
| Z3 | 76–90% | 68-81w | Tempo |
| Z4 | 91–105% | 82-94w | Threshold |
| Z5 | 106–120% | 95-108w | VO₂max |
| Z6 | 121–150% | 109-135w | Anaerobic |
| Z7 | 151%+ | 136w+ | Neuromuscular |
| SS | 84–97% | 75-87w | Sweetspot |

**Current FTP:** 90 (Indoor: 90)  
**Max HR:** 195  
**Threshold HR:** 160

### Current Fitness Markers

| Metric | Value | Notes |
|--------|-------|-------|
| FTP (Outdoor) | 90 | |
| FTP (Indoor) | 90 | Adjusted for indoor conditions |
| LT2 Power (MLSS) | [W] | ≈[%] of FTP |
| LT2 HR | [bpm] | |
| LT1 (AeT) | [W] | HR ≈[bpm] |
| VO₂max Interval Power | 95-108w | |
| Sweetspot Target | 75-87w | |
| Weekly Volume | [hours] | [TSS range] |

### Weight Tracking

**Protocol:** Once a week, Tuesday, during gym  
**Adjustment Control:** Weight adjustments only permitted during readiness-positive periods (DI ≥ 0.95, HR drift ≤ 3%, RI ≥ 0.8)

---

## 5. Nutrition / Fueling

### Training Fuel Recipe

```
[Your carb mix recipe]
```

**CHO per bottle:** [g]  
**Target absorption:** [g CHO/h]

### Recovery Drink Recipe

```
[Your recovery drink recipe]
```

### Fueling by Workout Type

| Workout Type | Duration | CHO Target | Setup |
|--------------|----------|------------|-------|
| Recovery / Z1–Z2 | < 1.5 h | [g/h] | [Description] |
| Endurance | 1.5–3 h | [g/h] | [Description] |
| Long Endurance | 3–6 h | [g/h] | [Description] |
| Threshold / SS | 1–2 h | [g/h] | [Description] |
| VO₂ / High Intensity | 1–1.5 h | [g/h] | [Description] |
| Race / Event | 4–6 h | [g/h] | [Description] |

### Hydration

**Target:** [ml/hour]  
**Sodium:** [mg/L] base, + [mg/h] additional for long/hot rides

---

## 6. Adaptation & Current Focus

### Current Adaptation Focus

- [ ] [Focus item 1]
- [ ] [Focus item 2]
- [ ] [Focus item 3]
- [ ] [Focus item 4]

### Next-Phase Options

[Description of upcoming phase transition criteria and options]

---

## 7. Outdoor Transition Plan (if applicable)

### Transition Timeline

| Month | Changes | Notes |
|-------|---------|-------|
| [Month] | [Transition step] | [Details] |
| [Month] | [Transition step] | [Details] |
| [Month] | [Transition step] | [Details] |

**General Rules:**
- Outdoor rides replace indoor 1:1
- HR < 85% of threshold = aerobic
- Use HR to guide intensity early season

---

## 8. Long-Term Performance Roadmap

### Primary Objective

Ironman

### Progression Overview

| Year | Focus | FTP Target | W/kg Target | Key Metrics |
|------|-------|------------|-------------|-------------|
| [Year] | [Focus] | [W] | [W/kg] | [Metrics] |
| [Year] | [Focus] | [W] | [W/kg] | [Metrics] |
| [Year] | [Focus] | [W] | [W/kg] | [Metrics] |

### Event-Specific Targets (Optional)

| Event/Segment | Year | Priority | Target Time | Target Power |
|---------------|------|----------|-------------|--------------|
| [Event] | [Year] | [A/B/C] | [Time] | [W] |
| [Event] | [Year] | [A/B/C] | [Time] | [W] |

> **Race tagging for automated protocol activation:** Tag races in Intervals.icu as `RACE_A`, `RACE_B`, or `RACE_C` using the event category selector. The race-week protocol (Section 11A) activates automatically for A and B races within 7 days. C races are training races — no taper adjustments. For best results, also set expected duration (`moving_time`) in the event to enable event-type modifiers (carb loading, opener intensity, TSB targets).

---

## 9. Coach Notes

[Space for coach observations, athlete-specific considerations, or important reminders]

---

## 10. Operational & Data Integrity Log

### Training Timeline & Event Log

| Date | Event | Notes |
|------|-------|-------|
| [Date] | [Event] | [Details] |
| [Date] | [Event] | [Details] |

### Calibration & Data Log

| Date | Item | Action |
|------|------|--------|
| [Date] | [Equipment] | [Action taken] |
| [Date] | [Equipment] | [Action taken] |

---

## Data Mirror Configuration

### JSON Endpoint (for AI coaches)

**URL:** `https://raw.githubusercontent.com/[username]/[repo]/main/latest.json`

**Archive:** `https://github.com/[username]/[repo]/tree/main/archive`

**— OR (GitHub connector) —**

**Repo:** `[username]/[repo]` (connected via platform's GitHub integration — AI reads files directly, no URLs needed)

> **Tip:** If you commit `DOSSIER.md` to your data repo alongside `latest.json`, `history.json`, and `intervals.json`, connecting the repo gives the AI both your data and your profile in one connection. The only remaining piece is `SECTION_11.md`, which the AI can fetch from the public CrankAddict/section-11 repo or a second connector.

**— OR (local setup) —**

**Path:** `latest.json` (data directory root, alongside this dossier)

**History:** `history.json` (data directory root)

**Intervals:** `intervals.json` (data directory root — on-demand, for structured session analysis)

**Data Path (optional):** `[/path/to/training-data/]`
Only needed if the AI agent's working directory is different from where data files live (e.g., OpenClaw workspace is `~/clawd/` but data is in `~/training-data/`). Leave blank if they are the same directory.

For local setups where sync.py runs on the same machine as the AI agent, files are read directly from the filesystem — no URLs needed. See `examples/json-local-sync/SETUP.md` for the complete local pipeline.

This endpoint provides synchronized Intervals.icu metrics for deterministic AI parsing. See **Section 11** for the full AI Coach Guidance Protocol.

---

## Protocol Reference

This dossier follows the **Section 11 A/B AI Coach Guidance Protocol** for AI integration.

**Protocol Location:** [Link to your Section 11 document or repo]

---

## Changelog

### v1.0 ([Date])
- Initial dossier creation
