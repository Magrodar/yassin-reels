# (D) Production Plan — to the 30-Clip Pilot (and a Forecast for v1)

Status: **DRAFT v0.1.** All costs are **planning estimates in EGP for Cairo, late 2026**. They are not quotes. Get three quotes for every line above 5,000 EGP before committing. A USD figure uses an assumed ~50 EGP/USD; re-check the rate on the day of any foreign-currency purchase.

---

## 1. Crew and roles (pilot)

| Role | Who | Days | Notes |
|---|---|---|---|
| Producer / director | Freelance producer, **or** Mahmoud/Reham with a written checklist | 8–10 days spread over 5 weeks | Owns the schedule, consent, props, the day's running order. If a founder does this, it costs about 60–80 hours; see the time warning in section 7. |
| Speech-language pathologist (أخصائي تخاطب), advisor | Licensed Egyptian SLP who works with 2–4-year-olds | 3 reviews + optional half day on set | Reviews the ladders, scripts and the field-test protocol. **Not optional** (doc E). |
| Camera operator / DoP | Freelancer with his or her own kit (a recent phone or a mirrorless camera, lights, lav mics) | 1 + 0.5 pickup | Must have filmed children or food before. Ask for a reel. |
| Assistant (sound, props, slate) | Freelancer or a trained family member | 1 + 0.5 | Also watches continuity (e.g. how many biscuits are on the plate). |
| Adult woman — on camera + **voice-over narrator** | Actress or experienced voice talent | 1 shoot + 0.5 studio | Casting the same person for the face and the voice keeps IMITATE and VO consistent. |
| Adult man — hands, torso, one IMITATE | Actor or trusted non-actor | 1 | |
| Child actors | Boy and girl, 4–6 years, **each with their parent** | 0.5 | Signed consent and a child-performer agreement (section 5). |
| Editor | Freelance short-form editor | 5–7 days | Edits to the timing sheet; exports segments and holds separately. |
| Legal | Lawyer (IP, data protection, contracts) | a few hours | Consent forms, talent releases, voice-rights assignment, privacy notice. |

---

## 2. Equipment

If the DoP brings a kit, the pilot needs **no equipment purchase**. For v1 and for later in-house shoots, a small owned kit pays back in one shoot:

| Item | Purpose | Estimate (EGP) |
|---|---|---|
| Recent phone that shoots 4K 25 fps with manual exposure | Camera (you likely own one) | 0 |
| Phone cage or clamp + sturdy tripod + low tripod for the POV height | Stable POV framing at 70–80 cm | 2,500–5,000 |
| Wireless lavalier mic kit (2 transmitters) | IMITATE sync sound | 6,000–14,000 |
| Small shotgun or second recorder | Natural sound close to the action | 2,000–5,000 |
| 2 × bi-colour LED panels with soft diffusion + stands | Even, soft, flicker-free light | 5,000–10,000 |
| 5-in-1 reflector, gaffer tape, clamps, batteries, 2 × 1 TB SSD | Basics and backups | 3,000–6,000 |
| **Total (if bought)** | | **18,500–40,000** |

Voice-over is **not** recorded with this kit. It is recorded in a small studio (section 4).

---

## 3. Licensed stock footage

- **Pilot: none needed.** Every pilot clip can be filmed in the apartment.
- **v1:** about 20–30 clips (farm animals, zoo, traffic, rain, birds flying, a sleeping or laughing baby if none is available).
  - Per-clip marketplaces (HD/4K): typically **USD 30–200 per clip**.
  - Subscription libraries: typically **tens of USD per month**.
- **Checklist for every clip before download:**
  1. The licence allows commercial use **inside a paid app**, not "editorial use only".
  2. There is a model release for any identifiable person and a property release where needed.
  3. The rights continue for already-published content if the subscription is cancelled.
  4. Any "per end-product" limit is understood.

  Keep a PDF of the licence per clip in the CMS `licence_source` field.
- **Budget for v1 stock:** USD 600–2,500 (≈ 30,000–125,000 EGP). The wide range depends on the marketplace and 4K vs HD. Choosing HD, which is enough for a 1080×1920 output, keeps it at the low end.

---

## 4. Voice recording

- **Where:** a small commercial voice studio in Cairo, or a treated room with a good condenser mic and an engineer. Not a phone in a living room: the default narration is the product's quality signal.
- **What:** segment recording, not whole clips. For the pilot's 10 ladders that is ≈ 40 level lines + ≈ 15 feminine variants + ≈ 25 prompts and extras ≈ **80 short lines**. Record 3 takes of each and pick the best.
- **Delivery direction:** warm, natural home Egyptian, about 15% slower than normal speech, clear word boundaries, no sing-song, no baby voice. Questions are recorded with a real rising intonation. A03 lines are whispered.
- **Spec:** master WAV 48 kHz / 24-bit, one file per line, named `R01_L2_m.wav`, `R01_L2_f.wav`, `R01_Q.wav`. Delivered to the app as mono AAC ~96 kbps, loudness-normalised to about −16 LUFS so every segment is equally loud.
- **Rights:** a written assignment of the recordings and permission to use them in the app worldwide without time limit. Also a clear clause that **no voice cloning or AI training** will be done with the voice (it protects the talent and avoids a future dispute).
- **Order:** record the VO **before** the edit. The editor then cuts picture to the real segment lengths.

---

## 5. Consent, legal and child safety

- **Child performers:** written consent from both legal guardians where possible, and a child-performer agreement. It should cover the fee, maximum hours (≤ 3.5 h on set including breaks), that a parent is always present, the right to stop at any moment, and where and for how long the footage is used. **Ask an Egyptian lawyer to confirm the current rules on children in commercial filming.** This plan does not claim what they are.
- **Adults:** talent release (image and voice), with the no-cloning clause.
- **Location:** a short written permission from the apartment owner.
- **App side (before the field test):** a plain-language privacy notice. The design goal (nothing about the child leaves the device) must be checked against Egypt's Personal Data Protection Law No. 151 of 2020 and its executive regulations. Google Play's Families policy and COPPA / GDPR-K matter later, at store launch. **Do this at prototype stage, not at launch.**

---

## 6. Cost — pilot (30 clips)

| Line | Lean (EGP) | Recommended (EGP) |
|---|---|---|
| SLP advisor: 3 reviews (+ half day on set) | 6,000 | 12,000 |
| Producer (freelance) | 0 (founder-run) | 15,000 |
| DoP with own kit: 1 day + 0.5 pickup | 9,000 | 15,000 |
| Assistant: 1.5 days | 2,500 | 4,500 |
| Adult woman: shoot day + VO session | 6,000 | 10,000 |
| Adult man: shoot day | 2,500 | 4,000 |
| Two child actors (half day each, parents present) | 4,000 | 8,000 |
| Voice studio + engineer (half day) | 2,500 | 5,000 |
| Location (friend or family flat vs rented flat) | 0 | 5,000 |
| Props, food, set dressing | 2,500 | 4,000 |
| Catering for the shoot day | 2,000 | 3,500 |
| Editor: 30 clips + segment export | 7,500 | 12,000 |
| Legal: consent forms, releases, privacy notice | 4,000 | 10,000 |
| Stock footage | 0 | 0 |
| Contingency (15%) | 7,300 | 16,200 |
| **Total** | **≈ 56,000 EGP (≈ USD 1,100)** | **≈ 124,000 EGP (≈ USD 2,500)** |

Not included: the clickable prototype (a separate design/dev cost), the field test itself (small: gift vouchers for 3–5 families and 2–3 SLP observation hours), or equipment purchase.

---

## 7. Calendar — to 30 finished pilot clips

| Week | Work | Gate (review before moving on) |
|---|---|---|
| **W1** | SLP review of docs A + B (pilot ladders first). Fix dialect and levels. Draft consent forms. Shortlist DoP and talent (reels, voice samples). | **Scripts for the 10 pilot ladders locked** |
| **W2** | Casting: 2–3 women (read 5 lines, on camera + audio), children meet the crew. Location recce with the phone: light at 10:00 and 15:00. Buy props. Sign releases. | **Talent and location signed** |
| **W3** | VO session (half day) → segments delivered. Tech recce + a 1-hour test shoot of 2 clips (checks POV height, flicker, the hold). **Shoot day** at the end of the week. | **All pilot footage + backup on 2 drives** |
| **W4** | Edit: 30 clips, holds, segment timing sheet (`script_with_timings`, `pause_position`). Pickup half-day if needed. | **30 clips pass QC checklist** |
| **W5** | Encode (H.264, 1080×1920, ≤ 2 MB), fill CMS records, load into the clickable prototype. Internal test with 1–2 known children. | **Pilot content ready for the field test** |

**Realistic calendar: 5 weeks to a finished pilot, 6 if casting slips.** The field test (3–5 children) then needs at least **2–3 weeks** for questions 1–3 in section 11 of the brief. The 8-week MLU question cannot be answered by the pilot at all (doc E).

> **Founder-time warning.** A founder-run lean pilot saves ≈ 15–30k EGP but costs ~70 hours of Mahmoud's or Reham's time over 5 weeks. That time would otherwise go to Glowin (priority #2). Unless the time genuinely exists, the freelance producer is the cheaper option.

---

## 8. Forecast — full v1 content (≈ 230 clips), after the field test

| Item | Estimate |
|---|---|
| Shoot days | **6–7** (≈ 35–40 clips/day with good planning; exteriors and animals slower) + 1 pickup day |
| Crew and talent per shoot day | 25,000–40,000 EGP |
| VO: ≈ 66 ladders × ~9 lines incl. feminine variants and prompts ≈ **600 lines** | 1.5–2 studio days, 25,000–50,000 EGP incl. talent |
| Editing: 230 clips | 60,000–100,000 EGP |
| Stock: 20–30 clips | 30,000–125,000 EGP |
| SLP: full script review + field-test design | 20,000–40,000 EGP |
| Legal, props, locations, catering, contingency | 60,000–100,000 EGP |
| **Content total for v1** | **≈ 370,000–735,000 EGP (≈ USD 7,400–14,700)** |
| **Calendar** | **≈ 10–12 weeks** from a green field test to 230 clips in the CMS |

App development (Android-first MVP) is a separate budget, covered after sections 9–10 of the brief are approved.
