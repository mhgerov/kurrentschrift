# Custom Kurrentschrift

Guidelines for writing my custom handscript. Unless otherwise specified, stick to the normal kurrent handscript guidelines.

Constraints:
- All modifications should be able to orthographically reconstruct the original english word.
    - This does not apply to whole common-word replacements (e.g. and -> ⁊); those may be arbitrary signs learned by memory, same as historical shorthand grammalogues.

## Morphemes
- 'th' splits by voicing, following the modern Icelandic convention (Old English used þ and ð fairly interchangeably, but Icelandic today keeps them phonemically distinct the same way):
    - voiceless /θ/ is replaced with þ (thorn). ex: think -> þink, three -> þree, math -> maþ, thin -> þin
    - voiced /ð/ is replaced with ð (eth). ex: this -> ðis, father -> faðꝛ, though -> ðoȝ
- 'ing' suffix is replaced by ŋ. ex: running -> runŋ
- 'er' suffix is replaced by ꝛ. ex: meter -> metꝛ
- 'or' suffix is replaced by ꝝ (r rotunda with a stroke across the stem — precomposed Unicode, U+A75D). Historically this was the medieval sign for -rum/-orum/-arum, so it's a real r-rotunda-family mark rather than an invented one; using it for -or keeps the same "stroke = marked variant within the family" logic as con-/com- and per-/pro- below, with plain ꝛ as the more common default (-er) and struck ꝝ as the less common one (-or). ex: motor -> motꝝ, doctor -> doctꝝ
- -ed suffix is just d. ex: printed -> printd
- 'gh' (the historical /x/ sound) is replaced with yogh (ȝ), except word-initially. ex: night -> niȝt, though -> ðoȝ, right -> riȝt, daughter -> dauȝtꝛ, burgh -> burȝ
    - word-initial "gh" (ghost, ghastly, aghast, gherkin, ghetto) is a separate, unrelated origin — a silent h inserted after g by early printers under Flemish/Dutch spelling influence, representing a plain /g/ sound, not the old fricative. It stays as gh. ex: ghost -> ghost, aghast -> aghast
- silent ending e
    - a silent ending e that modifies the pronunciation of the proceding vowel just has an umlaut over the preceding vowel instead. ex: case -> cäs.
    - if it does not modify the preceding vowel, the ending consonant gets a cedilla. ex: fence -> fenç, throttle -> throttļ
    - c and g also take this same mark whenever they're directly followed by the silent e, regardless of whether the vowel further back is separately modified — they're the two letters with a real hard/soft alternation in English (c: /k/ vs /s/, g: /ɡ/ vs /dʒ/), so the mark can stack with the umlaut rule above rather than replace it. Which shape it takes depends on the letter, not the word: c has no descender, so it keeps the plain cedilla (ç); g has a descender that a cedilla collides with, so it takes a hook above instead (◌̉, combining hook above — no precomposed Unicode form for g, same situation as the com- stroke overlay below). ex: range -> räng̉ (umlaut + hook, stacked), face -> fäç (umlaut + cedilla, stacked), hinge -> hing̉ (hook alone, vowel unaffected)
        - same shape logic (cedilla for a letter with no descender, hook above for one with a descender) carries over to any other letter that ends up needing this mark.
- consonant doubling that only marks a short preceding vowel (rather than a real doubled sound): drop the doubled letter and mark the preceding vowel with a breve below (inverted breve, ˕) instead. ex: hopping -> ho̯pŋ, latter -> la̯tꝛ, dinner -> di̯nꝛ, written -> wri̯ten
    - placed below rather than above so it doesn't collide with the line already used over u to distinguish it from n. ex: supper -> su̯pꝛ vs super -> süpꝛ

## Letterforms
- 'w' is replaced with wynn (Ƿ/ƿ) in all places. ex: with -> ƿið, written -> ƿri̯ten (composes with the other rules as usual)
    - this collided with two existing Kurrent letterforms, so those had to be modified to stay distinct:
        - capital P (which wynn's capital form otherwise resembles) is now written like capital R minus the tail, so it's no longer confusable with capital wynn.
        - lowercase k had its curve start from the middle of the stroke instead of the top, since starting from the top made it read too much like lowercase wynn.

## Prefixes
- 'con-' is replaced with ꝯ (the medieval scribal abbreviation mark for con-/contra-, one of the oldest abbreviation signs, going back to Tironian notes). ex: contract -> ꝯtract, consider -> ꝯsider, control -> ꝯtrol
    - 'com-' uses the same mark with a stroke across the stem (ꝯ̶ — no precomposed Unicode form, just the con-mark plus a combining stroke overlay), matching the same family of stroke-modified letters as ꝑ (per-) and ꝓ (pro-): the stem itself is what changes to signal the nasal shift from n to m, since com- is just the labial-assimilated spelling of the same underlying prefix before b/p/m. ex: combine -> ꝯ̶bine, complete -> ꝯ̶plete, common -> ꝯ̶mon
    - cum- doesn't show up often enough in English to be worth its own treatment; if it comes up, fold it under the com- form.

## Common Words

Generally going with tildes representing 'n', circumflex representing 't'.

Articles:
- the: ð̈ (voiced th, per the eth/thorn split above)
- an: ã

Conjunctions:
- and: Tironian et ⁊
- or: o + rotunda r oꝛ

- in: ĩ
- on: õ
- at: â
- to: ô

Verb "to be":
- am: m
- are: ꝛ (rotunda r)
- is: s

Negation:
- not, 'nt: macron over the n (borrowed from the medieval Latin abbreviation n̄ for "non")
    - standalone "not": n̄. ex: not now -> n̄ now
    - as the "-n't" suffix: the n̄ sign is just appended to the full stem, no letters merged or dropped. ex: can't -> cann̄, don't -> don̄, isn't -> isn̄
