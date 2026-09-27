# 3-Day Push / Pull + Legs Programme

**Structure:** 3 sessions/week, at least one rest day between each (e.g. Mon / Wed / Fri).
**Session length:** ~60–70 min.
**Every session:** 5-min warm-up → main leg lift → Superset A → Superset B → leg accessory → core finisher.

| Day | Upper focus | Leg focus |
|-----|-------------|-----------|
| A   | Push        | Quads (squat pattern) |
| B   | Pull        | Posterior chain (hinge pattern) |
| C   | Push + Pull mix | Single-leg |

Rotating A → B → C means every movement pattern is trained once a week at high quality, with no day where legs are hammered twice in a row.

---

## Warm-up (5 min, every session)

1. 1 min – bike / row / skipping, easy pace
2. 10 x world's greatest stretch (5 per side)
3. 10 x band pull-aparts
4. 10 x bodyweight squats
5. 1–2 lighter ramp-up sets of your first lift (not counted as working sets)

---

## Day A – Push + Quads

| # | Exercise | Sets x Reps | Rest | Notes |
|---|----------|-------------|------|-------|
| 1 | Back Squat (or Hack Squat) | 4 x 5–8 | 2–3 min | Main lift. Leave 1–2 reps in the tank |
| 2a | Barbell / DB Bench Press | 4 x 6–10 | – | Straight into 2b |
| 2b | Chest-Supported Row (light, for balance) | 4 x 10–12 | 90 s | |
| 3a | Seated DB Shoulder Press | 3 x 8–12 | – | Straight into 3b |
| 3b | Cable Triceps Pushdown | 3 x 10–15 | 60–90 s | |
| 4 | Leg Extension | 3 x 12–15 | 60 s | Pause 1 s at the top |
| **Core** | Dead Bug + Plank | 3 rounds: 10/side + 40 s | 30 s | Circuit |

## Day B – Pull + Posterior Chain

| # | Exercise | Sets x Reps | Rest | Notes |
|---|----------|-------------|------|-------|
| 1 | Romanian Deadlift | 4 x 6–10 | 2–3 min | Main lift. Hips back, stop when hamstrings are stretched |
| 2a | Pull-up / Lat Pulldown | 4 x 6–10 | – | Straight into 2b |
| 2b | Push-up (balance) | 4 x 10–15 | 90 s | |
| 3a | Seated Cable Row | 3 x 8–12 | – | Straight into 3b |
| 3b | DB Hammer / Bicep Curl | 3 x 10–15 | 60–90 s | |
| 4 | Lying / Seated Leg Curl | 3 x 10–15 | 60 s | Slow on the way down (3 s) |
| **Core** | Hanging Knee Raise + Side Plank | 3 rounds: 12 + 30 s/side | 30 s | Circuit |

## Day C – Push/Pull Mix + Single-Leg

| # | Exercise | Sets x Reps | Rest | Notes |
|---|----------|-------------|------|-------|
| 1 | Bulgarian Split Squat | 3 x 8–10 per leg | 90 s | Main lift. Hold DBs |
| 2a | Incline DB Press | 3 x 8–12 | – | Straight into 2b |
| 2b | Single-Arm DB Row | 3 x 10–12 per arm | 90 s | |
| 3a | Lateral Raise | 3 x 12–20 | – | Straight into 3b |
| 3b | Face Pull | 3 x 12–15 | 60 s | |
| 4 | Hip Thrust (or Walking Lunge) | 3 x 10–12 | 90 s | |
| 5 | Standing Calf Raise | 3 x 12–15 | 45 s | Pause at bottom |
| **Core** | Pallof Press + Ab Wheel / Stir-the-Pot | 3 rounds: 10/side + 8–10 | 30 s | Circuit |

---

## The part that actually drives results: progression

**Double progression** on every exercise:

1. Pick a weight you can do for the **bottom** of the rep range with 1–2 reps left in the tank.
2. Each session, add reps with the same weight.
3. When you hit the **top** of the range on **all** sets → increase load next time
   (upper body +1–2.5 kg, lower body +2.5–5 kg) and drop back to the bottom of the range.
4. Log **every set**: exercise, weight, reps, reps-in-reserve (RIR).

If a lift has not moved in 3 sessions: check sleep and calories first, then swap the exercise for a close variation.

## Block structure (7 weeks, then repeat)

| Weeks | Focus |
|-------|-------|
| 1–2 | Settle weights. Stop 2 reps short of failure |
| 3–5 | Push. Stop 1 rep short; last set of each isolation exercise to failure |
| 6 | Heaviest week – aim for rep PRs |
| 7 | Deload – same exercises, half the sets, ~10% lighter |

Re-test after each block: squat/RDL 6-rep weight, bench 8-rep weight, max pull-ups, bodyweight (7-day average), waist measurement.

## Nutrition targets (set before starting)

- **Protein:** 1.6–2.2 g per kg of bodyweight daily. Non-negotiable regardless of goal.
- **Calories – pick ONE goal per block:**
  - Build muscle: ~200–300 kcal above maintenance; aim to gain ~0.25–0.5% bodyweight/week.
  - Lose fat: ~300–500 kcal below maintenance; aim to lose ~0.5–1% bodyweight/week.
- Weigh daily, judge on the **weekly average**, adjust calories by ~150 kcal if the trend is off for 2 weeks.

## Data to capture (for the app you're planning)

Minimum schema that makes this programme trackable:

- `session`: date, day type (A/B/C), block week, bodyweight
- `set`: exercise, set number, weight, reps, RIR, superset tag
- `daily`: calories, protein (g), sleep hours
- `block_test`: date, test lift results, waist measurement

With that data you can auto-flag "ready to increase load" (top of range hit on all sets) and "stalled" (no progress in 3 sessions).
