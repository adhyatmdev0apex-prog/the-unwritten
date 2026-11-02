# Generation Prompts — THE UNWRITTEN (Direction B Locked)

> **Source of Truth:** Matches [`plans/short/SHOT_LIST_1m30.md`](../plans/short/SHOT_LIST_1m30.md) (27 shots, 1:30 max) and [`plans/short/COMPETITION_CUT_58s.md`](../plans/short/COMPETITION_CUT_58s.md) (21-cut 58s reel).
> **Focus Guard:** Generate and lock the character reference sheets in `characters/lucien/` and `characters/elara/` BEFORE generating scene clips.

## Shared Prompt Blocks (Attach to Every Prompt)

- **`[STYLE]`**: `photorealistic cinematic fantasy film, 35mm lens optics, vertical 9:16 (1080x1920), controlled physical camera movement, realistic materials, natural skin texture, natural fabric folds, physically plausible inverse-square lighting falloff. Palette: slate-teal and cold-blue shadows, restrained 2700K molten-gold magic, weathered black basalt stone, aged bronze.`
- **`[LUCIEN]`**: `Lucien, 16, tall, observant dark eyes, dark tousled hair, tailored charcoal long school coat with subtle dark-teal lining and minimal bronze fasteners, carrying an old leather notebook. Match supplied character reference exactly.`
- **`[ELARA]`**: `Elara, 16, sharp observant expression, tailored charcoal long school coat with visible dark-teal scarf lining, wooden pencil tucked behind her ear. Match supplied character reference exactly.`
- **`[MARK]`**: `one thin molten-gold kintsugi line across the center of the palm, identical design in every shot, soft internal glow without excessive bloom.`
- **`[NEG]`**: `cartoon, anime, 3d render, plastic skin, excessive bloom, neon purple/blue magic, random glowing runes, shaky camera, morphing faces, extra fingers, distorted hands, costume changes, text, watermarks, black borders.`

---

## Step 1: Character Reference Prompts (Generate First)

### CHAR-01 — Lucien Master Reference Sheet
`photorealistic character turnaround reference sheet, vertical 9:16 layout, neutral studio grey background, soft even 5500K lighting: front portrait, 3/4 view portrait, side profile, and full-body standing pose of Lucien, a 16-year-old boy, tall, dark hair, calm observant eyes, wearing a tailored charcoal long school coat with subtle dark-teal inner lining and minimal bronze fasteners, holding an old leather notebook. Natural skin texture, film grain, 85mm portrait lens. [NEG]`

### CHAR-02 — Elara Master Reference Sheet
`photorealistic character turnaround reference sheet, vertical 9:16 layout, neutral studio grey background, soft even 5500K lighting: front portrait, 3/4 view portrait, side profile, and full-body standing pose of Elara, a 16-year-old girl, sharp intelligent eyes, wearing a tailored charcoal long school coat with a dark-teal scarf lining, a hexagonal wooden pencil tucked behind her ear. Natural skin texture, film grain, 85mm portrait lens. [NEG]`

### CHAR-03 — Hands & Palm Mark Reference
`photorealistic macro reference sheet, vertical 9:16: (top) two teenage hands—one male, one female—interlaced tightly; (bottom) two open palms side-by-side showing a single thin molten-gold kintsugi line across each palm that forms a continuous interwoven loop when joined. Natural skin texture, five fingers on each hand, warm 2700K gold rim light in cold slate shadow. [NEG]`

---

## Step 2: Scene-by-Scene Shot Prompts (27 Shots)

See [`plans/short/SHOT_LIST_1m30.md`](../plans/short/SHOT_LIST_1m30.md) for full camera, duration, audio, dialogue, and continuity specifications for `S01-SH01` through `S05-SH06`.

| Shot ID | 1:30 Short | 58s Comp Cut | Summary |
|---|---|---|---|
| `S01-SH01` | 3.0s (0:00–0:03) | Cut 1 (2.0s) | Fade in, back-of-class high angle sweeps down + slight zoom out |
| `S01-SH02` | 5.0s (0:03–0:08) | Cut 2 (3.0s) | Bell rings, students pack bags and leave; Lucien & Elara stay |
| `S01-SH03` | 5.0s (0:08–0:13) | Cut 3 (4.0s) | *"You're not even going to pretend you were studying?" / "I was trying to." / "Clearly."* |
| `S01-SH04` | 3.0s (0:13–0:16) | Cut 4 (2.0s) | Pencil rolls, stops dead at desk edge; thin gold crack under desk |
| `S01-SH05` | 2.0s (0:16–0:18) | Cut 5 (3.0s) | *"Lucien…?" / "Stay close."* Crack spreads; cut to black |
| `S02-SH01` | 2.0s (0:18–0:20) | Cut 6 (1.5s) | Classroom floor fractures into impossible geometry |
| `S02-SH02` | 3.0s (0:20–0:23) | Cut 7 (2.0s) | Falling together past upside-down forest, sky ocean, stone arches |
| `S02-SH03` | 2.0s (0:23–0:25) | Cut 8 (1.5s) | Hands slip apart in free fall, catch wrist and re-grip |
| `S02-SH04` | 2.0s (0:25–0:27) | *(Skipped)* | Land on black-stone causeway, release hands |
| `S02-SH05` | 5.0s (0:27–0:32) | Cut 9 (5.0s) | Crane rise: Gothic academy, floating bridges, turning dome, doors open |
| `S03-SH01` | 3.0s (0:32–0:35) | *(Skipped)* | Enter abandoned classroom of giant sketches and burned symbols |
| `S03-SH02` | 2.0s (0:35–0:37) | *(Skipped)* | Macro on unfinished humanoid drawing; one ink line twitches |
| `S03-SH03` | 4.0s (0:37–0:41) | Cut 10 (3.0s) | Ink creature emerges from parchment in 3D |
| `S03-SH04` | 3.0s (0:41–0:44) | *(Skipped)* | Creature stares at their hands; thin gold line crosses its body |
| `S03-SH05` | 4.0s (0:44–0:48) | Cut 11 (3.0s) | Creature leads toward sealed door bearing the fracture symbol |
| `S04-SH01` | 4.0s (0:48–0:52) | Cut 12 (3.5s) | Circular chamber, rotating bronze rings around zero-reflection sphere |
| `S04-SH02` | 3.0s (0:52–0:55) | *(Skipped)* | Rings slow and stop; Lucien steps forward |
| `S04-SH03` | 5.0s (0:55–1:00) | Cut 13 (4.0s) | Gold fissures form exact shape of interlaced fingers (*"Have we been here before?"*) |
| `S04-SH04` | 3.0s (1:00–1:03) | Cut 14 (2.0s) | Matching golden marks appear across both palms |
| `S04-SH05` | 4.0s (1:03–1:07) | Cut 15 (3.0s) | Silhouettes across unfamiliar worlds (*"Then why does this feel familiar?"*) |
| `S04-SH06` | 3.0s (1:07–1:10) | Cut 16 (1.5s) | Golden light dies; enormous shape moves in darkness behind sphere |
| `S05-SH01` | 4.0s (1:10–1:14) | *(Skipped)* | Rings spin backward; Elara reaches toward Lucien and hesitates |
| `S05-SH02` | 5.0s (1:14–1:19) | Cut 17 (5.0s) | Lucien deliberately takes her hand (*"Whatever that thing is… we face it together."*) |
| `S05-SH03` | 3.0s (1:19–1:22) | Cut 18 (2.0s) | Sphere illuminates chamber; gold lines race through academy walls |
| `S05-SH04` | 2.0s (1:22–1:24) | Cut 19 (1.5s) | Rotating dome stops; every window turns black |
| `S05-SH05` | 3.0s (1:24–1:27) | Cut 20 (2.5s) | Enormous shape behind sphere opens one glowing golden eye |
| `S05-SH06` | 3.0s (1:27–1:30) | Cut 21 (3.0s) | Cut to black; golden fissure forms **THE UNWRITTEN** |
