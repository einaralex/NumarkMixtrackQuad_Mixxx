NumarkMixtrackQuad_Mixxx
========================

Mixxx v11.1.0 mapper for Numark Mixtrack Quad 

This is a work in progress.

Add these files to 
`Applications/Mixxx.app/Contents/Resources/controllers`

What should be working.
---------------
- **2 channels only!**
-	Library Browse knob + Load A/B
-	Channel volume, cross fader, cue gain / mix, Master gain, filters, pitch and pitch bend
- 	JogWheel  (Only standard LED)
-  Scratch/CD mode toggle (kinda)
-	Headphone output toggle 
-	Play, Sync, Cue
-	Samples, only 4, each channel triggers the same samples
-	HotCues
    - (1-3) Hot cue
    - (4) Deletes hot cues
-	Loops
    - (1) Loop in
    - (2) Loop out
    - (3) Re-loop
    - (4) Loop halves
        - When loop is not active it toggles Quantize


 Not working and to do:
 ------------
- Pitch is inverted, up(-) is +bpm and down(+) is -bpm

  - Fix:    `Preferences > Interface > Pitch/Rate slider direction > Down increases speed`
-  Effects
-  Stutter
-  Shift + Sync, pads, keylock etc.
-  LED
-  Pitch Bend on outer jogwheel
-  4 decks? 16 samples?
-  Redo/Clean up code, some features are already available.
-  More?
