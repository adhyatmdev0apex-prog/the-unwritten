# 🎬 58-SECOND COMPETITION CUT — 6-CLIP MASTER GENERATION PIPELINE
## Engineered for Gemini Omni 1.1 Flash / Veo (10-Second Generation Limit)

> [!IMPORTANT]
> **Generation Hardware & Model Settings:**
> - **Model:** Gemini Omni 1.1 Flash / Veo
> - **Aspect Ratio:** `9:16` Vertical
> - **Resolution:** `720p` (or `1080p`)
> - **Frame Rate:** `24 FPS`
> - **Thinking:** `High`
> - **Max Duration per Clip:** `10 seconds`
> - **Total Duration:** 10s + 10s + 10s + 10s + 10s + 8s = **58 Seconds Exact** (Strictly within VIBGYOR 45–60s limit)

---

## 🛡️ THE GOLDEN RULES FOR THE MODEL (Treat It Like an Inexperienced Director)

The model can produce breathtaking visuals, but if left unconstrained, it will hallucinate floating crystals, random sci-fi gadgets, costume changes, or facial morphing. 

To guarantee continuity across all 6 clips:
1. **Never ask the model to generate the whole movie at once.** Give it ONE clip at a time.
2. **Every prompt contains 3 strict layers:**
   - **Layer 1: Permanent Rules** (Character identity, costumes, world aesthetic, photorealism, strict negative constraints).
   - **Layer 2: Second-by-Second Scene Instructions** (Precise choreography for the 10 seconds).
   - **Layer 3: Camera & Transition Instructions** (Focal length, movement speed, start/end framing).
3. **The Visual Anchor Technique:** Take the **exact last frame** of Clip N, save it as a still image, and upload it as the start-frame visual reference for Clip N+1.
4. **Dialogue & Sound are Added in Post-Production:** Do NOT ask the video generator to synthesize audio, dialogue, or lip-sync. Video models distort faces when trying to speak. Dialogue and score are mixed on separate tracks in DaVinci Resolve.

---

## 📋 CLIP BREAKDOWN SUMMARY (58 SECONDS TOTAL)

| Clip | Target Duration | Scene Narrative | Start Anchor → End Anchor |
|---|---|---|---|
| **Clip 1** | **10.0s** | Ordinary classroom → Bell rings → Students leave → Teasing moment → Golden fissure cracks under desk | Black screen → Crack spreading across floor |
| **Clip 2** | **10.0s** | Floor fractures → Free fall past surreal worlds → Wrist catch → Causeway landing → Monumental Academy reveal | Fracturing floor → Academy central doors opening |
| **Clip 3** | **10.0s** | Enchanted maths classroom (floating desks & constellations) → Science lab (spinning galaxy & equation doorway) | Stepping through academy doors → Equation doorway folding |
| **Clip 4** | **10.0s** | Living painting on stone wall → Dimensional infinite library → Ancient tome opens with golden fracture symbol | Entering library → Lucien pointing at glowing symbol |
| **Clip 5** | **10.0s** | Forbidden corridor with shrouded portraits → Lanterns click dark → 20-foot sealed iron door glides open | Shrouded hallway → Gliding into dark circular chamber |
| **Clip 6** | **8.0s** | Hand hesitates → Lucien takes Elara's hand → Palm marks connect → Dome stops → Colossal golden eye opens → Title | Both hands joining → Golden eye reflecting them → Black Title |

---

# 🚀 THE 6 PRODUCTION PROMPTS (COPY-PASTE READY)

---

### 🎬 CLIP 1 of 6: The Ordinary Classroom & The First Fracture
* **Duration:** `10.0 seconds`
* **Scene Timeline:**
  * `0:00–0:04`: Camera at back of warm classroom sweeps down to eye-level. Students finishing work in afternoon sunbeams.
  * `0:04–0:07`: School bell rings. Students stand, pack backpacks, and file out of the open door. Lucien and Elara remain seated at their wooden desk in mid-room.
  * `0:07–0:09`: Lucien closes his leather notebook; Elara glances at his unfinished work with an amused smile. (Dialogue in post: *"You're not even going to pretend you were studying?" / "I was trying to."*)
  * `0:09–0:10`: A hexagonal wooden pencil rolls and stops dead at the desk edge without falling. Beneath the desk, a hair-thin crack of glowing molten gold splits the floor shadow. Elara looks down in surprise.
* **Anchor Reference to Upload:** Initial classroom reference image (`assets/references/classroom.png`) + Lucien & Elara character turnarounds.

#### Prompt to Paste:
```text
[PERMANENT RULES - DO NOT VIOLATE]
Format: Vertical 9:16 composition. 24 FPS. Live-action cinematic photorealism.
Characters:
- LUCIEN: 16-year-old teenage boy, tall, dark tousled hair, thoughtful observant eyes, tailored charcoal school coat with dark-teal lining, carrying a worn leather notebook.
- ELARA: 16-year-old teenage girl, natural understated appearance, tailored charcoal school coat with visible dark-teal scarf lining, small wooden pencil behind her ear.
Style: Natural warm late-afternoon sunlight, 35mm lens optics, realistic wooden desks, natural fabric folds, physically plausible shadows.
STRICT NEGATIVE CONSTRAINTS: No cartoon, no anime, no 3D CGI look, no neon purple/blue light, no floating gadgets, no invented characters, no camera shake, no morphing faces, no generated dialogue or text.

[SCENE INSTRUCTIONS - EXACT 10-SECOND SEQUENCE]
Second 0-4: Fade in from black. An ordinary high school classroom in warm late-afternoon light with dust motes drifting in sunbeams. Students are finishing work at wooden desks. Lucien and Elara sit calmly together at a desk in mid-room.
Second 4-7: The classroom bell rings. Other students stand, pack backpacks, and walk out through the doorway. Lucien and Elara stay seated at their desk, watching. Hands rest on the desk, not touching.
Second 7-9: Lucien closes his old leather notebook. Elara looks over at his unfinished page with a small amused smile. Understated friendly chemistry. They do not hold hands.
Second 9-10: On their desk, a hexagonal wooden pencil rolls normally, reaches the edge, and stops dead in mid-air without falling. Camera tilts downward to the shadow beneath their desk where a hairline crack of intense molten gold splits the floor like glowing kintsugi, casting warm amber rim-light on their shoes.

[CAMERA & MOVEMENT INSTRUCTIONS]
Start high at the back of the classroom looking down, smoothly sweeping down to a straight-on eye-level view with a very slight zoom out during seconds 0-4. Hold steady during departure. At second 9, smoothly tilt downward toward the rolling pencil and floor shadow beneath the desk. Clean end-frame on the spreading golden fissure.
```

---

### 🎬 CLIP 2 of 6: The Fall & The Academy Reveal
* **Duration:** `10.0 seconds`
* **Scene Timeline:**
  * `0:00–0:03`: The classroom floor fractures along golden seams into an infinite dark abyss. Lucien and Elara fall together past fragments of surreal worlds (an upside-down pine forest, floating Gothic arches, an ocean suspended in sky).
  * `0:03–0:05`: In free fall, their hands slip apart; Lucien reaches out and catches Elara's wrist; she grips his hand firmly.
  * `0:05–0:06`: They land solidly on a wet black-basalt stone causeway suspended above a vast sea of teal clouds. They steady each other and immediately release hands.
  * `0:06–0:10`: Camera executes a slow, majestic crane pedestal rise behind them to reveal the colossal Gothic academy floating above the clouds. Towers rise into mist, floating bridges link cliffs, a massive central bronze dome rotates slowly, and tall windows glow with teal light. The central doors slowly open.
* **Anchor Reference to Upload:** Last frame of Clip 1 (fissure under desk) + Academy Concept Image (`assets/references/academy.png`).

#### Prompt to Paste:
```text
[PERMANENT RULES - DO NOT VIOLATE]
Format: Vertical 9:16 composition. 24 FPS. Live-action cinematic photorealism.
Characters: Same LUCIEN (16, charcoal coat with dark-teal lining, dark hair) and same ELARA (16, charcoal coat with dark-teal scarf lining). Identical faces, clothing, and proportions to Clip 1.
World: Monumental Gothic fantasy architecture, weathered black basalt stone, aged bronze gears, cold slate-teal clouds, restrained molten-gold light.
STRICT NEGATIVE CONSTRAINTS: No cartoon, no anime, no plastic skin, no extra limbs, no distorted hands, no spaceships, no sci-fi lasers, no camera roll, no generated text.

[SCENE INSTRUCTIONS - EXACT 10-SECOND SEQUENCE]
Second 0-3: The wooden classroom floor breaks open along geometric molten-gold seams into deep void. Lucien and Elara fall in free fall side-by-side through an impossible surreal dimension, passing an upside-down pine forest floating above and stone arches drifting in dark mist. Clothes flutter naturally in high wind.
Second 3-5: Close macro view in free fall: their hands reach out, slip, and Lucien firmly catches Elara's wrist as she grips his hand back. Five fingers per hand, natural skin texture.
Second 5-6: They land with solid physical weight on a wet black-basalt stone causeway above an endless ocean of rolling teal clouds. Lucien steadies Elara; they immediately let go of their hands and stand side-by-side, breathing hard.
Second 6-10: Both characters stand small in the foreground looking upward in awe (not holding hands). Before them, their ordinary school has transformed into an immense Gothic academy floating above the clouds: towering black stone spires, floating bridges, moving staircases, a massive rotating bronze astrolabe dome, and teal stained-glass windows. The central arched doors slowly part open.

[CAMERA & MOVEMENT INSTRUCTIONS]
Begin with a dynamic downward tracking shot following the fall (0-3s). Quick cut to macro hand grip (3-5s). Cut to low angle on stone causeway (5-6s), transitioning into a slow, majestic crane pedestal rise upward behind their shoulders from low-angle to extreme wide establishing framing (6-10s).
```

---

### 🎬 CLIP 3 of 6: The Enchanted Classroom & The Equation Doorway
* **Duration:** `10.0 seconds`
* **Scene Timeline:**
  * `0:00–0:05`: Lucien and Elara step through the grand entrance into an enchanted Gothic classroom. Desks float weightlessly in zero gravity at varying heights. An antique slate blackboard displays rotating golden star constellations. Spun-gold mathematical vectors drift through the air.
  * `0:05–0:08`: They walk toward a carved teacher's desk where a delicate miniature solar system rotates with glowing rings. A complex geometric equation folds inward like origami into a glowing golden doorway.
  * `0:08–0:10`: Close-up as Elara reaches her hand toward the glowing equation doorway. The golden light bends gently toward her fingertips like living light. She smiles in pure wonder; Lucien watches beside her.
* **Anchor Reference to Upload:** Last frame of Clip 2 (central academy doors parting) + Enchanted Classroom Reference (`assets/references/enchanted_classroom.png`).

#### Prompt to Paste:
```text
[PERMANENT RULES - DO NOT VIOLATE]
Format: Vertical 9:16 composition. 24 FPS. Live-action cinematic photorealism.
Characters: Same LUCIEN and same ELARA in identical charcoal school coats with dark-teal lining. Identical faces, hairstyles, and costumes. Hands are NOT joined.
Environment: Ancient Gothic classroom of weathered black stone, tall lancet windows with teal twilight outside, warm 2700K golden magical equations, dust motes.
STRICT NEGATIVE CONSTRAINTS: No cartoon, no anime, no wand shooting, no neon fairy wings, no chaotic floating debris, no face morphing, no generated text.

[SCENE INSTRUCTIONS - EXACT 10-SECOND SEQUENCE]
Second 0-5: Smooth tracking shot following Lucien and Elara as they walk cautiously into an enchanted Gothic classroom. Wooden school desks float gently in zero gravity at different heights around the room. On the back wall, a giant antique blackboard displays glowing golden star constellations moving in real time. Three-dimensional mathematical equations made of spun gold drift slowly through the air.
Second 5-8: They approach a heavy dark-wood teacher's desk. Above the desk, a miniature glowing solar system rotates with tiny planets and orbital rings. A complex geometric equation hovering in the air folds inward upon itself like golden origami, expanding into a rectangular glowing dimensional doorway.
Second 8-10: Close-up on Elara's hand reaching toward the folding equation doorway. As her fingers approach, the golden light bends and ripples gently toward her skin. Her face expresses awe and wonder, not fear. Lucien stands half a pace behind her, looking at the doorway with intense curiosity.

[CAMERA & MOVEMENT INSTRUCTIONS]
Begin as a smooth forward tracking dolly behind the characters entering the classroom (0-5s). Pan gently toward the teacher's desk and the folding equation (5-8s). Move into a medium close-up pushing toward Elara's hand and the doorway of light (8-10s).
```

---

### 🎬 CLIP 4 of 6: The Living Painting & The Library Between Worlds
* **Duration:** `10.0 seconds`
* **Scene Timeline:**
  * `0:00–0:04`: Stepping through the glowing doorway, they enter a colossal multi-tiered Gothic library. Thousands of leather-bound books orbit a massive spiral stone staircase in smooth zero-gravity rings. A giant rose window reveals a purple spiral galaxy.
  * `0:04–0:07`: Along the stone balustrade, they pass an ancient living architectural painting on the wall where hand-drawn ink figures and architectural lines visibly move and shift.
  * `0:07–0:10`: On a carved stone pedestal, an ancient leather tome opens itself. Lucien and Elara lean over it. On the aged vellum page is an illustration of the academy marked with the exact geometric golden fracture symbol from their classroom desk. Lucien points to it; wonder turns to mystery.
* **Anchor Reference to Upload:** Last frame of Clip 3 (stepping through equation door) + Library Concept Reference (`assets/references/library.png`).

#### Prompt to Paste:
```text
[PERMANENT RULES - DO NOT VIOLATE]
Format: Vertical 9:16 composition. 24 FPS. Live-action cinematic photorealism.
Characters: Same LUCIEN and same ELARA in identical charcoal coats with dark-teal lining. Identical faces, hair, and clothing. Hands are separate.
Environment: Monumental infinite Gothic library, spiral stone staircases, floating brass book platforms, deep violet-indigo galaxy outside the rose window, warm candlelight.
STRICT NEGATIVE CONSTRAINTS: No cartoon, no anime, no flying broomsticks, no modern books, no digital computer screens, no text errors, no morphing faces.

[SCENE INSTRUCTIONS - EXACT 10-SECOND SEQUENCE]
Second 0-4: Lucien and Elara step onto a high stone walkway inside a monumental Gothic library extending endlessly upward. Thousands of antique leather-bound books float and orbit in smooth concentric paths around a central spiral stone staircase. Through an immense circular rose window, a deep purple and indigo spiral galaxy rotates slowly in deep space.
Second 4-7: As they walk along the stone balcony, they pass an ancient framed architectural drawing on the stone wall. The hand-drawn black-and-gold ink lines on the parchment are living and moving—a sketch of an ancient academy tower that redraws itself before their eyes.
Second 7-10: On a carved stone lectern ahead, a heavy leather tome opens itself with fluttering parchment pages. Lucien steps forward and leans over the open book. On the aged page is a detailed architectural diagram of the school, stamped with the exact geometric molten-gold fracture symbol from their classroom. Lucien points to it; Elara looks at him with sharp, serious realization.

[CAMERA & MOVEMENT INSTRUCTIONS]
Slow pedestal rise capturing the vertical scale of the library and floating books (0-4s). Lateral slider shot tracking past the living wall drawing (4-7s). Smooth push-in to macro close-up on the opening book page and Lucien's pointing hand, tilting up to their serious faces (7-10s).
```

---

### 🎬 CLIP 5 of 6: The Forbidden Corridor & The Chamber of the Sphere
* **Duration:** `10.0 seconds`
* **Scene Timeline:**
  * `0:00–0:05`: Following the direction indicated by the symbol, they walk into a long, shadowed Gothic corridor lined with framed portraits draped in black shroud cloth. As they walk, the wall lanterns extinguish sequentially into darkness behind them.
  * `0:05–0:07`: At the end of the hall, a colossal 20-foot double door of blackened iron—etched with the glowing golden fracture symbol—slowly parts inward with a deep hydraulic groan.
  * `0:07–0:10`: They step across the threshold into a vast subterranean circular chamber of black basalt pillars. Suspended at the center is a 20-foot sphere of pitch-black glass that reflects nothing, surrounded by concentric rotating bronze mechanical rings.
* **Anchor Reference to Upload:** Last frame of Clip 4 (Lucien looking up from ancient book) + Forbidden Corridor & Chamber References (`assets/references/corridor.png`, `assets/references/chamber.png`).

#### Prompt to Paste:
```text
[PERMANENT RULES - DO NOT VIOLATE]
Format: Vertical 9:16 composition. 24 FPS. Live-action cinematic photorealism.
Characters: Same LUCIEN and same ELARA in identical charcoal school coats. Identical faces, hairstyles, and costumes. Hands remain separate, walking alertly.
Environment: Dark Gothic stone hallway, framed portraits draped in black cloth, cold teal shadows, transitioning into a monumental circular subterranean vault with black basalt pillars and flooded mirror-black floor.
STRICT NEGATIVE CONSTRAINTS: No cartoon, no anime, no monsters jumping out, no gore, no modern technology, no camera shake, no generated text.

[SCENE INSTRUCTIONS - EXACT 10-SECOND SEQUENCE]
Second 0-5: Camera tracks backward in front of Lucien and Elara as they walk cautiously down a narrow Gothic stone hallway. The walls are lined with tall framed portraits, every single one covered in dark black shroud cloth. As the characters advance, the brass wall lanterns click off into darkness one after another right behind them, creating a creeping wave of shadow.
Second 5-7: They arrive at a dead end before a monumental 20-foot blackened-iron door etched with an intricate geometric fracture symbol glowing with faint molten gold. The heavy double iron doors groan and part inward by themselves, spilling cold air and deep shadow into the hall.
Second 7-10: Symmetrical one-point perspective shot gliding forward through the parting doors into a vast circular subterranean chamber. Black basalt pillars surround a flooded mirror-black stone floor. Floating at the exact center is a 20-foot flawless sphere of pitch-black glass that absorbs all light and reflects nothing, surrounded by slowly rotating aged-bronze gyroscopic rings. Lucien and Elara stand small in the doorway in awe.

[CAMERA & MOVEMENT INSTRUCTIONS]
Tracking backward ahead of the characters down the dark corridor (0-5s). Push-in toward the parting blackened iron door (5-7s). Smooth, symmetrical gliding shot passing through the doorway and entering the circular chamber, holding the black sphere centered (7-10s).
```

---

### 🎬 CLIP 6 of 6: The Choice, The Awakening & The Eye
* **Duration:** `8.0 seconds`
* **Scene Timeline:**
  * `0:00–0:03`: In the dark chamber, Elara reaches her hand toward Lucien and hesitates. Lucien looks from her hand to her face, makes a deliberate decision, and firmly takes her hand. As their palms join, their golden marks connect into a glowing continuous symbol. The sphere's fissures flare amber.
  * `0:03–0:05`: Golden lines race outward across the chamber walls and through the academy. Exterior wide: the central dome stops rotating; every window turns black one by one.
  * `0:05–0:07`: Back inside the dark chamber, behind the black sphere, a colossal golden eye slowly opens in the darkness, reflecting the two silhouettes of Lucien and Elara holding hands.
  * `0:07–0:08`: SMASH CUT TO BLACK. A hair-thin molten-gold fissure cracks across the black screen and draws the title: **THE UNWRITTEN**.
* **Anchor Reference to Upload:** Last frame of Clip 5 (looking at the black sphere) + Hand Mark Reference (`assets/references/hand_mark.png`) + Golden Eye Reference.

#### Prompt to Paste:
```text
[PERMANENT RULES - DO NOT VIOLATE]
Format: Vertical 9:16 composition. 24 FPS. Live-action cinematic photorealism.
Characters: Same LUCIEN and same ELARA in charcoal coats. Identical faces, hairstyles, and costumes.
Climax: Emotional resolution through deliberate choice. Golden marks on palms connect into one continuous loop.
STRICT NEGATIVE CONSTRAINTS: No cartoon, no anime, no full CGI monster body, no sudden romantic kiss, no explosions, no extra fingers, no morphing faces.

[SCENE INSTRUCTIONS - EXACT 8-SECOND SEQUENCE]
Second 0-3: Close two-shot in the dark chamber. Elara reaches her marked hand toward Lucien, her fingers hovering in hesitation. Lucien looks at her hand, looks at her eyes with calm determination, and deliberately takes her hand. Their palms press together; the thin molten-gold lines on their palms connect into a glowing continuous interwoven loop. The black sphere behind them flares with brilliant amber fissures.
Second 3-5: Rapid cinematic montage: molten-gold veins surge across the black stone floor. Exterior wide cut: the monumental Gothic academy floating above clouds as its rotating bronze dome grinds to a dead stop, and all window lights extinguish into pitch black one after another.
Second 5-7: Back inside the chamber, looking past the dark silhouettes of Lucien and Elara with joined glowing hands. In the pitch-black void behind the suspended sphere, an enormous, ancient golden eye with a vertical reptilian iris slowly opens, reflecting the two tiny silhouettes in its wet cornea. Ominous, intelligent, Denis Villeneuve cinematic lighting.
Second 7-8: Instant smash cut to black. In the center of the dark frame, a hair-thin crack of molten gold fractures open and draws the serif typography: THE UNWRITTEN.

[CAMERA & MOVEMENT INSTRUCTIONS]
Close-up on hands connecting, tilting up to their faces (0-3s). Rapid dynamic wide pull-back of academy dome stopping (3-5s). Slow push-in toward the darkness behind the sphere as the colossal golden eye opens (5-7s). Hard cut to black graphic title frame (7-8s).
```

---

## 🛠️ POST-PRODUCTION ASSEMBLY INSTRUCTIONS (DaVinci Resolve / FFmpeg)

Once you download your 6 generated MP4 files (`clip1.mp4` through `clip6.mp4`):
1. **Import Clips into Timeline:** Arrange on Track V1 in order: `Clip 1` (10s) + `Clip 2` (10s) + `Clip 3` (10s) + `Clip 4` (10s) + `Clip 5` (10s) + `Clip 6` (8s) = **58.0 Seconds**.
2. **Audio Track `A1` (Ambience):** Add classroom room tone, school bell at 0:04, rushing wind during fall, quiet library whisper, and subterranean drone.
3. **Audio Tracks `A2` & `A3` (Dialogue):** Place the 7 locked dialogue lines from [`plans/short/DIALOGUE.md`](../../plans/short/DIALOGUE.md) under the exact visual mouth actions.
4. **Audio Track `A4` (SFX):** Add pencil dead-stop, crystalline kintsugi crack, hydraulic iron door groan, bronze ring deceleration, 20Hz eye sub-bass drop, and final BRAAAM impact at 0:57.
5. **Audio Track `A5` (Score):** Lay the master hybrid orchestral score (solo cello into choir/brass into sudden silence at 0:55).
6. **Export with FFmpeg:**
   ```powershell
   ffmpeg -i resolve_master_58s.mov -c:v libx264 -profile:v high -pix_fmt yuv420p -crf 20 -preset slow -c:a aac -b:a 192k -movflags +faststart films/competition-cut/THE_UNWRITTEN_58s.mp4
   ```
