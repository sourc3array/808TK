# genAudio - 808TK (SFZ)

The **808TK** is a virtual drum kit instrument in the open-standard [SFZ file format](https://sfzformat.com/) that utilizes the free [**808 Tape**](https://www.wavealchemy.co.uk/product/808-tape/) sample library from [*Wave Alchemy*](https://www.wavealchemy.co.uk/).


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


## Compatibility

The **808TK** is designed for use with SFZ sample players and audio plug-ins.

## Installation

1.  Download the free **808 Tape** sample library from *Wave Alchemy*:

    https://www.wavealchemy.co.uk/product/808-tape/

2.  Open the 'genAudio_808TK_SFZ' folder and populate the empty 'Samples' folder with the sample files located in the 'wa_808_tape' folder from *Wave Alchemy*.

3.  Load the instrument file 'genAudio_808TK.sfz' into your SFZ plug-in or stand-alone player.

## 808TK Overview

The **808TK** features fifty-three (53) 24-bit drum samples layered over sixteen (16) individual sound pads. The sound bank has been curated for optimal use with 4x4 drum pad controllers and finger drumming:

  - **DRUMS**: Kick (Sub), Kick, Low Tom and High Tom
  - **SNARES**: Snare, Snare (Alt), Rim and Clap
  - **HI-HATS**: Closed Hat, Closed Hat (Alt), Mid Hat and Open Hat
  - **CYMBALS**: Crash and Crash (Alt)
  - **PERCUSSION**: Clave and Maracas (FX)

Each drum pad contains multiple velocity layers to provide clean, saturated and driven variations for each sound. The velocity ranges follow a non-linear progression, pushing the drive articulations into the upper velocity range. This gives the drum kit a *sweet spot* at higher volumes that plays like the power band of an internal combustion engine. Several pads feature additional sample layers and sound design nuances, giving the **808TK** its unique sonic texture. All pads feature an independent Volume control, with an additional Tight control for the hi-hats. Muting has been implemented for each cymbal for enhanced realism and playability.

## Controls

The **808TK** provides controls for:

  - (V) **Volume**: Sets the volume for each individual pad
  - (T) **Tight**: Varies the openness of the Mid Hat

### Continuous Controllers

Controls are assigned to MIDI CCs for automation in DAWs, linking to hardware MIDI controllers, live performance, etc. See the [Continuous Controller IDs](#continuous-controller-ids) section below for a complete list of CC IDs and their assignments.

## Customization

TBD

## MIDI Reference

### Key Note Mapping

Default MIDI numbers and note names for the **808TK**:

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
  - 46 - Clave -- A#1
  - 49 - Maracas (FX) -- C#2

### Continuous Controller IDs

The (T) Tight control for the Mid Hat is assigned to the MIDI default for *Foot Pedals*.

The default CC assignments for all (V) Volume controls correspond to *Undefined* channels in the MIDI specification to minimize potential comflicts in typical MIDI setups.

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

## Getting Help

If you have any questions, concerns, bug reports, etc., please file an issue in this repository's *Issue Tracker*.

## Getting Involved

[Contribute](CONTRIBUTING.md) to the **808 Tape Kit (SFZ)** and the *genAudio Project* with your constructive feedback and feature requests.


----


### Open Source Licensing Info

1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)

### Credits

1. SFZ programming and sound design by [SOURC3ARRAY](https://soundcloud.com/sourc3array).

### References

1. [808 Tape](https://www.wavealchemy.co.uk/product/808-tape/) is a free collection of TR-808 drum machine samples recorded directly to 1/4″ analogue tape.
2. [sforzando](https://www.plogue.com/products/sforzando.html) is a free, SFZ 2.0 compliant sample player.
2. [SFZFormat](https://sfzformat.com/) provides an overview and reference for the SFZ file format.
3. [Wave Alchemy](https://www.wavealchemy.co.uk/) makes award-winning virtual instruments, samples and FX.
