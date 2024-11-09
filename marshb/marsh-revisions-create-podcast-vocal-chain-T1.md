# How to Create a Podcast Vocal Chain in Logic Pro

#### A good podcast vocal engages listeners by being clear, warm, and expressive. Learn to create a podcast vocal chain by utilizing vocal effects within Logic Pro.

## Prerequisites
#### Before you begin, here is what you need to do.
- Download Equalizer and Compression vocal effects. 
- Create a vocal track.

## Creating a Podcast Vocal Chain

### 1. Add a Noise Gate
- Place a Noise Gate as the first effect in the vocal chain. This helps reduce background noise by cutting out sounds that are below a certain  volume threshold. 

![Noise Gate](<assets/images/revision screenshots/t1-noise_gate.jpg>)
- Set the threshold low enough to remove background noise but high enough to avoid clipping your voice. 

### 2. Add a Channel EQ
- Place a Channel EQ as the second effect in the vocal chain. This helps shape the overall tone and removes unwanted frequencies. 

![EQ](<assets/images/revision screenshots/t1-EQ.jpg>)

- Boost and reduce [common eq frequencies.](marsh-revisions-how-to-use-EQ.md)

### 3. Add a De-Esser
- Place De-Esser 2 (Logic Pro’s stock de-esser) as the third effect in the vocal chain: This plugin reduces harsh “S” sounds.

![DeEsser](<assets/images/revision screenshots/t1-de-esser.jpg>)

- Adjust the Frequency (typically between 4-8 kHz for most voices) to target where the sibilance occurs, and set the Threshold to soften it without distorting your voice.

### 4. Add a Compressor
- Place a Compressor as the fourth effect in the vocal chain: This balances out vocal dynamics so the voice maintains a steady level throughout the recording.

![Compressor](<assets/images/revision screenshots/t1-compressor.jpg>)

- Start with a ratio around 3:1 to 4:1, with an attack time around 10-20 ms to preserve natural vocal transients and a medium release. 

### 5. Add a Limiter
- Add an Adaptive Limiter as the fifth effect in the vocal chain: This plugin helps control any peaks in your voice to avoid clipping or distortion.

![Limiter](<assets/images/revision screenshots/t1-limiter.jpg>)

- Set the Output Ceiling to around -1 dB to give a bit of headroom, and use the Gain control sparingly to ensure the loudest peaks stay below this ceiling.

### 6. Check Your End Product
- By the end of this process, your vocal chain should look like this:

![End Result: Vocal Chain](<assets/images/revision screenshots/t1-vocal-chain.jpg>)