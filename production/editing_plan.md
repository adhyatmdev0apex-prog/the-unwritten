# Editing & Post-Production Plan — THE UNWRITTEN

**Recommended Editor:** DaVinci Resolve (or a lighter conventional editor if needed)
**Encoding & Validation Utility:** FFmpeg
**Deliverables:**
1. **Canonical Short Film:** `1:50` (110 seconds) — saved in `films/extended-cut/` (or short-film master folder)
2. **Competition Cut:** `0:58` (58 seconds, strictly within 45–60s) — saved in `films/competition-cut/`

---

## 1. Timeline Setup (DaVinci Resolve)
- **Timeline Resolution:** `1080 × 1920` (Vertical 9:16)
- **Frame Rate:** `24 fps` (or `30 fps`, consistent across all clips)
- **Color Space:** Rec.709 (Scene-referred grade progression: warm afternoon classroom → cold slate-teal fall/academy → deep obsidian chamber with restrained 2700K gold highlights)

---

## 2. Two-Deliverable Editing Workflow

1. **Assemble the 1:50 Canonical Master First:**
   - Place the 27 approved clips in order (`S01-SH01` through `S05-SH06`) using [`plans/short/SHOT_LIST_1m50.md`](../plans/short/SHOT_LIST_1m50.md).
   - Verify Scene timings: Scene 1 (`20s`), Scene 2 (`20s`), Scene 3 (`20s`), Scene 4 (`25s`), Scene 5 (`25s`) = **110 seconds**.
2. **Build the Independent 58-Second Competition Cut:**
   - Duplicate the project timeline and re-edit to the 21-cut structure in [`plans/short/COMPETITION_CUT_58s.md`](../plans/short/COMPETITION_CUT_58s.md).
   - Do **not** simply truncate the 1:50 film at 0:58—preserve the full narrative arc (classroom → fall & academy → ink creature → sphere & marks → deliberate hand-take, golden eye, and title).
3. **Title Card (`S05-SH06`):**
   - Build the final 3–4 second title card (`THE UNWRITTEN` emerging from a thin golden fissure on black) directly in DaVinci Resolve so typography is razor-sharp and free of AI text artifacts.

---

## 3. Six-Track Audio Architecture

Never use messy raw audio from video generators for the final mix. Lay out six dedicated tracks:

| Track | Content | Notes |
|---|---|---|
| **A1** | Classroom ambience & school bell | Warm room tone, rustling papers, bell at `0:04`, chairs scraping, footsteps leaving |
| **A2** | Lucien's dialogue | 7 lines in 1:50 version (4 lines in 58s cut); dry, intimate delivery |
| **A3** | Elara's dialogue | 8 lines in 1:50 version (3 lines in 58s cut); natural, understated delivery |
| **A4** | Supernatural & Foley SFX | Pencil roll/stop, kintsugi crack, tectonic floor break, wind, basalt footsteps, ink scrape, bronze rings, heartbeat, 20Hz eye sub-bass, final impact |
| **A5** | Musical Score | Generated via the Master Music Prompt in [`generation_prompts.md`](generation_prompts.md) (licensed/original); silent during the chamber reveal right before the final impact |
| **A6** | Master Bus / Final Mix | Peak level at `-1.0 dBTP`, integrated loudness around `-14 LUFS`, zero clipping |

---

## 4. FFmpeg Validation & Export Commands

```powershell
# 1. Normalize an individual generated clip to 1080x1920 @ 24fps (strip scratch audio)
ffmpeg -i raw_clip.mp4 -vf "scale=1080:1920:force_original_aspect_ratio=increase,crop=1080:1920,fps=24" -an normalized_clip.mp4

# 2. Encode the final Competition Cut (58s, 1080x1920, well under 100 MB)
ffmpeg -i resolve_export_58s.mov -c:v libx264 -profile:v high -pix_fmt yuv420p -crf 20 -preset slow -c:a aac -b:a 192k -movflags +faststart films/competition-cut/THE_UNWRITTEN_58s.mp4

# 3. Verify exact duration, resolution, aspect ratio, and file size
ffprobe -v error -show_entries format=duration,size -show_entries stream=width,height,r_frame_rate -of default=noprint_wrappers=1 films/competition-cut/THE_UNWRITTEN_58s.mp4
```
