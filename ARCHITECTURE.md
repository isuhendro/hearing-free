# Audio Processing

At the heart of the device is audio processing. The processor take audio as input, process it, and produce audio as output.
Audio processing needs fast processor. Arduino would not work, we need DSP (Digital Signal Processor).

Option 1 `TMS320C5000`
http://www.ti.com/lit/an/spra657/spra657.pdf

Option 2 `Ezairo® 7111`
https://www.onsemi.com/products/audio-video-assp/audiology-dsp-systems/ezairo-7111
Ezairo® 7111 is an open-programmable DSP-based hybrid module designed specifically for non-wireless hearing aids, including In-the-Canal (ITC) applications.

## Needed solutions
1. DIAGNOSIS tool to determine the amplification factor based on frequency range
2. SIGNAL PROCESSING for voice filtering
3. HEARING MOBILE APP - to control the voice filtering
