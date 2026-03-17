# Releases

## 0.9 - 17-03-2026
- Dual MIDI support enabled by default (USB + Serial)
- Added pitch control from a second MIDI channel (rotary channel + 1) using SC-02 pitch table
- Extended phoneme note range from 93 to 103

## 0.08 - 30-06-2024
- Disabled the randomization on P5
- Improved handling of phonemes in CV mode (Sound)

## 0.07 - 11-08-2021
- CC3 to control rate (7-bit value)

## 0.06b - 11-09-2020
- LED intensity is driven by Note Velocity

## 0.06 - 24-07-2020
- Added MIDI CC #2 to control Inflection/Pitch

## 0.05 - 08-04-2020
- Added CV controls: P1 master clock / P2 inflection / P3 filter frequency / P4 rate
- Added MIDI channel chooser via the rotary knob

## 0.04 - 05-04-2020
- Hack to avoid occasional carrier noise when external carrier is used

## 0.03 - 07-03-0220
- Update via SD card, external carrier via CC sustain or front panel switch (mid-low position)

## 0.02 - 20-10-2019
- MIDI clock available on Busy jack

## 0.01 - 22-06-2019
- Initial release



# MIDI controls
- MIDI note ON/OFF mapped to the SC02 phonemes
- Velocity
- Pitch
- Mod Wheel mapped to filter
- CC 64 sustain ON/OFF to choose between internal and external carrier

The MIDI clock is available on the Busy jack.

# Gate
Triggers the phoneme.

# CV controls
## P1
Master clock pitch control

## P2
Inflection

## P3
Filter frequency

## P4
Rate

## P5
Phoneme randomization

## SOUND
Phoneme

# Rotary
## Push
Activate/deactivate CV controls.

# Switch
- Upper position: Not used
- Middle position: external carrier
- Lower position: internal carrier