# (B) Content Matrix — Ladders 1–20

Status: **DRAFT v0.1 — for review before the voice script is locked.**
Level lines (L1–L4) for each ladder are in [doc A](A-language-map.md). This document gives, for each clip: what is on screen, the exact audio sequence, where the pause goes and how long it is, and what the child is expected to do.

---

## 1. Conventions — read these first

### 1.1 Audio is built from segments, not recorded per clip

Every ladder has a small **line inventory**:
- its four level lines `L1–L4`, plus the feminine versions where needed;
- a few prompt lines (a question, a cloze stem, a CHOOSE question).

The app **assembles** each clip's audio at playback from these segments, using the child's current level `n`. This is what makes "play the child's level, then model one level above" possible without recording 4× the clips. It also means **the parent records a ladder once (4–8 short lines), not every clip** (see doc E, change #2).

Notation used below: `Ln` = the child's current level line · `Ln+1` = one level up (at n = 4, `Ln+1` = `L4` again) · `⏸ 5s` = silent "your turn" window with the visual cue on.

### 1.2 Clip-type templates

| Type | Audio template | Pause | Child's job |
|---|---|---|---|
| MODEL | `Ln` · (1s) · `Ln` · (1.5s) · `Ln+1` | none | watch |
| IMITATE | on-camera adult: "قول:" `Ln` · ⏸ · `Ln` (smile, nod) | 5s | say `Ln` |
| COMPLETE | `stem(n)` · ⏸ · `Ln` · `Ln+1` | 4s | say the missing word |
| ANSWER | `question` · ⏸ · `Ln` · `Ln+1` | 6s | answer at own level |
| ADD A WORD | `L1` · `L2` · … up to `Ln+1` (1.5s between) · ⏸ · `Ln+1` | 5s | follow, then try the longest |
| CHOOSE | `question` · ⏸ (tap enabled) · on tap: that item's `Ln` | 6s | tap + say |
| FIND IT | `question` · ⏸ (tap enabled) · on correct tap: "أهي!" + `Ln`; on wrong tap: calm re-ask once, then show | 6s | tap the right one |
| DO AND SAY | `command` · ⏸ (move) · `Ln` in first person · ⏸ | 5s + 5s | move, then say |
| MINI STORY | 3–4 shots with VO · `question` · ⏸ · `Ln` · `Ln+1` | 6s | answer |
| **TEMPTATION** *(proposed new type)* | the problem is shown, **no words** · ⏸ · `Ln` · the problem is solved · `Ln+1` | 6s | ask on their own |

**Why TEMPTATION is added.** For requests, the most effective prompt used by SLPs is a *communication temptation*: a need is created (a closed box, a toy out of reach) and the adult waits without asking anything. It trains starting to talk, not just repeating. It fits the brief's "do not fill the silence" rule perfectly.

### 1.3 Rules that hold for every clip

- **After the pause, the app always re-models the sentence. It never judges.** The app cannot hear the child and must not pretend to. There is no "برافو" for a right answer; the acknowledgement is the re-model itself plus a gentle visual.
- **A speaking face appears only in IMITATE clips.** Everywhere else speech is voice-over over action, so a parent's voice can replace it without a lip-sync mismatch.
- **The pause length (4–6s) can be changed by the parent.** The video therefore needs a *hold* section (6–8s of still or expectant footage) that the player can stretch. See the shot list rules in doc C.
- **Approximations count.** "مي" for مية, "كمّا" for كمان. The expected responses below are targets, not pass/fail criteria.

---

## 2. Matrix

### 1 · R01 — مية (POV) ✅ pilot
Lines: `مية | عايز مية | أنا عايز مية | أنا عايز مية ساقعة` · ♀ عايزة
Stems: `مـ… | عايز… | أنا عايز… | أنا عايز مية…`
Extra lines for CHOOSE: `لبن | عايز لبن | أنا عايز لبن | أنا عايز لبن سخن`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R01-01 | MODEL | POV: adult hands pour water from a bottle into a clear glass; the glass is brought toward the lens; sip sound | template | — | watches |
| R01-02 | IMITATE | Adult woman, face close-up, glass of water held next to her cheek | "قول:" `Ln` ⏸ `Ln` | 5s | says `Ln` |
| R01-03 | COMPLETE | Close-up: water glugging into the glass | `stem(n)` ⏸ `Ln` `Ln+1` | 4s | says the last word |
| R01-04 | ANSWER | POV: adult hands hold a bottle toward the lens, adult's torso at child height, no face | "عايز إيه؟" (♀ "عايزة إيه؟") ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| R01-05 | CHOOSE | Two stills side by side: glass of water · glass of milk | "عايز تشرب إيه؟ مية ولا لبن؟" ⏸ → tapped item's `Ln` | 6s | taps + names |

### 2 · R02 — كمان (POV) ✅ pilot
Lines: `كمان | بسكوت كمان | عايز بسكوت كمان | أنا عايز بسكوت كمان` · ♀ عايزة
Stems: `كمـ… | بسكوت… | عايز بسكوت… | أنا عايز بسكوت…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R02-01 | MODEL | POV: plate with one biscuit; child's hand takes it; plate is empty; child's hand taps the plate; adult hand adds another | template | — | watches |
| R02-02 | ANSWER | POV: empty plate with crumbs, adult hand holding the biscuit pack just above it | "البسكوت خلص… عايز إيه؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| R02-03 | ADD A WORD | Plate that fills one biscuit at a time as each line is spoken | `L1`…`Ln+1` ⏸ `Ln+1` | 5s | tries the longest line |
| R02-04 | TEMPTATION | POV: adult hand holds the pack, closed, still, just out of reach | *(silence)* ⏸ `Ln` · pack opens · `Ln+1` | 6s | asks on their own |

### 3 · R03 — لأ / مش عايز (POV) ✅ pilot
Lines: `لأ | مش عايز | مش عايز شوربة | أنا مش عايز شوربة` · ♀ عايزة
Stems: `— (L1: no stem, play MODEL instead) | مش… | مش عايز… | أنا مش عايز…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R03-01 | MODEL | POV: a spoon of soup comes toward the lens; child's hand gently pushes it away; adult hand puts it down (the "no" is respected) | template | — | watches |
| R03-02 | IMITATE | Adult face close-up, gentle head shake, hand raised like "stop" | "قول:" `Ln` ⏸ `Ln` | 5s | says `Ln` |
| R03-03 | ANSWER | POV: bowl of soup offered | "عايز شوربة؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| R03-04 | COMPLETE | Same bowl, spoon resting | `stem(n)` ⏸ `Ln` | 4s | last word |

Parent tip: *When the child says "مش عايز" clearly, respect it whenever it is safe. Words must work, or the child goes back to crying.*

### 4 · R04 — ساعدني (POV)
Lines: `ساعدني | بابا، ساعدني | بابا، ساعدني ألبس | بابا، ساعدني ألبس الجزمة`
Stems: `ساعـ… | بابا… | بابا، ساعدني… | بابا، ساعدني ألبس…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R04-01 | MODEL | POV looking down: child's feet, hands struggling with a shoe; man's hands come in and help | template | — | watches |
| R04-02 | IMITATE | Man's face close-up, holding a small shoe | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| R04-03 | TEMPTATION | POV: shoe half on, hands pulling, not working; a man's knees visible nearby, not helping | *(silence)* ⏸ `Ln` · hands help · `Ln+1` | 6s | asks for help |
| R04-04 | ADD A WORD | Same shoe scene, wide | `L1`…`Ln+1` ⏸ `Ln+1` | 5s | longest line |

### 5 · R05 — حمام (POV)
Lines: `حمام | عايز حمام | عايز أروح الحمام | ماما، عايز أروح الحمام` · ♀ عايزة
Stems: `حمـ… | عايز… | عايز أروح… | ماما، عايز أروح…`
**Filming limit:** no child is ever filmed undressed or on the toilet. Only the door, the potty or seat as objects, and a fully dressed child at the door.

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R05-01 | MODEL | POV: walking down the hall to the bathroom door; woman's hand opens it; potty visible | template | — | watches |
| R05-02 | IMITATE | Woman's face close-up | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| R05-03 | ANSWER | POV: standing at the closed bathroom door | "عايز تروح فين؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| R05-04 | COMPLETE | Same door | `stem(n)` ⏸ `Ln` | 4s | last word |

### 6 · F01 — بتوجعني (POV)
Lines: `بتوجعني | إيدي بتوجعني | ماما، إيدي بتوجعني | ماما، إيدي بتوجعني هنا`
Stems: `بتوجـ… | إيدي… | ماما، إيدي… | ماما، إيدي بتوجعني…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| F01-01 | MODEL | POV: small hand held out to a woman, a finger points to a spot; woman's hands hold it and blow on it gently | template | — | watches |
| F01-02 | IMITATE | Woman's face, caring expression, holding her own hand | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| F01-03 | ANSWER | POV: woman kneeling, hands open toward lens (face cropped at the chin) | "مالك؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| F01-04 | FIND IT | Two stills: a child's hand · a child's foot | "فين إيدك؟" ⏸ → "أهي!" `L2` | 6s | taps the hand |

Parent tip: *Practise this one when nothing hurts. The goal is that a real pain gets a word, not only a cry.*

### 7 · E01 — خلص (POV) ✅ pilot
Lines: `خلص | العصير خلص | العصير خلص كله | أنا شربت العصير كله`
Stems: `خـ… | العصير… | العصير خلص… | أنا شربت العصير…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| E01-01 | MODEL | POV: glass of orange juice with a straw at the bottom of the frame; the level drops to empty; slurp sound | template | — | watches |
| E01-02 | COMPLETE | Close-up of the empty glass, last drops | `stem(n)` ⏸ `Ln` `Ln+1` | 4s | last word |
| E01-03 | MINI STORY (≈25s) | Shot 1: juice poured · Shot 2: POV drinking · Shot 3: empty glass put down · Shot 4: woman's hand lifts it and looks inside | VO: "ده عصير." / "بنشرب العصير." / "خلاص!" / "العصير فين؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| E01-04 | ADD A WORD | Empty glass turned upside down | `L1`…`Ln+1` ⏸ `Ln+1` | 5s | longest line |

### 8 · R06 — افتح (POV) ✅ pilot
Lines: `افتح | افتح العلبة | بابا، افتح العلبة | بابا، افتح العلبة دي`
Stems: `افـ… | افتح… | بابا، افتح… | بابا، افتح العلبة…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R06-01 | MODEL | POV: clear plastic box with a toy car inside; child's hands try the lid and fail; hands pass the box to a man; he opens it | template | — | watches |
| R06-02 | IMITATE | Man's face close-up, box held up next to it | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| R06-03 | TEMPTATION | POV: child's hands shake the closed box, car rattles inside; man's hands rest nearby, still | *(silence)* ⏸ `Ln` · box opens · `Ln+1` | 6s | asks on their own |
| R06-04 | DO AND SAY | Woman's hands open a jar lid in an exaggerated way | "افتح إيدك… اقفل إيدك!" ⏸ (child opens and closes hands) "أنا فتحت إيدي" ⏸ | 5s+5s | moves, then says |

### 9 · R07 — هات (POV) ✅ pilot
Lines: `هات | هات الكورة | بابا، هات الكورة | بابا، هات الكورة الحمرا`
Stems: `هـ… | هات… | بابا، هات… | بابا، هات الكورة…`
Extra lines for CHOOSE: `هات العربية | بابا، هات العربية | بابا، هات العربية الزرقا` (L1 = هات)

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R07-01 | MODEL | POV: red ball on a shelf, out of reach; child's arm reaches up; a man takes it down and rolls it to the lens | template | — | watches |
| R07-02 | TEMPTATION | POV: man sits holding the red ball on his lap, still, smiling (face cropped) | *(silence)* ⏸ `Ln` · ball rolls to lens · `Ln+1` | 6s | asks on their own |
| R07-03 | CHOOSE | Two stills: red ball · blue car | "عايز إيه؟ الكورة ولا العربية؟" ⏸ → tapped item's `Ln` | 6s | taps + says |
| R07-04 | IMITATE | Man's face, ball held up | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |

### 10 · F02 — جعان (POV)
Lines: `جعان | أنا جعان | أنا جعان أوي | أنا جعان، عايز آكل` · ♀ جعانة / عايزة
Stems: `جعـ… | أنا… | أنا جعان… | أنا جعان، عايز…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| F02-01 | MODEL | POV at the table: empty plate, child's hand taps a spoon on it; a woman brings a plate of rice | template | — | watches |
| F02-02 | IMITATE | Woman's face, hand on her own tummy | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| F02-03 | ANSWER | POV: woman leaning down to the lens (face cropped) | "مالك؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| F02-04 | COMPLETE | Empty plate close-up | `stem(n)` ⏸ `Ln` | 4s | last word |

### 11 · F03 — عطشان (POV)
Lines: `عطشان | أنا عطشان | أنا عطشان أوي | أنا عطشان، عايز مية` · ♀ عطشانة / عايزة
Stems: `عطشـ… | أنا… | أنا عطشان… | أنا عطشان، عايز…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| F03-01 | MODEL | POV: after kicking a ball in the hallway, child's hand wipes the forehead, then reaches for a water bottle | template | — | watches |
| F03-02 | IMITATE | Woman's face, fanning herself | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| F03-03 | FIND IT | Two stills: water bottle · shoe | "فين المية؟" ⏸ → "أهي!" `Ln` | 6s | taps the bottle |
| F03-04 | COMPLETE | Water bottle close-up | `stem(n)` ⏸ `Ln` | 4s | last word |

### 12 · R08 — تاني (POV)
Lines: `تاني | نلعب تاني | يلا نلعب تاني | يلا نلعب كورة تاني`
Stems: `تا… | نلعب… | يلا نلعب… | يلا نلعب كورة…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| R08-01 | MODEL | POV on the floor: man rolls the ball to the lens, it is rolled back, repeat | template | — | watches |
| R08-02 | TEMPTATION | Man holds the ball after one roll and waits, still (face cropped) | *(silence)* ⏸ `Ln` · rolls again · `Ln+1` | 6s | asks for more |
| R08-03 | DO AND SAY | A woman's feet jump once on a rug | "نُط!" ⏸ (child jumps) "تاني!" ⏸ `Ln` | 5s+5s | jumps, then says |
| R08-04 | ADD A WORD | Ball rolling back and forth | `L1`…`Ln+1` ⏸ `Ln+1` | 5s | longest line |

### 13 · Q01 — أيوه (POV)
Lines: `أيوه | أيوه، عايز | أيوه، عايز لبن | أيوه، أنا عايز لبن` · ♀ عايزة
Stems: not used (a yes/no answer needs a question, not a cloze).

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| Q01-01 | MODEL | POV: woman's hand offers a cup of milk; child's hands take it | template | — | watches |
| Q01-02 | ANSWER | Same offer, the cup held still | "عايز لبن؟" ⏸ `Ln` · hands take cup · `Ln+1` | 6s | `Ln` |
| Q01-03 | ANSWER (contrast) | Same framing, bowl of soup | "عايز شوربة؟" ⏸ R03 `Ln` | 6s | "لأ / مش عايز" — shows the yes/no contrast with R03 |
| Q01-04 | ADD A WORD | Milk being poured | `L1`…`Ln+1` ⏸ `Ln+1` | 5s | longest line |

### 14 · A01 — بياكل (Observe) ✅ pilot
Lines: `بياكل | الولد بياكل | الولد بياكل موزة | الولد بياكل موزة كبيرة`
Stems: `بيا… | الولد… | الولد بياكل… | الولد بياكل موزة…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| A01-01 | MODEL | Boy (4–6 y) at the kitchen table peels a big banana and takes a bite; close-up of the bite | template | — | watches |
| A01-02 | COMPLETE | Close-up: boy chewing | `stem(n)` ⏸ `Ln` `Ln+1` | 4s | last word |
| A01-03 | ANSWER | Medium shot: boy eating, clearly visible | "الولد بيعمل إيه؟" ⏸ `Ln` `Ln+1` | 6s | at L1: "بياكل" |
| A01-04 | IMITATE | Woman's face; she mimes a bite of banana | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |

### 15 · A02 — بتشرب (Observe) ✅ pilot
Lines: `بتشرب | البنت بتشرب | البنت بتشرب لبن | البنت بتشرب لبن بالكوباية`
Stems: `بتشـ… | البنت… | البنت بتشرب… | البنت بتشرب لبن…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| A02-01 | MODEL | Girl (4–6 y) drinks milk from a clear glass, milk moustache, puts the glass down | template | — | watches |
| A02-02 | ANSWER | Medium shot, girl mid-drink | "البنت بتعمل إيه؟" ⏸ `Ln` `Ln+1` | 6s | at L1: "بتشرب" |
| A02-03 | FIND IT | Two stills from the pilot: the girl drinking · the boy eating (A01) | "مين بيشرب؟" ⏸ → "أهي! البنت بتشرب." | 6s | taps the girl |
| A02-04 | COMPLETE | Close-up on the glass at her lips | `stem(n)` ⏸ `Ln` | 4s | last word |

### 16 · E02 — وقعت (Observe) ✅ pilot
Lines: `وقعت | الكورة وقعت | الكورة وقعت تحت | الكورة وقعت تحت الترابيزة`
Stems: `وقـ… | الكورة… | الكورة وقعت… | الكورة وقعت تحت…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| E02-01 | MODEL | Ball rolls to the edge of the table, falls, bounces, rolls under the table and stops — all in frame | template | — | watches |
| E02-02 | COMPLETE | Same action, close angle (the second take) | `stem(n)` ⏸ `Ln` `Ln+1` | 4s | last word |
| E02-03 | ANSWER | Ball resting under the table, woman's hand reaches in | "الكورة فين؟" ⏸ `Ln` `Ln+1` | 6s | `Ln` |
| E02-04 | ADD A WORD | Slow-motion replay of the fall | `L1`…`Ln+1` ⏸ `Ln+1` | 5s | longest line |

### 17 · A03 — نايم (Observe · IN/STOCK)
Lines: `نايم | البيبي نايم | البيبي نايم ع السرير | البيبي الصغير نايم ع السرير`
Stems: `نا… | البيبي… | البيبي نايم… | البيبي الصغير نايم…`
Delivery note: record these lines *whispered*. The prosody teaches "quiet, the baby is sleeping".

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| A03-01 | MODEL | Real infant asleep on a bed (a family volunteer at nap time, or stock) | template (whispered) | — | watches |
| A03-02 | COMPLETE | Close-up of the sleeping face | `stem(n)` ⏸ `Ln` | 4s | last word |
| A03-03 | DO AND SAY | Woman lays her head on her hands, eyes closed | "نام زي البيبي!" ⏸ "أنا نايم… هس" ⏸ | 5s+5s | pretends to sleep, then says |
| A03-04 | FIND IT | Two stills: baby sleeping · baby laughing | "فين البيبي النايم؟" ⏸ → "أهو!" `L2` | 6s | taps sleeping baby |

### 18 · Q02 — فين؟ (POV) ✅ pilot
Lines: `فين؟ | فين الكورة؟ | الكورة راحت فين؟ | ماما، الكورة راحت فين؟`
Delivery note: a clear rising question intonation on every line.

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| Q02-01 | MODEL | POV: child's hands lift a sofa cushion (nothing there), then look behind a curtain; the ball is under the chair | template · then "أهي!" | — | watches |
| Q02-02 | IMITATE | Woman's face, palms up, "where?" gesture | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| Q02-03 | FIND IT | Two stills: ball under a chair · empty chair | "فين الكورة؟" ⏸ → "أهي! تحت الكرسي." | 6s | taps correctly |
| Q02-04 | TEMPTATION | Ball rolls behind the sofa and disappears; POV stays on the empty spot | *(silence)* ⏸ `Ln` · hand finds it · "أهي!" | 6s | asks "فين؟" |

### 19 · Q03 — إيه ده؟ (POV)
Lines: `إيه؟ | إيه ده؟ | ماما، إيه ده؟ | ماما، إيه ده هناك؟`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| Q03-01 | MODEL | POV: a paper bag on the table; woman's hand slowly pulls out a toy car | template · then "دي عربية!" | — | watches |
| Q03-02 | IMITATE | Woman's face, curious, pointing off-screen | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| Q03-03 | TEMPTATION | The bag rustles, part of a banana is visible, then stops | *(silence)* ⏸ `Ln` · reveal · "دي موزة!" | 6s | asks "إيه ده؟" |

### 20 · L01 — هنا (POV)
Lines: `هنا | تعالى هنا | بابا، تعالى هنا | بابا، تعالى اقعد هنا`
Stems: `هـ… | تعالى… | بابا، تعالى… | بابا، تعالى اقعد…`

| Clip | Type | On screen | Audio | Pause | Expected response |
|---|---|---|---|---|---|
| L01-01 | MODEL | POV on the sofa: child's hand pats the empty cushion; a man walks over and sits down beside | template | — | watches |
| L01-02 | IMITATE | Man's face, patting a cushion | "قول:" `Ln` ⏸ `Ln` | 5s | `Ln` |
| L01-03 | COMPLETE | Cushion being patted, man standing across the room | `stem(n)` ⏸ `Ln` · man comes over | 4s | last word |
| L01-04 | DO AND SAY | Woman's hand pats the floor | "اقعد هنا!" ⏸ (child sits) "أنا قاعد هنا" (♀ قاعدة) ⏸ | 5s+5s | sits, then says |

---

## 3. Totals for ladders 1–20

- **80 clips** (4 per ladder; R01 has 5, Q03 has 3).
- Type mix: MODEL 20 · IMITATE 13 · COMPLETE 11 · ANSWER 11 · TEMPTATION 7 · ADD A WORD 6 · FIND IT 5 · DO AND SAY 4 · CHOOSE 2 · MINI STORY 1. (Mini stories are cheaper to write once ~15 ladders exist to combine; more come in ladders 21–66.)
- IMITATE is kept at about 16% of clips on purpose. For a late talker, direct "قول…" demands can create pressure, and some children shut down. Modelling plus expectant waiting carries most of the load.
- **Voice lines to record for ladders 1–20:** 80 level lines + 34 feminine variants + ~60 prompts/stems/extras ≈ **175 short lines** ≈ one studio half-day.
