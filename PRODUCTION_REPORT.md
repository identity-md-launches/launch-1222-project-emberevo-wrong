# EmberEVO — THE WRONG FLOOR

Deliverable: `artifacts/video.mp4`

## Technical delivery

- Runtime: 30.000 seconds
- Frame: 1920 × 1080, 16:9, 30 fps
- Video: H.264 / AVC, `yuv420p`
- Audio: AAC stereo, 48 kHz
- File size: 11,218,928 bytes (10.7 MiB)
- Browser delivery: MP4 is fast-start enabled (`moov` atom front-loaded).
- Production stills: the four 1672 × 941 source plates are retained as high-quality JPEGs in `assets/` to keep the submitted source bundle below the 8 MiB limit. The rendered MP4 is unchanged.

## Edit outline

- 0–3s — Frog-and-coffee close-up in the elevator; the 12 → ∞ change is the opening hook.
- 3–7s — Portal/world-break transition and `WELCOME TO EMBEREVO`.
- 7–12s — Orange, star-filled falling sequence with a musical impact.
- 12–23s — Sweeping riverside-village reveal, including visually identifiable ferry, cable cars, houses and snowy mountains; `STEP INTO THEIR WORLD.` appears on the reveal.
- 23–26s — Arrival/reaction beat in the village.
- 26–30s — EmberEVO flame mark and `imdember.com` end card.

## Sources and rights

- The live `https://imdember.com/` page was fetched during production. Its served HTML describes **IMD Ember World** as a 3D village drawn from the public IMD agent network, where agent seats have homes and the town reflects online/working state.
- The end-card flame mark is rasterized from the site’s served `https://imdember.com/favicon.svg` (the official orange flame asset).
- Elevator, portal, character and trailer world shots are original AI-generated cinematic artwork created for this edit. The score and sound design are original synthesized audio (oscillators, impact envelopes and pink-noise wind), encoded into the AAC track; no third-party music was used.

## Limitation

The site could be fetched directly, but its interactive WebGL scene was not capturable in the available environment. Consequently the destination shots are stylized cinematic interpretations, not literal website captures. They include the requested riverside-town, ferry, cable-car, home/building and snowy-mountain motifs, but do **not** assert exact live agent activity, exact building layouts, or unverified in-world features. Owner approval remains required before public release.

## Local verification

`ffprobe` confirmed H.264 video at 1920 × 1080 with AAC stereo audio and a 30.000-second duration. Representative frames at 1s, 16s and 28s were decoded successfully for visual inspection.
