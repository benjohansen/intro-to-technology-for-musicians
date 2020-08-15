---
description: a creative task! there is no right way!
---

# Analog Sound Reinforcement

{% hint style="success" %}
Resource = “[Microphone Techniques for Live Sound Reinforcement](https://baylor.box.com/shared/static/g1rxbu1vysmfx2u530gwjdc9rhoyjrij.pdf)” a [Shure Educational Publication](https://www.shure.com/en-US/support/educational)
{% endhint %}

## **Parts of the system** 

In order from performer’s mouth or instrument ⇨ audience

1. mic
2. channel strip \(top to bottom = signal path\)
   * preamp = boosts mic level to line level using a [**gain knob**](https://www.sweetwater.com/insync/gain-vs-trim/)\*\*\*\*
   * EQ = shapes tone 
   * auxiliary sends = additional outputs \(to stage monitors for example\)
   * fader = adjust channel line level volume
   * pan
3. main output \(on the mixer\)
4. amplifier = boosts signal from line level to very high levels
   * active \(powered\) speakers have amplifiers built into them
   * passive speakers require an amplifier to be placed in the signal chain between the mixer and the passive speaker
   * some mixers have amplifiers built in \(called power mixers\) and are sold along with passive speakers \(a complete kit\)
5. loudspeakers \(active or passive “main” speakers\)

{% hint style="info" %}
[Microphone Polar Patterns](https://en.wikipedia.org/wiki/Microphone#Polar_patterns)
{% endhint %}

{% hint style="info" %}
* **mic level** = a few thousandths of a volt; 1-50mV \(requires a preamp to boost to line level\)
* **instrument level** = between mic and line level in strength; 70-150mV \(the level that comes out of guitar is instrument level and must be amplified by a preamp\)
* **line level** = about 1000 times the level of mic level
  * consumer line level = -10dB \(320mV\)
  * professional line level = +4dB \(1-1.5V\)
* **speaker level** = the level that comes out of an amplifier \(no max voltage limit\)
{% endhint %}

## **Setup system and run sound check \(proper gain staging … also known as proper gain structure\):**

{% hint style="warning" %}
Turn powered speakers \(amplifiers\) **on last** and **off first.**
{% endhint %}

1. turn off amplifiers \(main speakers and stage monitors are often "active" which means they have amplifiers inside the speaker\)
2. on the mixer:
   1. set channel volume faders and main outs to Unity \(ØdB\)
   2. set the preamp gain knob to lowest setting
   3. with headphones \(or just visually\) set proper gain structure for each channel:
      1. press PFL/SOLO button on the channel
      2. engage HPF if source has no low end \(always engage for vocals\)
      3. slowly bring up preamp gain knob as performer sounds into the mic until the VU meter averages **around -18dB** and never peaks at higher than -6dB
      4. unSOLO the track and perform these three steps with the next channel, etc.
3. after all channels have been setup individually, have everyone perform together
4. with volume knob of amplifiers \(main speakers and stage monitors\) turned all the way down, slowly turn up volume knobs on amplifiers until you reach the desired volume in the space

{% hint style="info" %}
Analog equipment is different than digital equipment. Analog equipment has a completely different \(much higher\) headroom. The "magic" -18dB target is really for the digital world \(0dB is more of a target for the analog world\), but developing a habit of aiming for -18dB is best when you work with both analog and digital equipment \(especially if you are combining the two\).
{% endhint %}

## Feedback

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

## **Effects processors:**

* compressor = a dynamics processor that boosts quiet sounds and attenuates loud sounds above a set threshold level

{% embed url="https://youtu.be/5pXbd1QcdcU" caption="Compressors" %}

* limiter = a dynamics processor that is much like a compressor with a compression ratio of infinity:1 \(not signals can go louder than a set threshold\); many times, limiters are combined with compressors as an added safety net.

{% embed url="https://youtu.be/l85nH\_kWfK0" caption="Limiters" %}

* special effects processors = add ambience \(reverb\), flange, delay, distortion, etc.

## **Additional concepts to research and work on:** 

* mic 3-to-1 rule
* wireless mics
* DI boxes
* in-ear monitors
* power management
* using digital mixing boards
* HPF on voice

