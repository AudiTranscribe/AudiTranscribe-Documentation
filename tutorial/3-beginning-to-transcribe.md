---
description: Learn how to start transcribing audio.
---

# Beginning to Transcribe

AudiTranscribe is built to assist you with transcribing audio pieces. This walkthrough will guide you through the
process of transcribing an audio file.

{% hint style="warning" %}
This page assumes familiarity with the user interface. If you are not familiar with it, read the tutorial guide on
the [2-user-interface.md](2-user-interface.md "mention").
{% endhint %}

{% hint style="info" %}
We will use the example project created in [1-first-project.md](1-first-project.md "mention").
{% endhint %}

<details>

<summary>Adjusting Project Settings</summary>

We will first need to adjust the music key, beats per minute (BPM), time signature, and playback offset.

If you are using the example project file, and enabled estimation of both the BPM and the music key, the top section of
the UI should show the following information:

* **Music Key**: C♯ Minor
* **BPM**: 120.2
* **Time Signature**: 4/4
* **Offset**: 0

Unfortunately, although the music key and BPM are close to the actual values, these are not the correct settings for the
project. Adjust the settings so that they have the following values:

* **Music Key**: C♯ Major
* **BPM**: 120
* **Time Signature**: 6/8
* **Offset**: 0.5

Once you have updated the settings, **save the project**.

</details>

<details>

<summary>Hearing How the Audio Sounds</summary>

Once the project settings are correct, we would like to hear how the audio sounds. There are two ways to do this:

1. Press the **play/pause button** at the bottom of the window.
2. Press the **space bar**.

To stop playing the audio file, press the pause/play button again or press the space bar.

</details>

<details>

<summary>Basics of Navigation</summary>

To move around the spectrogram, you can do one of a few things.

* To scroll up or down, use the **scroll** **wheel** to scroll up or down.
* To move left or right, drag the spectrogram by clicking and dragging on the spectrogram.
* Alternatively, you can click the **scroll to playhead button** to help you move along the spectrogram.

</details>

<details>

<summary>Transcribing</summary>

Now that we have a good idea of how the music sounds, let's try and transcribe it by hand.

1. Find a spot where the audio intensity is high.
    * The higher the audio intensity, the brighter the colour of the spectrogram. Some spots that are high intensity are
      shown in the image below.

      <figure><img src="img/3-beginning-to-transcribe/high-intensity.png" alt="High Intensity Spots"><figcaption><p>Some high intensity spots on the spectrogram</p></figcaption></figure>
    * To determine if a note at that pitch is playing at that time, click on the spectrogram to hear how that note would
      sound.
2. Identify the note that is being played by looking at the left sidebar.
3. The duration of the note can be identified by looking at how long the bar lasts.

</details>

Congratulations! You have transcribed an audio file! Don't forget to save the project.

{% hint style="info" %}
For more information, read the reference pages for [playing-notes.md](../reference/playing-notes.md "mention").
{% endhint %}
