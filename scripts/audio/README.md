# Audio scripts (ElevenLabs)

Text-only versions of the scripts for text-to-speech, with no scene headings, action lines
or animator notes. Generated from the approved scripts in `scripts/`; edit the script, not these.

| File | Use |
|---|---|
| `ep01-the-hound-comes-home-elevenlabs.txt` | Plain `SPEAKER: line` format. Safest for any ElevenLabs tool. |
| `ep01-the-hound-comes-home-elevenlabs-v3-tagged.txt` | Same lines with the script's parentheticals as `[tags]` (for example `[whispering]`), for Eleven v3 / Text to Dialogue. Tags are suggestions; delete any that read oddly. |

**Format:** one line per speaker turn, a blank line between turns, 200 lines, about 1,380
spoken words (roughly 9 to 10 minutes of speech; the other 12 minutes of the pilot are action,
music and silence).

## Voices to assign (11 speakers)

| Speaker | Lines | Notes |
|---|---|---|
| HOLMES | 65 | Kurstin Holmes, 10. Quick, precise, warm. |
| HENRY | 31 | 9, shy, gentle, grows braver. |
| WATSON | 23 | Mateo Watson, 10. Kind and bright. Also reads the journal entries. |
| JASPER | 15 | 11, formal and stiff, then shaky and honest. |
| ANJALI | 14 | 11, theatrical. Narrates the legend. |
| TAVITA | 11 | 9, loud and cheerful. |
| MINH | 11 | 10, calm and quiet. |
| LINH | 10 | 10, bouncy. |
| BERYL | 8 | 9, soft and steady. |
| ZAID | 5 | 6, tiny voice. |
| MOONY | 6 | Howls and one sneeze only. Use a sound-effects or voice-design prompt, not speech. |
| BA NGOAI | 1 | Off-screen grandmother, one line. |

## What was left out, and why

- **Minh's signed line** (dining room, "Why don't we do that?") is subtitle-only in the film, so it
  has no spoken line. Minh has 11 other lines.
- **Group moments** ("LINH & MINH", "HENRY & WATSON") appear as two consecutive lines with the same
  words. Generate both and lay them on top of each other when editing.
- **Group howl, Moony's tiny "woo" in the meadow, and the final gag's "woo"** are in action lines,
  not dialogue, so they are not included. Add them from sound effects.
- **Title cards** and **Part One / Part Two** cards have no voice.

## Episode 2: The Case of the Missing Sandwiches

`ep02-the-case-of-the-missing-sandwiches-elevenlabs.txt` (plain) and `...-v3-tagged.txt` (with tags).
103 lines, about 570 spoken words, 7 speakers.

| Speaker | Lines |
|---|---|
| HOLMES | 38 |
| LINH | 18 |
| MINH | 17 |
| WATSON | 15 |
| TAVITA | 10 |
| ANJALI | 4 |
| EVERYONE | 1 (Tavita, Anjali and the others whispering "Shh!"; use one voice or layer several) |

- **Signed lines left out:** Minh's "Please help.", Watson's "Yes." and Linh's "I'm sorry, too." are signed and subtitle-only in the film.
  Minh's "I was stubborn. I'm sorry I sulked." is spoken aloud for the audience in the script, so it is kept.
- **Twins speaking together:** "LINH & MINH" lines are two consecutive identical lines. Layer them when editing.
- **Moony** has no lines in this episode.

## Episode 3: The Light in the Attic Window

`ep03-the-light-in-the-attic-window-elevenlabs.txt` (plain) and `...-v3-tagged.txt` (with tags).
103 lines, about 620 spoken words, 9 speakers.

| Speaker | Lines |
|---|---|
| HOLMES | 38 |
| JASPER | 20 |
| HENRY | 16 |
| WATSON | 12 |
| TAVITA | 9 |
| BERYL | 3 |
| ANJALI | 2 |
| ALL | 1 ("AH!", the group jump; use one voice or layer several) |
| EVERYONE | 1 ("Shh!") |
| MOONY | 1 (a sneeze, "Achoo.") |

- **Signs and notes:** the attic sign ("ATTIC: CLOSED...") is written text, not spoken, so it is left out. Watson reads "J.S." aloud, which is kept.
- **Tool note:** the converter now skips only real sign-language lines, not lines like "taps the sign".
