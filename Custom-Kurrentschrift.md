# Custom Kurrentschrift

Guidelines for writing my custom handscript. Unless otherwise specified, stick to the normal kurrent handscript guidelines.

Rationale, design history and edge-case notes live in [JUSTIFICATION.md](JUSTIFICATION.md), referenced below as §n.n.

Constraints:
- All modifications should be able to orthographically reconstruct the original english word.
    - This does not apply to whole common-word replacements (e.g. and -> ⁊); those may be arbitrary signs learned by memory, same as historical shorthand grammalogues.

## Morphemes
- 'th' splits by voicing (§1.1):
    - voiceless /θ/ -> þ (thorn). ex: think -> þink, three -> þrē, math -> maþ, thin -> þin
    - voiced /ð/ -> ð (eth). ex: this -> ðis, father -> faðꝛ, though -> ðŏȝ
- 'gh' (the historical /x/ sound) -> yogh (ȝ), except word-initially. ex: night -> niȝt, though -> ðŏȝ, right -> riȝt, daughter -> dăȝtꝛ, burgh -> burȝ
    - word-initial "gh" stays as gh (§1.2). ex: ghost -> ghost, aghast -> aghast
- silent ending e: no single mark — split by function (§1.3):
    1. marking a long/tense preceding vowel (magic-e): a diagonal slash struck through that vowel, e dropped (§1.3.1). Precomposed: ⱥ ø ɏ. ex: case -> cⱥs, hope -> høp, make -> mⱥk, note -> nøt, type -> tɏp
        - only a, o and y have the open bowl or descender a slash can cross. e and i take a macron above instead. Precomposed: ē ī. ex: ride -> rīd, time -> tīm, complete -> ꝯ̶plēt
            - on i, the macron absorbs the letter's own dot rather than stacking above it — the same convention ordinary Latin diacritics already use (í, ī never carry a separate tittle under the accent).
        - u takes the macron too, but by substitution rather than addition: its native line (§1.4.3) is a breve, and magic-e length simply swaps that breve for a macron in the same stroke instead of adding a second mark beside it. Precomposed: ū. ex: dune -> dūn, tribune -> tribūn, cube -> cūb, use -> ūs — against bare u for a genuinely short vowel: cub, tub, cut, us.
        - the macron is also the fallback for a/o/y at small scale, where a slash closes up into a blot. ex: cās, hōp, tȳp
    2. softening a preceding c or g: both take a cedilla, e dropped — ç on the c, ģ on the g, where the cedilla rides above the bowl because the descender owns the space below (§1.3.2). ex: face -> fⱥç, cage -> cⱥģ, range -> rⱥnģ, notice -> notiç (short i — the e softens the c and nothing else, so there is no length mark)
        - where the e does two jobs at once, both are marked — the long-vowel mark on the vowel and the softening mark on the consonant (§1.3.5). The two marks never share a letter, so neither is crowded.
    3. propping up a word that would otherwise end in bare v or u: final v takes a cedilla (v̧), still required — it marks the dropped letter, not a change in sound (§1.3.3). ex: have -> hav̧, give -> giv̧, love -> lov̧. -ue words fall out of the digraph umlaut instead: blue -> blü, true -> trü
    4. voicing a final th: nothing extra — the eth/thorn split already carries it. ex: bath -> baþ vs bathe -> bað, teeth -> tēþ vs teethe -> tēð, breathe -> brêð
- doubled consonants: drop the doubled letter and put a right hook — an ogonek (◌̨) — under the preceding vowel. Precomposed: ą ę į ǫ ų (y̨ must be composed). ex: letter -> lętꝛ, hopping -> hǫpŋ, dinner -> dįnꝛ, latter -> lątꝛ, written -> ƿrįten
    - the hook means exactly one thing: a doubled letter follows (§1.4.1). It has the below zone entirely to itself now — magic-e length lives above throughout: the primary slash on a/o/y, a macron everywhere else, including u, where the macron simply replaces the native breve rather than adding to it (§1.3.1).
    - marks above and below stack freely, on different letters or the same one. balloon has no stacking, since the ll-hook and the oo-titlo land on different letters: balloon -> bąlon (titlo on the o — §2.4). Where a doubled vowel is immediately followed by a doubled consonant, both marks land on the one letter doing double duty — ogonek below, titlo above — as two independent combining marks on a bare base, not by stacking the titlo onto the precomposed ogonek letter, which renders unpredictably in most fonts since it isn't a tested combination. ex: roommate -> rǫmⱥt, coolly -> cǫly, bookkeeper -> bǫkepꝛ — each marked o also carries a titlo above the ogonek shown here (the precomposed form only shows the below-mark; add the titlo by hand when writing), and bookkeeper's e in keeper carries a lone titlo for its own ee.
    - the source of the doubling is never asked about — assimilated prefixes and morpheme seams are written like any other double. ex: apply -> ąply, occur -> ǫcur, illegal -> įlegal, accord -> ącord, correct -> cǫrect, suffer -> sųfꝛ, unnatural -> ųnatural, misspell -> mißpęl
    - no hook where another glyph already swallowed the double (§1.4.8). ex: commit -> ꝯ̶mit, common -> ꝯ̶mon, connect -> ꝯnect, misspell -> mißpęl (hooks only its ll)

## Digraph Vowels
A two-letter vowel digraph is written as its first letter carrying a diacritic that stands for the second letter — the pair collapses to one glyph, and the dropped letter is reconstructed from the diacritic. The diacritic-to-second-letter mapping:
- second letter a -> circumflex/caret ( ◌̂ ). ex: boat -> bôt, bread -> brêd
- second letter e -> umlaut ( ◌̈ ). ex: toe -> tö, blue -> blü, field -> fïld
- second letter i -> dot above ( ◌̇ ). ex: rain -> rȧn, boil -> bȯl, rein -> rėn
- second letter o -> ring above ( ◌̊ ). ex: people -> pe̊ple, leopard -> le̊pard
- second letter u -> breve above ( ◌̆ ). ex: soup -> sŏp, feud -> fĕd, sauce -> săç (sauce's final c is soft, so it also takes the silent-e cedilla)
- second letter y -> grave ( ◌̀ ). ex: day -> dà, joy -> jò, key -> kè
- Only a/e/i/o/u/y second letters are covered; a digraph is any of these following the first vowel — except the i/u pair, below.
- a doubled identical vowel takes a titlo (◌҃, U+0483, borrowed from Cyrillic) instead of the letter's own mapped mark (§2.4). No precomposed Latin forms exist — these are combining sequences: a/e/o + titlo. ex: boom -> bo҃m, seem -> se҃m, see -> se҃, moon -> mo҃n, book -> bo҃k, three -> þre҃, aardvark -> a҃rdvark
    - ii and uu are excluded: they never spell a single vowel sound in English (ski-ing, ra-di-i, vac-u-um are syllable breaks), and uu is doubly excluded since u has no free above-zone stroke to begin with (§1.3.1, §2.4.1).
    - the titlo is a distinct shape from the macron that marks magic-e length (§1.3.1) — the two occupy the same above zone on e, told apart by shape only, the same way the cedilla and ogonek share the below zone told apart by hook direction (§1.4.4).
- the i/u pair doesn't collapse in either direction (§2.1): ui and iu are both written out in full. ex: suit -> suit, fruit -> fruit, juice -> juiç, build -> build, guide -> gui̲d, medium -> medium, radius -> radius, triumph -> triumph
- when u is the first vowel of a digraph, its u/n line is dropped (§2.3). ex: blue -> blü, with no extra line underneath. Covers ue/ua/uo/uy.

## Letterforms
- 'qu' is written as q with a breve above (q̆) — the same "second letter u" mark as the Digraph Vowels table, riding a consonant (§3.1). ex: queen -> q̆ēn, quick -> q̆ick, quit -> q̆it, require -> req̆i̲r, equal -> eq̆al
    - the breve only stands for the u immediately after q; any following vowel is written as normal. ex: quote -> q̆øt, quiet -> q̆ït
- 'ss' is written as ß (eszett). A letterform substitution in its own right, not the consonant-doubling rule — the vowel takes no hook (§3.2). ex: missing -> mißŋ, kiss -> kiß, glass -> glaß
- 'w' is replaced with wynn (Ƿ/ƿ) in all places. ex: was -> ƿas, written -> ƿrįten
    - two Kurrent letterforms were modified to stay distinct from it (§3.3): capital P is now capital R minus the tail; lowercase k starts its curve from the middle of the stroke instead of the top.
- 'c' is a minim with a small tick at its top. The tick is what separates c from i, which is the same minim with a dot instead — so it is never simply dropped for economy. Three environments (§3.4):
    - before h and k, the tick is dropped and the c ligatures into the following letter — the inherited Kurrent form. ex: chair, ƿhich, q̆ick, black, church. Covers sch, where the c is before h anyway: schōl, schism
    - before t, the tick is *extended* into an arch carrying over to the t; the c keeps its full form (§3.4.3). ex: act, fact, doctꝝ, picture, octobꝛ
    - everywhere else, the plain ticked c. ex: cat, scar, cⱥs, ꝯtract, secret
    - these are allographs, not spellings: c is written as c in all three, and nothing is dropped or reconstructed. ck in particular stays two letters (§3.4.4)

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
- abbreviation for 'from'
