# Clickable prototype (throwaway)

`real-world-talk.html` is a page fragment published as a private claude.ai Artifact:
https://claude.ai/artifact/TaHgJrG9fvGbuCfcb615Uf

- Target: Chrome on an Android phone. Everything is stored in that phone's browser only (localStorage + IndexedDB).
- Covers the 10 pilot ladders / 30 clips from docs B and C: child start screen, co-view screen, the feed (swipe up/down, tap to replay, 2-second long press to exit, swipe locked during the pause, hold to extend the pause), end screen with no "one more", parent gate, parent mode (setup, recording studio, progress with "said it at home", tips, privacy), daily session limit and a simple spaced-repetition planner.
- The page cannot open the microphone or camera directly, so recording goes through file inputs with `capture`. Android opens the phone's own recorder or camera. "Record all at once" splits one recording into lines by detecting 0.7 s+ silences.
- No placeholder footage, AI media or TTS: until the parent films and records, each clip shows a dashed frame with the scene description and the caption only.
- Not production code. The MVP is built natively after the field test (brief §10).
