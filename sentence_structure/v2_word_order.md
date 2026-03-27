# V2 word order (V2-regelen)

Norwegian is a **verb-second (V2) language**: in any main clause, the finite verb always
occupies the second position, regardless of what element comes first.

## Notation
```
<hoved_setning> ::= <subjekt_først> | <forfelt_først>

<subjekt_først> ::= <subjekt> <verbal> <midtfelt> <sluttfelt>

<forfelt_først>  ::= <forfelt> <verbal> <subjekt> <midtfelt> <sluttfelt>

<forfelt>  ::= <adverbial> | <objekt> | <predikativ> | <bi_setning>

<midtfelt> ::= <negasjon> <adverbial> | <adverbial> | <negasjon> | ε

<sluttfelt> ::= <objekt> | <adverbial> | <predikativ> | ε

<negasjon>  ::= "ikke"

<adverbial> ::= "i dag" | "alltid" | "her" | "der" | "nå" | ...

<bi_setning> ::= <subjunksjon> <subjekt> "ikke" <verbal> <sluttfelt>

<subjunksjon> ::= "fordi" | "når" | "hvis" | "at" | "selv om" | ...
```

## Key rule
When `<forfelt>` is anything other than the subject, the subject moves to after the verb
(subject-verb inversion). This is called **inversjon**.

## Examples

### Normal order (subject first, no inversion)
| Position 1     | Position 2 (verbal) | Rest                  |
|---------------|---------------------|-----------------------|
| Jeg           | spiser              | fisk i dag            |
| *I*           | *eat*               | *fish today*          |
| Vi            | bor                 | i Oslo                |
| *We*          | *live*              | *in Oslo*             |

### Inverted order (adverbial or object fronted)
| Position 1 (forfelt) | Position 2 (verbal) | Subjekt | Rest        |
|----------------------|---------------------|---------|-------------|
| I dag                | spiser              | jeg     | fisk        |
| *Today*              | *eat*               | *I*     | *fish*      |
| Fisk                 | spiser              | jeg     | i dag       |
| *Fish*               | *eat*               | *I*     | *today*     |
| Her                  | bor                 | vi      |             |
| *Here*               | *live*              | *we*    |             |

### Subordinate clause (no inversion — V2 does NOT apply)
| Subjunksjon | Subjekt | (ikke) | Verbal  | Rest    |
|-------------|---------|--------|---------|---------|
| fordi       | jeg     |        | spiser  | fisk    |
| *because*   | *I*     |        | *eat*   | *fish*  |
| fordi       | jeg     | ikke   | spiser  | fisk    |
| *because*   | *I*     | *not*  | *eat*   | *fish*  |

Note: V2 inversion applies **only in main clauses**. In subordinate clauses the verb stays after the subject.
