# Aquel Nap ZzZz — Guitar MIDI Reconstruction Analysis

> Source: Tatum's uploaded MIDI reconstruction files. This is a study of the reconstructed guitar arrangement and timing, not a claim that every note exactly matches the released master.

## Source files

- `Aquel_Nap_ZzZz_Guitar_background_chords(2).mid`
- `Aquel_Nap_ZzZz_Guitar_1(2).mid`
- `Aquel_Nap_ZzZz_Guitar_2_I_was_to_lazy_to_merge_the_guitars_its_the_same_thing(2).mid`

## Measured project facts

- MIDI tempo marker: approximately **84 BPM**
- Meter: **4/4**
- Background-chord track: **778 note events**, ending around beat 157.6
- Main guitar track: **359 note events**, ending around beat 188.5
- Auxiliary guitar track: **6 note events**, mostly restoring/duplicating sparse melodic fragments that are absent from the main guitar file
- The first 8-bar guitar pattern repeats with very high similarity in bars 9–16
- The background harmony cycles through the same 8-bar field repeatedly through roughly bar 40, then thins and disappears before the rubato ending
- The final guitar-only section abandons the grid enough to create a clear accelerando/rubato feel even though the MIDI tempo metadata itself remains fixed at 84 BPM

---

# 1. Core emotional reading

The most accurate emotional description is not simply “sad.”

The track feels:

- nocturnal
- intimate
- lullaby-like
- softly dark
- dreamy
- suspended
- inward
- warm
- gently uneasy in places
- emotionally shaded without becoming tragic

A useful distinction is:

> **darkness here means “a direction away from bright/happy,” not “threatening” or “creepy.”**

That darkness comes largely from:

- minor-centered harmony
- chromatic neighboring notes
- repeated semitone approaches
- low urgency
- circular harmonic motion
- soft guitar timbre
- absence of hard cadential resolution

The result is more like:

> **quiet shadow**

than:

> **sadness**

---

# 2. Harmonic home: C# minor / E-major-adjacent

The recurring background progression is strongly centered around **C# minor**, with frequent use of relative-major material.

A practical 8-bar reduction is:

1. **C#m**
2. **G#m/B shell** or ambiguous G#–B dyad over B
3. **C#m**
4. **E/B**
5. **F#m**
6. **G#m7**
7. **C#m**
8. **E/B**

This repeats across most of the structured portion.

Important pitch collections in the background track:

- C#m = C#–E–G#
- bar-2 shell = B–G#
- E/B = B–E–G#
- F#m = F#–A–C#
- G#m7 = G#–B–D#–F#

The progression is notable for what it does **not** do:

- it does not use a harsh dominant-major V to force resolution
- it does not create dramatic cadences
- it does not constantly introduce new harmonic regions

That makes the harmony feel circular and sleepy.

Reusable principle:

> **A nighttime/lullaby feeling can come from a minor-centered loop that keeps returning to familiar relatives without strongly “arriving.”**

---

# 3. The background rhythm is part of the lullaby effect

The background guitar attacks are not placed like a conventional downbeat-heavy accompaniment.

The recurring six-hit pattern per bar lands approximately on:

- **1&**
- **2**
- **2&**
- **3&**
- **4**
- **4&**

The strongest downbeats, especially beat 1, are often left relatively open.

This creates:

- rocking motion
- soft forward pull
- floating syncopation
- less sense of “marching” through the bar
- a cradle-like asymmetry

The notes themselves are very short in the MIDI conversion, but the onset pattern is the important part.

The strums are also physically humanized:

- velocities span roughly **63–119**
- notes within one strum are spread by about **11 ms on average**
- some strums spread by as much as about **30 ms**

So the chord rhythm is repetitive but never mechanically identical.

Reusable principle:

> **A lullaby pulse does not have to be slow block chords. A soft syncopated pattern can rock around the beat instead of landing squarely on it.**

---

# 4. Smooth harmonic voice leading keeps the darkness gentle

The chord loop uses a large number of common tones and small movements.

Examples:

## C#m → E/B

C#m:

**C# – E – G#**

E/B:

**B – E – G#**

Two notes remain:

- E
- G#

Only the C# changes meaningfully.

This makes the shift feel like recoloring rather than relocation.

## F#m → G#m7

F#m:

**F# – A – C#**

G#m7:

**G# – B – D# – F#**

Important voice-leading possibilities:

- F# stays
- A → G# = half step down
- C# → D# = whole step up

The A → G# semitone is especially important.

## G#m7 → C#m

Possible internal moves:

- G# stays
- D# → E = half step up
- B → C# = whole step up
- F# can fall to E or disappear

The harmony therefore contains chromatic tenderness even before the foreground guitar adds its own approach tones.

Reusable principle:

> **Soft darkness often comes from one inner voice sliding by a semitone while the rest of the chord remains familiar.**

---

# 5. Half steps are not decoration here — they are a language

The main guitar contains many recurring semitone patterns.

Within just the first 8-bar cycle, a simple register-based voice split reveals a large number of semitone adjacencies in both the low and upper voices.

The important recurring shapes are more useful than the raw count.

## B → C → C#

This appears repeatedly in the low register.

Function:

- chromatic ascent
- directional pull
- arrival into the stable C# tonal center

Emotion:

**soft tension becoming home**

The important thing is that C natural is not treated as a destination.

It is a bridge.

---

## B → A# → B → C → C#

This is one of the strongest chromatic chains in the reconstruction.

It briefly moves below B:

**B → A# → B**

then climbs:

**B → C → C#**

The line therefore surrounds the stable tones before moving onward.

This creates a sense of the bass “searching” around its target.

Reusable principle:

> **A neighbor-tone half step can make a stable bass line feel alive without changing the chord progression.**

---

## D# → E

This is another recurring semitone resolution.

Because E is a major chord tone in C# minor and E-major-related harmony, D# behaves like a leading approach into warmth.

This contributes to the track’s soft pull.

---

## E → D# → E

This is the same-place/different-shade move.

E is stable.

D# sits a half step below it.

The line leaves home by the smallest possible distance and returns immediately.

This is one reason the music feels intimate rather than dramatic.

---

## E → D# → E → F → F#

This longer chromatic neighborhood is especially revealing.

The line first dips below E, returns, then climbs above it chromatically.

It effectively frames E from both sides.

The listener hears instability, but all of it is directed toward nearby stable notes.

---

## G# → G → G#

This is one of the clearest “dark” colors in the melody.

G# is structurally important in C# minor.

G natural is foreign and only one semitone below it.

The melodic figure:

**G# → G → G#**

creates a brief shadow around a familiar note.

Because G natural is not sustained as a new harmonic center, it feels like:

> **the familiar note momentarily dimmed**

rather than:

> **the key changed**

This is an excellent model for “dark but not sad.”

---

# 6. Why the half steps feel dark but not sad

The chromatic notes are generally:

- brief
- directional
- neighboring
- resolving
- placed inside a stable harmonic loop

So the listener hears friction without hearing collapse.

This is different from using a chromatic note as a long structural harmony.

The underlying chords remain:

- consonant
- repetitive
- familiar
- soft

The half steps create **shadow around stability**.

That is the central mechanism.

Best reusable rule:

> **If you want slight darkness without sadness, keep the harmonic home stable and let short half-step neighbors brush against important chord tones.**

---

# 7. The clearest melodic hook is a descending two-strand staircase

One of the most memorable phrases appears around bar 4 and returns around bar 12.

The upper-guitar sequence is:

**C#5 → A4 → B4 → G#4 → A4 → F#4 → G#4 → E4 → F#4**

At first glance this looks irregular.

But it contains a very strong hidden structure.

Separate the phrase into alternating strands:

High strand:

**C# → B → A → G# → F#**

Lower answering strand:

**A → G# → F# → E**

Both strands descend.

So the melody is essentially a descending staircase woven between two registers.

The repeated interval idea is roughly:

- high note
- drop by a third
- next high note one step lower
- drop by another third
- repeat

This is one of the strongest reasons the phrase is catchy.

It has:

- clear direction
- internal repetition
- descending motion
- alternating register
- recognizable rhythm

The rhythmic fingerprint also repeats:

**long-short / long-short / long-short / then broader settling notes**

This makes the phrase feel composed rather than improvised.

Reusable principle:

> **A catchy descending melody does not need to be a simple scale. Two interlocking descending strands can create a stronger fingerprint.**

This should be remembered for future composition work because it directly addresses the user’s preference for melodies that are easy to latch onto.

---

# 8. Secondary melodic motifs reinforce the identity

The song does not rely on only one phrase.

Several smaller motifs recur around the main descending figure.

## F# → G# → A → G# → F#

A compact arch.

Emotion:

- gentle lift
- immediate return
- no dramatic climax

## repeated A → B → A → G#

This keeps the melodic world centered and singable.

## G# → G → G# → B → A

This combines:

- chromatic neighbor motion
- a small leap upward
- a soft descending answer

It is particularly characteristic because the G-natural half step immediately marks the phrase as darker than ordinary C#-minor scale writing.

---

# 9. Repetition is extremely strong

Bars 1–8 and bars 9–16 are approximately **95% identical** at the note-event level in the main guitar file, allowing for a few omissions/differences.

The background harmony also repeats the same 8-bar pattern.

This matters because the track’s emotional identity is not based on constant invention.

It is based on:

- repetition
- small removals
- selective chromatic details
- density changes
- later performance transformation

Reusable principle:

> **For dreamy music, repeated material can create hypnosis. Development can happen by thinning, restoring, or changing timing instead of writing a new melody every section.**

---

# 10. Bars 17–32: subtraction rather than new harmony

The structured harmony continues, but the main guitar becomes much sparser.

Much of the upper melodic material disappears.

The auxiliary Guitar 2 file restores only a handful of isolated melodic events, including:

- an A4 around the start of this reduced region
- a later **G# → G → G# → B → A** fragment near the end of the cycle

So the melody is not entirely gone.

Instead, it is reduced to remembered fragments.

This is an important arrangement technique:

> **Let the listener mentally supply a melody they already learned.**

The repeated harmony remains familiar while the foreground partially vanishes.

That creates intimacy and space.

---

# 11. Bars 33–40: a new melodic state over the same harmonic world

The background progression continues.

But the main guitar becomes more active again with a different melodic treatment.

Important features include:

- broader melodic register
- more explicit upper notes
- recurring scalar fragments such as C#–D#–E–F#
- continued semitone relationships such as D#→E
- new melodic phrases without abandoning the original harmonic home

This works because the harmonic ground remains recognizable.

The section feels like a new perspective on the same nighttime environment rather than a new song.

---

# 12. The ending changes both harmony and time

The most important structural break arrives after the background-chord ostinato stops.

From roughly bar 41 onward, the main guitar increasingly uses only white-note material:

**C – D – E – F – G – A – B**

The C#/G#/D#-heavy C#-minor world disappears.

This is a major tonal simplification.

The coda can be heard broadly as moving through shapes resembling:

- **Em7**
- **Fmaj7 / Fmaj9 / Fmaj13-like colors**
- **Am7 / Am11-like colors**

The exact arpeggiation varies, so these are functional reductions rather than literal block chords.

The emotional effect is striking:

> **The song stops looping inside C# minor and slips sideways into a softer A-minor/C-major-adjacent world.**

This new world is still not bright.

But it is more open and human.

---

# 13. The E → F half step becomes structural in the outro

Earlier in the track, half steps are mostly passing or neighboring details.

In the coda, the bass itself repeatedly moves:

**E → F**

That is a semitone at the foundation of the harmony.

This is more consequential than a passing note.

It makes the ending feel as if the floor itself is shifting.

Yet the harmony stays gentle because F leads into rich, consonant upper notes rather than a harsh cluster.

Reusable principle:

> **A semitone in the bass can create a larger emotional shift than the same semitone in a melody, especially when the timbre stays soft.**

---

# 14. The ending really does speed up

The MIDI contains only one formal tempo event:

**84 BPM**

So there is no programmed tempo automation.

However, the later notes increasingly stop landing on the original quantized grid.

A rough measurement of note spacing in the free section shows:

- early free-time passage: equivalent to roughly **mid-80s BPM**
- later free-time passage: equivalent to roughly **99–100 BPM** if interpreted as continuation of the earlier eighth-note pulse

This means the perceived acceleration is encoded in the performance timing itself.

The user’s hypothesis that the original guitarist may simply have played the ending freely is plausible, but the MIDI alone cannot prove the recording method.

What the MIDI *does* prove is:

> **the ending is intentionally or naturally rubato and accelerando relative to the earlier grid.**

---

# 15. Why the rubato ending feels intimate

During most of the track:

- harmony loops
- background strums establish a reliable grid
- chromatic details move inside that grid

At the end:

- the background ostinato disappears
- harmony changes
- the note grid loosens
- phrases speed up
- durations become irregular
- the guitar feels physically performed rather than sequenced

That makes the ending feel closer.

It sounds less like “production” and more like “someone playing.”

Reusable principle:

> **Moving from strict repetition into human rubato can make an outro feel more personal without adding any new instrument.**

---

# 16. Why the track feels nighttime-like

The nocturnal effect is not one isolated chord.

It comes from a bundle of behaviors:

## 84 BPM

Slow enough for spacious phrasing, but not so slow that the music becomes static.

## Minor-centered harmonic home

C# minor provides emotional shadow.

## No aggressive dominant cadence

The harmony circles rather than demands resolution.

## Soft syncopated guitar pulse

The accompaniment rocks around strong beats instead of stamping them.

## Repetition

The same harmonic environment stays present long enough to feel like a place.

## Half-step neighboring

Small chromatic shadows repeatedly darken stable notes.

## Upper-register melodic detail

The melody often floats above the accompaniment rather than sitting heavily in the middle register.

## Free-time ending

The final loss of strict grid makes the track feel private and late-night.

Best summary:

> **The track sounds nocturnal because it is low-urgency, repetitive, softly minor, gently chromatic, and physically intimate.**

---

# 17. Why it does not sound sad

Several things prevent the minor harmony from turning into obvious sadness:

1. The guitar pulse remains active.
2. The melody contains motion and curiosity.
3. Most chromatic notes resolve quickly.
4. The progression does not dwell on heavy downward cadences.
5. Relative-major material such as E appears repeatedly.
6. The timbre is warm and close.
7. Repetition makes the harmony comforting rather than tragic.
8. The ending becomes freer rather than more emotionally heavy.

So “dark” is a reasonable description if it is defined as:

> **slightly shaded away from happiness**

rather than:

> **disturbing or depressing**

---

# 18. Comparison with Mice on Venus

These two tracks produce atmosphere differently.

## Mice on Venus

Main mechanism:

**establish modal home → violate pitch language → return**

Unease comes from a reserved harmonic region becoming foreign.

## Aquel Nap ZzZz

Main mechanism:

**keep harmonic home stable → constantly brush it with half-step neighbors**

Darkness comes from small chromatic shadows inside familiarity.

That distinction is extremely useful.

Mice on Venus says:

> **“The environment changed.”**

Aquel Nap ZzZz often says:

> **“The environment stayed the same, but tiny things inside it keep slipping.”**

---

# 19. Most reusable rules from this study

1. **A nighttime feeling can come from low urgency rather than extremely dark harmony.**
2. **Stable minor harmony plus short chromatic neighbors creates shadow without sadness.**
3. **B→C→C# is an excellent soft-pull device when C is only a bridge.**
4. **G#→G→G# creates a brief darkening around a stable note.**
5. **E→D#→E creates intimate neighbor motion because the listener never loses the home note.**
6. **Use common-tone voice leading so chromatic details feel intentional rather than random.**
7. **Avoid strong dominant resolution if you want a circular, lullaby-like atmosphere.**
8. **A syncopated repeating accompaniment can rock around the beat instead of landing on every downbeat.**
9. **A clear hook can be built from two interlocking descending strands.**
10. **Exact 8-bar repetition can create hypnosis; not every repeat needs melodic variation.**
11. **Remove the foreground melody and leave fragments to create space without changing harmony.**
12. **A late tonal shift can feel intimate when the instrumentation gets simpler, not bigger.**
13. **Moving a half step in the bass is more structurally powerful than using the same interval as a passing upper note.**
14. **Rubato/accelerando at the end can make a sequenced-feeling track suddenly sound human.**
15. **Nighttime music does not have to sound sad; it can be warm, repetitive, chromatic, and low-urgency instead.**

---

# 20. Implications for future original composition

For a new nighttime/tropical/atmospheric track drawing from this study without copying it:

- Build one stable minor or modal harmonic home.
- Avoid a strong dominant-major cadence.
- Create one unmistakable melodic hook with a descending contour.
- Make the hook readable even with all effects muted.
- Use 2–4 recurring semitone gestures as a vocabulary.
- Let one semitone motion live in the bass, one in a sustained background voice, and one in the melody.
- Keep most chromatic notes brief so the track feels shaded rather than tense.
- Use a syncopated accompaniment that rocks around strong beats.
- Repeat the main harmonic loop long enough for it to become environmental.
- Remove the hook for one section but leave recognizable fragments.
- Save a free-time or timing-loosened coda for the end.
- Consider changing tonal vocabulary in the coda while keeping timbre intimate.
- Let the outro accelerate naturally rather than automating a dramatic tempo ramp.

Most important compositional test:

> **If the guitar tone, reverb, and ambience are removed, is the descending hook still memorable?**

That should be a requirement for the next original piece.
