You are editing the dialogue of an existing video with Higgsfield. This is a word-swap edit, not a new generation: the output must look and sound like the original clip, with only the listed words changed and the burned-in caption removed.

## Input
- `lockemup_tiktok_cut.mp4`: vertical 576x1024, 30 fps, 36.57 s, two speakers.
  - The old man in the white pickup is on camera.
  - The guy filming is behind the camera and mostly off-screen.

## What to change (15 swaps, times in the clip)

| # | Time | Original | Replace with |
|---|---|---|---|
| 1 | 0:03.6 | Trey Taylor | Sony |
| 2 | 0:04.6 | Trey Taylor | Sony |
| 3 | 0:05.5 | Crewe Tractor | PlayStation |
| 4 | 0:06.5 | Crewe Tractor | PlayStation |
| 5 | 0:09.7 | fish | play GTA 6 |
| 6 | 0:11.4 | state | PC |
| 7 | 0:13.3 | state | PC |
| 8 | 0:15.5 | state | PC |
| 9 | 0:16.9 | Hit the road | Alt-F4 |
| 10 | 0:18.7 | state | PC |
| 11 | 0:19.8 | private | PlayStation |
| 12 | 0:27.1 | state | PC |
| 13 | 0:28.7 | Hubert | Cyber |
| 14 | 0:30.8 | Jones | Leek |
| 15 | 0:31.7 | Hubert Jones | Cyber Leek |

"PC" is read as "P-C", "Alt-F4" as "alt F four" and "GTA 6" as "G-T-A six".

Swap 5 adds four syllables. Re-time that whole line ("Who told you you could play GTA 6 here?") so it fits between 0:08.2 and 0:10.7. The old man drags out "who told" in the original, which leaves room. The next line must still start on time.

## What to remove
The burned-in caption **"POV -Grandpa kicks me out my fishing spot"**:
- two lines of white text with a soft shadow, centered,
- about 60-68% of the way down the frame (roughly y 610-690 of 1024),
- on screen for the whole clip.

Remove it from every frame. The area behind it (the truck door, grass and the old man's hand when it passes) must look natural, with no blur patch, smear or flicker.

## Full edited dialogue (for any tool that wants the whole transcript)
You got permission? / Yeah. Oh. / Written permission from Sony. / Sony? / PlayStation. / Oh, PlayStation. / Yeah. Who told you you could play GTA 6 here? / I thought it was PC property. / PC? / Yeah. / This? / Yeah. / PC? / It ain't. / Alt-F4, dude. / This ain't no PC property. / This is PlayStation property. / Oh, okay. / What is your name? I want your name. / I can call down and see who gave you permission. / My name? PC property. / My name, Cyber. / Last name? / Leek. / Cyber Leek. / Yeah. / I ain't never heard that before in my life.

## Rules
1. Keep each speaker's own voice. Clone it from this clip and match its tone, energy and the outdoor room sound.
2. Lip-sync only where the speaker's mouth is on screen. Off-screen lines are an audio-only swap.
3. Everything that isn't a swap or the caption removal stays untouched: picture, framing, background noise, other words and timing.
4. Keep the length at 36.57 s and the format at 576x1024 9:16. Don't shift anything after a swap. If a new word is longer (state to PC, private to PlayStation), fit it inside the original word's slot plus the pause after it.
5. No added captions, music, watermarks, filters or upscaling.

## How to do it
1. Check which Higgsfield tools are available: lip-sync, dialogue or voice edit, voice clone, and text or object removal (inpainting). Prefer tools that edit existing footage over ones that generate new video.
   - Remove the caption first, so the lip-sync runs on the clean video.
   - If Higgsfield has no text-removal tool, say so. Don't crop or blur the caption away.
2. If no tool can replace single words in place, do it in parts:
   - generate the 15 new words in each speaker's cloned voice,
   - splice them into the original audio at the times above,
   - run lip-sync only on the on-screen stretches that changed.
3. Before spending any credits, tell the human which tool and model you'll use and the estimated cost, and wait for an OK.
4. Check the result before handing it over:
   - transcribe the output and confirm all 15 swaps are there and nothing else changed,
   - confirm the length is 36.57 s and the size is 576x1024,
   - watch the on-screen swaps for lip-sync errors,
   - scrub the whole clip to confirm the caption is gone and leaves no smear or flicker.

## Output
`lockemup_playstation_property.mp4`, plus a short note on which tools were used and any swap that didn't come out clean.
