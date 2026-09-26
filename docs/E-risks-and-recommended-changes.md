# (E) The Three Biggest Risks — and What I Would Change

Status: **for decision.** The brief asked for direct criticism. This document gives it.

---

## Risk 1 — Efficacy: a video on its own is a weak teacher for a late talker

**The problem.** Research on the "video deficit" shows that children under about 3 learn words from screens much less well than from a live, responsive adult. The gap is largest when nobody is interacting with them. Late talkers are the group that most needs *contingent* interaction: an adult who responds to *their* attempt, not a fixed recording.

The approaches with the best evidence for late talkers are **parent-implemented language interventions**: parents taught to model, expand, wait and follow the child's lead. The American Academy of Pediatrics also advises that for ages 2–5 screen time be limited and **co-viewed**.

So an app a child uses alone is likely to show weak results on the brief's headline metric (use of the sentence at home). That puts the whole product claim at risk.

**What the brief already gets right.** Parent voice, own media, the "said it at home" metric, the coaching tips and hard session limits all point the right way.

**What I would change.**
1. **Make co-viewing the product, not a tip.** Before the session starts, one parent screen: "Sit beside [name]. Your job today: wait, then say it again." The caption line under each clip is already for the adult; make it the adult's script.
2. **Every clip carries a one-line "say it in real life today" prompt** for the parent (the `offline_activity` field). The closing screen shows the 2–3 sentences from today to use at home.
3. **Reframe the positioning:** "a daily 5-minute routine that teaches parents how to grow their child's sentences, using real-life clips". That is both more honest and easier to defend than "a speech app for children".
4. **Recommend a real SLP assessment** in onboarding copy for any child who is behind, without diagnosing. This protects the child and the company.

---

## Risk 2 — The parent voice-over feature, as specified, contradicts the rest of the brief

The feature is right, but the specification has four internal conflicts.

| Conflict | Why it breaks | Fix |
|---|---|---|
| **Lip-sync.** Section 5.3 wants the speaker's mouth visible; section 6 wants the parent to replace the audio. | A parent's voice over a stranger's moving mouth is a mismatch. That is exactly what a child watching mouths will notice, and it teaches the wrong audio-visual link. | **A speaking face appears only in IMITATE clips.** All other clips are voice-over over action (POV hands, observation). IMITATE clips are narrator-only. The parent can instead **film a selfie IMITATE clip** of their own face ("add own clip"), which is better anyway. |
| **Levels.** The app plays "current level, then one above" (4.1), but the parent records "a clip" (6). | One recording per clip cannot serve 4 levels. Otherwise the parent has to record 230 clips × 4 levels. | **Audio is assembled from segments** (doc B §1.1). The parent records a **ladder** once: its 4 level lines plus 1–3 prompts, about 60 seconds. It then applies to every clip of that ladder. 66 short sessions instead of 230+. |
| **Gender.** The brief does not mention it. | Egyptian Arabic marks gender in "I want / I'm hungry": عايز/عايزة, جعان/جعانة. A girl who hears "أنا عايز" all day is being modelled wrong grammar. | Feminine variants for 20 of the 66 ladders (doc A). The child's profile selects them. Audio only; no extra video. |
| **Pronouns.** First-person lines ("أنا عايز مية") played over another child on screen. | The child hears "I" attached to someone else, which can confuse pronoun learning. | **POV filming** for first-person ladders: the camera is the child's eyes and their "own" hands are in frame. Third-person ladders stay observational. |

**Engineering consequence.** A clip is *video + segment timing + a stretchable hold* plus a list of audio segments, not a finished MP4. The `script_with_timings` field in section 9 becomes the core of the player, not metadata. This is simpler than it sounds. It is also exactly what makes the separate-audio-track requirement (5.4) worth it.

---

## Risk 3 — The production plan is under-scoped, and 2–3-year-old actors will not deliver it

**The problem.**
- "A two-day shoot covers the overwhelming majority of 200–260 clips" is not realistic. With children, a well-run day gives about 30–40 usable clips. 230 clips is **6–7 shoot days + pickups** (doc D §8).
- The brief implies child actors of the target age (2–3.5). Children that young cannot hit a mark, repeat an action on cue, or stay regulated for a morning, and the ethics of pushing them are poor.
- The biggest cost driver is not the camera; it is re-shoots caused by missing holds, actions that do not finish in frame, and continuity.

**What I would change.**
1. **Cast children aged 4–6** for on-camera roles. They follow direction and are still clearly "a kid", which is good peer modelling for a 2–3-year-old.
2. **Use POV and hands for about half of the library** (all first-person ladders). Fewer faces means faster shoots, fewer child hours, fewer releases, and better privacy.
3. **Film a stretchable 8-second hold after every prompt** (doc C rules). Without it, the variable 4–6 s pause, the heart of the product, cannot be built.
4. **Pilot first, 1 day, 30 clips; field-test; then book the 6–7 v1 days** with a producer. The pilot also measures the real clips-per-day rate, which turns the v1 budget from an estimate into a number.

---

## Other issues to decide (smaller, but real)

| # | Issue | Recommendation |
|---|---|---|
| 4 | **Swipe-to-next is the reels gesture.** A 2-year-old will learn to swipe through the silence, killing the wait time. | Swipe is **disabled during the pause** and until the clip finishes. After the session's last clip, swipe does nothing. The repo name "reels" signals the wrong mental model; consider renaming internally. |
| 5 | **The app cannot hear the child**, and should not (a child's microphone is a privacy and trust problem). | Acknowledgement is always a **neutral re-model**, never "correct!". The parent can **hold the screen to extend a pause** for a child who needs longer. |
| 6 | **Measurement.** 3–5 children cannot show an 8-week MLU change, and parent reports are biased toward seeing progress. | Pilot measures questions 1–3 only (watching, imitation attempts, answers after exposure), **observed by an SLP**. For the 8-week question later: a baseline and week-8 **10-minute play sample** transcribed by an SLP, plus a fixed checklist of the 60 target sentences. Check whether a validated Egyptian-Arabic parent vocabulary checklist (a CDI adaptation) can be used. |
| 7 | **No SLP in the team.** The brief makes the AI the "language specialist". | A licensed Egyptian SLP reviews every script and the test protocol (budgeted in doc D). This is both a quality control and a credibility asset. |
| 8 | **Business model not defined.** Section 2 says "paid app". | Before the v1 budget (≈ 0.37–0.74 M EGP, content only), test willingness to pay: 20 parent interviews + a landing page with a price. It is cheap and quick, and it does not delay the pilot. |
| 9 | **Colours, "ليه", numbers.** | Kept out of v1 as briefed; one colour ladder only (D05). |

---

## Summary of changes proposed to the brief

1. Co-viewing is the core design; add a parent "before we start" screen and a daily real-life carry-over list.
2. Speaking faces only in IMITATE; everything else is voice-over, so parent audio always fits.
3. Segment-based audio assembled by level; parents record **per ladder**, not per clip.
4. Feminine variants for first-person ladders.
5. POV filming for first-person ladders.
6. New clip type **TEMPTATION** (a problem is shown, then silence) for request ladders.
7. On-camera children aged 4–6; the pilot first; 6–7 shoot days for v1.
8. Stretchable holds on every prompt; the parent can extend the pause; swipe is locked during the pause.
9. A licensed SLP advisor from week 1.
10. Level rule: L4 is at most 4 words, and only one new element per level (the brief's own example is corrected in doc A).
