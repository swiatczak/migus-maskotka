# Stitch/Count Review (tables) — Standard + Keychain mini

Reference image used: `images/body/crocheted-amigurumi-doll-keychain.png`

![Reference keychain doll](../../images/body/crocheted-amigurumi-doll-keychain.png)

Assumptions for math checks:
- US terms; worked in **continuous rounds** unless stated.
- `inc` = 2 sc in 1 stitch (**+1 stitch**). `dec` = sc2tog / invisible decrease (**-1 stitch**).
- End count per round = `start + (#inc) - (#dec)`.

## Summary (validity of table counts)

| File | Section | Table math | Integration / notes |
|---|---|---:|---|
| `baseball_cap.md` | Crown + brim | ✅ | Brim attachment span matches final brim width. |
| `body.md` | Torso (Std + mini) | ✅ | Pattern closes to 6 sts; if this is a **torso**, you likely want an opening for joining to head/legs. |
| `pants.md` | Legs + join + waist | ✅ (counts), ⚠️ (clarity) | Join round is count-correct but needs clearer “where round starts” + chain-bridge handling. Mini waist (22/20) does **not** match mini torso widest (18). |
| `hair.md` | Hair cap | ✅ | Cap rounds/counts are fine. |
| `hair.md` | Attachment zones | ✅ | Zones are now defined by **layer/round**, so totals stay consistent. |

---

## `baseball_cap.md` — Baseball cap counts

### Crown (Standard, 30 sts)
- R1–R5: classic 6‑increase circle: 6 → 12 → 18 → 24 → 30 ✅
- R6–R9: even rounds at 30 ✅
- R10: “sl st around” = 30 slip stitches ✅ (note: optional round; keep it consistent with how you’ll sew the brim)

### Crown (Mini, 24 sts)
- R1–R4: 6 → 12 → 18 → 24 ✅
- R5–R7: even rounds at 24 ✅

### Brim rows
Standard brim:
- Row 1: `ch 7`, sc in 2nd ch, sc 5 ⇒ 6 sc ✅
- Row 2: `inc, sc 4, inc` on 6 sts ⇒ 8 ✅
- Row 3: `inc, sc 6, inc` on 8 sts ⇒ 10 ✅

Mini brim:
- Option A (2 rows): 5 → 7 ✅
- Option B (3 rows): 5 → 7 → 9 ✅

Attachment span check:
- Standard brim top width is 10 sts; guide says sew across 10 sts ✅
- Mini brim top width is 7 or 9; guide says 7–9 ✅

---

## `body.md` — Torso counts

### Standard torso (max 24)
- R1–R4: 6 → 12 → 18 → 24 ✅
- R5–R9: 24 ✅
- R10: `(2sc, dec) x6` = 6 decreases ⇒ 24 − 6 = 18 ✅
- R12: `(sc, dec) x6` = 6 decreases ⇒ 18 − 6 = 12 ✅
- R13: `dec x6` ⇒ 12 − 6 = 6 ✅

### Keychain mini torso (max 18)
- R1–R3: 6 → 12 → 18 ✅
- R4–R6: 18 ✅
- R7: `(sc, dec) x6` ⇒ 18 − 6 = 12 ✅
- R8: `dec x6` ⇒ 12 − 6 = 6 ✅

Design/proportion note (based on the reference image):
- The reference is a **keychain chibi** with a very large head and compact torso; the *counts* here produce a neat “bean/capsule” body.
- If you need a **true torso** that joins to head/legs, consider stopping while still at the target circumference and leaving an opening (instead of decreasing down to 6 and closing).

---

## `pants.md` — Pants counts + join logic

### Standard leg (top is 10 sts)
- R1–R2: 6 → 12 ✅
- R3–R8: 12 ✅
- R9: `(sc 4, dec) x2` = 2 decreases ⇒ 12 − 2 = 10 ✅
- R10–R11: 10 ✅

### Standard join round (target 24)
Round 12 states: `10 (leg2) + ch2 + 10 (leg1) + ch2 = 24` ✅

Clarity risks (math is fine, but crocheters can lose the round start):
- In continuous rounds, explicitly state **where the next round begins** after the final chain bridge; place the marker in that first stitch.
- When you “include chains as stitches”, say *how* (e.g., “sc into each chain”).

Waist shaping:
- R17: 24 with 2 decreases ⇒ 22 ✅
- R20: 22 with 2 decreases ⇒ 20 ✅

Integration check (Standard):
- Standard pants waist is 24, which matches Standard torso’s widest (24) ✅

### Keychain mini (integration check)
Mini legs now end at **8 sts** each; join gives:
- Join: `8 + ch1 + 8 + ch1 = 18` ✅

This matches mini torso widest **18** (`body.md`) ✅

---

## `hair.md` — Hair cap + attachment-zone counts

### Hair cap counts
Standard cap:
- R1–R5: 6 → 12 → 18 → 24 → 30 ✅
- R6–R7: 30 ✅

Mini cap:
- R1–R4: 6 → 12 → 18 → 24 ✅
- R5–R6: 24 ✅

### Attachment zones (count-consistent approach)
Define “zones” by **round/layer**, not by trying to subdivide a single edge multiple ways:
- Layer A: edge (fringe + edge filler) on the last round
- Layer B: crown sweep on the round above
- Layer C: optional top/back fill on the round above that

This keeps totals consistent and matches how the locks are physically layered on a 3D cap.

---

## Reference image → “full figure” vs “miniature” guidance (count implications)

The reference is a **mini keychain** seated doll (short torso, compact legs, oversized head).

To keep the same *style* in a larger “full figure”:
- Keep widths similar (chibi proportions), and increase **length** more than circumference:
  - Add 1–3 extra plain rounds to torso before shaping.
  - Add 2–6 extra plain rounds to legs before the join/waist.

To keep the mini closer to the reference:
- Shorten legs (fewer straight rounds) and keep the torso compact.
- Ensure pants waist and torso widest match (see mini mismatch in `pants.md` vs `body.md`).

Seated vs standing (important for “looks like the photo”):
- The photo’s legs are visually **bent** and the feet are prominent; `pants.md` produces straight tubes.
- If you want the same seated silhouette, the count tables can stay correct, but you’ll need *construction changes* (e.g., sew legs on at an angle, add foot pieces, or add a bend with shaping/short rows).
