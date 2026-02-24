# houdini-hips
A collection of Houdini hip files, examples, tech r&amp;d's, vex, all the good stuff...

## SOP
[Custom HUD](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/custom_hud.hiplc)

Using NDC (normalized device coordinates) to build a custom HUD with extended viewport info.

![](./thumbs/custom_hud.jpg)

[Fake volume lights](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/fake_volume_lights.hiplc)

Fake volume light using VEX, with support for omni and spherical area ligths, shadows, light samples (for area lights+shadows), shadow transparency, and a basic surface roughness model.

![](./thumbs/fake_volume_lights.gif)

[RBD cube bots](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/rbd_cube_bots.hiplc)

Motor based robot RBDs, scattered over surface, collide with each other.

![](./thumbs/rbd_cube_bots.gif)

## CHOP
[Audio visualizers](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/chop_audio_visualizers.zip)

Assorted audio visualizers: spectrum, waveform, audio volume / channels, frequencies.

![](./thumbs/chop_audio_visualizers.gif)

[Single audio visualizer, but many controls](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/single_audio_viz_many_controls.zip)

Audio viz with lots of controls.

![](./thumbs/single_audio_viz_many_controls.gif)

[Midi piano score](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/midi_piano_score.zip)

A piano score that animates to midi files, in the likes of guitar hero.

![](./thumbs/midi_piano_score.jpg)

[Midi impact balls sound gen](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/midi_impact_balls_sound_gen.zip)

Reads a midi file, generates rbd balls for each note, balls collide with a piano geo (it "plays" the music). The impacts are stored and transformed into a .wav file, as if the balls really played that song. 

![](./thumbs/midi_impact_balls_sound_gen.jpg)

## DOP
[Filament solver](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/filament_solver.hiplc)

Using the filament solver in DOPs for fake fluid looking ink sims.
Also, [YT video tutorial](https://www.youtube.com/watch?v=jm4mWT_WomE)

![](./thumbs/filament_solver.jpg)

## COP (legacy)

[Arcade/Retro games FX](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/arcade_cop.zip)

Retro game visuals with pixelization, palette reduction, layered tv glitches (scanlines/vignete/crop/running bars/etc) and blinking fonts.

![](./thumbs/arcade_cop.gif)

## Misc
[Pong game](https://github.com/fabriciochamon/houdini-hips/raw/refs/heads/main/hips/pong_game.hiplc)

A complete mini game with RBD based collisions, chop keyboard controls, logic for item power-ups, score, multi camera angles, ball split after N hits, game intro, etc. Backgrounds made in copernicus.

![](./thumbs/pong_game.gif)
