# Sonic Unleashed PS2 Hacks

Here are some of my hacks made for Unleashed PS2 during a quick session of screwing around.

## TODO:

- figure out time scaling issues for 60FPS

- remap actions to other buttons

- port to other regions (currently only SLES-55380 PAL-E is supported)

- figure out UI scaling for widescreen -- partially done, needs a few finishing touches...

## Host filesystem usage

1. Ensure that you have "Enable Host Filesystem" enabled in your PCSX2 settings (or `EmuCore/HostFs` enabled in the PCSX2.ini)

2. Extract all of the data from the ISO

3. Rename the game executable to `serialnumber.elf`, e.g. `SLES-55380.elf`

4. Move everything from PS2ROOT to the root directory (next to the ELF)

5. Launch the game by using "Start File" option and selecting the elf

6. Go to "Game Properties" and enable the cheat `Use Host Interface (HTCI)` (NOTE: if you do not see cheats - make sure your pnach filename has no serial number and ONLY the CRC, just like in the repo)

7. Reset


