# Master Generation Specification & Prompt Pack — THE UNWRITTEN (90s / 40% Exploration)

**Master Story Plan:** [`plans/short/SHORT_FILM_PLAN.md`](../plans/short/SHORT_FILM_PLAN.md) (90s, 40% School Exploration)
**Shot List:** [`production/shot_list.md`](shot_list.md) / [`plans/short/SHOT_LIST_1m30.md`](../plans/short/SHOT_LIST_1m30.md) (21 shots)
**Competition Cut:** [`plans/short/COMPETITION_CUT_58s.md`](../plans/short/COMPETITION_CUT_58s.md) (58.0s)
**Relationship Direction:** **B — Drawn together without understanding why** | **Narration:** None

---

## 1. Recommended AI Toolkit & Hybrid Production Pipeline

| Tool | Purpose | Priority | Focus |
|---|---|---|---|
| **ChatGPT / Gemini / Claude** | Scripting, continuity checks, prompt crafting | Essential | Maintain exact production specifications |
| **Gemini Image Generation (Imagen)** | Character references, environment concepts, keyframes | Primary Stills | High-fidelity 9:16 concept and turnaround sheets |
| **Google Flow / Veo** | Cinematic image-to-video clips | Primary Video | Atmospheric camera moves, fluid physics, architectural grandeur |
| **Kling AI** | Secondary video generation | Backup | Free-fall physics and complex hand interactions |
| **Hailuo AI** | Complex character motion | Optional | Fallback if character movement distorts |
| **DaVinci Resolve** | Assembly, color grading, sound mixing, title card | Recommended Editor | Multi-track post-production and lossless typography |
| **FFmpeg** | Aspect ratio validation, compression, QA | Essential Utility | Encode final vertical MP4 <100MB for portal upload |

---

## 2. Master Reference Prompts (Stage 1 & Stage 2)

### A. Master Visual Style (Attach to All Prompts)
```text
PROJECT: THE UNWRITTEN — A School Beyond Reality
FORMAT: Vertical 9:16 composition (1080 × 1920). Cinematic fantasy short film. Photorealistic live-action aesthetic. Natural skin texture, realistic materials, physically plausible lighting.
VISUAL IDENTITY: Ancient Gothic architecture constructed from weathered black basalt, aged bronze mechanical details, teal stained glass, cold slate-blue shadows, restrained molten-gold supernatural fissures, black reflective surfaces, monumental arches and impossible architecture.
LIGHTING: Natural warm late-afternoon light in ordinary classroom; cold teal-blue environmental light in academy; restrained amber-gold illumination from supernatural fissures. Physically plausible falloff, no excessive bloom.
CINEMATOGRAPHY: Intentional framing, controlled camera movement, natural motion blur, subtle film grain, 35mm lens optics.
CONTINUITY: Preserve character costumes, architecture, color palette, and supernatural symbols across all generations. No narrator, no random visual effects, no text generated inside footage.
```

### B. Character Reference: Lucien
*(Save approved sheet in `characters/lucien/`)*
```text
Create a photorealistic character reference sheet for LUCIEN, an original fictional teenage character in a cinematic fantasy film.
He is approximately 16 years old, tall and lean, with dark tousled hair, observant dark eyes, and a quiet, thoughtful expression.
COSTUME: A tailored charcoal school coat, subtle dark-teal inner lining, minimal aged-bronze fasteners, simple dark school uniform underneath, an old leather notebook carried throughout the film.
PERSONALITY EXPRESSED THROUGH APPEARANCE: Observant, reserved, intelligent, quietly protective. His expression should be natural rather than exaggerated.
REFERENCE SHEET: Show the same character in: 1. Front-facing portrait, 2. Three-quarter portrait, 3. Side profile, 4. Full-body neutral standing pose, 5. Close-up expression showing uncertainty, 6. Close-up expression showing quiet determination.
Neutral grey studio background, soft even lighting, natural skin texture, photorealistic live-action appearance. No fantasy effects, no glowing eyes, no watermark, no text. --ar 9:16
```

### C. Character Reference: Elara
*(Save approved sheet in `characters/elara/`)*
```text
Create a photorealistic character reference sheet for ELARA, an original fictional teenage character in a cinematic fantasy film.
She is approximately 16 years old, with an intelligent, observant expression and a natural, understated appearance.
COSTUME: A tailored charcoal school coat, visible dark-teal scarf lining, simple dark school uniform underneath, a small hexagonal wooden pencil tucked behind her ear.
PERSONALITY EXPRESSED THROUGH APPEARANCE: Curious, perceptive, quietly courageous. Believable student, not a stylized fantasy heroine.
REFERENCE SHEET: Show the same character in: 1. Front-facing portrait, 2. Three-quarter portrait, 3. Side profile, 4. Full-body neutral standing pose, 5. Close-up expression showing curiosity, 6. Close-up expression showing uncertainty, 7. Close-up expression showing resolve.
Neutral grey studio background, soft even lighting, natural skin texture, photorealistic live-action appearance. No fantasy effects, no glowing eyes, no watermark, no text. --ar 9:16
```

### D. Environment Reference: The Academy Exterior
*(Save in `assets/references/`)*
```text
Create a cinematic environment concept image for THE UNWRITTEN — A School Beyond Reality.
An immense Gothic academy suspended above an endless sea of teal clouds.
ARCHITECTURE: Weathered black basalt stone, aged bronze mechanisms, monumental pointed arches, floating bridges between impossible towers, a vast rotating central dome, tall teal stained-glass windows, moving staircases in the distance.
SUPERNATURAL DETAIL: Thin molten-gold fissures running through selected areas of the stone architecture like glowing veins.
ATMOSPHERE: Cold slate-blue sky, volumetric clouds, deep atmospheric perspective, monumental scale, beautiful but subtly threatening.
CAMERA: Vertical 9:16 composition, low viewpoint looking upward, strong foreground/middle ground/background depth. Photorealistic cinematic fantasy. No characters, no text. --ar 9:16
```

### E. Environment Reference: The Enchanted Classroom
*(Save in `assets/references/`)*
```text
Create a cinematic environment concept image for THE UNWRITTEN — A School Beyond Reality.
An enchanted Gothic classroom inside the fantasy academy.
INTERIOR: Weathered black stone walls, tall lancet windows with teal twilight outside. Wooden school desks floating gently at varying heights in zero gravity. An antique slate chalkboard in the background displaying moving golden star constellations. Spun-gold mathematical and geometric equations orbiting weightlessly in 3D space. Above a central carved teacher's desk, a glowing miniature solar system rotates with delicate orbital rings.
LIGHTING: Cold teal ambient room tone contrasted with warm 2700K amber-gold glow from floating equations. Photorealistic materials, dust particles in light, no characters, no text. --ar 9:16
```

### F. Environment Reference: The Library Between Worlds
*(Save in `assets/references/`)*
```text
Create a cinematic environment concept image for THE UNWRITTEN — A School Beyond Reality.
A colossal multi-tiered Gothic library extending infinitely upward.
INTERIOR: Spiral stone staircases surrounded by thousands of leather-bound books orbiting slowly in the air. Floating brass platforms gliding between towering dark-wood and stone bookshelves. A massive central rose window revealing a deep purple and indigo spiral galaxy with swirling nebulae instead of an ordinary sky.
LIGHTING: Deep violet-blue galaxy light pouring through the window, warm lantern light on carved stone balustrades. Photorealistic cinematic fantasy, monumental vertical scale, no characters, no text. --ar 9:16
```

### G. Environment Reference: The Forbidden Corridor
*(Save in `assets/references/`)*
```text
Create a cinematic environment concept image for THE UNWRITTEN — A School Beyond Reality.
A long, narrow Gothic stone corridor inside the academy.
INTERIOR: Arched stone ceiling, flagstone floor, walls lined with framed portraits draped in dark black shroud cloth. Wall lanterns mounted along the stone. At the far end of the corridor stands a massive 20-foot double door of blackened iron, etched with an intricate geometric fracture emblem glowing with a hairline seam of molten gold.
ATMOSPHERE: Eerie suspense, cold teal shadows, heavy silence, no characters, no text. --ar 9:16
```

### H. Environment Reference: The Forbidden Chamber & Sphere
*(Save in `assets/references/`)*
```text
Create a cinematic environment concept image for THE UNWRITTEN — A School Beyond Reality.
A forbidden subterranean circular chamber concealed deep inside the academy.
CENTRAL OBJECT: A perfectly dark 20-foot black-glass sphere suspended above a circular stone platform. The sphere reflects almost no light. Thin molten-gold fissures run beneath its surface.
SURROUNDING STRUCTURE: Concentric aged-bronze mechanical gyroscopic rings rotating around the sphere with precise mechanical teeth and bronze gears.
ENVIRONMENT: Black basalt pillars, flooded mirror-black stone floor, cold teal light from narrow shafts, a vast, pitch-black void behind the sphere concealing an immense presence.
ATMOSPHERE: Ominous, ancient, awe-inspiring, restrained golden internal glow. No visible monster, no characters, no text. --ar 9:16
```

---

## 3. Core Image-to-Video Motion Prompts (By Scene)

### Act 1 — The Last Bell (0:00–0:12)
* **`S01-SH01` (Classroom Opening, 5s):**
  `Slow, smooth camera sweep from an elevated high angle at the back of the warm late-afternoon classroom down to a straight-on eye-level view, with a very slight zoom out. Students make subtle natural writing movements. Lucien and Elara remain seated calmly at their desk. Grounded physics, realistic 35mm motion, no camera shake.`
* **`S01-SH02` (The Bell Rings, 4s):**
  `Locked camera shot. Students stand up, sling bags over shoulders, and walk out through the open classroom door over 4 seconds. Lucien and Elara stay seated at their desk, watching. Room empties naturally, warm afternoon light.`
* **`S01-SH03` (Connection & Crack, 3s):**
  `Medium two-shot pushing slowly in. Lucien closes his leather notebook; Elara smiles. Camera tilts down as a hexagonal wooden pencil stops at the desk edge and a thin molten-gold kintsugi crack splits the floor shadow beneath the desk and spreads across the floor.`

### Act 2 — Their School, Beyond Reality (0:12–0:48 | 40% Exploration)
* **`S02-SH01` (Impossible Fall, 3s):**
  `Camera tracks downward alongside Lucien and Elara as they fall through impossible surreal fragments of floating worlds: an upside-down pine forest, drifting stone arches, and a sky ocean. Clothes and coats flutter naturally in high wind. Smooth vertical motion.`
* **`S02-SH02` (Reaching & Landing, 3s):**
  `Macro cut of hands grasping and gripping wrist in free fall, cutting immediately to the two characters landing solidly on a black basalt platform above clouds. They stand up, steady each other, let go of their hands, and look forward in disbelief.`
* **`S02-SH03` (Fantasy School Reveal, 7s):**
  `Slow crane pedestal rise behind Lucien and Elara standing on the causeway, revealing the colossal floating Gothic academy above rolling clouds. Familiar classroom windows glow teal. Floating staircases shift slowly. Central doors open in the distance.`
* **`S02-SH04` (Enchanted Classroom: Desks, 4s):**
  `Smooth tracking camera moving behind Lucien and Elara as they walk into the enchanted classroom. Wooden desks bob gently in zero gravity at varying heights. Moving star constellations rotate on the chalkboard. Golden equations drift slowly in the air.`
* **`S02-SH05` (Equation Doorway, 3s):**
  `Close-up shot. A hovering golden geometric equation folds smoothly like origami into a dimensional glowing doorway. Elara's hand moves forward; the light bends toward her fingertips. Camera pushes forward toward the doorway.`
* **`S02-SH06` (Library Between Worlds, 4s):**
  `Slow pedestal rise in the monumental library. Books orbit slowly in smooth paths around a central spiral staircase. Distant purple galaxy outside the rose window slowly rotates. Lucien and Elara walk along the stone balcony.`
* **`S02-SH07` (Book of the Academy, 3s):**
  `Macro push toward the ancient book as its page settles. The golden fracture symbol on the architectural drawing glints. Lucien's hand points toward the symbol, then camera tilts up to his alarmed eyes.`
* **`S02-SH08` (Forbidden Corridor, 5s):**
  `Camera tracks backward ahead of Lucien and Elara walking forward down the stone hallway lined with draped portraits. Behind them, wall lanterns click off sequentially into darkness. They stay alert.`
* **`S02-SH09` (Sealed Door Opens, 4s):**
  `Push forward between Lucien and Elara's shoulders toward the heavy black iron door bearing the fracture emblem as it slowly parts inward. Cold air and deep shadow spill out from the dark chamber.`

### Act 3 — The Chamber That Remembers (0:48–1:05)
* **`S03-SH01` (Sphere in Void, 5s):**
  `Slow, smooth push forward through the parting doorway into the circular chamber. Bronze gyroscopic rings turn smoothly around the stationary pitch-black glass sphere. Total silence, cold teal shafts of light.`
* **`S03-SH02` (Interlaced Fingers & Marks, 4s):**
  `Macro shot. Golden fissures on the sphere surface morph smoothly into the shape of two interlaced hands. Camera tilts to Lucien and Elara's open palms as a matching thin gold mark illuminates on their skin.`
* **`S03-SH03` (Silhouettes Across Worlds, 4s):**
  `Gentle push-in on the black sphere as faint golden silhouettes dissolve softly between different alien horizons inside the dark glass. Lucien and Elara watch motionless.`
* **`S03-SH04` (Light Dies & Shape Moves, 4s):**
  `Slow creeping push-in on the darkened black sphere. The bronze rings slow and freeze. In the deep shadow behind the sphere, an immense curved silhouette shifts slowly in the dark void.`

### Act 4 — The Choice & Climax (1:05–1:30)
* **`S04-SH01` (The Decision, 7s):**
  `Medium two-shot. Elara reaches her marked hand out and hesitates. Lucien looks at her hand, looks at her face, and deliberately takes her hand. The golden marks on their palms touch and form a complete glowing circuit. Camera tilts up to their determined faces.`
* **`S04-SH02` (Academy Awakens, 4s):**
  `Fast camera movement as golden light streams through stone channels. Rapid cut to the enchanted classroom: floating desks and equations instantly freeze in place. Rapid cut to the library: floating books freeze mid-air.`
* **`S04-SH03` (Dome Stops & Windows Black, 5s):**
  `Wide shot of the exterior Gothic academy. The massive bronze central dome shudders and stops rotating. The golden and teal lights in the windows extinguish sequentially into pitch black. Clouds churn into a spiral.`
* **`S04-SH04` (Golden Eye Opens, 6s):**
  `Slow push-in toward the darkness behind the black sphere. A massive golden eyelid parts, revealing a colossal ancient golden eye that dilates and looks directly down at the foreground silhouettes holding hands. Hold.`
* **`S04-SH05` (Title Card, 3s):**
  `Smash cut to black. In DaVinci Resolve, a hair-thin molten-gold fissure animates across the black screen, etching the title: THE UNWRITTEN.`
