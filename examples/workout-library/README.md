# Workout Reference Library

Companion document to **Section 11 B — AI Training Plan Protocol**.

## What This Is

A catalog of structured workout templates that AI coaching systems can select from when prescribing sessions. It provides the *how* — Section 11 provides the *when* and *why*.

## Relationship to Section 11

```
Section 11 A (Readiness) → determines go/modify/skip and adaptation target
Section 11 B (Plan Rules) → constrains session type, load, and distribution
Workout Reference Library → provides the actual session template
Section 11 C (Validation) → audits the result
```

Section 11 B §8 defines the formal interface between the plan protocol and this library.

## Contents

**`WORKOUT_REFERENCE.md`** — The full library, containing:

1. **Workout Type Catalog** — 39 session templates across the base catalog plus C20/FTP specialization
2. **C20/FTP Development Track** — 13 specialization templates for C20 testing, threshold TTE, over-unders, VO₂ ceiling, fatigue-resistant threshold work, and fueling practice
3. **Warm-Up & Cool-Down Protocols** — Standard, progressive, abbreviated, and intensity-specific variants
4. **Session Sequencing Rules** — Spacing, ordering, C20 specialization patterns, and non-cycling integration
5. **Block Periodisation Sketches** — Build:deload ratios, volume trajectories, phase transitions, and a 12-week C20/FTP specialization block
6. **Interval Format Selection Guide** — Decision matrix, progression logic, format change criteria
7. **Adaptation & Customisation Notes** — How to modify for your needs

## Customisation

This document is designed to be forked. You can:

- Add sport-specific sessions (running, swimming, SkiErg)
- Adjust durations for your available training time
- Replace templates with sessions that work for you
- Map to a different zone model if not using Intervals.icu

As long as your sessions follow the template format (name, zones, structure, duration, coaching notes, selection criteria), the AI coaching system can reference them.

## Version

Current: **0.7.0**
