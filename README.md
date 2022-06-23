# ArduinoMidiCV

This is a quick and dirty script to read Midi commands via an arduino and output a control voltage to analog synthesizers using digital potentiometers. It could definitely be optimized but I really just wanted a quick proof-of-concept and never really returned to this project. If I were to return, I would definitely use DAC's instead of digi-pots and I would make the DAC's 12-16 bit in order to raise the resolution and potentially be able to control pitch. 

As it stands, the digi-pots I used are 8 bit, and therefore only have a resolution of 256. This is adequate for midi-cc signals as they are 7bit, but is definitely not enough to output a controlled voltage precise enough to use for pitch. Maybe I'll return to this one day...
