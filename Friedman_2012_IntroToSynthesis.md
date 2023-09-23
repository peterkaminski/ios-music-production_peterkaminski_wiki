# Friedman_2012_IntroToSynthesis  

These are a set of notes taken by [[Bill Anderson]] in 2017 whilst watching a three-part introduction to synthesis by Dean Friedman. The videos were uploaded to YouTube in 2012, but they are from early days on electronic music synthesis (circa 1986).

A link to the entire Introduction to Synthesis videos is here: <https://www.matrixsynth.com/2012/01/intro-to-synthesis-part-1-building.html> (accessed: 2023-09-23)
## Introductions to Synthesis 3-1 Part 1
 - Intro to Synthesis Part 1 - the building blocks of sound & synthesis Dean Friedman
 - Published on YouTube Jan 4 2012  <www.youtube.com/watch?v=atvtBE6t48M>  (accessed: 2023-09-23)  

```
05:12 Basic Terminology
08:00 3 Elements of Sound 08:20 Pitch
10:01 Timbre
10:45 Harmonics
14:57 *
16:40 Filter Cutoff/Timbre 18:08 Volume
21:53 5 most common Waveforms 
22:11 Square Wave
23:21 Sawtooth Wave
23:56 Triangle Wave
24:59 Pulse Wave
27:21 Sine Wave
28:48 *Waveforms as Modulators
30:47 7 Components of Synth 
32:11 Amplifier
32:43 Oscillator
34:18 Filter
18:53 36:37 Volume Envelope 
39:06 Filter Envelope
39:56 Pitch envelope
40:42 *Corresponding Components* 
41:54 LFO
44:41 DEMO 
52:05 Review
```
WLA Notes 2017-12-08

1. Sound - all sound is vibration 

2. 3 Elements of sound:  
   Pitch  
   Timbre  
   Volume  
   
3. 5 most common waveforms:  
	Square  
	Sawtooth  
	Triangle  
	Pulse  
	Sine  
	
4. 7 main components of a synthesizer:  
   Oscillator  
   Amplifier  
   Filter  
   Volume Envelope  
   Filter Envelope  
   Pitch Envelope  
   LFO  
   
VIBRATIONS  

Synth: controlling vibrations  

Cycle = unit of vibration  
Frequency = speed of vibration  
HERTZ = cycles per second  
KILOHERTZ = 1,000 Hertz  

Human audible frequency range: 20Hz - 20KHz  

#### THREE ELEMENTS of SOUND  

- PITCH: musical term for frequency (Synth oscillator controls pitch)  

- TIMBRE: unique character, tone of a sound

- HARMONICS:  
	 most sounds are composite sounds  
	 fundamental + harmonics (overtones, partials)  
	 sound harmonic spectrum  
	
	 pitched instruments vs. non-pitched instruments (e.g., saxophone
	vs. drums)  

	 e.g., bell: short attack, long release  
		dissonant harmonics  

	 Filters are how to add and subtract harmonics  
	 Upper harmonics - brighter  
	 Lower harmonics - darker  
	
- VOLUME: overall sound shape  
	 different sounds have different shapes  
	 volume envelope  
	
#### FIVE MOST COMMON WAVEFORMS  

- SQUAREWAVE: instant on, instant off  

- SAWTOOTH: instant on, gradual off  

- TRIANGLE: gradual on, instant off  

- PULSE: instant on, instant off (Squarewave with a variable ratio)  

- SINE: single pure frequency  

 Modulation: applying one waveform to another

#### SEVEN MAIN COMPONENTS OF A SYNTHESIZER  

- AMPLIFIER (controls volume)  

- OSCILLATOR (OSC, VCO) (controls pitch)  

- FILTER (VCF, DCF) (controls harmonic content - timbre)  

- VOLUME ENVELOPE (instructions about rates and levels over time)  
	 Attack, Decay, Sustain, Release  
	
- FILTER ENVELOPE (shape for brightness; harmonic envelope)  

- PITCH ENVELOPE (shape for pitch)  

- LFO (Low Frequency Oscillator) (make things wiggle)  
	- lower than audible range  
	- used as a modulator  
	- frequency modulation - vibrato  
	- amplitude modulation - tremolo  
	- filter modulation  
	- pulse modulation  

#### DEMO  
 - Choose waveform in oscillator  
 - Designed a volume env - shape for sound  
 - Designed a filter env - brightness shape  
 - LFO - using a triangle wave as a modulator on the pulse wave  
 

## Introduction to Synthesis - Part 2
	- types of synthesis & programming Dean Friedman

```
2:22 The Different Kinds of Synths 
4:40 Additive
5:41 Subtractive
6:29 FM (Frequency Modulation) 
7:38 Phase Distortion
7:47 Samplers 
9:00 Hybrids
12:34 Amplifier (DCA)
16:51 Oscillator (OSC, Freq) 
25:35 Filter
28:14 Resonance
30:10 Envelope Amount 
31:39 Modulator
34:08 Volume Envelope 
35:11 37:56 41:06 ADSR 
46:27 29:01 Filter Envelope 
48:50 Pitch Envelope
51:44 LFO
55:46 LFO Sync
```

DIFFERENT KINDS OF SYNTHS  

 - all have volume envelope   
 - all have a way to change the shape of a sound  
 - all have LFO  

ANALOG - prior to computer tech  
 raw current vibrating oscillator directly to speaker  
 
DIGITAL  
 sound generated via software or microprocessor  
 
 A or D: How is the sound originally generated?

ADDITIVE / SUBTRACTIVE  

 Additive synth: add individual sine ways to create a harmonic spectrum  
 very precise - need a separate oscillator for each note  

 Subtractive synth: generate a single waveform rich in harmonics then filter 
 - subtract harmonics  

FM Frequency Modulation
 - modulate frequency of one sine wave with the frequency of another sine wave  
   yields a complex waveform rich in harmonics  

Phase Distortion - related to FM  

SAMPLERS: make digital recordings of real sounds  
 - play back from a keyboard  
 - all have volume envelope & LFO (& filter)  

HYBRIDS  
 - use complex digital stored wavetables (samples) as source material
 (other than simple waveforms)  
	 Linear Algorithmic (LA) synthesis  
	 
## 7 COMPONENTS of a SYNTH  

 Amplifier - loudness  
 Oscillator - pitch  
 Filter - brightness / timbre  
 Volume Envelope - w/ the amplifier modifies shape of sound over time  
 Filter Envelope - w/ the filter modifies shape of sound harmonic content over time  
 Pitch Envelope - w/ the oscillator modified shape of sound pitch over time LFO - wiggles the sound (vibrato or tremolo)  

### AMPLIFIER  
controls loudness / volume / level  
control relative levels between different oscillators  

### OSCILLATOR  
	VCO, DCO, OSC, Frequency  
	control relative levels between different oscillators  

	width of pulse wave  
	(also called duty cycle)  
	Octave / Semitones / Fine tuning  
	
	D50 Master (Soundquest) Voice editing software  
	- edit voice architecture (structure?)

	chorusing / de-tuning: create more distinctive sound

	intelligent choices made on source material prior to any other modifications

### FILTER (VCF)
	controls harmonic content of a sound; overall brightness

	CUTOFF control: cut-off point (frequency) at which the filter cuts off harmonics (closed - dull; open - bright)

	RESONANCE: exaggerate harmonic frequencies around cutoff point

	ENVELOPE AMOUNT: degree to which filter envelope affects the sound (cutoff point of the filter)  
		(Envelope Generator (EG) intensity; Envelope amount / depth / intensity)

	Filters controls by removing or replacing the upper portions of harmonic spectrum (SUBTRACTIVE)

	MODULATOR [FM Synths]
	- Controls the harmonic content of the sound; the timbre of the sound

	ADDITIVE: changes harmonics by adding harmonics to a sound  

	Frequency Modulation (FM): one waveform modulates another waveform => complex waveform
		(like multiplication)

controls loudness / volume / level


### VOLUME ENVELOPE

	ADSR - Attack Decay Sustain Release  
	  (Peak - max volume; located between Attack and Decay)

	Increase attack: sound begins gradually  
	Decrease attack: sound begins suddenly 

	Attack: rate control; speed sound takes from 0 level to peak level
	(cannot be adjusted)  
	Decay: rate control: speed sound level travels from peak to sustain  
	Sustain: volume level the sound will remain at while key is held down (only variable level)  
	Release: rate control: speed sound takes to travel from sustain to 0 level  

	ENVELOPE shape   

	![[ENVELOPE.png]]  


	ENVELOPE Rates and Levels  
	
	![[ENVELOPE-ratesLevels.png]]  
		
### FILTER ENVELOPE
	(Harmonic Envelope)  
	ADSR Controls the shape of a sound's brightness (timbre) over time

	Filter Envelope is superimposed over the Volume Envelope

### PITCH ENVELOPE
	Controls direction of the sound's pitch
	(usually easy to hear pitch level changes and rates)
	Slide up, down, up & down

### LFO: LOW FREQUENCY OSCILLATOR  
	"wiggles" the sound (modulates)  
	sends a continuously repeating vibration to some aspect of the sound (the volume, timbre, or pitch)

	Control Level (amount / intensity)  
		Frequency (rate/speed)
		Waveform (triangle, sawtooth, square, sine, noise(random))  
		
		- route LFO to modulate the amplifier - amplitude modulation -  "tremolo"  
		- route LFO to modulate the oscillator - frequency modulation - "vibrato"  
		- route LFO to modulate the filter - filter modulation  
		- possible to route LFO to modulate the width of the Pulse Wave  
		- LFO SYNC: Off/On


## Introductions to Synthesis - Part 3
 - Additional Synth Features, Performance Controls, & Wrap Up
<https://www.youtube.com/watch?v=zK3m8sMkTE4>

```
	02:28 Noise
	04:44 Sync
	08:00 Amplitude (Cross) Modulation
	Performance Controls / Controllers
	11:25 Pitch Bend wheel
	13:28 Modulation Wheel
	16:20 Velocity Sensitivity
	21:22 24:13 Aftertouch
	26:53 28:24 Keyboard Tracking [key tracking / scaling / follow] 
	29:15 DEMO #1
	32:18 * 32:57 34:24 DEMO #2 Attack Vol Env/Frequency LFO 
	34:45 39:13 DEMO #3 Rate & Sustain Vol Env/Frequency LFO 
	40:00 48:01 DEMO #4 Filter Env/Vol Env/LFO
	48:55 DEMO #5
	50:30 54:11 DEMO #6 LFO/Detune
	55:27 DEMO #7
```

	Synths used in demos
	Roland D50 
	Casio CZ 
	Roland DX7 
	Korg M1 
	Ensonic SQ80

	NOISE 
	
	SYNC
                         
## Modular Synth Basics (The Tuesday Night Machines)  

### Modular Synth Basics #04: Simple synth voice patch  
 <https://youtu.be/lJ0M9b4mRNc>

Our first patch! A simple synth voice, like in a non-modular synthesizer. EXPAND FOR MORE INFOS 
	
**PATCH NOTES:**
	
	VCO = Voltage Controlled Oscillator (creates audible waves)  
	VCF = Voltage Controlled Filter (removes frequencies from audio)  
	VCA = Voltage Controlled Amplifier (controls a signals volume/amplitude)  
	ADSR = Attack Decay Sustain Release Envelope Generator (creates a 4- stage CV envelope when triggered)  
	LFO = Low Frequency Oscillator (creates very slow inaudible waves, used as CV)  

	Audio Signal Routing:  
	VCO waveform output to VCF audio input  
	VCF Low Pass output to VCA audio input  
	VCA audio output to Mixer input  
	Mixer output to Audio Recorder input  

	Control Voltage (CV) Signal Routing:  
	MIDI-CV Gate output to ADSR Gate input  
	ADSR Envelope output to VCA CV input  
	MIDI-CV Pitch CV output to VCO 1V/Oct input  
	LFO output to VCF Frequency CV input  
	
   ==============================================

	VCO > Mixer
	VCO > VCF > Mixer
	VCO > VCF > VCA > Mixer

	MIDI-CV Gate > VCA | MIDI-CV PitchCV > VCO  
	MIDI-CV Gate > ADSR > VCA | MIDI-CV PitchCV > VCO  
	MIDI-CV Gate > ADSR > VCA | MIDI-CV PitchCV > VCO | LFO > VCF  

### Modular Synth Basics #02: CV, Gate, Trigger, MIDI  
	https://youtu.be/7TcHzHhjzs8

	Terminology

	- Gate = high voltage over time

	- Trigger = short voltage spike

	- Pitch CV = variable CV to control 1V/Octave Oscillators

### Modular Synth Basics #03: How to start?  
	https://youtu.be/Q0ltu37toDc

	Software synth: Modular for iPad

	modulargrid.net muffwiggler.com

### Modular Synth Basics #08: Multiples
	- Multiples create copies of a signal
	- Passive multiples do not need electricity
	- Buffered multiples need electricity and copy precisely (no voltage loss)  
	- Have enough multiples available (1 2x4 multiples per row)  

### Modular Synth Basics #09: Linear & Exponential
	https://youtu.be/QXS1v2CQLOY

	Exponential modules for audio processing (human sense experience)  
	Linear modules for CV processing (want CV mods to be linear)  

	- The human ear perceives volume increases logarithmically  
	- To be perceived linear (smooth changes), need to increase	exponentially  
	- CV operations usually stay linear

### Modular Synth Basics #10: Clocks & Sequencers
	https://youtu.be/Zoeo8mK_zsE

	Clock divider modules  
	Sequencers

	- Clock CV signals are repeating Gates or Triggers  
	- Clock CV can be generated from LFOs, Clock Modules, Expert Sleepers, etc.  
	- Clock Divider creates synced slower clocks from incoming clock CV signal  
	- Gate / Trigger Sequencers output pulses at fixed voltage levels (drum rhythm)  
	- CV Sequencers output continous variable voltage levels (melody)  
	- Reset inputs start sequencers from the beginning  

### Modular Synth Basics #11: Self-playing synth voice patch  
	(with Sample & Hold)

	Previous patch:
	VCO > VCF > VCA > Mixer
	MIDI-CV Gate > ADSR > VCA | MIDI-CV PitchCV > VCO | LFO > VCF

	This patch:
	LFO > ADSR > VCA | MIDI-CV PitchCV > VCO | LFO > VCF
	
	Add Sample & Hold
	LFO > ADSR > VCA | Noise > S&H > VCO | LFO > VCF

	Use a Multiplier

	LFO > Mult > ADSR > VCA | Noise > S&H > Attenuator > VCO | LFO > VCF  
		--------------------------> Clock Div >

### Modular Synth Basics #12: Envelopes & Function Generators
	https://youtu.be/SBTiaGG6T6A

	- Function generators create CV signals that change over time  
	- Also called envelope generators (EG)  
	- Have to be triggered to create CV  
	- Many are based around ADSR concept  

### Modular Synth Basics #15: The cheap way into Eurorack (modular synths on a budget)
	https://youtu.be/xvu1ZCR5Iy8

	Get:
		- a semi-modular synth
		Arturia Microbrute  
		Doepfer Dark Energy  
		- a Eurorack case  
			6 U Eurorack case with power (Doepfer DIY case)  
     
   	 - 1 or 2 Eurorack modules  
	 VCO  
	 LFO (cannot have too many)  
	 EFFECTS: VC delay, VC bitcrusher, VC Fuzz  

### Modular Synth Basics #16: Waveforms on an oscilloscope
	https://youtu.be/0nuxXM9QQPA


-----
CLEANUP NOTES:
- what happened to Synth Basics #13, #14?
- where does this go, if anywhere?

VCO > VCF > VCA > Mixer
Modular Synth Basics (The Tuesday Night Machines) 7-2 Mod Synth Basics #04
MIDI-CV Gate > VCA | MIDI-CV PitchCV > VCO
MIDI-CV Gate > ADSR > VCA | MIDI-CV PitchCV > VCO
MIDI-CV Gate > ADSR > VCA | MIDI-CV PitchCV > VCO | LFO > VCF
           - Clock CV signals are repeating Gates or Triggers

