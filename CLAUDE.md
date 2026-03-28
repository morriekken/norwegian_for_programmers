# Norwegian for Programmers — CLAUDE.md

## Project Purpose
A reference for Norwegian grammar (Bokmål) using BNF/EBNF-like notation, aimed at programmers learning the language. Content was generated with ChatGPT assistance and is **not verified by a Norwegian language teacher**.

---

## Repository Structure
```
verbs/              # Verb conjugation rules and vocabulary lists
adjectives/         # Adjective declension rules and vocabulary lists
substantives/       # Noun declension tables (currently neuter only)
sentence_structure/ # BNF rules for sentence construction
expressions/        # Idiomatic expressions and phrases
```

---

## Conventions

### BNF Notation (in rule files)
- Non-terminals: `<rule_name>`
- Terminals: `"literal"`
- Production: `::=`
- Alternatives: `|`
- Concatenation by juxtaposition: `<a> "x"` means a followed by "x"
- Terminal strings should be written as single units: `"ere"` not `"e" "r" "e"`
- All BNF is wrapped in a fenced code block under a `## Notation` heading
- Examples follow under a `## Examples` heading

### Verb Tables (in list files)
Columns: `Infinitiv | Presens | Preteritum | Pres. perfektum | Engelsk`

- **Pres. perfektum** = "har" + perfect participle (e.g., "har snakket")
- "har" is the auxiliary — it is NOT part of the participle form itself

### Adjective Tables
Columns: `Norsk (m/f) | Norsk (n) | Norsk (pl) | Engelsk`

- Some adjectives are **invariant** (same form in all columns), e.g., "blå", "dårlig", "viktig"
- Definite/plural adjective form typically ends in `-e`; neuter indefinite adds `-t`

### Substantive Tables
Columns: `Ubestemt | Bestemt | Ubestemt flertall | Bestemt flertall | Engelsk`

---

## Norwegian Grammar Notes
- This repository covers **Bokmål** only, not Nynorsk
- Verb groups: **v1** (preteritum -et, participle -et) and **v2** (preteritum -te, participle -t)
- Adjective definite form = stem + "e" (same for all genders in definite/plural)
- Perfect participle = stem + suffix only; "har"/"hadde" are separate auxiliary verbs
- `<predikativ>` (predicate complement) can be a noun phrase, adjective, or prepositional phrase

---

## Quality Guidelines
When adding or editing content:
1. Verify Norwegian forms against [ordbokene.no](https://ordbokene.no/) or the Norwegian Grammar Tutor linked in readme.md
2. Check for invariant adjectives before adding `-e` plural forms
3. Keep BNF rule names in Norwegian (e.g., `<stamme>`, `<verbal>`, `<setning>`)
4. Do not include auxiliary verbs inside participle BNF rules

---

## Branch Strategy
- Feature work: `feature/<description>`
- All changes should be committed with clear messages describing the grammar or notation aspect changed
