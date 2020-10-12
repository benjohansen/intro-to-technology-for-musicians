# Audition/Screening Video \(1 camera\)

**General tips:**

* 👏 visually clap \(slate\) three times to assist in later synching audio and video
* use a tripod \(holding the camera with your hand is too shaky\)
* use only optical zoom \(don’t use digital zoom\)
* never stop recording on the camera or external audio recorder so you just have to sync the two once

**Camera settings:**

* use a separate audio recorder from the camera \(cameras have bad microphones\)
  * uncompressed \(AIFF, WAV\) 48kHz sample rate for audio
* [frame rate](https://www.diyphotography.net/learn-choose-best-frame-rate-videos-just-10-minutes/) = 24fps gives the “film” look; higher frame rates will look more like a news show 
* MP4 and MOV are easy to work with \(AVCHD can produce higher quality\)
* custom white balance or use a preset \(such as “tungsten”\)

## DaVinci Resolve Editing \(free from Blackmagicdesign\)

1. open DaVinci Resolve
2. create a new project
3. click on the "Edit" tab at the bottom if the screen

#### Auto Sync Audio

1. drag your video file and your audio file into the media pool
   * if asked, change the project to match the frame rate of the media
2. select both files \(video and audio\)
3. right click on the files and choose "Auto Sync Audio &gt; Based on Waveform and Append Tracks"
4. drag the video file \(only\) onto the timeline
5. mute the first audio track \(that is the track recorded with the inferior on-camera microphones\)

#### Conduct further editing

1. use Blade Edit Tool \(press "b"\)  to split track where you want the video to begin and end
   * slice the track where you want the video to begin
   * use the Selection Tool \(press "a"\) to select the part you want to delete \(from beginning to where you just sliced\)
   * hold down Shift and press delete
   * use Blade Edit Tool to cut off the end of the video as well, select it and delete it
2. fade in from black and fade out to black
   * choose the Effect Library tab at the top
   * under Toolbox, choose Video Transitions
   * drag the "Dip to Color Dissolve" to the beginning and end of your video
   * select what you just added \(on the video track\) and change color from white to black on the settings in the right sidebar

#### Get Audio Loudness Set

1. watch this video = [https://www.youtube.com/watch?v=SyWFLS4VWvA](https://www.youtube.com/watch?v=SyWFLS4VWvA)

#### Save/Export

1. Choose the "Deliver" tab at the bottom

## **Premiere Pro Editing** \($$ from Adobe\)

1. **choose the Assembly tab at the top of the screen**
2. drag the video and audio files into the project folder \(“Import media here to start”\)
   * if using AVCHD: you must right click and “import” using the Media Browser
3. double click the audio file; in the window that is showing the audio waveform
   * click the wrench and select “Show Audio Time Units” ![](../../../.gitbook/assets/asdf-55.png)
   * put playhead on first clap and press “m”
4. double click the video file; in the window that is displaying the video - click the waveform button to show the video’s audio waveform; put playhead on first clap and press “m”
5. **choose the Editing tab at the top of the screen**
6. drag the video file into the timeline on the bottom right 
7. drag the audio file below the video/audio
8. on the timeline \(bottom right\) = make sure “Show Audio Time Units” is checked under t the hamburger menu and “Show Audio Waveform” is checked under the wrench
9. select all the tracks in the timeline
10. right click on them and select “Synchronize”, select “clip marker”, and click OK
11. mute the camera audio track

#### **more editing**

* use the razor tool to cut clips, use the selection too \(arrow\) to select clips and delete them, lastly select all the clips and drag to very left to make it start at the right time
* **choose the Effects tab at the top of the screen**
  * choose Video Transitions &gt; Dissolve … drag “Dip to Black” over the end of the video clip to make it fade to black \(or the beginning to fade in from black\)
  * choose Audio Transitions &gt; Crossfade … drag one of the fades over the beginning and end of the audio track to fade in and fade out the audio

#### **When you are done:**

* File &gt; Export &gt; Media ...
* Format \(codec\) = H.264
* Container = MPEG-4

