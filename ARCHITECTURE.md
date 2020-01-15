# Audio Processing

At the heart of the device is audio processing. The processor take audio as input, process it, and produce audio as output.
Audio processing needs fast processor. Arduino would not work, we need DSP (Digital Signal Processor).

Option 1 `TMS320C5000`
http://www.ti.com/lit/an/spra657/spra657.pdf

Option 2 `Ezairo® 7111`
https://www.onsemi.com/products/audio-video-assp/audiology-dsp-systems/ezairo-7111
Ezairo® 7111 is an open-programmable DSP-based hybrid module designed specifically for non-wireless hearing aids, including In-the-Canal (ITC) applications.

DSP 101 Part 3: Implement Algorithms on a Hardware Platform
https://www.analog.com/en/analog-dialogue/articles/dsp-101-part-3.html#

> Hardware implementation: Here the code is run on a real DSP, typically in several phases: 
> a) tryout on an evaluation platform such as EZ-Kit Lite; 
> b) in-circuit emulation, and 
> c) production ROM generation. 
> Tryout provides a quick go/no-go determination of the program’s operation; this technique is the implementation method used in this article. In-circuit emulation monitors software debug in the system, where a tool such as an EZ-ICE™ controls processor operation on the target platform. After all debug is complete, a boot ROM of the final code can be generated; it serves as the final production implementation.

## VisualDSP++
https://www.analog.com/en/design-center/evaluation-hardware-and-software/software/vdsp-bf-sh-ts.html#software-relatedsoftware

## Needed solutions
1. DIAGNOSIS tool to determine the amplification factor based on frequency range
2. SIGNAL PROCESSING for voice filtering
3. HEARING MOBILE APP - to control the voice filtering
