# Noun declension (Substantivbøyning)

Norwegian has three genders: **masculine** (en), **feminine** (ei), and **neuter** (et).
Gender determines the indefinite article and the definite suffix added to the noun.

## Notation

### Masculine nouns (Maskulinum)
```
<maskulin_bøyning> ::= <ubestemt_sg> | <bestemt_sg> | <ubestemt_pl> | <bestemt_pl>

<ubestemt_sg> ::= "en" <stamme>
<bestemt_sg>  ::= <stamme> "en"
<ubestemt_pl> ::= <stamme> "er"
<bestemt_pl>  ::= <stamme> "ene"

<stamme> ::= "bil" | "stol" | "hund" | "lærer" | ...
```

### Feminine nouns (Femininum)
```
<feminin_bøyning> ::= <ubestemt_sg> | <bestemt_sg> | <ubestemt_pl> | <bestemt_pl>

<ubestemt_sg> ::= "ei" <stamme>
<bestemt_sg>  ::= <stamme> "a"
<ubestemt_pl> ::= <stamme> "er"
<bestemt_pl>  ::= <stamme> "ene"

<stamme> ::= "jente" | "bok" | "avis" | "dør" | ...
```

Note: in Bokmål, feminine nouns may also use the masculine definite suffix (-en instead of -a).
Both "jenta" and "jenten" are acceptable. The -a form is more common in spoken Norwegian.

### Neuter nouns (Nøytrum)
```
<nøytrum_bøyning> ::= <ubestemt_sg> | <bestemt_sg> | <ubestemt_pl> | <bestemt_pl>

<ubestemt_sg> ::= "et" <stamme>
<bestemt_sg>  ::= <stamme> "et"
<ubestemt_pl> ::= <stamme> | <stamme> "er"
<bestemt_pl>  ::= <stamme> "ene"

<stamme> ::= "hus" | "barn" | "bord" | "vindu" | ...
```

Note: monosyllabic neuter nouns take no suffix in the indefinite plural (hus→hus, barn→barn).
Polysyllabic neuter nouns typically add -er (vindu→vinduer, hotell→hoteller).

## Examples

### Masculine
| Ubestemt | Bestemt | Ubestemt flertall | Bestemt flertall | Engelsk |
|----------|---------|-------------------|------------------|---------|
| en bil   | bilen   | biler             | bilene           | car     |
| en stol  | stolen  | stoler            | stolene          | chair   |
| en hund  | hunden  | hunder            | hundene          | dog     |
| en lærer | læreren | lærere            | lærerne          | teacher |

### Feminine
| Ubestemt  | Bestemt | Ubestemt flertall | Bestemt flertall | Engelsk   |
|-----------|---------|-------------------|------------------|-----------|
| ei jente  | jenta   | jenter            | jentene          | girl      |
| ei bok    | boka    | bøker             | bøkene           | book      |
| ei avis   | avisa   | aviser            | avisene          | newspaper |
| ei dør    | døra    | dører             | dørene           | door      |

### Neuter (monosyllabic — no plural suffix)
| Ubestemt | Bestemt | Ubestemt flertall | Bestemt flertall | Engelsk |
|----------|---------|-------------------|------------------|---------|
| et hus   | huset   | hus               | husene           | house   |
| et barn  | barnet  | barn              | barna            | child   |
| et bord  | bordet  | bord              | bordene          | table   |

### Neuter (polysyllabic — adds -er in plural)
| Ubestemt    | Bestemt      | Ubestemt flertall | Bestemt flertall | Engelsk |
|-------------|--------------|-------------------|------------------|---------|
| et vindu    | vinduet      | vinduer           | vinduene         | window  |
| et hotell   | hotellet     | hoteller          | hotellene        | hotel   |
| et nummer   | nummeret     | numre             | numrene          | number  |
