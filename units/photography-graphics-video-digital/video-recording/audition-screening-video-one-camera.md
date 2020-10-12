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
   * select the transition that you just added \(on the video track\) and change color from white to black on the settings in the right sidebar \(you may have to select the "inspector" tab\)

#### Get Audio Loudness Set

1. watch this video = [https://www.youtube.com/watch?v=SyWFLS4VWvA](https://www.youtube.com/watch?v=SyWFLS4VWvA)

#### Save/Export

1. Choose the "Deliver" tab at the bottom
2. Choose the settings for YouTube
3. add to queue
4. render
5. upload to Box using this link \(add your name to the file name!\) = [https://baylor.app.box.com/f/013c1360e3f0485dbdaed4a75acb071a](https://baylor.app.box.com/f/013c1360e3f0485dbdaed4a75acb071a) 

