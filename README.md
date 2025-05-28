# Comparison of OXI One, Squarp Hapax, Synthstrom Deluge, Torso T-1and MidiPhy Seq v4+ as MIDI Sequencers

(This is maintained at both [OXI One versus Hapax vs T1 vs Deluge](https://docs.google.com/document/d/1etLnCeL0BIIc-4HeFqp3lRIB2nNKVJaVp3NsHARar3Q/edit?usp=sharing) and [https://github.com/gramster/sequencers](https://github.com/gramster/sequencers). I added the Github page to help discoverability, but the document should be considered the definitive copy, as it is easier to maintain and take suggestions this way).

I have never seen a head-to-head comparison video of these, so created this table and welcome feedback to keep it current.

I have owned all these devices at different points as I searched for the best fit for me. I still own a Deluge and had an Oxi One, but that just recently got stolen/”lost in the mail” after I sent it to a friend to try out. ☹️*By June 2025 there will be a new Oxi One mkII shipping, so I will attempt to update this, but at $899 I don’t think I can personally justify buying one so will rely on input from others. Unless Oxi wants to give me a discount ;-).*

Tl;dr recommendations:

- If you want a portable battery-powered sequencer with lots of live and generative features, the Oxi One is the best option (especially when paired with an iPad). The Oxi is also the only one that can be driven from MIDI as a control surface (versus as a sequencer), allowing you to create your own custom use cases (something that Driven by Moss takes advantage of; see [OXI One \- New Sequencers and more for Bitwig and Reaper\!](https://youtu.be/buUjbQ6TYzk?si=CwvKmVYgS9Q1Do1y)). It strikes a great balance between all of these and the compact form factor, built-in battery and Bluetooth support provide a lot of flexibility. The main drawback is the number of button press combinations needed for all the functionality that has been added (an age-old problem the Deluge suffers from too), but the mk2 should help with that. The mk2 also makes the Oxi provide stiff competition to the more powerful Hapax and MidiPhy Seq v4+.  
- If you are interested in generative music and live performance tweaking, all of these are good, but IMO the T-1 is the most immediate and fun; it's very deep though and requires an investment to learn. I would watch some videos and think carefully before buying it as a general purpose sequencer.  
- If you want a complete portable audio/MIDI workstation, not just a sequencer, the Deluge is it. It’s the most limited in terms of MIDI effects and live or generative MIDI fun (although the community firmware team is working to improve that), but its the most capable if you just want to sequence many long sequences due to its unlimited number of tracks and track length.  
- If you want a rock solid sequencer for leaving in the studio and composing/arranging, the Hapax or MidiPhy Seq v4+ are probably the best choice, although the Oxi Mk2 should now be a contender. The Hapax is unquestionably the easiest to learn IMO, due to the dual displays and multiple encoders for setting parameters that clearly convey most of your options at any moment. It’s a sequencer that almost anyone can figure out the basics of immediately without a manual. The pads are stiff though, and not great for real-time.  
- The MidiPhy Seq v4+ is very deep and arguably the most powerful (there are several things the MidiPhy Seq has that the others don’t that are not in the table), although it is limited in track count to 16, and if you want free-form polyphony (versus canned chords, although it has many of those) you need to allocate one track per simultaneous note. It also has a rather different way of doing things, using sequencing “layers”, up to 24 per track, with each property (note, gate, probability, etc…) sequenced on a separate layer. The DIY nature of the sequencer and its someone dated UX may be off putting to some. It’s most comparable to the Cirklon (but more affordable if you discount the labor costs you put in), although I have never owned a Cirklon so it’s not included in this table.

| Feature | [Oxi One](https://oxiinstruments.com/oxi-one/) | [Hapax](https://squarp.net/hapax/) | [Deluge](https://synthstrom.com/product/deluge/) | [Torso T-1](https://torsoelectronics.com/pages/t-1) | [Midiphy Seq v4+](https://www.midiphy.com/en/mbseq-v4-/) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Inputs | 1 x MIDI TRS A,1xCLK/CV in | 1× MIDI DIN, 1x MIDI TRS2× CV inStereo pedal (footswitch), MIDI USB | 1 x MIDI DIN, CLK IN, USB MIDI | 1xMIDI TRS, 1xCLK, 1xRST, 1xCV MOD, USB C | 4 x DIN, USB MIDI |
| Outputs | 1 x MIDI TRS (3xDIN with Split at x3 bandwidth) 8 CVs, 8 gates CLK, MIDI USB | 3× MIDI DIN, 1 x MIDI TRS),4 CVs, 4 gates, MIDI USB | 1 x MIDI DIN, 2xCV, 4xGATE, CLK OUT, USB MIDI | 1xTRS MIDI OUT/THRU, 4xCV, 2xgate, 1xCLK, 1xRST, USB C | 8 x DIN, USB MIDI |
| MIDI BLE Support built in | Yes | No | No | No | No |
| Ableton Link Support | No | No | No | Yes | No |
| MIDI Instrument Definitions | \~50 included (fixed in firmware)  | Must be added by user to SD card. There are some in support forum. | Not yet [https://github.com/SynthstromAudible/DelugeFirmware/issues/1056](https://github.com/SynthstromAudible/DelugeFirmware/issues/1056)  | No | No |
| Open Source | No | No | Yes | No | Yes |
| USB Host Support | Yes | Yes | Yes | No | Yes (limited) |
| SD Card | Yes (mkII only) | Yes | Yes | No | Yes |
| CPU | ? | 2xARM | Renesas RZ/A1L  (ARM Cortex A9 @ 400Mhz) | ESP32 | STM32F4 (ARM Cortex M4 single core @168MHz) |
| RAM | ? | 32MB | 64MB | ? | 64MB |
| Dual Project Support | No, but projects load fast so may not matter. | Yes | No, but projects load fast | No | No |
| Per-step polyphony | 7 voices, 4 CCs | 12+ | Unlimited | 8 | 6 with chord sequencing |
| Max tracks | Mk1: 32 limited-functionality monophonic or 4 full-functionality polyphonic. (There are 4 “sequencers” which can be configured as polyphonic, drum tracks, or 8 limited-functionality monophonic tracks \-  some properties like the arpeggiator are per-sequencer, not per track) Doubled on mkII | 32 polyphonic (16 full polyphonic per project; can play two projects simultaneously for 32\) | Unlimited | 16 | 16 |
| Velocity-sensitive pads | No | No | No | No | No |
| Pad feel (softer is easier to play live) | Medium | Stiff | Soft | Medium | Computer keys |
| Live Modes | Notes/Drums or  Chords. 4 or 5 offset isomorphic and classic layouts available.  | Notes/Drums or, Chords. 0-8, 12, 16 adjustable isomorphic layout. | Notes/Drums. Adjustable isomorphic layout. | Arguably the whole thing is a live instrument | Every parameter can be tweaked in live mode |
| Step Modes | Multitrack, Mono, Poly, Chord, Stochastic, Matriceal | Poly, Drums, MPE | Drums, Poly, Chord | Can combine dynamic generative notes with manually-entered Poly. | Drums, Poly, Chord |
| Max Projects | 15 (but can be saved to PC) | Unlimited | Unlimited | 16 banks (of 16 tracks with 16 patterns each). | Unlimited |
| Song Mode | Yes | Yes, with named sections | Yes |  | Yes |
| Patterns per Project | 64 | 16 (x16 tracks) | Unlimited | 16 (x16 tracks) | 256 |
| Voices per Track | 8 (drums), 7 (polyphonic) | 8 (drums), 15? (polyphonic) | Unlimited |  | 1 on note tracks Up to 6 on chord tracks ? on drum tracks |
| Max pattern steps | 128 steps | 512 steps | Unlimited | 64 steps | 256 |
| Velocity View | Yes | Yes | Yes (with community firmware) | No | Yes |
| Pattern play modes | Forward, reverse, pingpong, random, drunk | Forward, reverse, pingpong, random | Forward, reverse, pingpong | Forward only, but with way deeper control than most of the others | Forward/Backward/PingPong/Pendulum/Random Dir/Random Step |
| Graphic display of full pattern piano roll | No | Yes | No | No | No |
| Loop Points | Full fledged Looper | Yes | Yes | Yes | Yes |
| Conditionals | Yes | Yes | Yes | No | Yes |
| Probability |  In N   | Yes | Yes | Yes | Yes |
| Repeats | Yes | Yes | Yes | Yes | Yes |
| MIDI CC Automation | Yes (4-8 Mod Lanes/Seq) | Yes (Comprehensive Automation) | Yes (Parameter Locks) | Limited (Filter Prob via Vel knob) | Yes (Parameter Layers) |
| Probability (Note-on) | Yes ("Prob") | Yes ("Chance") | No | No (Filter Prob only) | Yes (Parameter Layer / Random Gate) |
| Conditional Triggers / Logic | Yes (Extensive Logic Conditions) | Yes ("Conditional Trigs") | No | No | Limited (Implied by Random Gate/Val) |
| Ratcheting / Repeats / Roll | Yes ("Retrigger") | Yes ("Roll") | No | Yes (Repeats, Offset, Time, Pace) | Yes (Roll Layer / Roll Trigger) |
| Micro-Timing / Nudge | Yes ("Timing Offset") | Yes ("uTime") | Limited (Swing effect) | Yes ("Timing" knob for swing/offset) | Yes (Groove Templates/Humanizer) |
| Swing | Yes (Track Level, affects steps) | Yes (Track Level, affects steps) | Yes (Track Level, affects steps) | Yes (Track Level, affects steps) | Yes (Groove Styles/Templates) |
| Glide / Portamento (MIDI Out) | No (CV Only for dedicated Glide) | Yes (via Pitchbend Automation) | No (Internal Synth only) | No | Yes (Glide Trigger / Layers) |
| Glide / Portamento (CV Out Only) | Yes | N/A (Focus on MIDI features) | N/A | N/A | Yes (CV outputs can be configured) |
| Note Offset / Per-Step Transpose | Limited (Track param in some modes) | No (Track Transpose or automation) | No | Yes ("Rotate" for pattern phase) | Yes (Note Layer manipulation) |
| Per-Step LFO Modulation | Yes (via Mod Lanes targeting LFOs if present) | Yes (Automate LFO params) | No | Yes (LFO on Note Range) | Yes (LFO Fx assignable per step) |
| Per-Step Aftertouch | Yes (Mod Lanes) | Yes (Automation) | No | No | Yes (Parameter Layers) |
| Per-Step Pitchbend | Yes (Mod Lanes) | Yes (Automation) | No | No | Yes (Parameter Layers) |
| Per-Step NRPN | No | Yes (Automation) | No | No | Yes (Parameter Layers, if supported) |
| Per-Step Program Change | Yes (Mod Lanes) | Yes (Automation) | No | No | Limited (Likely via CC or SysEx Layer) |
| Per-Step Skip / Step Mute | Yes ("Skip") | No (Track Mute) | No | No | Yes (Skip Trigger) |
| Per-Step Randomization (Params) | Yes (Various Randomize functions) | Yes ("Chance" for notes) | No | Yes ("Random" knob for any param) | Yes (Random Value Trigger / Humanizer) |
| Per-Step FX Param Modulation | N/A (No internal MIDI FX described) | Yes (MIDI FX params automatable) | N/A (Internal audio FX) | N/A (No internal MIDI FX described) | Yes (Echo Fx, LFO Fx params) |
| Chord-Specific Per-Step (Strum etc.) | Yes (Strum, Spread, Voicing, Type) | No | No | No | Yes (Multiple Chord Layer types) |
| Generative-Specific Per-Step | Yes (Stochastic/Matriceal/accumulator params) | Yes (Conditional Trigs) | No | Yes (Core design, various params) | Yes (Euclidean, Random Gens) |
| Groove Templates/Engines | Limited (Swing), New groove engine in mk2 | Limited (Swing) | Limited (Swing) | Limited (Swing) | Yes (Customizable Groove Templates) |
| Draw Automation using pads | Almost anything | CC, Pitchbend, Aftertouch, Program Change, NRPN, CC pair, CV, effect parameters | Yes (need details of which) | N/A | Yes, with Matrix accessory |
| Scales | \>30 | \>70 | 15? | 7 \+ 1 custom (per track) | 166 |
| Chord Mode Controls | Chord type, voicing, spread, bass  | Octave, voicing, spread,extended chords, bass drops. Four stackable modifiers. | ? | Voicing, spread | No, but it has about 200 predefined chords available. |
| Chord Recognition | No | Yes | No | No | No |
| Repeater/ratchet patterns | ? | ? | Yes |  | Yes, with editable config file |
| Live Generative Modes | Stochastic, Matriceal | None specifically but live playing on tracks with stacked MIDI effects can act as such. | ? | Everything can be tweaked live | Everything can be tweaked live  |
| Generative Algorithms | Euclidean, Drum pattern generator | Random,Curved,Symmetric (melodic) Euclidean (drums) | Euclidean | Euclidean | Euclidean, Random |
| LFOs | 8 (4 sequencers x 2). Can modulate almost anything. | 2 Global LFOs, plus as (un stackable) MIDI effects on tracks. | 2 per synth or per drum part | ? | Yes |
| LFO shapes |  |  |  | 8 | ? |
| Modulation lanes | 32 | 32?. There is a mod matrix MIDI effect that can be applied per track. | ? |  | 4 internal “bus” outputs that can be routed as inputs to other tracks |
| ARP Styles | “Many”. Note that each sequencer has one arp, so limited to 4 total. | Arps are per track stackable MIDI effects, so can have many | Arp is on synth presets, no sequencer arp | 6? | Custom |
| Tempo changes are sequenceable | ? | ? | ? | ? | Yes, with ramp control |
| Undo/Redo | Yes, 10 previous states | Yes, “many” | Unlimited | No | Undo |
| Snapshot/Revert | Yes | Yes | No | Yes | Yes, with live pattern load/save |
| MIDI Routing | Yes (USB/TRS/BLE/CV) | Yes? |  |  | Yes |
| Max Recording Resolution | Up to 24 ppqn? | Up to 192ppqn | 192 ppqn | 96 | 384ppqn |
| Latency Compensation | Yes, at sequencer level | Yes, at track level | No? |  | Yes |
| MPE Support | No | Yes | Yes | No | No |
| Auto-harmonize tracks | Yes | Yes | No | No | Yes (transpose \+force to scale) |
| MIDI Effects | Arp,Randomize,Swing, Rolll, Chance, Euclidean, Chord generator , Harmonizer, LFOs, Internal MIDI modulations | Arp, Chance,Echo,Euclid, Filter, Harmonize, LFO,Randomize, Scale, Swing, ArPoly, Register, Mono, Shapes. Chainable, and accessible with Mod Matrix | Maybe one day [https://github.com/SynthstromAudible/DelugeFirmware/discussions/466](https://github.com/SynthstromAudible/DelugeFirmware/discussions/466)  | Many | Echo, LFO, Pattern Morph, Transpose, Note Limit, Humanize/Robotocize, Force to Scale. |
| Import/Export MIDI | No | Yes | Yes | No? | Yes (can import while running) |
| Custom Control Mode | Yes | No | No | No | No, but sequencer can be controlled by MIDI |
| Accessories | [Oxi Split](https://oxiinstruments.com/product/oxi-split/), [Oxi Pipe](https://oxiinstruments.com/product/oxi-pipe/) |  |  |  | [Midiphy Matrix](https://www.midiphy.com/en/matrix/), various Eurorack modules |
| Dimensions | 36x13x3cm (mk1) | 36×21×6 cm | 31x21x5cm   | 31x12x4cm | 3U in 19” rack |
| Weight | 890g/950g | 1850g | 1500g | 815g | 3300g |
| Build quality | Full aluminum frame and knobs | Metal top with plastic case. | Metal with wooden sides | Metal | Metal |
| Power | 8 hour (2200mAh) battery, USB-C charging | 15v AC adapter | 6 hour battery, USB-B, 9-12v 500mA DC. User-replaceable (standard LiOn battery) | USB-C | USB-B |
| Display | Monochrome OLED 30x15mm | 2xGrayscale OLED 65x30mm each | Monochrome OLED | None; uses 16 pads for visual feedback | 2 x OLED |
| Price (direct) | 655€ (mk1) 819 € (mk2) | 1080€ (VAT excl.) | US$1400 | US$599 | DIY Kit; costs about 1000 euros in parts |
| Company Location | Spain | France | New Zealand | Denmark | Germany |

Comment: Live Input Quantization? Possible ? 

