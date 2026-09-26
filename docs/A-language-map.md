# (A) Language Map — 66 Sentence Ladders

Status: **DRAFT v0.1 — for review by Mahmoud + an Egyptian speech-language pathologist (SLP) before any filming.**
Machine-readable source: [`data/ladders.csv`](../data/ladders.csv) (this table is generated from it — edit the CSV, not this file).

## How the ladders were built

**Level rule (stricter than the brief's example, on purpose).**

| Level | Length | Typical structure added |
|---|---|---|
| L1 | 1 word | the target word |
| L2 | 2 words | agent + action · action + object · want + object · attribute + object · negation |
| L3 | 3 words | full clause, or addressee (بابا، …) + request |
| L4 | max 4 words | one extra element only: adjective, place, or one short second clause |

Clitics that Egyptian speech glues to the next word (ع، م، ب) are not counted as separate words.

> **Correction to the brief.** The example ladder `الكورة الكبيرة وقعت على الأرض` is 5 words and adds two elements at once (adjective + place) in one step. For a late talker that is two steps, not one. It is revised here as E02: `وقعت → الكورة وقعت → الكورة وقعت تحت → الكورة وقعت تحت الترابيزة`.
> Also `مية باردة` → `مية ساقعة`: at home, Egyptians say ساقعة for a cold drink. باردة sounds like a textbook.

**Ranking.** Global rank = usefulness to a 2.5–3.5-year-old late talker. Ladders that let the child *get something done* (a need, a refusal, help, pain, toilet, "more", "finished") come first. That is what turns into real use at home, and home use is the headline metric. The brief's module order still decides ties.

**Perspective (new rule — see risk #2 in doc E).**
- `POV` = first-person ladder ("أنا عايز…"). Filmed from the child's eye level. The child's own hands are in frame and an adult's hands and torso face the lens. **No speaking face.** The child then hears the sentence as *their own* line, not as a line said by a stranger on screen. This avoids pronoun confusion and keeps the audio fully replaceable by the parent.
- `Observe` = third-person ladder ("الولد بياكل…"). Filmed as observation of another person.

**Gender.** `gender_forms` lists the words that must be re-recorded in the feminine for a girl (e.g. عايز→عايزة). The app picks the variant from the child's profile. 20 of the 66 ladders need this. It adds audio only, never video.

**Pilot.** The 10 ladders marked ✅ are the 30-clip pilot (see doc C). All of them can be filmed in one apartment in one day.

**Out of scope (as briefed):** letters, numbers, shapes, English, colours beyond one ladder (D05; expressive colour naming usually comes after age 3), "ليه؟" questions.

## The 66 ladders

| # | ID | Module | L1 | L2 | L3 | L4 | ♀ forms | View | Source | Pilot |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | R01 | Requests | مية | عايز مية | أنا عايز مية | أنا عايز مية ساقعة | عايز→عايزة | POV | IN | ✅ |
| 2 | R02 | Requests | كمان | بسكوت كمان | عايز بسكوت كمان | أنا عايز بسكوت كمان | عايز→عايزة | POV | IN | ✅ |
| 3 | R03 | Requests | لأ | مش عايز | مش عايز شوربة | أنا مش عايز شوربة | عايز→عايزة | POV | IN | ✅ |
| 4 | R04 | Requests | ساعدني | بابا، ساعدني | بابا، ساعدني ألبس | بابا، ساعدني ألبس الجزمة | — | POV | IN |  |
| 5 | R05 | Routine | حمام | عايز حمام | عايز أروح الحمام | ماما، عايز أروح الحمام | عايز→عايزة | POV | IN |  |
| 6 | F01 | Feelings | بتوجعني | إيدي بتوجعني | ماما، إيدي بتوجعني | ماما، إيدي بتوجعني هنا | — | POV | IN |  |
| 7 | E01 | What happened | خلص | العصير خلص | العصير خلص كله | أنا شربت العصير كله | — | POV | IN | ✅ |
| 8 | R06 | Requests | افتح | افتح العلبة | بابا، افتح العلبة | بابا، افتح العلبة دي | — | POV | IN | ✅ |
| 9 | R07 | Requests | هات | هات الكورة | بابا، هات الكورة | بابا، هات الكورة الحمرا | — | POV | IN | ✅ |
| 10 | F02 | Feelings | جعان | أنا جعان | أنا جعان أوي | أنا جعان، عايز آكل | جعان→جعانة؛ عايز→عايزة | POV | IN |  |
| 11 | F03 | Feelings | عطشان | أنا عطشان | أنا عطشان أوي | أنا عطشان، عايز مية | عطشان→عطشانة؛ عايز→عايزة | POV | IN |  |
| 12 | R08 | Requests | تاني | نلعب تاني | يلا نلعب تاني | يلا نلعب كورة تاني | — | POV | IN |  |
| 13 | Q01 | Questions | أيوه | أيوه، عايز | أيوه، عايز لبن | أيوه، أنا عايز لبن | عايز→عايزة | POV | IN |  |
| 14 | A01 | Actions | بياكل | الولد بياكل | الولد بياكل موزة | الولد بياكل موزة كبيرة | — | Observe | IN | ✅ |
| 15 | A02 | Actions | بتشرب | البنت بتشرب | البنت بتشرب لبن | البنت بتشرب لبن بالكوباية | — | Observe | IN | ✅ |
| 16 | E02 | What happened | وقعت | الكورة وقعت | الكورة وقعت تحت | الكورة وقعت تحت الترابيزة | — | Observe | IN | ✅ |
| 17 | A03 | Actions | نايم | البيبي نايم | البيبي نايم ع السرير | البيبي الصغير نايم ع السرير | — | Observe | IN/STOCK |  |
| 18 | Q02 | Questions | فين؟ | فين الكورة؟ | الكورة راحت فين؟ | ماما، الكورة راحت فين؟ | — | POV | IN | ✅ |
| 19 | Q03 | Questions | إيه؟ | إيه ده؟ | ماما، إيه ده؟ | ماما، إيه ده هناك؟ | — | POV | IN |  |
| 20 | L01 | Location | هنا | تعالى هنا | بابا، تعالى هنا | بابا، تعالى اقعد هنا | — | POV | IN |  |
| 21 | A04 | Actions | بيلعب | بيلعب كورة | الولد بيلعب كورة | الولد بيلعب كورة مع بابا | — | Observe | IN |  |
| 22 | R09 | Requests | دوري | دوري أنا | هات، دوري أنا | هات الكورة، دوري أنا | — | POV | IN |  |
| 23 | R10 | Routine | باي | باي بابا | باي، بابا رايح | باي بابا، ارجع بسرعة | — | POV | IN |  |
| 24 | A05 | Actions | راح | بابا راح | بابا راح الشغل | بابا راح الشغل بالعربية | — | Observe | IN |  |
| 25 | A06 | Actions | جه | بابا جه | بابا جه البيت | بابا جه وجاب بسكوت | — | Observe | IN |  |
| 26 | D01 | Description | بتاعي | الكورة بتاعتي | دي الكورة بتاعتي | دي الكورة الحمرا بتاعتي | — | POV | IN |  |
| 27 | E03 | What happened | اتدلق | اللبن اتدلق | اللبن اتدلق ع الأرض | أوبس، اللبن اتدلق ع الأرض | — | Observe | IN |  |
| 28 | E04 | What happened | اتكسرت | البسكوتة اتكسرت | البسكوتة اتكسرت نصين | أوبس، البسكوتة اتكسرت نصين | — | Observe | IN |  |
| 29 | D02 | Description | سخن | الشاي سخن | الشاي سخن أوي | حاسب، الشاي سخن أوي | — | Observe | IN |  |
| 30 | L02 | Location | جوه | جوه العلبة | العربية جوه العلبة | العربية الصغيرة جوه العلبة | — | Observe | IN |  |
| 31 | L03 | Location | فوق | الكورة فوق | الكورة فوق الدولاب | الكورة الحمرا فوق الدولاب | — | Observe | IN |  |
| 32 | L04 | Location | تحت | القطة تحت | القطة تحت الترابيزة | القطة نايمة تحت الترابيزة | — | Observe | IN/STOCK |  |
| 33 | L05 | Location | حط | حط الكورة | حط الكورة جوه | حط الكورة جوه السبت | — | POV | IN |  |
| 34 | T01 | Routine | باكل | أنا باكل | أنا باكل رز | أنا باكل رز بالمعلقة | — | POV | IN |  |
| 35 | T02 | Routine | بلبس | بلبس الجزمة | أنا بلبس الجزمة | أنا بلبس الجزمة لوحدي | — | POV | IN |  |
| 36 | T03 | Routine | سناني | بغسل سناني | أنا بغسل سناني | أنا بغسل سناني بالفرشة | — | POV | IN |  |
| 37 | T04 | Routine | أنام | عايز أنام | أنا عايز أنام | أنا تعبان، عايز أنام | عايز→عايزة؛ تعبان→تعبانة | POV | IN |  |
| 38 | F04 | Feelings | تعبان | أنا تعبان | أنا تعبان خالص | أنا تعبان، بابا شيلني | تعبان→تعبانة | POV | IN |  |
| 39 | F05 | Feelings | مبسوط | أنا مبسوط | أنا مبسوط أوي | أنا مبسوط مع بابا | مبسوط→مبسوطة | POV | IN |  |
| 40 | F06 | Feelings | زعلان | أنا زعلان | أنا زعلان خالص | أنا زعلان، اللعبة اتكسرت | زعلان→زعلانة | POV | IN |  |
| 41 | D03 | Description | كبيرة | كورة كبيرة | دي كورة كبيرة | دي كورة كبيرة أوي | — | Observe | IN |  |
| 42 | D04 | Description | صغيرة | عربية صغيرة | دي عربية صغيرة | دي عربية صغيرة خالص | — | Observe | IN |  |
| 43 | D05 | Description | حمرا | كورة حمرا | دي كورة حمرا | أنا عايز الكورة الحمرا | عايز→عايزة | Observe | IN |  |
| 44 | D06 | Description | ساقع | العصير ساقع | العصير ساقع أوي | العصير ساقع وحلو | — | POV | IN |  |
| 45 | D07 | Description | حلو | طعمه حلو | البسكوت طعمه حلو | البسكوت ده طعمه حلو | — | POV | IN |  |
| 46 | A07 | Actions | بيغسل | بيغسل إيديه | بابا بيغسل إيديه | بابا بيغسل إيديه بالصابون | — | Observe | IN |  |
| 47 | A08 | Actions | شوط | شوط الكورة | الولد شاط الكورة | الولد شاط الكورة جامد | — | Observe | IN |  |
| 48 | A09 | Actions | بيجري | الولد بيجري | الولد بيجري بسرعة | الولد بيجري بسرعة برا | — | Observe | IN |  |
| 49 | A10 | Actions | قاعدة | تيتة قاعدة | تيتة قاعدة ع الكنبة | تيتة قاعدة ع الكنبة الكبيرة | — | Observe | IN |  |
| 50 | A11 | Actions | بيضحك | البيبي بيضحك | البيبي بيضحك أوي | البيبي بيضحك مع ماما | — | Observe | IN/STOCK |  |
| 51 | A12 | Actions | طالع | بابا طالع | بابا طالع السلم | بابا طالع السلم بسرعة | — | Observe | IN |  |
| 52 | E05 | What happened | وسخة | إيدي وسخة | إيدي وسخة خالص | إيدي وسخة، عايز أغسلها | عايز→عايزة | POV | IN |  |
| 53 | E06 | What happened | النور | النور طفي | بابا طفى النور | بابا طفى النور، ضلمة | — | Observe | IN |  |
| 54 | Q04 | Questions | مين؟ | مين ده؟ | مين بيخبط؟ | مين بيخبط ع الباب؟ | — | POV | IN |  |
| 55 | R11 | Requests | يلا | يلا نروح | يلا نروح برا | يلا نروح عند تيتة | — | POV | IN |  |
| 56 | L06 | Location | برا | بابا برا | بابا واقف برا | بابا واقف برا البيت | — | Observe | IN |  |
| 57 | L07 | Location | جنب | جنب ماما | قاعد جنب ماما | أنا قاعد جنب ماما | قاعد→قاعدة | POV | IN |  |
| 58 | T05 | Routine | بستحمى | أنا بستحمى | أنا بستحمى دلوقتي | أنا بستحمى بمية سخنة | — | POV | IN |  |
| 59 | A13 | Actions | قطة | القطة بتشرب | القطة بتشرب لبن | القطة الصغيرة بتشرب لبن | — | Observe | IN/STOCK |  |
| 60 | A14 | Actions | عربية | العربية ماشية | العربية ماشية بسرعة | العربية الحمرا ماشية بسرعة | — | Observe | IN/STOCK |  |
| 61 | A15 | Actions | كلب | الكلب بيجري | الكلب بيجري برا | الكلب بيجري ورا الكورة | — | Observe | STOCK |  |
| 62 | E07 | What happened | طارت | العصفورة طارت | العصفورة طارت فوق | العصفورة طارت فوق الشجرة | — | Observe | STOCK |  |
| 63 | A16 | Actions | ألو | ألو بابا | ألو بابا، إزيك؟ | ألو بابا، تعالى بسرعة | — | POV | IN |  |
| 64 | A17 | Actions | بوسة | بوسة لماما | هدي ماما بوسة | أنا هدي ماما بوسة | — | POV | IN |  |
| 65 | F07 | Feelings | خايف | أنا خايف | خايف م الكلب | أنا خايف م الكلب | خايف→خايفة | POV | IN/STOCK |  |
| 66 | R12 | Requests | استنى | استنى شوية | بابا، استنى شوية | بابا، استنى، أنا جاي | جاي→جاية | POV | IN |  |

## Coverage by module

| Module | Ladders |
|---|---|
| Requests | 10 |
| Routine | 7 |
| Feelings | 7 |
| What happened | 7 |
| Questions | 4 |
| Actions | 17 |
| Location | 7 |
| Description | 7 |
| **Total** | **66** |

Source: `IN` = film in-house · `STOCK` = licensed stock footage · `IN/STOCK` = film in-house if a real animal or baby is available on the day, otherwise use stock.

## Notes for the SLP review

1. **Check every line for dialect.** It must sound like a Cairo home, not a textbook and not baby talk. Ask a second native speaker from outside Cairo (e.g. Alexandria or Upper Egypt) to flag words that are not understood nationally.
2. **Check the L2 semantic relations.** L2 lines should cover the main two-word relations: want+object (R01), recurrence (R02), negation (R03), agent+action (A01), action+object (A04), attribute+entity (D03), possession (D01) and location (L01).
3. **A01/A02/A05… use بابا / الولد / البنت.** In the parent's own clips these can be swapped for the child's real family names (e.g. "تيتة بتاكل"). This personalisation is one of the strongest levers the product has.
4. **The questions module (Q) teaches the child to *ask*.** Teaching the child to *answer* a question is built into every ladder through the ANSWER clip type.
