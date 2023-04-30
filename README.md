![UI screenshot of the '01-Portland' kit preset from the 808TK virtual drum kit instrument for Decent Sampler]( /Docs/Images/Preset_UI_01_Portland.png )

# 808TK (DS)

The **808TK** is a virtual drum kit instrument for [Decent Sampler]( https://www.decentsamples.com/product/decent-sampler-plugin/ ) that utilizes the free [*808 Tape*]( https://www.wavealchemy.co.uk/product/808-tape/ ) sample library from [Wave Alchemy]( https://www.wavealchemy.co.uk/ ).

***

1.  Compatibility
2.  Installation
3.  808TK Overview
4.  Controls
    - Continuous Controllers (CCs)
5.  Customization
6.  MIDI Reference
    - Key Note Mapping
    - CC IDs
7.  Getting Help
8.  Getting Involved
9.  Open Source Licensing Info
10.  Credits
11.  References

***

## Requirements

The **808TK** drum kit is built for use with Decent Sampler, a free sampling plugin and stand-alone player for creating and playing virtual instruments in the Decent Sampler format. Decent Sampler must be installed to utilize the **808TK** kit presets. Decent Sampler is available in the following formats:

 - **Windows** (32-bit/64-bit): VST, VST3, AAX, Standalone
 - **Mac** (Intel & M1): VST, VST3, AU, AAX, Standalone
 - **Linux** (Intel 64-bit): VST, VST3, Standalone
 - **iOS**: AUv3, Standalone

***

## Compatibility

The **808TK** is compatible with Decent Sampler 1.7.3 and above.

***

## Installation

1.  Download the **808TK** drum kit for Decent Sampler:

    https://github.com/sourc3array/Bare_Bones_XS

2.  Extract the ZIP file archive and move the '808TK.dsbundle' folder into your instruments folder for Decent Sampler.

3.  Download the free *808 Tape* sample library from Wave Alchemy:

    https://www.wavealchemy.co.uk/product/808-tape/

4.  Open the '808TK.dsbundle' folder and populate the empty *Samples* folder with the sample files located in the *wa_808_tape* folder from Wave Alchemy.

5.  Load the **808TK** drum kit using the file browser in the Decent Sampler plug-in or standalone player.

6.  Choose an instrument preset using the options menu.

***

## 808TK Overview

The **808TK** features fifty-three (53) 24-bit drum samples layered over sixteen (16) individual sound pads. The sound bank has been curated for optimal use with 4x4 drum pad controllers and finger drumming:

  - **DRUMS**: Kick (Sub), Kick, Low Tom, and High Tom
  - **SNARES**: Snare, Snare (Alt), Rim, and Clap
  - **HI-HATS**: Closed Hat, Closed Hat (Alt), Mid Hat, and Open Hat
  - **CYMBALS**: Crash and Crash (Alt)
  - **PERCUSSION**: Clave and Maracas (FX)

Multiple sound layers per pad with independent volume controls enable you to blend sounds to create unique sonic textures. Each drum pad contains multiple velocity layers to provide clean, saturated and driven variations for each sound. Round-robin sampling and non-linear sound design keep beats from sounding robotic. Switches provide a Loose/Tight option for the Hi-Hats and a Fast/Slow release option for the Cymbals.

***

## Controls

The **808TK** provides controls for:

  - **Volume**: Five (5) Drum Groups with independent Volume controls for Sound Layers A and B. 
  - **Loose/Tight Switch**: Varies the sample used for the Mid Hat and the release time for the Open Hat.
  - **Fast/Slow Switch**: Varies the release time for the Cymbals.

***

## MIDI Reference

### Key Note Mapping

Default MIDI note numbers and names for the **808TK**:

  - 35 - Kick (SUB) -- B2
  - 36 - Kick -- C1
  - 41 - Low Tom -- F1
  - 43 - High Tom -- G1

  - 38 - Snare -- D1
  - 40 - Snare (ALT) -- E1
  - 37 - Rim -- C#1
  - 39 - Clap -- D#1

  - 42 - Closed Hat -- F#1
  - 44 - Closed Hat (ALT) -- G#1
  - 45 - Mid Hat -- A1
  - 47 - Open Hat -- B1

  - 48 - Crash -- C2
  - 50 - Crash (ALT) -- D2
  - 46 - Maracas (FX) -- A#1
  - 49 - Clave -- C#2

### Continuous Controller IDs

*Support for MIDI continuous controllers (CCs) will be included in the *Vancouver* drum kit preset.*

The Tight/Loose switch for the Mid Hat is assigned to the MIDI default for *Foot Pedals*.

The default CC assignments for all Volume controls correspond to *Undefined* channels in the MIDI specification to minimize potential comflicts in typical MIDI setups.

  - 04 - (T) Tight
  
  - 14 - (V) Kick (SUB)
  - 15 - (V) Kick
  - 20 - (V) Low Tom
  - 21 - (V) High Tom

  - 22 - (V) Snare
  - 23 - (V) Snare (ALT)
  - 24 - (V) Rim
  - 25 - (V) Clap

  - 26 - (V) Closed Hat
  - 27 - (V) Closed Hat (ALT)
  - 28 - (V) Mid Hat
  - 29 - (V) Open Hat     

  - 30 - (V) Crash
  - 31 - (V) Crash (ALT)
  - 85 - (V) Clave
  - 86 - (V) Maracas (FX)

***

## Getting Help

If you have any questions, concerns, bug reports, etc., please contact us:

 - File an issue in this repository's *Issue Tracker* on GitHub.
 - Send us an email at support@genaudio.biz

***

## Getting Involved

Contribute to the future development of the **808TK** drum kit with your:

  - Constructive feedback
  - Feature requests

***

### Open Source Licensing Info

1. [LICENSE](LICENSE)

***

### References

2. [808 Tape](https://www.wavealchemy.co.uk/product/808-tape/): Free collection of TR-808 drum machine samples recorded directly to 1/4″ analogue tape.
5. [Wave Alchemy](https://www.wavealchemy.co.uk/): Makers of award-winning virtual instruments, samples and FX.
