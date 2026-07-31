# Custom Kurrentschrift

Guidelines for writing my custom handscript. Unless otherwise specified, stick to the normal kurrent handscript guidelines.

Constraints:
- All modifications should be able to orthographically reconstruct the original english word.
    - This does not apply to whole common-word replacements (e.g. and -> ⁊); those may be arbitrary signs learned by memory, same as historical shorthand grammalogues.

## Morphemes
- 'th' splits by voicing, following the modern Icelandic convention (Old English used þ and ð fairly interchangeably, but Icelandic today keeps them phonemically distinct the same way):
    - voiceless /θ/ is replaced with þ (thorn). ex: think -> þink, three -> þrë (ee digraph collapses per Digraph Vowels below), math -> maþ, thin -> þin
    - voiced /ð/ is replaced with ð (eth). ex: this -> ðis, father -> faðꝛ, though -> ðŏȝ (ou digraph collapses too, same as gh below)
- 'gh' (the historical /x/ sound) is replaced with yogh (ȝ), except word-initially. ex: night -> niȝt, though -> ðŏȝ, right -> riȝt, daughter -> dăȝtꝛ (au digraph collapses per Digraph Vowels below, same as sauce -> săç), burgh -> burȝ
    - word-initial "gh" (ghost, ghastly, aghast, gherkin, ghetto) is a separate, unrelated origin — a silent h inserted after g by early printers under Flemish/Dutch spelling influence, representing a plain /g/ sound, not the old fricative. It stays as gh. ex: ghost -> ghost, aghast -> aghast
- silent ending e: no single mark — what the -e does in English varies, so it's split by function:
    1. marking a long/tense preceding vowel (magic-e: case, ride, hope, make, note): an underbar under that vowel, and the e is dropped. Kurrent already puts a breve-like line over u to distinguish it from n, so a mark riding above the vowel (a macron) would collide with that on words like dune; going below sidesteps it regardless of which vowel it's on. ex: case -> ca̲s, ride -> ri̲d, hope -> ho̲p, make -> ma̲k, note -> no̲t, time -> ti̲m, dune -> du̲n. It sits on a vowel, which keeps it distinct from the consonant-doubling underline in Morphemes below (that one only ever rides a consonant).
    2. softening a preceding c or g (face, notice, cage, range): the soft consonant takes a mark and the e is dropped. c has no descender, so it takes a cedilla (ç); g has a descender a cedilla would collide with, so it takes a hook above instead (◌̉, combining hook above, no precomposed form). Same shape logic — cedilla if the letter has no descender, hook above if it does — carries to anything else that ends up soft this way. ex: face -> faç, notice -> notiç, cage -> cag̉, range -> rang̉
    3. propping up a word that would otherwise end in bare v or u (have, give, love, blue, true — English words don't end in v/u): the final v takes a cedilla (v̧), same shape logic as the soft-c cedilla in function 2 above. ex: have -> hav̧, give -> giv̧, love -> lov̧. For -ue words this coincides with the Digraph Vowels umlaut anyway: blue -> blü, true -> trü.
    4. voicing a final th (bath -> bathe, breath -> breathe, teeth -> teethe): nothing extra needed — the voicing split already writes voiced /ð/ as eth, and word-final eth vs thorn is itself the cue, so eth alone stands in for the dropped -e. ex: bath -> baþ vs bathe -> bað, teeth -> tëþ vs teethe -> tëð, breathe -> brêð
- consonant doubling that only marks a short preceding vowel (rather than a real doubled sound): drop the doubled letter and underline the remaining consonant. ex: hopping -> hop̲ŋ, dinner -> din̲ꝛ, latter -> lat̲ꝛ, written -> writ̲en
    - the mark rides on the consonant now, not the vowel, so it no longer competes with the line over u: supper -> sup̲ꝛ vs super -> supꝛ (plain u already carries its own inherent u/n line as part of the Kurrent letterform — no added mark needed). Being on a consonant also keeps it distinct from the long-vowel underbar of silent-e function 1, which only ever sits on a vowel.
    - doubled s skips the underline device entirely and just becomes ß (eszett, historically a ligature of long-s + s) — since English doubling only ever exists to mark a short preceding vowel and never a real geminate sound, ß already reconstructs unambiguously to "ss" on its own, no extra stroke needed. This sidesteps Kurrent's long-tailed s, which is long enough that a separate underline has nowhere convenient to sit anyway. ex: missing -> mißŋ, kiss -> kiß, glass -> glaß
        - German traditionally uses ß the other way round (after long vowels, with ss reserved for short ones) — worth knowing as the source, but not imported here; this reuses only the ligature shape, same as how thorn/eth/r-rotunda were repurposed without their full historical usage rules.

## Digraph Vowels
A two-letter vowel digraph is written as its first letter carrying a diacritic that stands for the second letter — the pair collapses to one glyph, and the dropped letter is reconstructed from the diacritic. The diacritic-to-second-letter mapping:
- second letter a -> circumflex/caret ( ◌̂ ). ex: boat -> bôt, bread -> brêd, aardvark -> ârdvark
- second letter e -> umlaut ( ◌̈ ). ex: see -> së, toe -> tö, blue -> blü, field -> fïld
- second letter i -> dot above ( ◌̇ ). ex: rain -> rȧn, boil -> bȯl, rein -> rėn
    - exception: on a u base, dot above collides with a bare i — once u's distinguishing line is dropped (per the u-as-first-vowel rule below), u+dot reads identically to i followed by the next consonant's minims (ruin vs rim). Use acute ( ◌́ ) instead. ex: ruin -> rún, suit -> sút, juice -> júç (soft c also takes the silent-e cedilla)
- second letter o -> ring above ( ◌̊ ). ex: moon -> mo̊n, book -> bo̊k
- second letter u -> breve above ( ◌̆ ). ex: soup -> sŏp, feud -> fĕd, sauce -> săç (sauce's final c is soft, so it also takes the silent-e cedilla)
- second letter y -> grave ( ◌̀ ). ex: day -> dà, joy -> jò, key -> kè
- Only a/e/i/o/u/y second letters are covered; a digraph is any of these following the first vowel.
- u is the only vowel with an inherent mark of its own (the u/n distinguishing line), so it's the only base letter with a possible collision: when u is the first vowel of a digraph, that line is dropped — the digraph diacritic alone is enough to mark it as a vowel, so keeping the line is unnecessary. ex: blue -> blü, not blü with an extra line underneath. (Exception: the ui digraph substitutes acute for dot rather than dropping anything, since dot itself is what collides — see above.)

## Letterforms
- 'w' is replaced with wynn (Ƿ/ƿ) in all places. ex: was -> ƿas, written -> ƿrit̲en (composes with the other rules as usual)
    - this collided with two existing Kurrent letterforms, so those had to be modified to stay distinct:
        - capital P (which wynn's capital form otherwise resembles) is now written like capital R minus the tail, so it's no longer confusable with capital wynn.
        - lowercase k had its curve start from the middle of the stroke instead of the top, since starting from the top made it read too much like lowercase wynn.

## Prefixes
- 'con-' is replaced with ꝯ (the medieval scribal abbreviation mark for con-/contra-, one of the oldest abbreviation signs, going back to Tironian notes). ex: contract -> ꝯtract, consider -> ꝯsider, control -> ꝯtrol
    - 'com-' uses the same mark with a stroke across the stem (ꝯ̶ — no precomposed Unicode form, just the con-mark plus a combining stroke overlay), matching the same family of stroke-modified letters as ꝑ (per-) and ꝓ (pro-): the stem itself is what changes to signal the nasal shift from n to m, since com- is just the labial-assimilated spelling of the same underlying prefix before b/p/m. ex: combine -> ꝯ̶bi̲n, complete -> ꝯ̶ple̲t, common -> ꝯ̶mon (combine/complete also take the silent-e magic-e underbar, per Morphemes above)

## Suffixes
- 'ing' suffix is replaced by ŋ. ex: running -> run̲ŋ (doubled n marks the short vowel per the Morphemes consonant-doubling rule, same as hopping -> hop̲ŋ)
- 'er' suffix is replaced by ꝛ. ex: meter -> metꝛ
- 'or' suffix is replaced by ꝝ (r rotunda with a stroke across the stem — precomposed Unicode, U+A75D). Historically this was the medieval sign for -rum/-orum/-arum, so it's a real r-rotunda-family mark rather than an invented one; using it for -or keeps the same "stroke = marked variant within the family" logic as con-/com- and per-/pro- in Prefixes, with plain ꝛ as the more common default (-er) and struck ꝝ as the less common one (-or). ex: motor -> motꝝ, doctor -> doctꝝ
- -ed suffix is just d. ex: printed -> printd
- '-tion' suffix is abbreviated to ꝷ (U+A777). ex: nation -> naꝷ
- other '-ion' suffixes are abbreviated to ꝸ (U+A778). ex: version -> versꝸ

## Common Words

Articles:
- the: ð (voiced th, per the eth/thorn split above)
- an: ã

Conjunctions:
- and: Tironian et ⁊
- or: ꝝ 

Prepositions:
- in: ĩ
- on: õ
- at: @ (commercial at-sign — historically a scribal ligature of 'ad', a flourished a merging with the ascender of d; same logic as reusing Tironian et for and)
- to: t˞ (t with a flourish — no real Unicode glyph for a decorative tail stroke, so approximated with U+02DE MODIFIER LETTER RHOTIC HOOK; in the actual handscript it's just a flourish off the tail of the t, not a phonetic hook)
- with: ƿþ (wynn + thorn — a whole-word abbreviation to the initial and final consonant, not the regular letter-substitution spelling ƿið)

Pronouns:
- it: ṫ (t with dot above, U+1E6B — the surviving consonant carries the digraph second-letter-i mark for the dropped vowel, same device as no: n̊ but for a leading vowel instead of a trailing one)

Verb "to be":
- am: m
- are: ꝛ (rotunda r)
- is: ṡ (s with dot above, U+1E61 — same device as it: ṫ, the surviving consonant carries the digraph second-letter-i mark for the dropped leading i)

Negation:
- not, 'nt: ꞥ (n with oblique stroke, U+A7A4/U+A7A5 — the stroke reads as the mundane negation slash, same logic as the struck marks in Prefixes/Suffixes). Falls back to ņ (n with cedilla) if the oblique stroke doesn't survive at small scale — fittingly, this mirrors real history: Latvian orthography used this exact letter until 1921, when it was replaced by cedilla-n for legibility.
- no: n̊ (ring above marks the dropped o, same digraph-o mark as moon/book in Digraph Vowels — but riding the n instead of a vowel, since no puts the consonant first, reversed from an/in/on where the vowel leads and the mark stands for a trailing n)

## TODO
- three-vowel sequences (beauty, queue, aqueous) aren't covered by the two-letter digraph rule — needs a convention.
