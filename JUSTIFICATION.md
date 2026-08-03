# Justification

Rationale, design history and edge-case notes for [Custom-Kurrentschrift.md](Custom-Kurrentschrift.md). The main document is the reference; this one explains why each rule takes the shape it does. Section numbers are referenced from the main document as §n.n.

## 1. Morphemes

### 1.1 The th split

Old English used þ and ð fairly interchangeably. The split by voicing follows the modern Icelandic convention, which keeps the two phonemically distinct — that gives a rule with a testable criterion rather than a free choice between two shapes.

### 1.2 Word-initial gh

Word-initial "gh" (ghost, ghastly, aghast, gherkin, ghetto) is a separate, unrelated origin: a silent h inserted after g by early printers under Flemish/Dutch spelling influence, representing a plain /g/ sound, not the old fricative. Since it never was /x/, it has no yogh to be replaced by and stays as gh.

### 1.3 Silent ending e

There is no single mark because what the -e does in English varies, so the rule is split by function.

#### 1.3.1 Function 1 — long vowel slash

The space above the vowel was never available: Kurrent puts a breve-like line over u to distinguish it from n, so a macron would collide with that on words like dune, and the Digraph Vowels table has since claimed the whole zone above anyway.

Below the vowel works but is crowded. The doubling hook of §1.4 hangs there too, so the pair had to be told apart by shape alone — flat bar = long vowel, right hook = doubled letter follows — two small marks in one place, distinguished in a fast hand only by curvature.

Striking through the letter is a third position that nothing else uses, which is why it is the primary form: above is digraph, below is doubling, through is length. The shape is the Nordic ø, where a slash through the bowl is a routine, fast, legible stroke rather than an exotic one. All three have precomposed forms — ⱥ (U+2C65), ø (U+00F8), ɏ (U+024F) — so nothing here depends on a combining overlay.

The slash needs something to cross. a and o have an open bowl and y has a descender, so the stroke has room to be a stroke; e, i and u in a minim-based hand are too cramped, and a slash through them lands as a smudge or, worse, reads as part of the letter. Those three keep the underbar. The same limit applies at small scale to a/o/y, where the bowl closes up — the underbar is the fallback there, so the two forms are one rule with a legibility escape hatch, not two competing marks.

høp (hope) vs hǫpŋ (hopping): the contrast that used to depend on bar-vs-hook now separates by position as well. Bare hop takes no mark at all, since there is neither length to mark nor a doubled letter to reconstruct.

An incidental payoff: the slash clears half of §7.2. The long-vowel underbar collided with the descender on y (ty̲p, sty̲l); a slash across that descender does not, so tɏp and stɏl are clean. The doubling hook on y is still open.

#### 1.3.2 Function 2 — soft c and g

Both letters take the same mark — a cedilla — so softening has one shape rather than two. What varies is where it sits: c has no descender and takes it below (ç); g's descender owns the space below, so the cedilla rides above the bowl instead (ģ, U+0123). Position bends around the letterform; the mark itself doesn't change, and the same logic carries to anything else that ends up soft this way.

This is not an improvisation. Latvian writes ģ exactly this way, with the cedilla lifted above the g for the same descender reason — the same source already borrowed from in §6.5.

The cedilla hooks left. That is what keeps it clear of the right-hooking ogonek of §1.4, which also hangs beneath the baseline — see §1.4.4 for the direction contrast.

#### 1.3.3 Function 3 — bare v or u

English words don't end in v or u, so the -e is there purely as a prop. The final v still takes a cedilla (v̧), same shape and placement logic as the soft-c cedilla in §1.3.2. For -ue words the fix coincides with the Digraph Vowels umlaut anyway: blue -> blü, true -> trü.

The mark is required even though nothing about the pronunciation changes. Every other function of the silent e alters something audible, so it would be easy to read this one as needing no mark at all — but the reconstruction constraint is orthographic, not phonetic: hav with no mark is not a recoverable spelling of have. The cedilla here says a letter was dropped, which is the same job it does in §1.3.2; the softening is a fact about c and g, not about the mark.

This is the same reasoning that makes the doubling hook orthographic rather than phonetic (§1.4.1) — the mark records what was written, and the sound change is a consequence that may or may not come along.

#### 1.3.4 Function 4 — voiced final th

Nothing extra is needed. The voicing split of §1.1 already writes voiced /ð/ as eth, and word-final eth vs thorn is itself the cue, so eth alone stands in for the dropped -e.

#### 1.3.5 When one e does two jobs

A silent e often works on the consonant and the vowel at once — range, cage, face all have both a soft consonant and a long vowel riding on that single letter. Both get marked: rⱥnģ, cⱥģ, fⱥç.

Marking only one would break the reconstruction constraint from the other end. A bare ranģ says the g is soft but leaves the a unmarked, which reads as the short a of rang; a bare rⱥng says the a is long but loses the soft g.

Neither mark implies the other, which is why each has to be checked on its own rather than inferred from the other. bathe has a long vowel and no soft consonant; notice and dance have a soft c after a short vowel, so they take the cedilla alone — notiç, danç. The test for function 1 is whether the vowel is actually long, not whether a softening mark happens to be present.

They never compete for space: the length mark rides the vowel and the softening mark rides the consonant after it, so this is one e spending itself on two different letters rather than two marks stacking on one.

### 1.4 Consonant doubling

#### 1.4.1 What the hook means

The hook means exactly one thing: a doubled letter follows. Not "this vowel is short" — that is the usual consequence, not the definition. Defining it orthographically rather than phonetically is what lets one rule cover every doubled consonant in English regardless of where it came from, and it keeps the reconstruction constraint mechanical: hook, therefore double the next letter, no judgment call about why the double was there.

#### 1.4.2 Why it rides the vowel

In the ordinary case the vowel is what the doubling is describing — nobody holds the p in hopping longer than the p in hoping. The doubled letter is a diacritic about the vowel in front of it, so putting the mark on the consonant would keep it one letter away from what it refers to.

Below the vowel is also where §1.3.1 falls back to its long mark — on e/i/u, and on any vowel at small scale — so the two still have to contrast by shape there: flat bar = long vowel, right hook = doubled letter. Where the length mark takes its primary slash form the question doesn't arise, since the two marks are no longer in the same place at all. They aren't two ends of one axis — one is phonetic and one is orthographic — but the pairing is worth the mnemonic, since a hook does imply a short vowel nearly every time.

#### 1.4.3 Why it hangs below

Hanging below means it doesn't compete with the line over u, which rides above. So u keeps its inherent u/n line and takes the hook underneath as well: supper -> sųpꝛ vs super -> supꝛ.

#### 1.4.4 Why it opens right

The hook opens to the right, and that is what keeps it apart from the cedilla of §1.3.2, which hooks left. Direction does the work, not position: the two stay legible against each other in a fast hand even though both hang below the baseline. Polish (ą, ę) against Latvian (ķ, ļ, ņ) leans on exactly this contrast, so it is a tested distinction rather than an assumed one.

#### 1.4.5 Provenance of the shape

The ogonek is itself a medieval scribal mark — the nasal hook of Latin manuscripts, ę standing in for ae — so it belongs to the same borrowed-shape family as thorn, eth, wynn and the con-mark. As with ß (§3.2), only the shape is imported and not the historical usage: here it marks a following doubled letter, not nasality.

#### 1.4.6 Stacking with marks above

Marks above and marks below stack freely, on different letters or on the same one: balloon -> bąlōn (ll hooks the a, oo collapses to an overbar on the o), roommate -> rǭmⱥt, coolly -> cǭly, bookkeeper -> bǭkēpꝛ (here the overbar and the hook share one o — the mark above says oo, the hook below says the next letter doubles).

This is where defining the hook orthographically pays off: the vowel in these is long, so a mark that meant "short" would be lying, but one that means "a double follows" is simply true.

#### 1.4.7 The source of the doubling is never asked about

Latin prefix assimilation (apply from ad-, occur from ob-, illegal from in-, suffer from sub-) and morpheme seams (unnatural from un + natural, misspell from mis + spell) are written the same as any other double: apply -> ąply, occur -> ǫcur, illegal -> įlegal, accord -> ącord, correct -> cǫrect, suffer -> sųfꝛ, unnatural -> ųnatural, misspell -> mißpęl.

#### 1.4.8 Where no hook is needed

No hook is needed where another glyph has already swallowed the double. The con-/com- marks stand for the whole prefix including its final consonant, so a seam double disappears into them: commit -> ꝯ̶mit, common -> ꝯ̶mon, connect -> ꝯnect. (correct is not one of these — there is no cor- mark — so it keeps its hook.) ß does the same for ss, which is why misspell above hooks only its ll. The hook is there to reconstruct a double that would otherwise be lost; when the double is already recoverable, it has no work to do.

## 2. Digraph Vowels

### 2.1 Why the i/u pair is excluded

i and u each identify themselves by a mark the other one owns — u by its line above, i by a dot on a single minim — so a mark standing for one, riding on the other, spells that letter instead of modifying it.

- ui fails because a lineless u (per §2.2) plus a dot reads as an i followed by the next consonant's minims: ruin vs rim.
- iu fails the same way in reverse, since the breve standing for a second-letter u *is* the u line — i+breve is one minim under a line, which is what a plain u already looks like, so medium would read medum.

Neither direction survives a fast hand, and reconstructing the original word is the whole point of the table.

### 2.2 Why the cost of that exclusion is small

ui and iu are the two rarest vowel pairs in English, and iu is never a real digraph at all — it is always a syllable break (me-di-um, ra-di-us, tri-umph), so no single vowel sound is being spelled out longhand. ui does hold genuine digraphs (fruit, suit, juice) alongside the silent-u-after-g class (guide, guilt, build), but the pair is rare enough that writing it in full is cheaper than minting another diacritic to dodge the collision.

### 2.3 Dropping the u line in a digraph

u is the only vowel with an inherent mark of its own (the u/n distinguishing line), so it is the only base letter with a possible collision. When u is the first vowel of a digraph the line is dropped: the digraph diacritic alone is enough to mark it as a vowel, so keeping the line is unnecessary. This covers ue/ua/uo/uy; ui is excluded per §2.1, so a lineless u never meets a dot.

### 2.4 Why identical pairs take an overbar

ee and oo are the two most common vowel digraphs in English, and they are the case where the second-letter table has the least to say: the mapped mark would stand for the same letter it is already sitting on (o carrying a ring that means "o"), which is a tautology rather than a reconstruction. The overbar says the one thing that actually needs saying — the letter beneath, twice — so the mark carries information instead of restating the base letter.

It also has to be a mark *above*. The hook below already means "a doubled letter follows" (§1.4.1), and using it here would be ambiguous in exactly the wrong place: bǫk could reconstruct as book or as bock, since nothing in the hook says whether the double is the vowel or the consonant after it. Splitting by position keeps each mark unambiguous — above the vowel: this vowel doubles; below it: the next letter doubles. That is why they stack cleanly on one letter (bǭkēpꝛ) rather than competing.

The shape is the medieval titulus, a bar over a letter marking an omitted following letter (nasals, most commonly). As with the ogonek (§1.4.5) and ß (§3.2), only the shape is imported, not the historical usage: here the omitted letter is a copy of the one under the bar.

#### 2.4.1 Why ii and uu are excluded

Neither is ever a genuine digraph in English — skiing, radii, vacuum, continuum all break across syllables (ski-ing, ra-di-i, vac-u-um), so there is no single vowel sound being spelled longhand and nothing for a collapse to buy. This is the same reasoning that keeps the cost of the i/u exclusion small (§2.2).

uu is doubly ruled out: an overbar on u is the u/n line, so ū is just a u. That collision is the same one that pushed the long-vowel mark below the baseline in §1.3.1, and it is what confines the overbar to a/e/o here — the three letters that have no inherent mark above to lose it in.

## 3. Letterforms

### 3.1 qu

English q is followed by u essentially without exception, so the u is predictable — but it isn't dropped silently. The breve is the same "second letter u" mark as the Digraph Vowels table (soup -> sŏp, feud -> fĕd), just riding a consonant instead of a vowel, the same way no -> n̊ rides the n.

The breve only ever stands for the u immediately after q, so any following vowel is written as normal, collapsing with its own neighbour if it forms a digraph in its own right: quote -> q̆øt, quiet -> q̆ït.

### 3.2 ss as ß

ß is historically a ligature of long-s + s. This is a letterform substitution in its own right, not an instance of the consonant-doubling rule (§1.4): since English doubling never represents a real geminate sound, ß reconstructs unambiguously to "ss" on its own, so the vowel takes no hook. It also sidesteps Kurrent's long-tailed s, which leaves awkwardly little room for anything else nearby.

German traditionally uses ß the other way round (after long vowels, with ss reserved for short ones) — worth knowing as the source, but not imported here. This reuses only the ligature shape, same as how thorn, eth and r-rotunda were repurposed without their full historical usage rules.

### 3.3 Letterforms modified for wynn

Wynn collided with two existing Kurrent letterforms, so those had to be modified to stay distinct:

- capital P (which wynn's capital form otherwise resembles) is now written like capital R minus the tail, so it is no longer confusable with capital wynn.
- lowercase k had its curve start from the middle of the stroke instead of the top, since starting from the top made it read too much like lowercase wynn.

## 4. Prefixes

### 4.1 con-

ꝯ is the medieval scribal abbreviation mark for con-/contra-, one of the oldest abbreviation signs, going back to Tironian notes. The mark stands for the whole prefix, final n included, so an assimilated double at the seam just disappears into it — no ogonek needed, per §1.4.8.

### 4.2 com-

com- uses the same mark with a stroke across the stem (ꝯ̶ — no precomposed Unicode form, just the con-mark plus a combining stroke overlay), matching the same family of stroke-modified letters as ꝑ (per-) and ꝓ (pro-). The stem itself is what changes, to signal the nasal shift from n to m: com- is just the labial-assimilated spelling of the same underlying prefix before b/p/m.

combine and complete also take the magic-e underbar (§1.3.1); common and commit show the seam absorption — com + mon, com + mit — with the doubled m needing no mark of its own.

## 5. Suffixes

### 5.1 -or as ꝝ

ꝝ is r rotunda with a stroke across the stem (precomposed, U+A75D). Historically it was the medieval sign for -rum/-orum/-arum, so it is a real r-rotunda-family mark rather than an invented one. Using it for -or keeps the same "stroke = marked variant within the family" logic as con-/com- (§4) and per-/pro-, with plain ꝛ as the more common default (-er) and struck ꝝ as the less common one (-or).

## 6. Common Words

### 6.1 at

@ is historically a scribal ligature of 'ad', a flourished a merging with the ascender of d — the same logic as reusing Tironian et for and.

### 6.2 to

t˞ is a t with a flourish. There is no real Unicode glyph for a decorative tail stroke, so it is approximated with U+02DE MODIFIER LETTER RHOTIC HOOK; in the actual handscript it is just a flourish off the tail of the t, not a phonetic hook.

### 6.3 with

ƿþ is wynn + thorn — a whole-word abbreviation to the initial and final consonant, not the regular letter-substitution spelling ƿið.

### 6.4 it, is

ṫ and ṡ use the same device: the surviving consonant carries the digraph second-letter-i mark for the dropped vowel. It is the device of no -> n̊, but for a leading vowel instead of a trailing one.

### 6.5 not

ꞥ is n with an oblique stroke (U+A7A4/U+A7A5); the stroke reads as the mundane negation slash, same logic as the struck marks in §4 and §5. It falls back to ņ (n with cedilla) if the oblique stroke doesn't survive at small scale — fittingly, this mirrors real history: Latvian orthography used this exact letter until 1921, when it was replaced by cedilla-n for legibility.

### 6.6 no

n̊ uses the ring above to mark the dropped o, the same second-letter-o mark as people/leopard in Digraph Vowels — but riding the n instead of a vowel, since no puts the consonant first, reversed from an/in/on where the vowel leads and the mark stands for a trailing n.

## 7. Open problems

### 7.1 Three-vowel sequences

beauty, queue, aqueous aren't covered by the two-letter digraph rule — this needs a convention. The qu rule (§3.1) takes the first u off the q-words (queue -> q̆ + eue, aqueous -> aq̆ + eous), but what's left is still a multi-vowel run.

### 7.2 The descender on y

The doubling hook collides with the descender on y (syllable, gypsy). The long-vowel mark used to share this problem, and no longer does: its slash form (§1.3.1) crosses the descender instead of fighting it, so tɏp and stɏl are clean. The hook is still stuck, since it has to hang below and that is exactly where the descender goes. The descender fix used for soft g in §1.3.2 (move the mark above instead) doesn't transfer, since the space above the vowel is fully spoken for by the Digraph Vowels table — and the small-scale underbar fallback inherits the collision too.
