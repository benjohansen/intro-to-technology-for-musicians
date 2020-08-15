# Assignment \(multi-camera editing\)



**Overview:** You will download the files provided, mix the multitrack audio into a single stereo file, and finally edit the 3 camera 1 stereo audio files into a single video.

1. [**Download the multicamera, multitrack files for this project: \(Links to an external site.\)**](https://baylor.box.com/s/z089aic1ot173byik8wz5laigaokyccw) Chris Sies improvising on percussion instruments.
   1. [here is a link to 480p \(much smaller\) camera files \(Links to an external site.\)](https://baylor.box.com/s/fok16nf7gexedflrf9mw9p0k2plc6mhf) if the file above is too big for you.
2. Mix the multitrack audio recording into a single stereo file using Reaper. [Part 1 tutorial video \(Links to an external site.\)](https://www.youtube.com/watch?v=QIqWjQKgmEo)[![](https://baylor.instructure.com/images/play_overlay.png)](https://www.youtube.com/watch?v=QIqWjQKgmEo)
3. Direct \(edit\) the multicamera video recording \(3 cameras\) along with the stereo rendered file from Reaper using DaVinci Resolve. [Part2 tutorial video \(Links to an external site.\)](https://www.youtube.com/watch?v=52Sq5NZAq_A)[![](https://baylor.instructure.com/images/play_overlay.png)](https://www.youtube.com/watch?v=52Sq5NZAq_A)
   1. [Download and install DaVinci Resolve \(Links to an external site.\)](https://www.blackmagicdesign.com/products/davinciresolve/) \(free, \*not\* studio version\).
   2. open Resolve.
   3. choose the Media tab at bottom, then Import media \(drag the audio and video files in\)
   4. Select all media, right click, select “New Multicam Clip Using Selected Clips…” and choose “Sound” as the Angle Sync
      * **NOTE:** _**if**_ syncing with "Sound" does not work for another project of yours \(it should work for the example files I gave you\): click on each file, view the waveform, and add a "Mark In" by pressing "i" to each clip at the clap board and sync using "Mark In"
   5. right click the new multicam clip, select “New Timeline Using Selected Clips…”
   6. choose the Edit tab at bottom \(and make sure playhead is at the beginning\)
      * click on ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-LudHWk1m4tx71EpDtOe%2F-LudMBSZ49oqXCo-nIml%2FScreen%20Shot%202019-11-26%20at%202.17.10%20PM.png?alt=media&token=edb0a0d6-e9a4-4844-a7c3-9c668f75002a) in the top right corner if you don't see two viewers \(monitors\)
   7. change the left viewer \(monitor\) panel from Source ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-LtfznlFJNdNwapbfNo9%2Fsource-37.png?alt=media&token=3074938c-6300-4ad2-bdff-387f62f0f405) to Multicam ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-LtfzqcKSxZTg_i2WydE%2Fmulti2-38.png?alt=media&token=94ec015b-18f8-489d-a98c-ba28e9b68c28)
   8. choose ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltfzv2Y2gd30AHCHtn6%2Faudio-39.png?alt=media&token=021710e1-7942-4888-a794-5568179b601b) hold Option \(Mac\) or Alt \(PC\) and click the audio “angle” \(still has a red box\)
   9. choose ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-17gQEfYIDaJVIgX%2Fvideo-41.png?alt=media&token=d240620e-70e0-4908-a5a1-21549ab64154) hold Option \(Mac\) or Alt \(PC\) and click the first video angle \(the video angle will now have a blue box and the audio "angle" will have a green box\)
   10. to “direct” = press play and choose camera with the mouse or number keys \(don't ever choose the audio "angle" ... and note, you will leave ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-17gQEfYIDaJVIgX%2Fvideo-41.png?alt=media&token=d240620e-70e0-4908-a5a1-21549ab64154) on\) ... you don't need to use the option key any more!
   11. _**after**_ you have played through the hole thing and changed camera angles \(in number 10 above\), you may want to adjust _**when**_ a camera change occurs \(you may have been a bit late or early\) ... so in Selection Mode ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-Bxe6cyz04PY-S28%2FPinClipart-74.png?alt=media&token=4c90c6ca-325f-44b6-b91c-6215de029ea2) hover between two clips until you see the Roll Edit cursor ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LroRRcyiuzPub4SVHLq%2F-Ltfz1B_V9CX8fGkDKLv%2F-Ltg-HPODRZEO9ps-fPL%2Froll-edit-cursor-72.png?alt=media&token=64408e8b-abde-4865-8d3b-3fad9c5216c7) click and drag left or right
   12. When you are done: Deliver tab at bottom and choose YouTube 720 or 1080 \(1080 is what it was shot in ... but if your internet or computer is slow, choose 720 to save time\).
   13. Upload the video to YouTube \(or Vimeo\) and make the video privacy "unlisted" \(that makes is unsearchable by the public, but makes the video shareable by link only\).
   14. Submit the URL to the YouTube video to complete this assignment.

