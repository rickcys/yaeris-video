# WhatsApp Blasting compliance Short — "3 things that get your WhatsApp number banned"

Status: script + real-timed audio done. HyperFrames composition not yet built.

Full row (storyline, script, sheet tracking) lives in the Yaeris "Video" tab:
https://docs.google.com/spreadsheets/d/1Wq-1zDPZx77c_N40Ol9I0xVxONbNad8xeXoZ_KF6aJU/edit — row 3.

## Real timeline (ffprobe-measured, not estimated)

Generated via `npx hyperframes tts` with local Kokoro (`af_heart` default voice), 2026-09-22.

| File | Scene | Start | Duration | End |
|---|---|---|---|---|
| `audio_lines/01_hook.wav` | Hook | 0.000s | 6.485s | 6.485s |
| `audio_lines/02_scene1.wav` | Scene 1 — opted-in / quality rating | 6.485s | 22.464s | 28.949s |
| `audio_lines/03_scene2.wav` | Scene 2 — volume spikes | 28.949s | 14.485s | 43.434s |
| `audio_lines/04_scene3.wav` | Scene 3 — unofficial tools | 43.434s | 17.749s | 61.183s |
| `audio_lines/05_closing.wav` | Closing — the fix | 61.183s | 17.323s | 78.506s |

Total runtime: 78.506s.

## Next step

Build the actual HyperFrames `index.html` composition using these 5 audio files and their real start/duration values as the `data-start`/`data-duration` timing for each scene's visuals. No avatar (motion-graphics + VO style, per the Inside Decoded reference videos this project is styled after).
