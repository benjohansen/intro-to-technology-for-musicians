---
description: 'record, mix, and master a micro-podcast (topic of your choice)'
---

# Podcast Assignment

## Project Requirements

* 2-5min in length for the total podcast
* use Audacity in the recording booth
* use Logic or Reaper during the mixing and mastering \(and for adding the virtual instrument\)
* mix and master the project in Logic Pro or Reaper
* add the following:
  * recording of you discussing a topic of your choice
  * at least one virtual instrument sound that cleverly fit seamlessly with the podcast speaking \(sound effect or musical … sampler or synthesizer\)
  * at least one recording of yourself performing on your main instrument and cleverly fit it in with your podcast speaking/content

## Recording Process

{% hint style="info" %}
[Reserve an Audio Booth](https://techpoint.libcal.com/spaces?lid=4700) in the Moody Media Lab
{% endhint %}

1. Login to the computer
2. Open Audacity
3. Make sure you set the input device to the Focusrite Scarlett and the number of channels to 1 \(mono\).

   ![](../../.gitbook/assets/screen-shot-2019-10-21-at-3.15.21-pm-83.png) 

4. Record yourself using the provided broadcast dynamic mic \(plugged into the Cloud Lifter amplifier to provide it with more gain before it goes to the Focusrite's preamp ... see diagram below\)
5. To have proper gain staging \([video](https://www.youtube.com/watch?time_continue=8&v=UvclmTMmGv0), [article](https://www.soundonsound.com/techniques/gain-staging-your-daw-software)\), set the \[preamp\] gain on the Focusrite so your ceiling is -6dB \(peak below -6dB … not near 0dB\) and average the recording around -18dB.

   ![](../../.gitbook/assets/screen-shot-2019-05-20-at-12.11.58-pm-70.png) 

6. Export as an uncompressed \(lossless\) audio file to edit later.

![](../../.gitbook/assets/img_1679-81.jpg)

## Mixing/Mastering Process

1. Open Logic Pro and make it function as Logic rather than GarageBand
   * click "ok" for Logic to access the microphone
   * choose "empty project"
   * add a track of any type \(you will delete this track after you add the stems\)
   * In the top left of Logic … go to **Logic Pro X** &gt; Preferences &gt; Advanced Tools …
   * put a checkmark on “Show Advanced Tools”
   * click the “Enable All” button at the bottom and close the window
2. Save \(somewhere you can find it, like the Desktop\) … and save often; Logic saves everything, including imported audio, in one convenient folder \(called a package\) ... when you are done with a working session and need to leave the school lab, completely close Logic and right click on the package of the project you are working on and choose "compress" - then you can upload that .zip file to Box or Google Drive, etc.
3. mix your tracks together so that the volume is consistent across the entire podcast \(horizontally as you transition, for example, from your virtual instrument to your speaking\)  
4.  remove mistakes in your speaking:
   1. select the region
   2. place the playhead at the beginning of the mistake in the region and press ⌘t
   3. place the playhead to the end of the mistake and press ⌘t
   4. select the mistake and press delete
   5. finally pull the regions together to fill the silence gap

### We will do the following during class together:

* **Apply the proper loudness level conversion** for streaming audio online
  1. Add the following Audio FX \(plugins\) to the "stereo out" track in the order given \(top down\):
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
  2. rename your file your name and [**upload it here**](https://baylor.app.box.com/upload-widget/view/w031wuulcloqijaa46nxcaxi9h6qysb2/105726715968).

{% hint style="info" %}
### Loudness

Aim for -14LUFS \(integrated\) and -1TP to prepare your tracks for streaming services \(Youtube = -13LUFS, Spotify = -14LUFS, iTunes = -16LUFS, etc.\)

Checkout the article "[Current Trends in Mastering](https://www.warpacademy.com/current-trends-in-mastering/)" for more details.

> LUFS stands for Loudness Units Full Scale, and is a way of measuring the overall volume of a song in a way that’s much closer to the way the human ear detects volume changes.

> TP in this case stands for True Peak, and is used to measure the actual peak loudness of the file when played back in the analog realm \(ie, a speaker\).

Also, checkout the article "[The End of Loudness War?](https://www.soundonsound.com/techniques/end-loudness-war)"

> Instead, loudness normalisation positively encourages the use of dynamics and transients. Tracks are made punchy by being dynamic rather than just loud, and compression and limiting become musical effects rather than essential competitive processing. Headroom is restored, inter-sample clipping is banished, and the digital environment finally achieves the sonic quality and dynamic range of which it is capable.

Also, checkout Sweetwater's article "[What is LUFS, and Why Should I Care?](https://www.sweetwater.com/insync/what-is-lufs-and-why-should-i-care/)"

> In theory, two pieces of music that register identical LUFS readings should sound like they’re at the same level, and in practice, they do indeed sound like they’re at the same level, regardless of whatever the peak or RMS readings say. So we have an immediate, practical benefit — if you’re mastering and want consistent levels among tracks, check their LUFS readings.
{% endhint %}



![](../../.gitbook/assets/image%20%281%29.png)

"_Both of these songs have the same apparent loudness, but the second track has been turned down considerably to make this happen."_ \(pic above and quote from "[Current Trends in Mastering](https://www.warpacademy.com/current-trends-in-mastering/)"\)

