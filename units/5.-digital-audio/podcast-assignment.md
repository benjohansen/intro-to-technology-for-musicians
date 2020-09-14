---
description: 'record, mix, and master a micro-podcast (topic of your choice)'
---

# Podcast Assignment

## Project Requirements

* 2-5min in length for the total podcast
* use Reaper for recording, mixing, and mastering \(and for adding the virtual instrument\)
* add all of the following to create a podcast \(check out [Radiolab](https://www.wnycstudios.org/podcasts/radiolab) if you are unsure how to incorporate sound effects and music\)
  * recording of you discussing a topic of your choice \(you may even interview someone\)
    * add proper EQ for your voice \(there are \*many\* articles online\)
    * add a compressor \(there are \*many\* articles online\)
  * at least one virtual instrument played and recorded in Reaper \(sampler or synthesizer\)
  * at least five samples from freesound.org
  * at least one musical recording you record yourself
* **all material must not be protected by copyright \(CC0 for freesound.org\)**

## Recording Your Voice

1. plug your interface into the computer and setup your interface with either the SM57 dynamic mic or Rode M5 with pop filter \(if using the Rode, turn on 48V phantom power\)
2. download and install Reaper = [http://reaper.fm/download.php](http://reaper.fm/download.php)
3. open Reaper
4. make sure your audio interface is selected in the device section of Reaper's preferences
5. add a new track
6. force the track to record in mono

   ![](../../.gitbook/assets/screen-shot-2020-09-14-at-11.58.03-am.png) 

7. record enable the track \(use headphones or make sure you turn off monitoring on the track\)
8. to have proper gain staging \([video](https://www.youtube.com/watch?time_continue=8&v=UvclmTMmGv0), [article](https://www.soundonsound.com/techniques/gain-staging-your-daw-software)\), set the \[preamp\] gain on your interface so your ceiling is -6dB \(peak below -6dB … not near 0dB\) and average the recording around -18dB.

   ![](../../.gitbook/assets/screen-shot-2020-09-14-at-12.12.56-pm.png)

9. press record

## Mixing/Mastering Process

1. 
## We will do the following _during_ class together:

* **Apply the proper loudness level conversion** for streaming audio online
  1. Add the following Audio FX \(plugins\) to the "MASTER" track in the order given \(top down\):
     * gain plugin
     * Level Meter \(select True Peak and drag yellow line to -1\)
     * Loudness Meter \(drag yellow line to -14\)
  2. press "start" on the Loudness Meter and play your piece all the way through, then press "pause"
     * "Integrated" on the Loudness Meter should be less than -14dB \(raise or lower the gain plugin accordingly and analyze again\)
     * the Level Meter should never go above -1dB for True Peak \(raise or lower the gain plugin accordingly\)
* **Export** as a compressed \(lossy\) audio format \(AAC is better sounding compression than MP3\)
  1. File &gt; Bounce &gt; Project or Section ...
     * MP4: ACC
     * Normalize: Off
  2. rename your file your name and ...

## Loudness

{% hint style="success" %}
**Aim for -14LUFS \(integrated\) and -1TP** to prepare your tracks for streaming services \(Youtube = -13LUFS, Spotify = -14LUFS, iTunes = -16LUFS, etc.\)
{% endhint %}

![](../../.gitbook/assets/image%20%281%29.png)

"_Both of these songs have the same apparent loudness, but the second track has been turned down considerably to make this happen."_ \(pic above and quote from "[Current Trends in Mastering](https://www.warpacademy.com/current-trends-in-mastering/)"\)

{% hint style="info" %}
### Loudness Resources

"[Current Trends in Mastering](https://www.warpacademy.com/current-trends-in-mastering/)"

> LUFS stands for Loudness Units Full Scale, and is a way of measuring the overall volume of a song in a way that’s much closer to the way the human ear detects volume changes.

> TP in this case stands for True Peak, and is used to measure the actual peak loudness of the file when played back in the analog realm \(ie, a speaker\).

"[The End of Loudness War?](https://www.soundonsound.com/techniques/end-loudness-war)"

> Instead, loudness normalisation positively encourages the use of dynamics and transients. Tracks are made punchy by being dynamic rather than just loud, and compression and limiting become musical effects rather than essential competitive processing. Headroom is restored, inter-sample clipping is banished, and the digital environment finally achieves the sonic quality and dynamic range of which it is capable.

"[What is LUFS, and Why Should I Care?](https://www.sweetwater.com/insync/what-is-lufs-and-why-should-i-care/)" \(Sweetwater article\)

> In theory, two pieces of music that register identical LUFS readings should sound like they’re at the same level, and in practice, they do indeed sound like they’re at the same level, regardless of whatever the peak or RMS readings say. So we have an immediate, practical benefit — if you’re mastering and want consistent levels among tracks, check their LUFS readings.
{% endhint %}

