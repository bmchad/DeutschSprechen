---
tags: [system, techniques]
updated: 2026-09-26
---

# Teaching Techniques

**The ratchet.** Without this file, every invented device evaporates at the end of the session and the next one starts from the same baseline. Anything that works gets written here so it accumulates.

Read at session start alongside [[5_Review_Queue]].

## The rule for using these

**Only when the device beats plain explanation for that specific error.** Never to look creative. An unnecessary device is padding, and padding costs Bernardo attention he needs for German.

**Woven in, never bolted on.** The technique goes inside the error block where it belongs. He sees one continuous analysis, never a "standard part" followed by a "creative part".

## Lifecycle

```
invent → name it → flag as experiment (once, one line)
       → he says keep or drop
       → keepers land here and persist
```

---

## ✅ In use

### Repair turn
**Invented:** 2026-09-21, mid-conversation. Not in any spec — the origin case for this whole file.

Instead of correcting, show the error located but not fixed — `Ich bin mit [meinen] Bruder gegangen` — give a hint naming the rule family but not the answer, and stop. He repairs it himself.

**Why it works:** retrieval beats reading. Trying and failing, then seeing the answer, sticks far harder than being told.

**Limits:** rules only, never vocabulary (he can't re-derive a word he never learned) · only if the first teaching was **prominent**, not one block buried among twenty · one per message · practice German only, never on a request or bug report · if he ignores it, let it go.

**Status:** fired once, he couldn't answer. Diagnosis was that the teaching hadn't been prominent enough, which is where the "prominent teaching" condition came from. Needs a fair second trial.

**Second trial, 2026-09-26 — it worked.** Fired during a warm-up on verb-final after `weil` (*weil ich möchte dort arbeiten*), a rule taught prominently in Session 2's pattern summary. The hint named only the rule family. Repaired correctly on the first retry: *weil ich dort arbeiten möchte*. Keep it.

**Third trial, 2026-09-30 — worked again.** Fired on a greeting (*damit [hast du] von Opus 5 zu Opus 5.5 (changed)?*). The hint named only the connector sorter row (`damit` = row 2). Repaired first try: *damit du … (changed) hast*. He moved the verb, kept his honest gap, and changed nothing else — exactly the scope asked for. **Two successes in a row since the "prominent teaching" condition was added.** Pairing it with the connector sorter as the hint looks strong: the sorter gives him the *question* to ask, and the repair makes him ask it.

---

### Free gender rule
**Invented:** 2026-09-21, explaining `die Korrekturrunde`.

When a noun's gender is predictable from its shape, hand him **the rule**, not just the word.

- **Compounds take the gender of the last element** — `die Runde` → `die Korrekturrunde`; `der Schutz` → `der Datenschutz`
- `-keit`, `-heit`, `-ung`, `-ion`, `-ität`, `-ee`, `-enz` → **feminine**
- Unassimilated loanwords default **masculine** — `der Skill`, `der Computer`

**Why it works:** gender is a stored field, not a drill target, so anything that removes a whole class of gender errors for free is pure profit.

**Status:** landed well. He guessed `die` for *Korrekturrunde* correctly and the rule explained why.

---

### Simplification route
**Invented:** 2026-09-21, on `wäre` and `korrigiert hättest`.

When the fully correct sentence needs B1 grammar, show it — then show an **A2 version that says the same thing**, usually by splitting one complex sentence into two simple ones.

**Why it works:** he shouldn't be handed Konjunktiv II as "the fix" at A2, but he also shouldn't be left thinking his idea was unsayable.

**Status:** used several times, no friction.

---

## 🧪 On trial

### Minimal pair
Two forms differing in exactly one feature, side by side, no prose between them:

> `in **die** Küche` — into the kitchen (motion)
> `in **der** Küche` — in the kitchen (position)

**Hypothesis:** for Wechselpräpositionen and case contrasts, seeing the single difference beats reading a paragraph about it.

**First used 2026-09-26**, flagged as an experiment: *Das Essen ist **fertig*** / *das **fertige** Essen* (no ending after `sein`), then *KI **kann** gut kopieren* / *KI **ist** gut **zu** kopieren* — the second pair shows a meaning flip ("good at copying" vs "easy to copy"), which is where the device is strongest. No verdict from Bernardo yet.

### Connector sorter
**Invented:** 2026-09-26, when `da` did three different jobs in one text and both word-order rules fired on the wrong connectors.

One table, one question: *where does the verb go?*

| Row | Connectors | The verb |
|:--|:--|:--|
| 0 · glue | `und` · `aber` · `oder` · `denn` · `sondern` | nothing changes |
| 1 · adverbs | `deshalb` · `darum` · `also` · `dann` · `da` = there | comes **next** |
| 2 · conjunctions | `weil` · `dass` · `wenn` · `ob` · `da` = since | goes **last** |

**Hypothesis:** the V2 and verb-final rules are both known now. What fails is *sorting* the connector into the right row, so teaching the sort beats re-teaching either rule. `da` is the showcase because it lives in two rows — and Portuguese *daí* adds a third, false meaning.

**Status:** flagged as an experiment. No verdict yet.

## 🧪 Proposed, not yet tried

### Reverse test
Give him **correct German** and ask what it means.

**Hypothesis:** the system currently only ever tests production. Comprehension is a separate skill and completely unmeasured — he may be far stronger there, which would be worth knowing.

### Forewarning
Before he writes something long, name the one rule most likely to bite him.

**Hypothesis:** if forewarning helps, it's extremely cheap. If it doesn't, that's informative too — it would mean his errors are automatic rather than attention-driven, which changes how they should be drilled.

**Evidence, 2026-09-26:** the verb-final error came unprompted and was fixed at once when a hint drew attention to it. The rule is known but not automatic — so attention is the bottleneck, which is exactly what forewarning targets. Still untested.

---

## ❌ Tried and dropped

*(nothing yet)*

**Repair turn, trial 4 (2026-09-30) — success.** V2 after a `wenn` clause, hint = "the whole wenn part is one block in position 1". Fixed first try. Three in a row.

**Reverse test — first natural data (2026-09-30).** Asked him *Merkst du einen Unterschied?* without translating; he glossed *merken* = notice and *Unterschied* = difference correctly. Comprehension is running ahead of production — worth testing deliberately.
