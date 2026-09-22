# WhatsApp Blasting compliance Short — "3 things that get your WhatsApp number banned"

Status: rendered, brand-compliant, ffprobe-verified. v3 rebuild (2026-09-22), superseding both v1 and v2 from the same day.

**v3 note:** v2's 17-beat pacing (~4.4s average) felt too fast per Rick's direct feedback
("i think it just too fast. let's do 8-10 secs avg between frames so we don't have to rush").
v3 regroups the same content into ~9 beats averaging ~8.7s, still cut on real transcript pause
boundaries. This 8-10s target is now the standing pacing rule in global memory going forward,
overriding the earlier 1.5-4s generic short-form guidance for this channel's explainer-style
content specifically.

Full row (storyline, script, sheet tracking) lives in the Yaeris "Video" tab:
https://docs.google.com/spreadsheets/d/1Wq-1zDPZx77c_N40Ol9I0xVxONbNad8xeXoZ_KF6aJU/edit — row 3.

## Why this got rebuilt

The v1 render (5 long static scenes, no captions, no transitions, ad-hoc teal palette) violated
several standing rules Rick set after reviewing it. This v2 rebuild applies all of them — see
`video_creation_global_standards.md` in global memory for the full standing rules these apply to
every future video, not just this one:

1. **Captions burned in** — real word-level timestamps via local `faster-whisper` (`small.en`)
   transcription of each of the 5 audio files (local HyperFrames' own `transcribe` command needs
   whisper-cpp, which requires a from-source cmake build on Windows with no prebuilt binary
   available in this environment — `faster-whisper`, pip-installable, was used instead as a
   legitimate ASR substitute with the same real word-timestamp output). 46 caption chunks, synced
   to real speech, burned into the composition as `.caption-pill` elements.
2. **Pacing** — the original 5 static scenes (~15.7s average) were first broken into 17 shorter
   visual beats (~4.4s average, v2), then regrouped into ~9 beats (~8.7s average, v3) after Rick
   said the v2 cut felt too fast. All cuts land on real speech-pause boundaries from the
   transcript, not a fixed timer.
3. **Smooth transitions** — every beat-to-beat cut is a real 0.3s crossfade (opacity + scale
   overlap between outgoing and incoming beats), not a hard jump-cut.
4. **Subscribe CTA** — an animated subscribe/bell pop-up appears mid-video (26.5–30.5s, during the
   Reason 1 → Reason 2 transition) with a bounce-in/ring/fade-out animation, plus an explicit
   "Subscribe for more" ask + bell icon on the end card.
5. **One consistent design system** — rebuilt on the real Yaeris Brand Kit's Video section spec
   (section 13 of the published Brand Kit artifact) instead of an invented one-off palette: fixed
   dark canvas `#1A1A2E`, violet `#6B2FA0`/`#4A2070`, cyan `#29ABE2`, green `#25D366`, Outfit
   (display) + Inter (body/captions) + Space Mono (labels), and an end card built from the Brand
   Kit's exact radial-gradient node pattern (violet/cyan/green blobs on a violet-deep ground).

## Real timeline (ffprobe-measured audio, unchanged from v1)

Generated via `npx hyperframes tts` with local Kokoro (`af_heart` default voice), 2026-09-22.

| File | Scene | Start | Duration | End |
|---|---|---|---|---|
| `audio_lines/01_hook.wav` | Hook | 0.000s | 6.485s | 6.485s |
| `audio_lines/02_scene1.wav` | Reason 1 — opted-in / quality rating | 6.485s | 22.464s | 28.949s |
| `audio_lines/03_scene2.wav` | Reason 2 — volume spikes | 28.949s | 14.485s | 43.434s |
| `audio_lines/04_scene3.wav` | Reason 3 — unofficial tools | 43.434s | 17.749s | 61.183s |
| `audio_lines/05_closing.wav` | Closing — the fix | 61.183s | 17.323s | 78.506s |

A silent 3.494s end card (subscribe CTA) was appended after the narration ends, bringing total
runtime to **82.0s** (v1 was 78.506s).

## Captions

Real word-level timestamps via `faster-whisper` (`small.en`, CPU, int8) — see
`audio_lines/*_words.json` for the raw per-word output and `captions_final.json` for the
46 grouped caption chunks actually burned into `index.html`. Two known whisper mis-transcriptions
("what's apps" → "WhatsApp's", hyphen splits like "seven -day") were manually corrected in the
caption text against the real known script.

## Final render

`whatsapp-ban-short.mp4` — ffprobe-verified: H.264, MP4, 1080×1920, AAC audio, 82.0s, 7.0MB.
Matches RobinReach's spec (MP4/H.264/1080×1920) exactly.

## Build sequence used

1. `npx hyperframes tts` → 5 real audio lines (unchanged from v1, still authoritative narration).
2. `pip install faster-whisper` → real word-level timestamps per audio line (whisper-cpp
   unavailable on this Windows machine without a from-source build).
3. Hand-authored beat/caption breakdown from the real transcript (17 visual beats, 46 caption
   chunks) — see this file's "Why this got rebuilt" section for the design rules applied.
4. `npx hyperframes lint` → 0 errors (advisory sub-composition warnings only, same class left
   as-is in v1).
5. `npx hyperframes check` → 0 errors, 36 warnings (all `content_overlap` during the intentional
   0.3s crossfade windows — expected, since both beats are briefly visible together by design),
   26/26 WCAG AA contrast checks pass.
6. `npx hyperframes snapshot` → visually reviewed both contact sheets before rendering, one real
   layout bug caught and fixed (gauge marker briefly covering the "Green" label text — the
   marker's move-to-red animation was delayed 2s after the scene became visible; fixed by
   starting the marker tween immediately when the scene appears).
7. `npx hyperframes render --quality looks` → 82.0s, 7.0MB.
8. `ffprobe` → confirmed H.264/MP4/1080x1920/AAC/82.0s independently of the render log.
