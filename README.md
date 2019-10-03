# Anycubic I3 MEGA (S) Custom G-Code
A collection of personal GCode variations to be used on Anycubic I3 Mega (S) 3D Printer. There are also a couple of "beeper tones" inside.

"Start G-Code" also contains a custom nozzle-wipe sequence, mostly usefull if you print a lot with high viscosity materials (ABS, PETG) or with special filaments that may need a good priming.

***On my machine I am using a custom gantry and a semi-custom plate with fixxed height***

The *Start G-Code* should be valid for any configuration, but just to be sure check the following command:
`G1 X5 Y5 F600`

The absolute movement should be fine for any buildplate, *even if your gantry slightly changes the limit switch position.*

(I have a -0.5mm difference on X-axis)

**Temperatures are not included** in those scripts: the Nozzle Temperature and the Buildplate Temperature will be set accordingly to your own project/slicer/setting.
I have done so in order to use the same "wipe" function for each of my prints, letting the slicer take care of setting the temperatures depending on material profile.

## Having fun with Beeper Tones

This part is mostly for fun, altough having a *"custom tune"* to play when the print is finished really helps if you have your printer in another room and/or if you are doing some test prints without remote control (ie. Octoprint).

***I don't reccomend using full-version theme tunes because they take too lonk to play and put some stress on the beeper***

### Tools & Credits

- http://ddrboxman.github.io/RepRapRingtone/

This is a wonderful tool both to *preview* your tune code and to *convert rtttl notation* into GCode M300 notation.

- http://arcadetones.emuunlim.com/ringtones_r/

Some RTTL files of well-know theme songs / intro / credit music.
