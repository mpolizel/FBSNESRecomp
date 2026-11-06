# Changelog

## 0.1.0 — 2026-11-06

First release: a setup pack that recompiles the game from your own ROM. Boots
through the Delphine and U.S. Gold logos, the opening cutscenes and the title
screen into the levels, at full speed; checked against snes9x with the same
input (same pictures, same pace). The cartridge has no battery: the game gives
passwords, and save states are kept in `build\saves\`. A fresh install starts
with no shader (the plain picture); scanline, CRT and upscaler presets
(ScaleFX, NNEDI3) are in Settings → Shader. Settings during play (Ctrl+L or
Select+L3), and a setting that needs a restart comes back to the same moment;
audio interpolation (I key: Gaussian, Cubic, Sinc); update check on start that
backs up your saves before installing; asks for the dedicated graphics card
on laptops with two; console-free Windows build.

The game keeps the console's speed (60 frames per second) through the
polygon cutscenes, where the host used to fall about 2% behind.

It ships with every framework fix of the earlier ports (see README → Framework
patches), so the problems found there do not come back here.
