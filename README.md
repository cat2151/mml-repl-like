# mml-repl-like

# DEMO
https://cat2151.github.io/mml-repl-like/

# twitter
https://twitter.com/cat2151/status/1394331295572922373

# Features
- A sound plays every time an MML character is typed.
  - Only the sound corresponding to the input character plays.
  - (In `chordArea`, the current line plays.)
- A sound plays when moving the cursor.
  - Only the sound at the current cursor position plays.
  - (When moving up/down in `chordArea`, the current line plays.)
- A sound plays with SHIFT + ENTER or CTRL + S.
  - The current line plays.
  - If a range is selected, only the sound within that range plays.
- Displays the MML currently being played.

# Use Cases
- When writing MML, you want to hear the sound immediately.
  - You want to hear the sound within 0.2 seconds of typing on the keyboard.
  - You want to play chords repeatedly by mashing SHIFT + ENTER.
- When writing phrases in MML:
  - You want to quickly iterate through the "play and modify" cycle.
- When writing chord progressions in MML:
  - You want to quickly iterate through the "play and modify" cycle.
  - You want to quickly play chord progressions by moving the cursor up and down.
- You want to write while transposing with the `kt` command.
  - You also want to transpose chords.
- You want to easily convert the generated MML into other MML formats using [mml-template-generator](https://cat2151.github.io/mml-template-generator/).

# Note
Since this is under development, a [forked version of Sionic.js](https://github.com/cat2151/sionicjs/) is being used.

---
Powered by [SiON](https://github.com/keim/SiON)
and [Sionic.js](https://github.com/minipop/sionicjs/)
and [pico.js](https://github.com/mohayonao/pico.js/)