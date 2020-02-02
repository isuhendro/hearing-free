# hearing-free
TOGETHER, let's make good quality hearing-aid affordable for everyone who needs them

## Background
Both eyes and ears are two of the most important human basic sense.
For eyes, you wikl be able to afford high quality eyeglasses for $200.
For ears, you will need at least 4000$ to buy the good quality hearing aids.

## Definition of a Good Quality Hearing Aid
1. Able to amplify the volume based on frequency range
2. Comfortable to use
3. Low battery consumption and must use `low energy` bluetooth connection

## Modules to create
1. Mobile app for hearing test

<p align="center">
  <img width="200" src="https://user-images.githubusercontent.com/241914/73419217-43fc9b00-4359-11ea-8e3f-9ef50173c584.png">
</p>

2. Signal processing audion processing
    - input: frequency based amplified factor + audio input
    - output: audio output
3. Mobile app for hearing app
    - upload audio amplification factor to device through bluetooth
4. Hearing device  

## Challenges
1. Programming DSP is not my cup of tea. We need an electrical engineer to kickstart the original code that does the audio processing.
2. Building hardware is not my expertise either. Possible Solution: The hardware industry could probably reuse the available software, assemble the hearing aid and within a small budget.

## How to Contribute
Send pull request (PR) or comment / feedback as issues. 

## References

* DSP Hardware - design & build
https://www.intel.co.jp/content/dam/altera-www/global/ja_JP/pdfs/literature/ug/ug_dsp_design_flow.pdf
https://www.udemy.com/course/ship-it-hardware-product-development-for-beginners/

* https://www.audiology.org/sites/default/files/journal/JAAA_03_02_09.pdf

* https://developer.mozilla.org/en-US/docs/Web/API/BiquadFilterNode
