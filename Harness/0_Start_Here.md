---
tags: [system]
learner: Bernardo
native_language: Portuguese (BR)
bridge_language: English
target_level: A2
started: 2026-09-21
---

# Deutsch Sprechen — How This Vault Works

A closed-loop German practice system. Mistakes go in, drills come back out.

## The learner

- Native Portuguese (BR), but learns German **through English** by choice — English and German are both Germanic, so the bridge is shorter.
- **All explanations in English.** Never Portuguese.
- Target level: **A2**. Explanations stay at A2 even when the grammar being explained is above it.

## Priorities, in order

1. **Cases** — Nominativ / Akkusativ / Dativ. The main weakness. Everything else is secondary.
2. **Plural forms** — including the Dativ plural `-n` rule, which serves priority 1 too.
3. **English interference** — false friends and verb+preposition mismappings, which is where most case errors are born.
4. **Gender** — *stored, not drilled.* Recorded on every noun purely so case errors can be diagnosed correctly (see below).

### Why gender is tracked but not drilled

`Ich sehe der Mann` has two possible causes:

- **Case error** — didn't know Akkusativ masculine needs `den`
- **Gender error** — thought `Mann` was feminine, so `der` looked right

Same symptom, opposite drills. Gender is logged on every noun so the right diagnosis is possible. It is never quizzed on its own.

### The English bridge for cases

English still has case — but only on pronouns, which is why Bernardo already uses them correctly by instinct:

| English | German | Case |
|:--|:--|:--|
| he | er | Nominativ |
| him | ihn | Akkusativ |
| him (indirect) | ihm | Dativ |
| his | sein | Genitiv |

*"I gave **him** the book"* → `him` = Dativ, `the book` = Akkusativ. He produces this flawlessly in English without thinking. **Use this bridge in every case explanation** — show the English sentence he'd already get right, then map it across.

## The files

Everything numbered lives here in **`Harness/`**. The repo root holds only `SKILL.md`, `Chat/`, and the Obsidian config. `[[wikilinks]]` resolve by filename, so no link needs a folder prefix.

| File | What lives there | Written when |
|:--|:--|:--|
| `0_Start_Here.md` | This file — the rules of the system | Rarely |
| `1_Sessions/` | One dated note per practice session, raw corrections | Every session |
| `2_Grammar_Ledger.md` | **Rule-centric.** One row per rule broken, with a hit counter | Every mistake |
| `3_Vocab_and_Nuance.md` | Words missed or looked up, with miss counts | Every unknown word |
| `4_Golden_Rules.md` | Rules auto-promoted at 3+ hits | Automatically |
| `5_Review_Queue.md` | Generated. What to drill next session | End of session |
| `6_About_Bernardo.md` | Real facts learned in conversation | **Chat mode only** |
| `7_Techniques.md` | Invented teaching devices that worked | When one lands |
| `../SKILL.md` | A copy of the skill, for version control — at the repo root | On every skill change |
| `../Chat/` | One `.md` per exchange, `/chat` output mode only — at the repo root | In `/chat` mode |

## The three layers

A contract for the tutor, **not a visible format**. Bernardo reads one continuous analysis per sentence — never a "standard part" followed by a "creative part".

| Layer | What it means |
|:--|:--|
| **FLOOR** | Guaranteed every time: every error gets a full block, case map on every sentence, every German sentence corrected, vault updated. Nothing overrides this |
| **DEFAULT** | The normal shape — protocols, nine sections, mode detection |
| **OPEN** | Standing licence to invent. The skill is the minimum, not the maximum. Never withhold something useful because it wasn't listed |

The open layer only fires **when it helps that specific sentence**. Creativity is not decoration. Anything that works gets recorded in [[7_Techniques]] so it accumulates instead of evaporating.

## The three modes

Every message is in one of three modes, and they behave differently:

| Mode | What it is | Follow-up question? | Writes to `6_About_Bernardo`? |
|:--|:--|:--|:--|
| 💬 **chat** | Real conversation about his life | Yes — a real question about him | Yes |
| 🔍 **analyse** | Isolated sentences from elsewhere, sent for correction | **No** | No |
| 📖 **story** | Collaborative fiction and roleplay | Yes — a plot advance | No |

Fiction is never recorded as fact. Only chat mode produces knowledge about him.

## The loop

```
SESSION START
  └─ Read 5_Review_Queue.md + top of 2_Grammar_Ledger.md
  └─ Warm-up: quiz 3 queue items before any new practice

DURING
  └─ Correct each sentence (9 sections, see the skill)
  └─ §8 example sentences are built from previously-missed vocab
  └─ §9 plot question is engineered to force the weakest case rule,
     using queue vocab as the English parenthetical words

SESSION END
  └─ Append instances to 1_Sessions/YYYY-MM-DD.md
  └─ Increment counters in 2_Grammar_Ledger.md and 3_Vocab_and_Nuance.md
  └─ Promote any rule hitting 3 to 4_Golden_Rules.md
  └─ Regenerate 5_Review_Queue.md
```

## The three predicates

Bernardo does not read this vault. He is busy learning German. Every decision about what to drill is made by the tutor, using three tests.

### 1. Is this mistake common?

**Rate, not count.** Erring 4 times out of 50 uses of `mit` is 8% — fine. Erring 4 times out of 4 uses of `wegen` is 100% — broken. Raw hit counts hide this, so every rule tracks `Attempts` (times the rule was in play, right or wrong) alongside `Hits`.

A rule is **common** when either:

- `Hits ≥ 3` **and** error rate `≥ 33%`, or
- error rate `≥ 60%` with `Attempts ≥ 3` — fast-track for something badly broken

Below 3 attempts, no rate is trusted. The row stays `unproven`.

**Recency matters as much as totals.** Every rule also tracks `Rec` — hits in the last 5 sessions. Two hits spread over three months is not a pattern; two hits in two sessions is. Old hits age out of `Rec` but stay in lifetime `Hits`, so a fluke from months ago counts for the record but can never trigger an intervention.

**Repair turns fire on `Rec`, never on `Hits`:** Tier 1 at `Rec ≥ 2`, Tier 2 at `Rec ≥ 3`. Tier 1 fires earlier because promotion to [[4_Golden_Rules]] already happens at 3 — waiting until 3 to intervene would mean acting at the exact moment the rule is already entrenched. The repair turn exists to stop it getting there.

**Avoidance counts as a signal, not as mastery.** If a structure that fits what he's saying never appears — no subordinate clauses, no Perfekt, no two-way prepositions — that is not a clean record. Flag it and build a §9 question that forces it.

### 2. Is it important?

Frequency is not importance. Writing `Kemma` for `gekommen` a hundred times is still not worth a single drill. Errors get a tier at correction time, and **only Tier 1 and Tier 2 ever touch a counter.**

| Tier | Meaning | Treatment |
|:--|:--|:--|
| **1 — Blocking** | Changes meaning, or breaks a high-frequency systematic rule in his priority list | Full ledger, repair turns, drilling, eligible for Golden Rule |
| **2 — Worth fixing** | Genuinely wrong and systematic, but doesn't change meaning and isn't a top priority | Counter tracked; drilled only when Tier 1 is clear |
| **3 — Noise** | Typos, capitalization, ß/ss, missing commas, regional or colloquial variants, one-off lexical facts | Fixed inline in one word. **Never logged, never counted, never drilled** |

**The test for Tier 3:** would a native misunderstand? would an A2 examiner mark it? Two nos → Tier 3.

What raises a tier:

- **Meaning-changing beats merely-wrong.** `in die Küche` (into) vs `in der Küche` (inside) is Tier 1. A wrong adjective ending nobody would notice is Tier 2.
- **Systematic beats lexical.** A rule covering hundreds of sentences outranks a fact about one word.
- **High-frequency triggers beat rare ones.** `mit` pays out daily; `gegenüber` does not.
- **His priorities.** Cases > plurals > English interference > everything else.
- **Above A2 is not Tier 1.** Genitiv subtleties and Konjunktiv II get noted and dropped.

**He can veto in-flow.** If he says *"stop correcting that"*, the rule moves to Tier 3 permanently and goes in the Ignored section of [[2_Grammar_Ledger]]. This is the escape hatch that makes tiering safe when he isn't auditing it.

### 3. When is it fixed?

`got_right ≥ 3`, with four qualifications that stop false mastery:

| Requirement | Why |
|:--|:--|
| **3 consecutive**, not 3 total | right-wrong-right-wrong-right is not fixed |
| **Unprompted** | A correct use in the same response as the correction is short-term memory. It doesn't count |
| **Across ≥ 2 sessions** | Spacing is what proves retention |
| **≥ 2 different contexts** | Three correct uses of `mit meinem Bruder` is one memorised phrase, not a rule |

All four met → status 🟢, drops out of [[5_Review_Queue]], moves to the **watch list**. Resurfaced once about 5 sessions later to confirm.

**Relapse:** a 🟢 rule that breaks again returns to active immediately. The counter resumes rather than resetting — relapse is information. **Two relapses promotes it to [[4_Golden_Rules]] regardless of hit count**, because a rule that keeps coming undone is exactly what a golden rule is for.

---

## Rules for maintaining the ledgers

- **The grammar ledger is rule-centric, not instance-centric.** Never add a row for a mistake — find the rule it violates and increment that row's counter. Only add a row when no existing rule covers it. This keeps the table ~30 rows and readable forever.
- **Raw instances go to the session log**, not the ledger. Nothing is lost.
- **Promotion is mechanical**: 3 hits on one rule → write it into `4_Golden_Rules.md`. No judgment call.
- **Every noun is stored with article and plural**: `das Fenster, die Fenster`. Never bare.
- **A word looked up is a word not known.** Single-word lookups get logged with `Times Missed: 1`.
- **Correct ≠ intended.** A sentence can be flawless German and still say the wrong thing. Flag intent mismatches separately from errors.

## Status legend for vocab

| Status | Meaning |
|:--|:--|
| 🔴 new | Just logged, never produced correctly |
| 🟡 learning | Produced correctly at least once, still missed recently |
| 🟢 solid | 3 correct productions, no miss in the last 10 sessions |
