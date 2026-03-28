# Questions (Spørsmål)

Norwegian has two question types: **yes/no questions** (ja/nei-spørsmål) and
**wh-questions** (hv-spørsmål). Both use subject-verb inversion.

## Notation
```
<spørsmål> ::= <ja_nei_spørsmål> | <hv_spørsmål>

<ja_nei_spørsmål> ::= <verbal> <subjekt> <resten> "?"

<hv_spørsmål> ::= <spørreord> <verbal> <subjekt> <resten> "?"
                | <spørreord> <verbal> <resten> "?"

<spørreord> ::= "hva" | "hvem" | "hvor" | "når" | "hvorfor" | "hvordan"
              | "hvilken" | "hvilket" | "hvilke" | "hvor mye" | "hvor mange"

<resten> ::= <objekt> | <adverbial> | <predikativ> | ε
```

Note: the second alternative for `<hv_spørsmål>` covers cases where the question word
itself is the subject — e.g. "Hvem snakker?" (Who is speaking?) — so no separate
`<subjekt>` appears after the verb.

## Examples

### Yes/no questions (verb comes first)
| Verbal | Subjekt | Resten          | Engelsk                  |
|--------|---------|-----------------|--------------------------|
| Spiser | du      | fisk?           | Do you eat fish?         |
| Er     | hun     | hjemme?         | Is she home?             |
| Kan    | de      | hjelpe meg?     | Can they help me?        |
| Har    | dere    | vært i Norge?   | Have you been to Norway? |

### Wh-questions (question word first, then inversion)
| Spørreord  | Verbal  | Subjekt | Resten        | Engelsk               |
|------------|---------|---------|---------------|-----------------------|
| Hva        | spiser  | du?     |               | What do you eat?      |
| Hvem       | er      |         | det?          | Who is that?          |
| Hvor       | bor     | de?     |               | Where do they live?   |
| Når        | kommer  | toget?  |               | When does the train come? |
| Hvorfor    | lærer   | du      | norsk?        | Why do you learn Norwegian? |
| Hvordan    | har     | du      | det?          | How are you?          |
| Hvilken    | bok     | leser   | du?           | Which book are you reading? |
| Hvor mye   | koster  | det?    |               | How much does it cost? |

## Question words reference
| Norsk       | Engelsk              |
|-------------|----------------------|
| hva         | what                 |
| hvem        | who / whom           |
| hvor        | where                |
| når         | when                 |
| hvorfor     | why                  |
| hvordan     | how                  |
| hvilken     | which (en-noun)      |
| hvilket     | which (et-noun)      |
| hvilke      | which (plural)       |
| hvor mye    | how much             |
| hvor mange  | how many             |
