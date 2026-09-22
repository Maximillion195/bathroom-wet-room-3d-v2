# Bathroom wet room — AI send package

Use this folder with an image AI (ChatGPT, Gemini, Midjourney, Flux, etc.) to generate a **nicer-looking version** while **keeping the same layout and proportions**.

## Files to attach

1. **`plan-topdown.png`** — measured top-down plan (authoritative for layout). **Custom schematic** with simple fixture symbols, spaced margin labels, and leader lines. Do **not** use Sweet Home 3D’s built-in 2D plan export — it shows clock/watch placeholder icons for custom furniture and overlapping duplicate labels.
2. **`view-from-door.jpg`** — eye-level from door, looking into room
3. **`view-toward-shower.jpg`** — eye-level toward shower / green wall
4. **`view-overhead.jpg`** — 3D overhead for spatial context
5. **`bathroom-3d.zip`** *(optional)* — full 3D OBJ model for technical viewers

## Plan orientation (important)

On **`plan-topdown.png`**:
- **Top** = door wall
- **Bottom** = window wall
- **Left** = vanity wall
- **Right** = shower / green tile wall

Standing at the **door facing the window** (into the room):
- **Left** = shower zone
- **Right** = vanity
- **Back** = window + bath
- **Back-left** = toilet on soil boxing

## Room (fixed — do not change)

- **Size:** 215.2 cm wide × 236.9 cm deep (door ↔ window), ceiling 237.2 cm
- **Type:** wet room — **no shower tray**
- **Soil box:** back-left, 18.4 × 77 cm, with 18.4 × 18.4 window chase + two shelf notches above toilet

## Fixture layout (keep positions)

| Fixture | Location (from door, facing in) | Notes |
|---------|----------------------------------|-------|
| Door | Front wall (top on plan), ~68 cm clear | Larger reveal on left |
| Window | Back wall (bottom on plan), centred | ~135 × 100 cm |
| Shower | **Left wall** | Open wet zone, square floor grate on green wall |
| Shower mixer | Left / green wall, waist height | Brushed brass thermostatic |
| Green feature wall | Full height on left wall | Subway tile, deep green |
| Glass screen | Walk-in panel from **door wall** | Frameless glass, open entry from door side |
| Toilet | On soil box, back-left | Wall-hung |
| Bath | **Back-right corner** (window side) | Freestanding island bath |
| Vanity | **Right wall**, floating ~24 cm off floor | Light oak cabinet, white top, basin, slim mirror |
| Vanity tap | Brass wall/deck mixer | Brushed brass |
| Floor | Whole room | Large grey tiles |

## Style direction

- Contemporary luxury wet room
- Palette: warm white walls, **deep green subway** shower wall, **light oak** vanity, **brushed brass** all metalwork
- Materials: matte large-format grey floor tiles, gloss/satin green wall tiles, frameless glass, freestanding bath as hero
- Lighting: soft natural daylight from window + warm mirror backlight + subtle ceiling wash
- Mood: calm, spa-like, high-end residential

## Hard constraints for the AI

- **Do not move** door, window, toilet, bath, vanity, shower, grate, or glass screen relative to the plan
- **Do not add** a shower tray, bath screen, or extra fixtures
- **Do not change** room dimensions or wall positions
- **Do improve:** materials, lighting, realism, styling, and atmosphere only

---

## Copy-paste prompt

```
Create a photorealistic interior render of this bathroom using the attached plan and reference views.

CONSTRAINTS (must follow exactly):
- Room size: 215.2 cm × 236.9 cm, ceiling 237.2 cm — wet room, NO shower tray
- Keep all fixture positions exactly as shown in the top-down plan
- On the plan: door at TOP, window at BOTTOM
- From door facing in: shower on LEFT, vanity on RIGHT, bath in BACK-RIGHT corner, toilet BACK-LEFT on soil boxing
- Walk-in frameless glass screen from door wall in front of shower (open entry from door side)
- Green subway tile feature wall full height on shower wall; grey floor tiles throughout
- Floating light-oak vanity with white top, wall-hung toilet, freestanding bath at window corner
- All tapware brushed brass

STYLE:
Contemporary luxury spa bathroom — warm, calm, high-end residential. Improve materials, lighting and realism only. Do not change layout or add/remove fixtures.

Output: one wide eye-level hero shot from the door, photorealistic.
```
