# Source level

## Introduction
- General comments on the generation of sound
	- Natural sources
	- Transducers
- Considerations that go into 

## Signal Level?



## Signal Types

### Continuous Wave (CW)

- Simplest waveform is one that contains a single frequency transmitted as a sine wave.
- Need for gating:
	- Short pulse (ping)
	- short pulse = less energy but better range resolution (connect to TS and TL?)
- Distinguishing targets (animals, man-made objects, etc.) often requires multiple frequencies
	- Send bunch of sinewaves at different frequencies
- Benefits:
	- Can be easy to create
		- relatively simple electronics and source
	- Easy to process and interpret
- Drawbacks:
	- May need to send many different pings to cover frequencies of interest
	- Short pulses needed for good range resolution but since they have low energy, it may make the scattered signal hard to identify in high noise.
- Simulation:
	- Combination of time series plot and spectrogram
	- Ability to define amplitude, frequency, pulse length, and maybe start time for multiple CWs?
		- Idea would be to see the how both time series and spectrogram looks when single and multiple CWs are transmitted.
### Chirp 

- Also known as frequency modulated (FM) signal
- Chirp has a range different frequencies in a single signal
- Pulse compression?
	- Received signal can be processed so that all the frequencies are shifted so that the occur at once
	- This creates a very narrow and strong signal.
- Types of chirps:
	- Linear chirp: Frequency increases (or decreases) at a constant rate as a function of time
		- Often used in echosounders and other types of sonars
	- Hyperbolic chirps: Frequency increases at a increasing rate as a function of time
		- More frequencies present at the beginning or end of the chirp
		- Examples: bats, beaked whales?
-  Benefits:
	- Single signal can carry a lot of frequency information
- Drawbacks
	-  sdfas
- Simulation:
	- Combination of time series plot and spectrogram
	- Ability to define amplitude, start and end frequencies, pulse length
		- Do we want to include type of chirp (linear, hyperbolic, etc.)?
### Impulsive sound

- A lot of frequencies are created at once to make a very short pulse
	- Simplest example is a hand clap.
- Examples:
	- Explosive sources
		- Implosion of light bulb (loud and cheap, and a bit random)
		- Airguns (how controllable are the sources?)
		- TNT
	- Animal sounds
		- Many animals use clicks for echolocation
			- bats, whales, dolphins,...
		- and communication
			- fish, shrimp,...
- Benefits:
	- Pulses can contain a lot of frequency information
	- Pulse can be very short leading to very good range resolution
- Drawbacks:
	- Can be hard to generate identical pulses
	- Require very specialized sources (light bulbs, explosives, air gun,...)

## Beam Pattern
