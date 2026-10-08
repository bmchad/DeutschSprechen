---
tags: [ledger, grammar]
updated: 2026-09-26
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
| `mit` takes Dativ | 1 | 3 | 3 | 4 | 75% | 0 | 🔴 | 2026-09-30 | *mit den Fähigkeit* → **der**; *mit viele Fälle* → **vielen** | `mit` is never Akkusativ. Feminine → **der**. Plural → **-en** on the determiner **and** `-n` on the noun. Got `mit seinen` right (S2) 09-30: *mit meine Lehrerin* → **mit meiner** (streak broken again). |
| `nach` takes Dativ | 1 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-23 | *nach das Arbeitad* → **nach dem Arbeitstag**; *Nach Arbeiten* → **Nach der Arbeit** | Always Dativ: **nach dem**, **nach der**. Before a whole clause the word is **nachdem** |
| `zu` vs `nach` for destinations | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-23 | *nazh Arbeiten* → **zur Arbeit** | **zu** for places and activities (**zur Arbeit**, **zur Schule**). **nach** only for cities, countries and **nach Hause** |

### 1c. Wechselpräpositionen (two-way) — *meaning-changing, always Tier 1*

`in` · `an` · `auf` · `über` · `unter` · `vor` · `hinter` · `neben` · `zwischen`
→ **Akkusativ** for motion (*wohin?*) · **Dativ** for position (*wo?*)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | My examples | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| **`in` = static location → Dativ** 🏆 | 1 | 8 | 8 | 9 | 89% | 0 | 🔴 | 2026-10-01 | *in viele anders Orten* → **in vielen**; *An schule* → **In der Schule**; *ins Büro* → **im Büro**; 10-01: *in chat* → **im Chat**, *in Markdown-Datei* → **in einer**, *in Antigravity IDE* → **in der** | Promoted — see [[4_Golden_Rules]]. No movement → Dativ. `in **der** Schule`, `in **vielen** Bereichen`, `im Büro`. Got `in Unternehmen` right |
| `in` = state change / motion → Akkusativ | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-10-01 | *in obsidian modus* → **in den Obsidian-Modus** | Changing state or mode is "movement" into it (*wohin?*). `der Modus` → `in den Modus` |
| `auf` = static → Dativ | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-23 | *über das Tisch* → **auf dem Tisch** | Lying on a surface = **auf** + Dativ (*wo?*). `über` = above it, not touching |

### 1d. Object roles (Nom subject / Akk direct / Dativ indirect)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | My examples | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| **`sein` / `werden` / `bleiben` take Nominativ** 🏆 | 1 | 3 | 3 | 3 | 100% | 0 | 🔴 | 2026-09-21 | *einen stück sein*, *ist einen Gelegenheit*, *was einen repair turn ist* | Promoted — see [[4_Golden_Rules]]. No `-n` after a linking verb, ever |
| **Masculine Akkusativ `-n`** 🏆 | 1 | 2 | 2 | 3 | 67% | 0 | 🔴 | 2026-09-21 | *meine Letzte Satz*, *mein Satz*. S2's *dein Arbeittag* and *dein Komputer* moved to 1e in S3: both nouns were believed neuter, and `dein` is right for a neuter object | Promoted — see [[4_Golden_Rules]]. **Only masculine changes in the Akkusativ.** `der→den`, `ein→einen`, `mein→meinen`. Diagnose the gender first |
| Time expressions take bare Akkusativ | 2 | 4 | 4 | 4 | 100% | 0 | 🔴 | 2026-09-23 | *an jedem tag* → **jeden Tag**; *jedemtag*, *jedem Tag* → **jeden Tag**; *alle Tag* → **den ganzen Tag** | No preposition. `jeden Tag`, `den ganzen Tag`, `letzte Woche`, `nächstes Jahr` |
| **`jeder` → `jedem` everywhere (Dativ leak)** | 1 | 5 | 5 | 5 | 100% | 0 | 🔴 | 2026-10-08 | 09-30: *jedem markdowns* · 10-08: *Jedem vergesen* (Nom) → **Jeder**; *jedem stuck* → **jede** (fem Akk); *jedem Tag* → **jeden Tag**; *jedem morgen* → **jeden Morgen** | `jedem` is **only** Dativ (masc/neut). Nom `jeder/jede/jedes`, Akk `jeden/jede/jedes`. He has frozen one form — the Dativ he drilled most |
| Pronoun as direct object → Akkusativ | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-23 | *sieht ihr* → **sie … sieht** | "them" = **sie**, just as "him" = **ihn**. `ihr` = "you all" or "to her" |

### 1e. Gender-caused (right case chosen, wrong article because gender was wrong)

Not case errors. Logged here only to keep the diagnosis honest — the real record is in [[3_Vocab_and_Nuance]].

| Noun | Hits | Att | Last | What I said | Correct |
|:--|:-:|:-:|:--|:--|:--|
| die Arbeit | 1 | 1 | 2026-09-21 | *für **den** Arbeit* — masculine Akk | *für **ihre** Arbeit*. He knew "für" takes Akk; he had the gender wrong |
| die KI | 1 | 1 | 2026-09-21 | *es ist benutzen gewesen* | **sie** wird verwendet — `die Intelligenz` is feminine |
| der Computer | 2 | 2 | 2026-09-23 | *das Komputer* as the subject (Nominativ right), then *dein Komputer* as the object — correct Akk for the neuter gender believed | **der** Computer → **den** Computer. The second hit moved here from masculine Akk `-n` in S3 |
| der Tisch | 1 | 1 | 2026-09-23 | *über das Tisch* — thought neuter | auf **dem** Tisch. The case was wrong too — see `auf` in 1c |
| der Arbeitstag | 2 | 2 | 2026-09-23 | *nach das Arbeitad* — thought neuter; then *dein Arbeittag* as the object, correct for a neuter | nach **dem** Arbeitstag · **deinen** Arbeitstag. Case wrong too in the first — see `nach` in 1b. The second hit moved here from masculine Akk `-n` in S3; the neuter belief is unconfirmed |
| die Work-Life-Balance | 1 | 1 | 2026-09-23 | *ein gut … (balance)* — Nominativ was right | **eine** gute Work-Life-Balance. The noun itself was a gap |
| der Ort | 1 | 1 | 2026-09-26 | *die besser Ort* — Nominativ right, thought feminine | **der** beste Ort |
| der Skill (oder die Datei) | 3 | 4 | 2026-10-01 | *das skill* 09-29 and 09-30; 10-01: *das skill.md* — defaults to neuter | **den** Skill / **die** SKILL.md. ⚠️ **Pattern across this table: masculine/feminine nouns keep getting `das`** — Computer, Tisch, Arbeitstag, Skill. His default for an unsure gender looks like neuter, probably English *it*. Neighbouring neuters (*das Repo*, *das Plugin*) likely pull it too |

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
| think **about** | denken **an** | Akk | 1 | 1 | 1 | 1 | 0 | 🔴 | 2026-09-23 | *denkst über Arbeit* → **denkst an die Arbeit** |
| ask **for** | bitten **um** | Akk | 1 | | | | | | |
| depend **on** | ankommen **auf** | Akk | 2 | | | | | | |
| be afraid **of** | Angst haben **vor** | Dat | 1 | | | | | | |
| belong **to** | gehören **zu** | Dat | 1 | | | | | | |

### 2b. False friends

| Looks like | Actually means | "That word" in German | T | Hits | Att | St | Last |
|:--|:--|:--|:-:|:-:|:-:|:-:|:--|
| **pasta** 🇵🇹 | folder → **der Ordner, die Ordner** | ⚠️ EN "paste" = `einfügen` — a **three-way trap**: PT *pasta* → EN "paste" → wrong German. His only Portuguese-source false friend so far. **`Ordner` missed a third time on 09-30** — wrote bare English *folder*, no gap | 1 | 3 | 3 | 🔴 | 2026-09-30 |
| putzen | to clean | versetzen / wechseln (to put) | 1 | 1 | 1 | 🔴 | 2026-10-01 |
| bekommen | to receive | werden (to become) | 1 | | | | |
| **also** 🏆 | so / therefore | auch (also) | 1 | 4 | 4 | 🔴 | 2026-09-23 |
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
| "leave" (in it) → `darin lassen` | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-10-01 | *oder lassen* → **oder darin lassen** | German needs the explicit prepositional adverb `darin` if you mean "leave it in that state/place" |
| **V2 after a fronted phrase** 🏆 | 1 | 21 | 21 | 23 | 91% | 0 | 🔴 | 2026-10-08 | Comma does not save you — see [[4_Golden_Rules]]. S2: 6 hits (*Deshalb*, *Darum*, *Nach Arbeiten*, *Wenn…* ×2, *aber (however), … hat*); right in *Außerdem, kannst du* (only the comma was wrong — Tier 3) and *Wenn …, kannst du*. S3: +3 (#9, #14, #17) 09-30: *Weil …, wir könnte* → **können wir**. *jetzt ich … kennen* → **jetzt kenne ich**. 10-08 text: *Zum Beispiel, wir* · *Wenn …, wir* ×2 · *Als (result), es kann*. |
| **`gerade` as filler** 🏆 | 1 | 7 | 7 | 7 | 100% | 0 | 🔴 | 2026-09-21 | Means "right now" only — see [[4_Golden_Rules]] |
| "which is why" → `weshalb` | 1 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | *welche ist weil* is not German. Use `weshalb` / `deshalb` / `darum` |
| **"more and more X" → `immer` + comparative** 🏆 | 2 | 3 | 3 | 3 | 100% | 0 | 🔴 | 2026-09-23 | *mehr und mehr wichtig* → **immer wichtiger**; *mehr und mehr menschen* → **immer mehr Menschen**. Promoted — see [[4_Golden_Rules]] |
| "by doing X" → `indem` | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | *von … erklären* → **indem sie … erklärt** |
| "for example" → `zum Beispiel` | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | Wrote ***für** Beispiel* — English "for" mapped straight onto `für`. It's **`zum`** = `zu` + `dem`, a Dativ contraction. Same trap as every other EN→DE preposition guess |
| English gerund as a subject → nominalized infinitive | 2 | 3 | 3 | 4 | 75% | 0 | 🔴 | 2026-09-23 | "Working from home" → **Das Arbeiten von zu Hause**, never *zu arbeiten*. Wrote *zu arbeiten aus Hause* ×3 (title + two subjects). Bare infinitives as subjects were right: *… oder spazieren gehen* |
| "good at -ing" → `gut` + infinitive + `können` | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-26 | *KI wirklich gut zu (replicate)* → **KI … wirklich gut kopieren kann**. *gut zu kopieren sein* = "easy to copy" — the meaning flips |
| "noun + to-verb" → relative clause | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-26 | "things (easy) to copy" → **Dinge, die leicht zu kopieren sind**. Wrote *einfach dings zu (replicate)* ×2 |
| Present continuous | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-23 | German has none — `ich lese` covers "I read" and "I am reading". *ist … legen* ("is lying") → **liegt** |

---

## 3. WORD ORDER (Syntax & V2)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|
| **Verb-final in subordinate clauses** 🏆 | 1 | 15 | 15 | 21 | 71% | 0 | 🟡 | 2026-10-08 | Promoted — see [[4_Golden_Rules]]. After `dass` / `weil` / `wenn` / `ob` / `da` **and in relative clauses**, the conjugated verb goes last. *dass manchmal es gibt* → **dass sie manchmal … gibt**; S2: 3 hits (*weil*, *wenn*, *da*), right in *Wenn du … wöllen* and *Wenn du diese Regeln (follow)*. S3: *Da denke ich* → **Da ich denke**, *Da ich studiere …* → **… studiere**; right in a `dass` clause 10-08 text: *Wenn irgendetwas ist nicht* · *weil wir gucken und hören …* · *ob wir haben … (locked)*. ✓ *dass wir … nicht weiß* — position right. |
| **`zu`-infinitive placement** 🏆 | 1 | 7 | 7 | 7 | 100% | 0 | 🔴 | 2026-09-30 | Promoted — see [[4_Golden_Rules]]. `zu` sits immediately before the final infinitive. Purpose takes **`um` … `zu`**. *zu fotos enhance* → **um Fotos zu verbessern**; *zu besser … (combine)* → **besser zu verbinden**; *zu einige … kopf* → **den Kopf freizubekommen**; *zu dass tuen* → **um das zu tun** 09-30: *zu mit ihr … renden* → **um mit ihr zu reden** — `um` missing again. |
| Negation placement | 2 | 3 | 3 | 3 | 100% | 0 | 🔴 | 2026-09-26 | `nicht` goes **before** what it negates. *nur Vorteile nicht* → **nicht nur Vorteile**; *ins Büro nicht* → **nicht im Büro**; *arbeit nicht* → **nicht … arbeiten** |
| With a modal, the infinitive goes to the end — separable verbs stay joined | 2 | 3 | 3 | 5 | 60% | 0 | 🔴 | 2026-09-30 | *kannst du spät fangen an* → **kannst du später anfangen**; *… und etwa anders macht* → **… und etwas anderes machen** (infinitive, not `macht`). Right with *(plan)* and *aufmachen* at the end. 09-30: *möchte … **zu** machen* → **möchte … machen** — position right, stray `zu`. No `zu` after a modal, ever |
| Perfekt participle placement | 1 | 0 | 0 | 0 | — | 0 | 🔴 | — | `haben`/`sein` second, participle at the very end |
| TeKaMoLo | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-23 | **Te**mporal → **Ka**usal → **Mo**dal → **Lo**kal. *arbeiten aus Hause heute* → **arbeiten heute von zu Hause** |

---

## 4. PLURALS

| Noun | T | Hits | Att | Streak | St | Last | What I said | Correct plural |
|:--|:-:|:-:|:-:|:-:|:-:|:--|:--|:--|
| der Mensch | 1 | 4 | 5 | 0 | 🔴 | 2026-09-23 | *mensche* / *mensch*; *etwa mensch* → **manche Menschen**. Got *menschen* right once (S2) | **die Menschen** — irregular, adds `-en` |
| der Lehrer | 2 | 1 | 1 | 0 | 🔴 | 2026-09-21 | *Lehrers* | **die Lehrer** — no change. The `-s` is an English habit |
| **English `-s` on German plural** 🏆 | 1 | 8 | 8 | 0 | 🔴 | 2026-09-30 | *freunds* → **Freunde**, *Arbeitfreunds* → **Kollegen**, *dings* ×3 → **Dinge**, *Machines* ×2 → **Maschinen**; 09-30: *markdowns* → **Markdown-Dateien** | Promoted — see [[4_Golden_Rules]]. Raised to Tier 1 in S3 (plurals are priority 2). German plurals use `-e`, `-er`, `-(e)n` or nothing; `-s` only for loanwords like *Autos* |
| das Wort | 2 | 1 | 1 | 0 | 🔴 | 2026-09-21 | *worte* | **die Wörter** (individual words) vs **die Worte** (utterances) |
| **Dativ plural `-n`** 🏆 | 1 | 3 | 3 | 0 | 🔴 | 2026-09-26 | *Arbeiter*, *viele Fälle*, *mit einfach dings* | **Arbeiter*n***, **vielen Aufgaben**, **mit einfachen Dingen**. Promoted — see [[4_Golden_Rules]] |
| Plural article: **`die`** for every gender | 1 | 1 | 1 | 0 | 🔴 | 2026-09-26 | *das … dings* — kept the singular article of *das Ding* | **die** … Dinge. Nominativ and Akkusativ plural are always **die**, whatever the singular: *das Ding → die Dinge*, *der Ort → die Orte*. Dativ plural: **den** … `-n` |

> **Dativ plural takes an extra `-n`**: `die Kinder` → `mit den Kinder**n**`. Exception: plurals already ending in `-n` or `-s`. Tier 1 — it sits at the intersection of both his priorities.

---

## 5. OTHER (tenses, pronouns, adjective endings)

| Rule | T | Hits | Rec | Att | Rate | Streak | St | Last | The fix |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--|:--|
| `wie` vs `was` ("how" vs "what") | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-10-01 | *was kann ich* → **wie kann ich** | "How" = `wie`. "What" = `was` |
| Formal vs Informal (`Sie` vs `du`) | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-10-01 | *lesen Sie* → **lies**; *vergleichen Sie* → **vergleiche** | We are using informal `du`. Imperative for `lesen` is `lies` |
| `welch-` vs `was` for "which noun" | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-10-01 | *was Modus* → **in welchem Modus** | "What mode" = "which mode" = `welch-` + ending. Also needs preposition `in` + Dativ |
| Simple past of `sein` (`waren`) | 1 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-10-01 | *wurden ... gewesen* → **waren** | Don't mix passive `wurden` with perfect `gewesen` for "were" |
| **Adjective endings** | 2 | 11 | 11 | 11 | 100% | 0 | 🔴 | 2026-10-01 | Attributive adjectives always take an ending. *wichtig factor* → **wichtiger**; *falsch Informationen* → **falsche**; *anders Orten* → **verschiedenen**; S2: *groß* → **große**, *ein gut* → **eine gute**, *ein schön Weg* → **ein schöner Weg**; S3: *mit einfach* → **mit einfachen**, *die besser Ort* → **der beste Ort**. 10-01: *Dein Antworten* → **Deine**. **Reverse case, 09-30:** *sind du fröhliches* → **bist du froh** — an ending added where none belongs. After `sein` / `werden` / `bleiben` the adjective is bare. Taught 09-26 with the minimal pair *Das Essen ist fertig* / *das fertige Essen* |
| Verb ending must match the subject | 2 | 8 | 8 | 11 | 73% | 1 | 🔴 | 2026-09-30 | `du` → **-st** (*bist*, *willst*); `man` / `das` / one noun → **-t** (*denkt*, *ist*). *man denkst* → **denkt man**; *Das meinst* → **Das bedeutet**; *Man zeit sparen* → **Man spart Zeit**; *wöllen* → **willst**; S3: *sind du* → **bist du**, *KI … sind*, *Deutschland sind* → **ist**. 09-29: ✓ *braucht man*. 09-30: ***sind du* again** → **bist du** — same form twice, looks like `sind` stored as a generic "are"; ✓ *du … hast* in the same sentence |
| **`dass` vs `damit`** | 1 | 2 | 2 | 2 | 100% | 0 | 🔴 | 2026-09-30 | `dass` = *that* (a statement follows) · `damit` = *so that* (a purpose). **Reversed once each way:** 09-28 *dass du push könnst* → **damit**; 09-30 *fröhlich, damit du … gewechselt hast* → **froh, dass**. The second is over-application of the first lesson. Both are row 2 — verb last either way |
| **Noun capitalization** | 2 | 9 | 9 | 25 | 36% | 0 | 🔴 | 2026-09-21 | Every noun, always. He gets it right more often than wrong — inconsistency, not ignorance |
| **Invented English-shaped words** | 1 | 7 | 7 | 24 | 29% | 1 | 🟡 | 2026-09-23 | *Kautious, Privaciheit, zweilich-gecheckt, Gegenheit, gewird*; S2: *überzeit*, *Personal-Leben*. Every honest gap is a correct attempt: 11 in S2, 6 in S3 with no inventions at all. S3's gaps came after an explicit reminder, so they add to `Att` but not to `Streak` — **don't remind next session**. Was promotable in S1–S2 but never promoted; at 29% it no longer qualifies, and it's improving, so no Golden Rule. **Leave a `(gap)` instead** — an honest gap teaches, an invented word does not |
| Passive voice | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-21 | `werden` + participle. *ist benutzen gewesen* → **wird verwendet** |
| `das` vs `dass` | 2 | 5 | 5 | 5 | 100% | 0 | 🔴 | 2026-10-08 | `dass` = conjunction · `das` = article/pronoun. Reversed once each way in S1, and again in S3: *das KI* → **dass KI**, *zu dass tuen* → **um das zu tun** 10-08: *Dass ist ganz normal* → **Das**. |
| Wrong connector | 2 | 3 | 3 | 3 | 100% | 0 | 🔴 | 2026-09-26 | *Ansonsten* → **Jedoch**; *Außer* → **Außerdem**; *Da, ich möchte* (= so) → **Deshalb möchte ich**. None of them means what was intended |
| Genitiv of possession | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-21 | *von unseren Leben* → **unseres Lebens** |
| Verb stem change (e→i) | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-23 | *helft* → **hilft**; *hilfen können* → **helfen können** — only `du` / `er` / `sie` / `es` change, never the infinitive. Also `geben→gibt`, `nehmen→nimmt` |
| `nicht …, sondern …` | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-23 | After a negation, "but (instead)" is **sondern**, never `aber`. *…, aber nach Hause* → **…, sondern zu Hause** |
| Relative pronoun matches its noun | 2 | 1 | 1 | 1 | ? | 0 | 🔴 | 2026-09-26 | The pronoun copies the noun's gender and number: *Dinge, das (exist)* → **Dinge, die existieren** |
| Superlative: `gut → besser → der beste` | 2 | 2 | 2 | 2 | ? | 0 | 🔴 | 2026-09-26 | "The best" is **der / die / das beste**; `besser` = better. *die besser Ort* → **der beste Ort**; *das meinst schlecht (dificult)* ("the most difficult") → **die schwierigsten** / **am schwersten**. German never builds "most" + adjective: **-st** goes on the adjective itself, however long — English *hard → hardest*, always, never *most difficult* |

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
