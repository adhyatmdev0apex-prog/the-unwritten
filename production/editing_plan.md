# Editing Plan

## Timeline
1. Create a 1080x1920, 24 or 30 fps vertical sequence.
2. Drop clips in the shot-list order (`shot_list.md`); set the pace before polishing.
3. Add audio: ambience first, then SFX, then music (first cue at the academy reveal at 0:32).
4. Add engraved text at C7 ("WELCOME TO YOUR REAL SCHOOL") and on the three C8 beats.
5. Build the title (black, gold line, one-frame iris) at 0:55-0:58.
6. Colour grade as a progression: restrained classroom - gold enters - academy cool/warm - chamber dark.
7. Check on a phone. Export.

## Export
- H.264 MP4, 1080x1920, 9:16, under 100 MB, runtime 58 s (hard limit 60).

## ffmpeg helpers (when assets exist)
```bash
# Normalise a clip to 1080x1920 at 30 fps
ffmpeg -i in.mp4 -vf "scale=1080:1920:force_original_aspect_ratio=increase,crop=1080:1920,fps=30" -an out.mp4

# Concatenate (clips listed in list.txt as: file 'c1.mp4')
ffmpeg -f concat -safe 0 -i list.txt -c copy joined.mp4

# Mix music under the video
ffmpeg -i joined.mp4 -i score.wav -filter_complex "[1:a]volume=0.8[a]" -map 0:v -map "[a]" -c:v copy -shortest final.mp4

# Compress to a target size
ffmpeg -i final.mp4 -c:v libx264 -crf 22 -preset slow -c:a aac -b:a 192k submit.mp4
```

## Transitions
Match the portal events: fissure under desk - fissure spreading - wide tear - reverse reveal of academy. Different views of one event. Hard cut to black after the fall, and again before the title.

## Quality gate
- No watermark, no borders, no distorted text.
- No audio clipping.
- Dialogue audible over music.
- Hands correct in C9-C10.

## Two cuts
- **Competition cut (58 s):** `films/competition-cut/`
- **Extended cut (~10 min):** `films/extended-cut/`, built from the master screenplay once the reel is shipped.
