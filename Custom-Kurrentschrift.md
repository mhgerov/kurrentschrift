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
    1. marking a long/tense preceding vowel (magic-e: case, ride, hope, make, note): an underbar under that vowel, and the e is dropped. Kurrent already puts a breve-like line over u to distinguish it from n, so a mark riding above the vowel (a macron) would collide with that on words like dune; going below sidesteps it regardless of which vowel it's on. ex: case -> ca̲s, ride -> ri̲d, hope -> ho̲p, make -> ma̲k, note -> no̲t, time -> ti̲m, dune -> du̲n. The doubling hook in the rule below hangs in the same place, under the vowel — the two are told apart by shape rather than position: flat bar = long vowel, right hook = doubled letter follows. ex: ho̲p (hope) vs hǫpŋ (hopping) — note that bare hop takes no mark at all, since there's no doubled letter to reconstruct.
    2. softening a preceding c or g (face, notice, cage, range): the soft consonant takes a mark and the e is dropped. c has no descender, so it takes a cedilla (ç); g has a descender a cedilla would collide with, so it takes a hook above instead (◌̉, combining hook above, no precomposed form). Same shape logic — cedilla if the letter has no descender, hook above if it does — carries to anything else that ends up soft this way. ex: face -> faç, notice -> notiç, cage -> cag̉, range -> rang̉
        - the cedilla hooks left. That's what keeps it clear of the right-hooking ogonek in the consonant-doubling rule below, which also hangs beneath the baseline — see there for the direction contrast.
    3. propping up a word that would otherwise end in bare v or u (have, give, love, blue, true — English words don't end in v/u): the final v takes a cedilla (v̧), same shape logic as the soft-c cedilla in function 2 above. ex: have -> hav̧, give -> giv̧, love -> lov̧. For -ue words this coincides with the Digraph Vowels umlaut anyway: blue -> blü, true -> trü.
    4. voicing a final th (bath -> bathe, breath -> breathe, teeth -> teethe): nothing extra needed — the voicing split already writes voiced /ð/ as eth, and word-final eth vs thorn is itself the cue, so eth alone stands in for the dropped -e. ex: bath -> baþ vs bathe -> bað, teeth -> tëþ vs teethe -> tëð, breathe -> brêð
- doubled consonants: drop the doubled letter and put a right hook — an ogonek (◌̨) — under the preceding vowel. Precomposed forms exist for every vowel that needs one: ą ę į ǫ ų (y̨ has to be composed). ex: letter -> lętꝛ, hopping -> hǫpŋ, dinner -> dįnꝛ, latter -> lątꝛ, written -> ƿrįten
    - the hook means exactly one thing: a doubled letter follows. Not "this vowel is short" — that's the usual consequence, not the definition. Defining it orthographically rather than phonetically is what lets one rule cover every doubled consonant in English regardless of where it came from, and it keeps the reconstruction constraint mechanical: hook, therefore double the next letter, no judgment call about why the double was there.
    - it still rides the vowel rather than the consonant, because in the ordinary case the vowel is what the doubling is describing — nobody holds the p in hopping longer than the p in hoping. The doubled letter is a diacritic about the vowel in front of it, so putting the mark on the consonant kept it one letter away from what it referred to. Below the vowel is also where silent-e function 1 already writes its long mark, so the two contrast directly by shape: flat bar = long vowel, right hook = doubled letter. They aren't two ends of one axis — one is phonetic and one is orthographic — but the pairing is worth the mnemonic, since a hook does imply a short vowel nearly every time.
    - hanging below means it doesn't compete with the line over u, which rides above — so u keeps its inherent u/n line and takes the hook underneath as well: supper -> sųpꝛ vs super -> supꝛ
    - the hook opens to the right, and that's what keeps it apart from the cedilla of silent-e function 2, which hooks left. Direction does the work, not position: the two stay legible against each other in a fast hand even though both hang below the baseline. Polish (ą, ę) against Latvian (ģ, ķ, ļ, ņ) leans on exactly this contrast, so it's a tested distinction rather than an assumed one.
    - the ogonek is itself a medieval scribal mark — the nasal hook of Latin manuscripts, ę standing in for ae — so it belongs to the same borrowed-shape family as thorn, eth, wynn and the con-mark. As with ß in Letterforms below, only the shape is imported and not the historical usage: here it marks a following doubled letter, not nasality.
    - marks above and marks below stack freely, on different letters or on the same one: balloon -> bąlo̊n (ll hooks the a, oo collapses to a ring above the o), roommate -> rǫ̊ma̲t, coolly -> cǫ̊ly, bookkeeper -> bǫ̊këpꝛ (here the ring and the hook share one o — the digraph mark above says oo, the hook below says the next letter doubles). This is where defining the hook orthographically pays off: the vowel in these is long, so a mark that meant "short" would be lying, but one that means "a double follows" is simply true.
    - the source of the doubling is never asked about. Latin prefix assimilation (apply from ad-, occur from ob-, illegal from in-, suffer from sub-) and morpheme seams (unnatural from un + natural, misspell from mis + spell) are written the same as any other double: apply -> ąply, occur -> ǫcur, illegal -> įlegal, accord -> ącord, correct -> cǫrect, suffer -> sųfꝛ, unnatural -> ųnatural, misspell -> mißpęl
        - no hook is needed where another glyph has already swallowed the double. The con-/com- marks stand for the whole prefix including its final consonant, so a seam double disappears into them: commit -> ꝯ̶mit, common -> ꝯ̶mon, connect -> ꝯnect (correct is not one of these — there's no cor- mark — so it keeps its hook). ß does the same for ss, which is why misspell above hooks only its ll. The hook is there to reconstruct a double that would otherwise be lost; when the double is already recoverable, it has no work to do.

## Digraph Vowels
A two-letter vowel digraph is written as its first letter carrying a diacritic that stands for the second letter — the pair collapses to one glyph, and the dropped letter is reconstructed from the diacritic. The diacritic-to-second-letter mapping:
- second letter a -> circumflex/caret ( ◌̂ ). ex: boat -> bôt, bread -> brêd, aardvark -> ârdvark
- second letter e -> umlaut ( ◌̈ ). ex: see -> së, toe -> tö, blue -> blü, field -> fïld
- second letter i -> dot above ( ◌̇ ). ex: rain -> rȧn, boil -> bȯl, rein -> rėn
- second letter o -> ring above ( ◌̊ ). ex: moon -> mo̊n, book -> bo̊k
- second letter u -> breve above ( ◌̆ ). ex: soup -> sŏp, feud -> fĕd, sauce -> săç (sauce's final c is soft, so it also takes the silent-e cedilla)
- second letter y -> grave ( ◌̀ ). ex: day -> dà, joy -> jò, key -> kè
- Only a/e/i/o/u/y second letters are covered; a digraph is any of these following the first vowel — except the i/u pair, see below.
- the i/u pair doesn't collapse in either direction: ui and iu are both written out in full. ex: suit -> suit, fruit -> fruit, juice -> juiç (the soft-c cedilla still applies), build -> build, guide -> gui̲d (the magic-e underbar still applies), medium -> medium, radius -> radius, triumph -> triumph
    - i and u each identify themselves by a mark the other one owns — u by its line above, i by a dot on a single minim — so a mark standing for one, riding on the other, spells that letter instead of modifying it. ui fails because a lineless u (per the rule below) plus a dot reads as an i followed by the next consonant's minims: ruin vs rim. iu fails the same way in reverse, since the breve standing for a second-letter u *is* the u line — i+breve is one minim under a line, which is what a plain u already looks like, so medium would read medum. Neither direction survives a fast hand, and reconstructing the original word is the whole point of the table.
    - the cost is small. ui and iu are the two rarest vowel pairs in English, and iu is never a real digraph at all — it's always a syllable break (me-di-um, ra-di-us, tri-umph), so no single vowel sound is being spelled out longhand. ui does hold genuine digraphs (fruit, suit, juice) alongside the silent-u-after-g class (guide, guilt, build), but the pair is rare enough that writing it in full is cheaper than minting another diacritic to dodge the collision.
- u is the only vowel with an inherent mark of its own (the u/n distinguishing line), so it's the only base letter with a possible collision: when u is the first vowel of a digraph, that line is dropped — the digraph diacritic alone is enough to mark it as a vowel, so keeping the line is unnecessary. ex: blue -> blü, not blü with an extra line underneath. This covers ue/ua/uo/uy; ui is excluded per the bullet above, so a lineless u never meets a dot.

## Letterforms
- 'qu' is written as q with a breve above (q̆). English q is followed by u essentially without exception, so the u is predictable, but it isn't dropped silently — the breve is the same "second letter u" mark as the Digraph Vowels table (soup -> sŏp, feud -> fĕd), just riding a consonant instead of a vowel, the same way no -> n̊ rides the n. ex: queen -> q̆ën (the remaining ee still collapses per Digraph Vowels), quick -> q̆ick, quit -> q̆it, require -> req̆i̲r, equal -> eq̆al
    - the breve only ever stands for the u immediately after q, so any following vowel is written as normal (collapsing with its own neighbour if it forms a digraph in its own right): quote -> q̆o̲t, quiet -> q̆ït
- 'ss' is written as ß (eszett, historically a ligature of long-s + s). This is a letterform substitution in its own right, not an instance of the consonant-doubling rule in Morphemes: since English doubling never represents a real geminate sound, ß reconstructs unambiguously to "ss" on its own, so the vowel takes no hook. It also sidesteps Kurrent's long-tailed s, which leaves awkwardly little room for anything else nearby. ex: missing -> mißŋ, kiss -> kiß, glass -> glaß
    - German traditionally uses ß the other way round (after long vowels, with ss reserved for short ones) — worth knowing as the source, but not imported here; this reuses only the ligature shape, same as how thorn/eth/r-rotunda were repurposed without their full historical usage rules.
- 'w' is replaced with wynn (Ƿ/ƿ) in all places. ex: was -> ƿas, written -> ƿrįten (composes with the other rules as usual)
    - this collided with two existing Kurrent letterforms, so those had to be modified to stay distinct:
        - capital P (which wynn's capital form otherwise resembles) is now written like capital R minus the tail, so it's no longer confusable with capital wynn.
        - lowercase k had its curve start from the middle of the stroke instead of the top, since starting from the top made it read too much like lowercase wynn.

## Prefixes
- 'con-' is replaced with ꝯ (the medieval scribal abbreviation mark for con-/contra-, one of the oldest abbreviation signs, going back to Tironian notes). ex: contract -> ꝯtract, consider -> ꝯsider, control -> ꝯtrol, connect -> ꝯnect (the mark stands for the whole prefix, final n included, so an assimilated double at the seam just disappears into it — no ogonek needed, per the consonant-doubling rule in Morphemes)
    - 'com-' uses the same mark with a stroke across the stem (ꝯ̶ — no precomposed Unicode form, just the con-mark plus a combining stroke overlay), matching the same family of stroke-modified letters as ꝑ (per-) and ꝓ (pro-): the stem itself is what changes to signal the nasal shift from n to m, since com- is just the labial-assimilated spelling of the same underlying prefix before b/p/m. ex: combine -> ꝯ̶bi̲n, complete -> ꝯ̶ple̲t, common -> ꝯ̶mon, commit -> ꝯ̶mit (combine/complete also take the silent-e magic-e underbar, per Morphemes above; common/commit show the seam absorption — com + mon, com + mit — with the doubled m needing no mark of its own)

## Suffixes
- 'ing' suffix is replaced by ŋ. ex: running -> rųnŋ (the doubled n collapses and hooks the u per the Morphemes consonant-doubling rule, same as hopping -> hǫpŋ)
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
- three-vowel sequences (beauty, queue, aqueous) aren't covered by the two-letter digraph rule — needs a convention. The qu rule in Letterforms takes the first u off the q-words (queue -> q̆ + eue, aqueous -> aq̆ + eous), but what's left is still a multi-vowel run.
- the short-vowel hook collides with the descender on y (syllable, gypsy). Not a new problem — the long-vowel underbar of silent-e function 1 already has it (ty̲p, sty̲l) and hasn't been addressed. The descender fix used for soft g in function 2 (move the mark above instead) doesn't transfer cleanly here, since the space above the vowel is already fully spoken for by the Digraph Vowels table.
