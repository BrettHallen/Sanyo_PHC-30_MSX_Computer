# Sanyo PHC-30 MSX Computer
Information about the 三洋 Sanyo PHC-30/PHC-30N computer.

![Sanyo PHC-30N](/Images/Sanyo_PHC-30N_Case_small.png)

## Specifications
- Sharp LH0080A Z80 CPU
- Fujitsu MB64H120 gate array (mask code Z03?)
- Mitsubishi M5L8255AP-5 peripheral interface (PPI)
- Hitachi HN613256P 32Kbit ROM (mask code Y00)
- General Instruments AY-3-8910 Programmable Sound Generator (PSG)
- 8 x Fujitsu MB8264A-15 64K x 1-bit main DRAM (64KB)
- TI TMS9118NL Video Display Processor (VDP)
- 2 x TI TMS4416-20NL 16K x 4-bit video DRAM (16KB)

## YouTube Videos
- [Part 1: Initial Look](https://youtu.be/X6lxfxol4aE)
- [Part 2: Pico9918 & Keyboard Refurbish](https://youtu.be/wInAnoi41x8)

## TMS9118 Replacement
I replaced the TMS9118 with a [Pico9918](https://github.com/visrealm/pico9918).  I had to de-solder the TMS9118 but it came out with a little gentle coaxing - I used my ENGINEER SS-03 Solder Sucker.<br>

There is one small issue: blank screen when doing a warm restart by pressing the RESET button but Troy has already sent me some test firmware to try out.<br>

## [Replacement Power Supply](/Sanyo_PHC-30_PSU)
My attempt at a "universal" 12VDC power supply to replace the original Japanese 100VAC power supply.<br>

The original power supply generates +5VDC and ±12VDC.<br>

My replacement generates the +5VDC and -12VDC via regulators and passes through the remaining 12VDC, so a good quality, regulated, 12VDC power supply rated at 3-4A should be used.<br>

It's currently pending testing.<br>

## [Images](/Images)
Images of the computer, motherboard & chips.
