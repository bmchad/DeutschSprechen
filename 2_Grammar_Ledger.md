---
tags: [ledger, grammar]
updated: 2026-09-21
---

# Grammar Ledger

**Rule-centric.** One row = one rule, not one mistake. When the same rule breaks again, increment `Hits` and add the example — do not add a new row.

Maintained by the tutor, not by Bernardo. See the three predicates in [[0_Start_Here]].

## Column meanings

| Column | Meaning |
|:--|:--|
| `T` | Tier — **1** blocking · **2** worth fixing. Tier 3 never appears here |
| `Hits` | Times wrong, lifetime. Never decreases |
| `Rec` | Hits **in the last 5 sessions**. Ages out — this is what triggers interventions |
| `Att` | Attempts — times the rule was in play, right or wrong |
| `Rate` | Hits ÷ Att. Under 3 attempts, write `?` — no rate is trusted yet |
| `Streak` | Consecutive correct, unprompted, since the last error |
| `St` | 🔴 active · 🟡 improving · 🟢 fixed · ⚠️ relapsed |

**Common** = `Hits ≥ 3` and `Rate ≥ 33%`, or `Rate ≥ 60%` with `Att ≥ 3`.
**Fixed** = `Streak ≥ 3`, unprompted, spanning ≥ 2 sessions and ≥ 2 contexts.
**Promote to [[4_Golden_Rules]]** at 3 hits while common — or on a second relapse, whatever the count.

**Repair turn fires on `Rec`, never on `Hits`.** Tier 1 at `Rec ≥ 2`, Tier 2 at `Rec ≥ 3`. Lifetime hits from months ago can't trigger anything — a punctual mistake ages out of `Rec` and stops mattering. Tier 1 fires earlier than Tier 2 because waiting until 3 would mean intervening at the same moment the rule gets promoted, which is too late to prevent it.

Sort each section by `Rate` descending, not by `Hits`. The top of section 1 is what gets drilled next.

---

## 1. CASES — the priority

Split by *cause*, because each cause needs a different drill. "You made a case mistake" is useless feedback; "you treat Wechselpräpositionen as always-Dativ" is drillable.

### 1a. Verb government (verbs that force Dativ)

`helfen` · `danken` · `folgen` · `gefallen` · `gehören` · `antworten` · `glauben` · `passen` · `schmecken` · `gratulieren`

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | My examples | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| `helfen` takes Dativ | 1 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | *Studenten zu lernen helfen* → **Schülern**; *helft Arbeiter* → **Arbeitern** | Never Akkusativ. `Ich helfe **dir**`, not *dich*. Plural adds `-n`: **Arbeitern** |

### 1b. Fixed prepositions

**Always Dativ:** `mit` · `nach` · `aus` · `zu` · `von` · `bei` · `seit` · `außer` · `gegenüber`
**Always Akkusativ:** `für` · `ohne` · `gegen` · `um` · `durch` · `bis` · `entlang`

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | My examples | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| `mit` takes Dativ | 1 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | *mit den Fähigkeit* → **der**; *mit viele Fälle* → **vielen** | `mit` is never Akkusativ. Feminine → **der**. Plural → **-en** on the determiner **and** `-n` on the noun |

### 1c. Wechselpräpositionen (two-way) — *meaning-changing, always Tier 1*

`in` · `an` · `auf` · `über` · `unter` · `vor` · `hinter` · `neben` · `zwischen`
→ **Akkusativ** for motion (*wohin?*) · **Dativ** for position (*wo?*)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | My examples | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| `in` = static location → Dativ | 1 | 2 | 2 | 3 | ? | 1 | 🔴 | 2026-09-21 | *in viele anders Orten* → **in vielen**; *An schule* → **In der Schule** | No movement → Dativ. `in **der** Schule`, `in **vielen** Bereichen`. Got `in Unternehmen` right |

### 1d. Object roles (Nom subject / Akk direct / Dativ indirect)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | My examples | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| **`sein` / `werden` / `bleiben` take Nominativ** 🏆 | 1 | 3 | 3 | 3 | 100% | 0 | 🔴 | 2026-09-21 | *einen stück sein*, *ist einen Gelegenheit*, *was einen repair turn ist* | Promoted — see [[4_Golden_Rules]]. No `-n` after a linking verb, ever |
| Masculine Akkusativ `-n` | 1 | 2 | 2 | 3 | 67% | 0 | 🔴 | 2026-09-21 | *meine Letzte Satz*, *mein Satz*, *das Claude skill* | **Only masculine changes in the Akkusativ.** `der→den`, `ein→einen`, `mein→meinen` |
| Time expressions take bare Akkusativ | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | *an jedem tag* → **jeden Tag** | No preposition. `jeden Tag`, `letzte Woche`, `nächstes Jahr` |

### 1e. Gender-caused (right case chosen, wrong article because gender was wrong)

Not case errors. Logged here only to keep the diagnosis honest — the real record is in [[3_Vocab_and_Nuance]].

| Noun | Hits | Att | Last | What I said | Correct |
|:--|:-:|:-:|:--|:--|:--|
| die Arbeit | 1 | 1 | 2026-09-21 | *für **den** Arbeit* — masculine Akk | *für **ihre** Arbeit*. He knew "für" takes Akk; he had the gender wrong |
| die KI | 1 | 1 | 2026-09-21 | *es ist benutzen gewesen* | **sie** wird verwendet — `die Intelligenz` is feminine |

---

## 2. ENGLISH INTERFERENCE

Composing through English is the right strategy, but it leaks. Predicted #1 error source.

### 2a. Verb + preposition mismatch → causes case errors

English prepositions almost never map 1:1, and the German preposition drags its own case with it. Guessing from English gets *both* wrong.

| English | German | Case | T | Hits | Rec | Att | Streak | St | Last |
|:--|:--|:--|:-:|:-:|:-:|:-:|:-:|:-:|:--|
| reach / search **for** | suchen **nach** | **Dat** | 1 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-21 |
| gloss / mean **by** | meinen **mit** | **Dat** | 1 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-21 |
| worry **about** | sich sorgen **um** | Akk | 1 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-21 |
| help **with** | helfen **bei** | Dat | 2 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-21 |
| careful **about** | vorsichtig **mit** | Dat | 2 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-21 |
| think **about** (reflect) | nachdenken **über** | Akk | 1 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-21 |
| wait **for** | warten **auf** | Akk | 1 | | | | | | |
| think **about** | denken **an** | Akk | 1 | | | | | | |
| ask **for** | bitten **um** | Akk | 1 | | | | | | |
| depend **on** | ankommen **auf** | Akk | 2 | | | | | | |
| be afraid **of** | Angst haben **vor** | Dat | 1 | | | | | | |
| belong **to** | gehören **zu** | Dat | 1 | | | | | | |

### 2b. False friends

| Looks like | Actually means | "That word" in German | T | Hits | Att | St | Last |
|:--|:--|:--|:-:|:-:|:-:|:-:|:--|
| **pasta** 🇵🇹 | folder → **der Ordner, die Ordner** | ⚠️ EN "paste" = `einfügen` — a **three-way trap**: PT *pasta* → EN "paste" → wrong German. His only Portuguese-source false friend so far | 1 | 2 | 2 | 🔴 | 2026-09-23 |
| bekommen | to receive | werden (to become) | 1 | | | | |
| also | so / therefore | auch (also) | 1 | | | | |
| Gift | poison | Geschenk (gift) | 1 | | | | |
| bald | soon | kahl (bald) | 2 | | | | |
| Chef | boss | Koch (chef) | 2 | | | | |
| eventuell | possibly | schließlich (eventually) | 1 | | | | |
| sensibel | sensitive | vernünftig (sensible) | 2 | | | | |
| aktuell | current | eigentlich (actual) | 2 | | | | |
| Rat | advice | Ratte (rat) | 2 | | | | |
| spenden | to donate | ausgeben (to spend) | 2 | | | | |

### 2c. English structure transfer

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|
| **V2 after a fronted phrase** 🏆 | 1 | 6 | 6 | 6 | 100% | 0 | 🔴 | 2026-09-21 | Comma does not save you — see [[4_Golden_Rules]] |
| **`gerade` as filler** 🏆 | 1 | 7 | 7 | 7 | 100% | 0 | 🔴 | 2026-09-21 | Means "right now" only — see [[4_Golden_Rules]] |
| "which is why" → `weshalb` | 1 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | *welche ist weil* is not German. Use `weshalb` / `deshalb` / `darum` |
| "more and more X" → `immer` + comparative | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | *mehr und mehr wichtig* → **immer wichtiger** |
| "by doing X" → `indem` | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | *von … erklären* → **indem sie … erklärt** |
| "for example" → `zum Beispiel` | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | Wrote ***für** Beispiel* — English "for" mapped straight onto `für`. It's **`zum`** = `zu` + `dem`, a Dativ contraction. Same trap as every other EN→DE preposition guess |
| Present continuous | 1 | 0 | 0 | 0 | — | 0 | 🔴 | — | German has none — `ich lese` covers "I read" and "I am reading" |

---

## 3. WORD ORDER (Syntax & V2)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|
| **Verb-final in subordinate clauses** | 1 | 7 | 7 | 8 | 88% | **1** | 🟡 | 2026-09-21 | After `dass` / `weil` / `wenn` / `ob` **and in relative clauses**, the conjugated verb goes last. *dass manchmal es gibt* → **dass sie manchmal … gibt**; *die online share sein* → **die sie online teilen** |
| `zu`-infinitive placement | 1 | 3 | 3 | 3 | ? | 0 | 🔴 | 2026-09-21 | `zu` sits immediately before the final infinitive. Purpose takes **`um` … `zu`**. *zu fotos enhance* → **um Fotos zu verbessern** |
| Negation placement | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | `nicht` goes **before** what it negates. *nur Vorteile nicht* → **nicht nur Vorteile** |
| Perfekt participle placement | 1 | 0 | 0 | 0 | — | 0 | 🔴 | — | `haben`/`sein` second, participle at the very end |
| TeKaMoLo | 2 | 0 | 0 | 0 | — | 0 | 🔴 | — | **Te**mporal → **Ka**usal → **Mo**dal → **Lo**kal |

---

## 4. PLURALS

| Noun | T | Hits | Att | Streak | St | Last | What I said | Correct plural |
|:--|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| der Mensch | 1 | 3 | 3 | 0 | 🔴 | 2026-09-21 | *mensche* / *mensch* | **die Menschen** — irregular, adds `-en` |
| der Lehrer | 2 | 1 | 1 | 0 | 🔴 | 2026-09-21 | *Lehrers* | **die Lehrer** — no change. The `-s` is an English habit |
| das Wort | 2 | 1 | 1 | 0 | 🔴 | 2026-09-21 | *worte* | **die Wörter** (individual words) vs **die Worte** (utterances) |
| **Dativ plural `-n`** | 1 | 2 | 2 | 0 | 🔴 | 2026-09-21 | *Arbeiter*, *viele Fälle* | **Arbeiter*n***, **vielen Aufgaben** |

> **Dativ plural takes an extra `-n`**: `die Kinder` → `mit den Kinder**n**`. Exception: plurals already ending in `-n` or `-s`. Tier 1 — it sits at the intersection of both his priorities.

---

## 5. OTHER (tenses, pronouns, adjective endings)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|
| **Adjective endings** | 2 | 5 | 5 | 5 | 100% | 0 | 🔴 | 2026-09-21 | Attributive adjectives always take an ending. *wichtig factor* → **wichtiger**; *falsch Informationen* → **falsche**; *anders Orten* → **verschiedenen** |
| **Noun capitalization** | 2 | 9 | 9 | 25 | 36% | 0 | 🔴 | 2026-09-21 | Every noun, always. He gets it right more often than wrong — inconsistency, not ignorance |
| **Invented English-shaped words** | 1 | 5 | 5 | 5 | 100% | 0 | 🔴 | 2026-09-21 | *Kautious, Privaciheit, zweilich-gecheckt, Gegenheit, gewird*. **Leave a `(gap)` instead** — an honest gap teaches, an invented word does not |
| Passive voice | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | `werden` + participle. *ist benutzen gewesen* → **wird verwendet** |
| `das` vs `dass` | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | `dass` = conjunction · `das` = article/pronoun. He reversed both, once each way |
| Wrong connector | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | *Ansonsten* → **Jedoch**; *Außer* → **Außerdem**. Neither word means what he wanted |
| Genitiv of possession | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | *von unseren Leben* → **unseres Lebens** |
| Verb stem change (e→i) | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | *helft* → **hilft**. Also `geben→gibt`, `nehmen→nimmt` |

---

## WATCH LIST — recently fixed

🟢 rules that met all four fixed conditions. Resurface each once about 5 sessions after promotion to confirm it held.

| Rule | Fixed on | Confirm after | Relapses |
|:--|:--|:--|:-:|
| | | | |

---

## IGNORED — Tier 3, never drilled

Noise, and anything Bernardo has vetoed with *"stop correcting that"*. Corrected silently inline at most; never counted.

| Thing | Why ignored | Since |
|:--|:--|:--|
| `Kemma` → `gekommen` | Colloquial/regional variant, not a grammar error | 2026-09-21 |
| Capitalization slips while typing fast | Typo, not knowledge | 2026-09-21 |
| ß vs ss | Orthography, no meaning impact at A2 | 2026-09-21 |

---

## AVOIDANCE WATCH

Structures that fit what he wants to say but never appear. Absence is not mastery.

| Structure | Last seen | Note |
|:--|:--|:--|
| | | |
