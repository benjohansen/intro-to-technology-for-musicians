# Assignment \(multi-camera editing\)

**Overview:** You will download the files provided, mix the multitrack audio into a single stereo file, and finally edit the 3 camera 1 stereo audio files into a single video.

First, checkout the tips for recording using multiple cameras:

{% page-ref page="video-recording/video-recording-concerts-3+-cameras.md" %}

1. [**Download the multicamera, multitrack files for this project:**](https://baylor.box.com/s/z089aic1ot173byik8wz5laigaokyccw) Chris Sies improvising on percussion instruments.
   * [**here is a link to 360p \(much smaller\) camera files if the file above is too big for you.**](https://baylor.box.com/s/fok16nf7gexedflrf9mw9p0k2plc6mhf)\*\*\*\*
   * Also note: you can get better performance out of your computer while editing by editing at a lower resolution = Playback &gt; Proxy Mode &gt; Half \(or Quarter\) Resolution
2. Park 1 = Mix the multitrack audio recording into a single stereo file using Reaper
   * [https://www.youtube.com/watch?v=QIqWjQKgmEo](https://www.youtube.com/watch?v=QIqWjQKgmEo)
3. Part 2 = Direct \(edit\) the multicamera video recording \(3 cameras\) along with the stereo rendered file from Reaper using DaVinci Resolve.
   * [https://www.youtube.com/watch?v=52Sq5NZAq\_A](https://www.youtube.com/watch?v=52Sq5NZAq_A)
   * Here are the instructions from the video written out:
     1. open Resolve.
     2. choose the Media tab at bottom, then Import media \(drag the audio and video files in\)
     3. Select all media, right click, select “New Multicam Clip Using Selected Clips…” and choose “Sound” as the Angle Sync
        * **NOTE:** _**if**_ syncing with "Sound" does not work for another project of yours \(it should work for the example files I gave you\): click on each file, view the waveform, and add a "Mark In" by pressing "i" to each clip at the clap board and sync using "Mark In"
     4. right click the new multicam clip, select “New Timeline Using Selected Clips…”
     5. choose the Edit tab at bottom \(and make sure playhead is at the beginning\)
     6. click on ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-LudHWk1m4tx71EpDtOe%2F-LudMBSZ49oqXCo-nIml%2FScreen%20Shot%202019-11-26%20at%202.17.10%20PM.png?alt=media&token=edb0a0d6-e9a4-4844-a7c3-9c668f75002a) in the top right corner if you don't see two viewers \(monitors\)
     7. change the left viewer \(monitor\) panel from Source ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-LtfznlFJNdNwapbfNo9%2Fsource-37.png?alt=media&token=3074938c-6300-4ad2-bdff-387f62f0f405) to Multicam ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-LtfzqcKSxZTg_i2WydE%2Fmulti2-38.png?alt=media&token=94ec015b-18f8-489d-a98c-ba28e9b68c28)
     8. choose ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltfzv2Y2gd30AHCHtn6%2Faudio-39.png?alt=media&token=021710e1-7942-4888-a794-5568179b601b) hold Option \(Mac\) or Alt \(PC\) and click the audio “angle” \(still has a red box\)
     9. choose ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-17gQEfYIDaJVIgX%2Fvideo-41.png?alt=media&token=d240620e-70e0-4908-a5a1-21549ab64154) hold Option \(Mac\) or Alt \(PC\) and click the first video angle \(the video angle will now have a blue box and the audio "angle" will have a green box\)
     10. to “direct” = press play and choose camera with the mouse or number keys \(don't ever choose the audio "angle" ... and note, you will leave ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-17gQEfYIDaJVIgX%2Fvideo-41.png?alt=media&token=d240620e-70e0-4908-a5a1-21549ab64154) on\) ... you don't need to use the option key any more!
     11. _**after**_ you have played through the hole thing and changed camera angles \(in number 10 above\), you may want to adjust _**when**_ a camera change occurs \(you may have been a bit late or early\) ... so in Selection Mode ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-Bxe6cyz04PY-S28%2FPinClipart-74.png?alt=media&token=4c90c6ca-325f-44b6-b91c-6215de029ea2) hover between two clips until you see the Roll Edit cursor ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-HPODRZEO9ps-fPL%2Froll-edit-cursor-72.png?alt=media&token=64408e8b-abde-4865-8d3b-3fad9c5216c7) click and drag left or right
     12. When you are done: Deliver tab at bottom and choose YouTube 720p or 1080p \(1080p is what it was shot in ... but if your internet or computer is slow, choose 720p to save time\).
         * Note: if you used the 360p files \(much smaller\), then choose "custom" under Resolution after choosing the YouTube preset ... then type in 640x360
     13. Upload the video to YouTube \(or Vimeo\) and make the video privacy "unlisted" \(that makes is unsearchable by the public, but makes the video shareable by link only\).
     14. [Email me](https://www.baylor.edu/music/index.php?id=951763) the URL of your video on YouTube.

{% hint style="info" %}
To expand multicam clip to edit cameras/audio individually \(to color grade or adjust sync\):

* right click on multicam clip in timeline, select “Open in Timeline”
* to exit expanded view: double click timeline name in bottom left \(e.g. Timeline &lt; Multicam\)
{% endhint %}

{% hint style="warning" %}
I'm still researching this! If Resolve just will not run well because you have a low performance laptop, you may be able to use [Shotcut](https://shotcut.org/).

* the following can actually be applied to both split screen and multiscreen projects = [https://youtu.be/fL4yjMVZlfg](https://youtu.be/fL4yjMVZlfg)
* you may also need to run in proxy mode to help your computer work easier = [https://youtu.be/PzHutxve2T0](https://youtu.be/PzHutxve2T0)
{% endhint %}



