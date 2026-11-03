# Short-Film Prompt Hub — THE UNWRITTEN

This directory contains the production-ready prompts engineered specifically for **10-second generation tools** (Gemini Omni 1.1 Flash / Google Flow / Veo).

---

## 📁 Available Workflows

### 1. [`COMPETITION_6_CLIPS_10S.md`](COMPETITION_6_CLIPS_10S.md) *(Recommended First)*
- **Runtime:** **58.0 Seconds** (Strictly within VIBGYOR 45–60s competition limit)
- **Structure:** 6 connected clips (10s + 10s + 10s + 10s + 10s + 8s)
- **Features:**
  - Preserves the full arc (Classroom → Fall → Academy & Enchanted Class → Living painting & Library → Forbidden Corridor → Sphere & Eye).
  - Every clip has explicit 3-layer instructions: Permanent Rules, Second-by-Second Choreography, and Camera Instructions.
  - Visual Anchor guide: use the last frame of Clip N as the start reference of Clip N+1.

### 2. [`MASTER_90S_CLIPS.md`](MASTER_90S_CLIPS.md)
- **Runtime:** **90.0 Seconds (1:30 max)**
- **Structure:** 9 clips of 10.0 seconds each
- **Features:**
  - Contains the full **40% Exploration Core (36s)**: dedicated shots for the enchanted classroom, the folding equation doorway, the infinite library, the ancient tome, and the covered corridor.

---

## ⚙️ Model Settings (Gemini Omni 1.1 Flash / Veo)
- **Aspect Ratio:** `9:16` Vertical (1080 × 1920)
- **Duration:** `10 seconds` (or `8 seconds` for Clip 6)
- **Resolution:** `720p` or `1080p`
- **Frame Rate:** `24 FPS`
- **Thinking:** `High`

## 🛠️ The Production Flow
1. **Generate Character Turnarounds First:** Use `characters/lucien/` and `characters/elara/` prompts in [`production/generation_prompts.md`](../../production/generation_prompts.md).
2. **Generate Clip 1:** Paste prompt from `COMPETITION_6_CLIPS_10S.md`. Inspect character stability.
3. **Capture End Frame:** Export the final frame of Clip 1 as a JPEG/PNG.
4. **Generate Clip 2:** Attach the end frame of Clip 1 as the visual reference along with the Clip 2 prompt.
5. **Assemble in Post-Production:** Join the 6 clips in DaVinci Resolve, place dialogue from [`plans/short/DIALOGUE.md`](../../plans/short/DIALOGUE.md), add SFX/Score, and export via FFmpeg.
