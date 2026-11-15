# QA report (v6)

All numbers below were measured on the delivered files.

## Videos

| Audio | File | Duration | Streams | Audio language tag |
|---|---|---|---|---|
| English | `audio_en/LearningAndAccessibilityTools_tutorial_audio-en.mp4` | 5:30.5 | video + audio (no subtitle stream) | `eng` |
| German | `audio_de/LearningAndAccessibilityTools_tutorial_audio-de.mp4` | 5:54.2 | video + audio (no subtitle stream) | `ger` |
| Romanian | `audio_ro/LearningAndAccessibilityTools_tutorial_audio-ro.mp4` | 6:32.8 | video + audio (no subtitle stream) | `rum` |

## Synchronization

Narration was synthesized sentence by sentence; each sentence's start and end were then re-measured in the finished narration audio (10 ms frames, −42 dBFS). Subtitle cues take their timing from the spoken sentence they translate (sentence *i* of a segment in the subtitle language ↔ sentence *i* of that segment in the audio language; sentence counts match in all 47 segments). No timings were derived from another language's video.

| Audio | Sentence starts vs. speech onsets detected independently in the MP4's decoded audio |
|---|---|
| English | 56/56 within 80 ms (max deviation 40 ms) |
| German | 56/56 within 80 ms (max deviation 32 ms) |
| Romanian | 56/56 within 80 ms (max deviation 12 ms) |

Cue timing rules: a cue that begins a sentence may appear up to 0.25 s before the voice; split points inside a sentence may trail the voice by at most 0.30 s; cues may stay up to 1.0 s after the speech they carry, never overlapping.

## Subtitle tracks

| Audio | Subtitles | Cues | Max chars/line | Max lines | Shortest cue | Max reading speed | Cues > 17 cps | Cues > 20 cps | SRT = VTT | Cues off speech |
|---|---|---|---|---|---|---|---|---|---|---|
| English | English | 95 | 42 | 2 | 0.9 s | 18.8 cps | 11 | 0 | yes | 0 |
| English | German | 105 | 42 | 2 | 1.1 s | 23.7 cps | 72 | 16 | yes | 0 |
| English | Romanian | 101 | 42 | 2 | 1.02 s | 22.5 cps | 50 | 9 | yes | 0 |
| German | English | 95 | 42 | 2 | 0.98 s | 19.1 cps | 6 | 0 | yes | 0 |
| German | German | 105 | 42 | 2 | 1.01 s | 19.8 cps | 45 | 0 | yes | 0 |
| German | Romanian | 101 | 42 | 2 | 1.28 s | 20.0 cps | 23 | 0 | yes | 0 |
| Romanian | English | 95 | 42 | 2 | 1.13 s | 16.8 cps | 0 | 0 | yes | 0 |
| Romanian | German | 105 | 42 | 2 | 1.31 s | 19.4 cps | 15 | 0 | yes | 0 |
| Romanian | Romanian | 101 | 42 | 2 | 1.5 s | 16.5 cps | 0 | 0 | yes | 0 |

cps = characters per second. Common guidance: up to about 17 cps is comfortable and about 20 cps is the upper limit for adults. Same-language tracks stay within 20 cps. German and Romanian subtitles on the **English** video are the hardest case: the English voice is the fastest and the translations are longer, so some cues exceed 20 cps (16 German cues, max 23.7 cps; 9 Romanian cues, max 22.5 cps). These were left as full translations; condensing them would be the next step if needed.

## Slides and highlights

| Audio | Checks (3 per sentence) | Mismatches | Slide changes during speech |
|---|---|---|---|
| English | 168 | 0 | 0 of 7 |
| German | 168 | 0 | 0 of 7 |
| Romanian | 168 | 0 | 0 of 7 |

Each sentence was checked at its start, middle and end: the slide on screen and the highlighted region match what the sentence refers to, with the highlight fade completed. Slides change only in pauses between sentences.

## Translation

German and Romanian texts were reviewed against the English by an independent reviewer pass; 11 fixes were applied (8 German, 3 Romanian) for accuracy, idiom and consistent register (German "Sie", Romanian polite plural). Romanian uses comma-below ș/ț. A native-speaker read-through is still recommended before publication.

## Not verified

- Nobody has listened to the full narrations; the German and Romanian pronunciation of English terms (pronunciation hints) in particular should be checked by ear.
- The project page contents mentioned on slide 7 were not checked.