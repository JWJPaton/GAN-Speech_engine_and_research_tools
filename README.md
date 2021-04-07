# GAN-Speech_engine_and_research_tools
A GAN (Generative Adversarial Network) can currently create a very good speech vocoder using linked voice and text data. This voice and text data exists license free on the web. This means the knowledge, data and tools exist to create a license free Speech Engine and to enable further work.
## To do
 - Identify GAN-TTS projects with a suitable license to allow creation of a license-free voice

## Datasets
[The "LJ Speech Dataset"](https://keithito.com/LJ-Speech-Dataset/)

[Librivox for other voices and prosody learning](https://librivox.org/)

+Any Voice data that is now out of copyright (Ethically this should be used for prosody learning rather than anything that would enable mimicking of the voice. They have not consented to have their voice stolen). 

## Research possibilities
 - Basic speech recognition tool
 - Text/Speech synchronisation tool (SMIL generator?)
 - Prosody generator based on:
   - grammar guessing from common words (the, at, in, a, and, or ...) 
   - position in document (start/end of paragraph, start/end of document)
   - common rhetorical patterns (repetions of words or phrases, alliteration etc)
- Emphasis recognition/generation for better natural language voice interfaces.
 - What is the effect of using IPA-phoneme generation rules for different languages? Does that produce accents? (anecdotal evidence says yes)
 - Accent generator/guesser (Does it help speech understanding/worldview for children to hear many accents? Should speech generators assign random (gentle) accents?)
 - Noise reduction 
   1. Apply speech recognition on audio, 
   2. generate probabilities of frequencies expecting for that text, 
   3. attenuate frequencies that don't meet a probability threshold 
