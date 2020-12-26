# Projet PureData ATIAM 2020

## Requirements
### Hardware
- MIDI Keyboard _(Tested with AKAI-LPK25)_
- Microphone _(Tested with ZOOM-H1)_
- (Optional) MIDI Controller _(Tested with KORG-NanoKontrol2)_

### Externals
- freeverb~[v1.2.3]


## Description
- Instructions in blue canvases are stuff that must be done to launch the patch 
- Components in purple canvases are stuff that can be manipulated
- Text in red canvases are the compulsory items of the subject
- (Optional) Stuff in pink canvases are related to the MIDI controller

Some things can be improved :
- A bug remains if the patch is not triggered with the bang twice (else, the bass and the drums are out of time) : it seems to be a problem in the initialization of the step sequencers...

## Timeline _record.wav_
0:00 > Glockenspiel samples played in a step sequencer  
0:09 > Bass : triangle oscillator in a step sequencer connected to amplitude modulation   
0:25 > Melody with random pitch and rhythm  
0:41 -  1:05 > Drums (kick, side stick, hi-hat) samples played in a step sequencer connected to a VCF   
1:13 > MIDI Keyboard connected to a delay effect  
1:53 > Out of tune external recording of a violin connected to a reverb effect   
2:41 > Change feedback gain of the delay effect  
3:01 > Bypass delay effect  
3:37 - 3:53 > Drop of cut frequency of the VCF connected to the drums
