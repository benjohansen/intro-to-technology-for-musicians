# 4. Analog Audio

{% hint style="info" %}
The air around and in your ears is made up of molecules of various types: oxygen, nitrogen, carbon dioxide, carbon monoxide, and others that we probably don’t want to think about. Between the molecules in the air is … nothing. This means that the air molecules can be pushed together, or compressed, into a smaller space. A property of air known as elasticity causes the molecules that have been compressed together to spring apart again.

Hosken, _Introduction to Music Technology_ \(Routledge, 2011\)
{% endhint %}

* [This Box folder](https://baylor.box.com/s/rrqiyvm3mj4utohgwjyccxohrg6lmmq7) contains a number of resources for students enrolled in this course.

1. What does the [equal-loudness contour](http://hyperphysics.phy-astr.gsu.edu/hbase/Sound/eqloud.html) \(originally called the _Fletcher—Munson curve_\) refer to? What does this have to do with Pink Noise vs. White Noise?
   * What unit is used to indicate a ratio of the following?: _silence to the perceived loudness of a sound_ \[for humans\] ... [provide at least 5 examples of the loudness levels of things/environments](https://www.google.com/search?q=decibel+chart&tbm=isch).
   * What is the [frequency range of human hearing](http://hyperphysics.phy-astr.gsu.edu/hbase/hframe.html)?
2. **Provide a drawing that illustrates a time-domain waveform representation of a sound wave \(label the following on your drawing: compression, rarefaction, wavelength, amplitude, and zero crossing\).**
3. Describe how a sound is initially created by \*your\* instrument and all it goes through \(transductions\) for another person to perceive it in their brain \(that means you’ll have to also include how the ear works\).
   * [Daniel Russell's acoustics page](https://www.acs.psu.edu/drussell/Demos/waves-intro/waves-intro.html) has many great animations
   * [How Digital Audio Works](https://docs.cycling74.com/max8/tutorials/02_mspdigitalaudio) \(MSP documentation by Cycling'74; the beginning discusses how sound works\)
   * [How the Ear Works](https://health.howstuffworks.com/mental-health/human-nature/perception/hearing.htm)
4. How is a spectrogram \(frequency domain\) different than a waveform \(time domain\)?
   * [3d Spectrogram in Chrome](https://musiclab.chromeexperiments.com/spectrogram-service/)
   * What is Fourier analysis? - [Fourier Transform video](https://www.youtube.com/watch?v=spUNpyF58BY)
   * software:
     * [SPEAR](http://www.klingbeil.com/spear/)
     * [Sonic Visualizer](https://www.sonicvisualiser.org/)
5. What are the terms aperiodic and periodic used to describe in the sound medium? What is something that produces an aperiodic waveform? What is something that produces a periodic waveform?
   * Define complex tone \(or complex wave form\) by comparing it to a sine wave.
     * [here is how a square wave is created](https://3.bp.blogspot.com/-CQXzUQenjKs/Whwr_LtHumI/AAAAAAAAB_c/tL3rrYgBbr8NFq6-Qmb_yGQRmj0xPDy-QCLcBGAs/s1600/Figure%2B2.png)
   * Define "overtone" and "harmonic" ... and "partial" - [Overtones and Harmonics](http://hyperphysics.phy-astr.gsu.edu/hbase/Music/otone.html)
     * partial = any of the sine waves that make up a complex wave form
     * harmonic = when the fundamental is divided by this number, it is a positive whole number
     * overtone = any partial above the fundamental \(simply excludes the fundamental\)
   * Define "timbre."
6. **Draw a diagram of a voltage-controlled \[analog\] synthesizer including signal/voltage paths \(control voltage, gate, trigger\).**
   * **Include the following components:** 
     * **1V/octave keyboard controller**
     * **VCO \(oscillator\)**
     * **EG \(envelop generator with ADSR\)**
     * **VCF \(filter\)**
     * **LFO \(modulation for tremolo and vibrato\)**
     * **VCA \(amplifier\)**
     * **mixer**
     * **output**
   * [Analog Synth 101](http://musicfromouterspace.com/analogsynth_new/ELECTRONICS/analogsynth101.html) \(diagram\)
   * \*\*\*\*[**Hans & Clint \| Masters At Work**](https://www.youtube.com/watch?v=NdG5dEfAcxQ)
   * [**Synthesizer Basics \(Berkley\)**](https://www.youtube.com/watch?v=c3udLCvoCC0)\*\*\*\*
   * \*\*\*\*[**Learning Synths \(Ableton interactive learning\)**](https://learningsynths.ableton.com/)\*\*\*\*
   * \*\*\*\*[**Online Virtual Analog Synth**](https://webaudiodemos.appspot.com/midi-synth/index.html)\*\*\*\*
7. What is proper gain staging \(or proper gain structure\) for live sound? Explain what each part of the system does including pan, EQ \(shapes tone\) and auxiliary sends. Define clipping \(or distortion\) and what it means to attenuate and boost the signal.
   * **\*First\*** turn off amplifiers \(main speakers and stage monitors are often "active" which means they have amplifiers inside the speaker\)
   * on the mixer
     1. set channel volume faders and main outs to Unity \(ØdB\)
     2. set the preamp gain knob to lowest setting
     3. with headphones \(or just visually\) set proper gain structure for each channel:
        1. press PFL/SOLO button on the channel
        2. engage HPF if source has no low end \(always engage for vocals\)
        3. slowly bring up preamp gain knob as performer sounds into the mic until the VU meter averages **around -18dB** and never peaks at higher than -6dB
        4. unSOLO the track and perform the three steps above with the next channel, etc.
   * **\*Last\*** \(after all channels have been setup individually\) have everyone perform together and with volume knob of amplifiers \(main speakers and stage monitors\) turned all the way down, slowly turn up volume knobs on amplifiers until you reach the desired volume in the space.
8. **What is feedback and what are some ways to avoid/lesson it?**
   * reasons for feedback:
     * mic too close to PA speaker
     * mic too far from source being amplified
     * too many mics
   * ways to minimize feedback issues:
     * experiment with the placement of a microphone
       * the closer the microphone is to the source the more the preamp gain can be lowered
       * placing the speakers between the microphone and the audience \(speakers along the front of the stage\) can greatly lesson feedback issues because the microphone will not pickup its own amplified signal
     * use directional mics to isolate sounds being picked up
     * add acoustic treatment \(absorption\) to especially "live" rooms with many hard surfaces
     * add an audience! \(rooms without an audience sound very different than rooms with no audience\)
     * use a spectral analyzer to identify feedback frequencies and fine tune EQ
9. What are some differences between condenser and dynamic microphones?
   * What does a microphone’s polar pattern tell you about how it functions? List and draw a few polar patterns.
10. Effect processors
    * compressor = a dynamics processor that boosts quiet sounds and attenuates loud sounds above a set threshold level
      * [https://youtu.be/5pXbd1QcdcU](https://youtu.be/5pXbd1QcdcU)
    * limiter = a dynamics processor that is much like a compressor with a compression ratio of infinity:1 \(not signals can go louder than a set threshold\); many times, limiters are combined with compressors as an added safety net.
      * [https://youtu.be/l85nH\_kWfK0](https://youtu.be/l85nH_kWfK0)
    * special effects processors = add ambience \(reverb\), flange, delay, distortion, etc.

{% hint style="warning" %}
Analog equipment is different than digital equipment. Analog equipment has a completely different \(much higher\) headroom. The "magic" -18dB target is really for the digital world \(0dB is more of a target for the analog world\), but developing a habit of aiming for -18dB is best when you work with both analog and digital equipment \(especially if you are combining the two\).
{% endhint %}

{% hint style="info" %}
* **mic level** = a few thousandths of a volt; 1-50mV \(requires a preamp to boost to line level\)
* **instrument level** = between mic and line level in strength; 70-150mV \(the level that comes out of guitar is instrument level and must be amplified by a preamp\)
* **line level** = about 1000 times the level of mic level
  * consumer line level = -10dB \(320mV\)
  * professional line level = +4dB \(1-1.5V\)
* **speaker level** = the level that comes out of an amplifier \(no max voltage limit\)
{% endhint %}

{% hint style="success" %}
Resource = “[Microphone Techniques for Live Sound Reinforcement](https://baylor.box.com/shared/static/g1rxbu1vysmfx2u530gwjdc9rhoyjrij.pdf)” a [Shure Educational Publication](https://www.shure.com/en-US/support/educational)
{% endhint %}

{% hint style="info" %}
[Microphone Polar Patterns](https://en.wikipedia.org/wiki/Microphone#Polar_patterns)
{% endhint %}

