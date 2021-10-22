# OpenXTalk Apple AudioUnitMIDIInstrument

Experimental OXT Builder Module that binds to Apple's AVAudioUnitMIDIInstrument allowing the loading of arbitrary Music Device AU Plug-ins such as Apple's DLSSynth and many others.

Version 0.1:
Built off of my OXT Apple AVAudioSampler project, this one retrieves a list of all Music Device AU Plugs available in the system and allows loading for sending MIDI commands, retreaval of standards Factory Presets property presets (if any) and the ability to load preset files into the AU Plug. Currently most Audio Unit graphical user interfaces can be opened in a window (generated on the fly), but this is still slightly unstable at the moment.
