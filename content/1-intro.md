---
title: How to Record and Edit a Podcast
nav: podcasting
---
In this tutorial, we will cover the basics of using the open-source software [Audacity](https://www.audacityteam.org/) to record and edit a podcast.
## 1. Preparation
Turn on the audio interface **Scarlett 18i20** (if it's not already on). If pressing the power switch does not turn it on, first power on the **Furman M-8X** located below the **Scarlett 18i20**.

{% include figure.html img="powerswitch.jpg" alt="Power Switch" caption="Power Switch" %}

Turn the gain knob for **Input 1** all the way to the right. If recording a two-person podcast, repeat this process for **Input 2**.

{% include figure.html img="gain.jpg" alt="Gain Knobs" caption="Gain Knobs" %}

Open **Audacity**, which can be accessed in the **Launchpad**.

{% include figure.html img="launchpad.png" alt="Launchpad" caption="Launchpad" %}

Ensure that both the input and output are set to the default **Scarlett 18i20 USB**. For a two-person podcast, make sure the recording channel is set to **2 (Stereo) Recording Channels**.

{% include figure.html img="inputoutput.png" alt="Input and Output" caption="Input and Output" %}

To test your microphone, begin speaking at a comfortable level. Pay attention to the **Recording Meter Toolbar**. The bars remain green until the signal reaches -12 dB then merge to yellow as the signal approaches -6 dB, which is a good maximum signal level to aim for.

{% include figure.html img="recordingmeter.png" alt="Recording Meter" caption="Recording Meter" %}

## 2. **Recording**
To record, press the red **Record** button.![image](https://user-images.githubusercontent.com/67883371/97648213-6c611500-1a11-11eb-993d-2ff3d0fc2dfa.png){% include figure.html img="record.png" alt="Record Button" caption="Record Button" %}

To stop recording, press the spacebar or the **Stop** button.{% include figure.html img="stop.png" alt="Stop Button" caption="Stop Button" %}

If you're recording with two microphones simultaneously, Audacity will create a single track with two channels: input 1 on the left channel and input 2 on the right channel.

{% include figure.html img="recordingtrack.png" alt="Recording Track" caption="Recording Track" %}

## 3. **Editing**
To delete any unwanted sounds, such as "Um", "uh", "mm" and other filler sounds and words, use the **Selection** tool to select the portion and press the delete key on the keyboard.
{% include figure.html img="selection.gif" alt="Selection Tool" caption="Selection Tool" %}

To create two individual clips from a single clip, use the **Split** command located under **Edit > Clip Boundaries > Split**.

{% include figure.html img="split.png" alt="Split" caption="Split" %}

To change the position of an audio clip in time, use the **Time Shift** tool and drag it forward or backward on the track.

{% include figure.html img="timeshift.png" alt="Time Shift Tool" caption="Time Shift Tool" %}

To fade in and fade out, such as intro and outro music tracks, and make micro-adjustments to the audio files, use the **Envelope** tool.

{% include figure.html img="envelope.gif" alt="Envelope Tool" caption="Envelope Tool" %}

If you have recorded with two microphones simultaneously, go to **Audio Track> Split Stereo to Mono** to edit the tracks separately.

{% include figure.html img="splittracks.png" alt="Split Stereo to Mono" caption="Split Stereo to Mono" %}

After finishing your editing, go to **Tracks > Mix > Mix and Render to New Track** and then delete the old tracks. This ensures that the sound will play from both monitors. Otherwise, the left monitor will only output the left channel, and the right monitor will only output the right channel.

{% include figure.html img="mixtracks.png" alt="Mix and Render to New Track" caption="Mix and Render to New Track" %}

## 4. **Exporting**
To export, go to **File > Export > Export as WAV**.

{% include figure.html img="export.png" alt="Export" caption="Export" %}

Once exported, your episode is ready to be uploaded to a podcast hosting service like Libsyn, Anchor, or Podbean.
