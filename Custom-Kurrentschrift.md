# Custom Kurrentschrift

Guidelines for writing my custom handscript. Unless otherwise specified, stick to the normal kurrent handscript guidelines.

Rationale, design history and edge-case notes live in [JUSTIFICATION.md](JUSTIFICATION.md), referenced below as §n.n.

Constraints:
- All modifications should be able to orthographically reconstruct the original english word.
    - This does not apply to whole common-word replacements (e.g. and -> ⁊); those may be arbitrary signs learned by memory, same as historical shorthand grammalogues.

## Morphemes
- 'th' splits by voicing (§1.1):
    - voiceless /θ/ -> þ (thorn). ex: think -> þink, three -> þrë, math -> maþ, thin -> þin
    - voiced /ð/ -> ð (eth). ex: this -> ðis, father -> faðꝛ, though -> ðŏȝ
- 'gh' (the historical /x/ sound) -> yogh (ȝ), except word-initially. ex: night -> niȝt, though -> ðŏȝ, right -> riȝt, daughter -> dăȝtꝛ, burgh -> burȝ
    - word-initial "gh" stays as gh (§1.2). ex: ghost -> ghost, aghast -> aghast
- silent ending e: no single mark — split by function (§1.3):
    1. marking a long/tense preceding vowel (magic-e): an underbar under that vowel, e dropped. ex: case -> ca̲s, ride -> ri̲d, hope -> ho̲p, make -> ma̲k, note -> no̲t, time -> ti̲m, dune -> du̲n
    2. softening a preceding c or g: c takes a cedilla (ç), g takes a hook above (◌̉), e dropped. ex: face -> faç, notice -> notiç, cage -> cag̉, range -> rang̉
    3. propping up a word that would otherwise end in bare v or u: final v takes a cedilla (v̧). ex: have -> hav̧, give -> giv̧, love -> lov̧. -ue words fall out of the digraph umlaut instead: blue -> blü, true -> trü
    4. voicing a final th: nothing extra — the eth/thorn split already carries it. ex: bath -> baþ vs bathe -> bað, teeth -> tëþ vs teethe -> tëð, breathe -> brêð
- doubled consonants: drop the doubled letter and put a right hook — an ogonek (◌̨) — under the preceding vowel. Precomposed: ą ę į ǫ ų (y̨ must be composed). ex: letter -> lętꝛ, hopping -> hǫpŋ, dinner -> dįnꝛ, latter -> lątꝛ, written -> ƿrįten
    - the hook means exactly one thing: a doubled letter follows (§1.4.1). Flat bar = long vowel, right hook = doubled letter.
    - marks above and below stack freely, on different letters or the same one. ex: balloon -> bąlo̊n, roommate -> rǫ̊ma̲t, coolly -> cǫ̊ly, bookkeeper -> bǫ̊këpꝛ
    - u keeps its inherent line above and takes the hook below as well. ex: supper -> sųpꝛ vs super -> supꝛ
    - the source of the doubling is never asked about — assimilated prefixes and morpheme seams are written like any other double. ex: apply -> ąply, occur -> ǫcur, illegal -> įlegal, accord -> ącord, correct -> cǫrect, suffer -> sųfꝛ, unnatural -> ųnatural, misspell -> mißpęl
    - no hook where another glyph already swallowed the double (§1.4.8). ex: commit -> ꝯ̶mit, common -> ꝯ̶mon, connect -> ꝯnect, misspell -> mißpęl (hooks only its ll)

## Digraph Vowels
A two-letter vowel digraph is written as its first letter carrying a diacritic that stands for the second letter — the pair collapses to one glyph, and the dropped letter is reconstructed from the diacritic. The diacritic-to-second-letter mapping:
- second letter a -> circumflex/caret ( ◌̂ ). ex: boat -> bôt, bread -> brêd, aardvark -> ârdvark
- second letter e -> umlaut ( ◌̈ ). ex: see -> së, toe -> tö, blue -> blü, field -> fïld
- second letter i -> dot above ( ◌̇ ). ex: rain -> rȧn, boil -> bȯl, rein -> rėn
- second letter o -> ring above ( ◌̊ ). ex: moon -> mo̊n, book -> bo̊k
- second letter u -> breve above ( ◌̆ ). ex: soup -> sŏp, feud -> fĕd, sauce -> săç (sauce's final c is soft, so it also takes the silent-e cedilla)
- second letter y -> grave ( ◌̀ ). ex: day -> dà, joy -> jò, key -> kè
- Only a/e/i/o/u/y second letters are covered; a digraph is any of these following the first vowel — except the i/u pair, below.
- the i/u pair doesn't collapse in either direction (§2.1): ui and iu are both written out in full. ex: suit -> suit, fruit -> fruit, juice -> juiç, build -> build, guide -> gui̲d, medium -> medium, radius -> radius, triumph -> triumph
- when u is the first vowel of a digraph, its u/n line is dropped (§2.3). ex: blue -> blü, with no extra line underneath. Covers ue/ua/uo/uy.

## Letterforms
- 'qu' is written as q with a breve above (q̆) — the same "second letter u" mark as the Digraph Vowels table, riding a consonant (§3.1). ex: queen -> q̆ën, quick -> q̆ick, quit -> q̆it, require -> req̆i̲r, equal -> eq̆al
    - the breve only stands for the u immediately after q; any following vowel is written as normal. ex: quote -> q̆o̲t, quiet -> q̆ït
- 'ss' is written as ß (eszett). A letterform substitution in its own right, not the consonant-doubling rule — the vowel takes no hook (§3.2). ex: missing -> mißŋ, kiss -> kiß, glass -> glaß
- 'w' is replaced with wynn (Ƿ/ƿ) in all places. ex: was -> ƿas, written -> ƿrįten
    - two Kurrent letterforms were modified to stay distinct from it (§3.3): capital P is now capital R minus the tail; lowercase k starts its curve from the middle of the stroke instead of the top.

## Prefixes
- 'con-' -> ꝯ (§4.1). ex: contract -> ꝯtract, consider -> ꝯsider, control -> ꝯtrol, connect -> ꝯnect (the mark covers the final n, so a seam double disappears into it)
- 'com-' -> ꝯ̶, the same mark with a stroke across the stem (§4.2). ex: combine -> ꝯ̶bi̲n, complete -> ꝯ̶ple̲t, common -> ꝯ̶mon, commit -> ꝯ̶mit

## Suffixes
- 'ing' suffix -> ŋ. ex: running -> rųnŋ, hopping -> hǫpŋ
- 'er' suffix -> ꝛ. ex: meter -> metꝛ
- 'or' suffix -> ꝝ (r rotunda with a stroke across the stem, U+A75D) (§5.1). ex: motor -> motꝝ, doctor -> doctꝝ
- '-ed' suffix -> d. ex: printed -> printd
- '-tion' suffix -> ꝷ (U+A777). ex: nation -> naꝷ
- other '-ion' suffixes -> ꝸ (U+A778). ex: version -> versꝸ

## Common Words

Articles:
- the: ð
- an: ã

Conjunctions:
- and: Tironian et ⁊
- or: ꝝ

Prepositions:
- in: ĩ
- on: õ
- at: @ (§6.1)
- to: t˞ (t with a flourish; U+02DE stands in for it) (§6.2)
- with: ƿþ (§6.3)

Pronouns:
- it: ṫ (U+1E6B) (§6.4)

Verb "to be":
- am: m
- are: ꝛ (rotunda r)
- is: ṡ (U+1E61) (§6.4)

Negation:
- not, 'nt: ꞥ (U+A7A4/U+A7A5), falling back to ņ at small scale (§6.5)
- no: n̊ (§6.6)

## TODO
- three-vowel sequences (beauty, queue, aqueous) aren't covered by the two-letter digraph rule — needs a convention (§7.1).
- the doubling hook collides with the descender on y (syllable, gypsy) (§7.2).
