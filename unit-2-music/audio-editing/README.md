# Audio Editing

Record at a quality as close to what you want for a final mix as possible \(spend time getting mic placement, room acoustics, preamp gains, etc. perfect!\). Don’t ever say you’ll wait to make something better at a later stage. You can only do so much with bad raw material. Use reference quality \(flat frequency response\) earphones and monitor speakers in your editing.

## **MULTITRACK RECORD** ⇨ **MIX** ⇨ **MASTER** ⇨ **DISTRIBUTE**

### **MIX** \(VERTICAL\)

> Put all the tracks of a single song together \([plugin guide](https://blog.landr.com/audio-effects-plugins-guide/)\)

1. Amplitude
   * gain plugin should be the first plugin for every mix \(get each track down to around -18dB and make -6dB the ceiling\)
   * Volume and panning automation \(also envelops such as fade in, fade out\)
   * Dynamics Processing: Compressor \([video](https://www.youtube.com/watch?v=5pXbd1QcdcU), [article1](https://patches.zone/compression-guide), [article2](https://flypaper.soundfly.com/produce/compression-audio-basics/)\), Limiter, Expander \(ex. noise gate\), Normalize, Distortion, Envelop
2. Spectral Filter
   * Equalization \(high pass, low pass, low shelf, high shelf, peak filter, notch filter\)
3. Time = combine the original audio signal with delayed and modified copies of itself
   * Delay = [Reverb](https://flypaper.soundfly.com/produce/artificial-space-place-reverb-tech-primer/), Delay, Echo
   * Modulation effects: Chorus, Tremolo, Flanger and Phaser

### **MASTER** \(HORIZONTAL\)

> Fine tune each completed song to fit best with all other songs in an album; many times, those that master are only given stereo mix downs of tracks \(rather than multitrack DAW files or stems\)

1. Slight adjustments to EQ, compression, limiting, stereo image, and reverb
2. Spacing and fades are added to the beginning and ending of each song
3. Make each song able to sound well played on any device

## **Computer**

* lossless audio files \(WAV, AIFF, FLAC, CAF\) = highest quality
  * use through entire recording/editing process \(note different maximum size for each … and make sure your DAW is setup to record unlimited time\)
* lossy audio files \(MP3, AAC, OGG\) = these discard data in order to compress and save space
  * save as lossy ONLY when you are completely done with all editing and are ready to stream online \(in which case use CBR\) or to save space on a device \(in which case VBR is better\)
* bit rate = amount of data \(bits\) required to represent one second of audio \(higher bit rate = better quality\)

### **Destructive vs. Non-destructive editing:**

* Destructive = changing the actual audio file
  * Most processes performed in an “audio file editor” \(normalizing the audio file, for example\)
  * Time stretch & pitch shift \(but DAWs invisibly create new files so original audio files is not changed\)
* Non-destructive = just changing how the software reads the original audio file
  * Edits done to “regions” in the main timeline of the DAW \(Cut, copy/paste\)
  * Run audio through DSP \(plugins\)

