---
title: "Windows 11 Bluetooth Headset Connected but No Sound: Verify Output and Mic"
description: "Fix Windows 11 Bluetooth headset connected but no sound by checking the output device and microphone settings. Step-by-step diagnosis and verification."
seo_title: "Windows Bluetooth Headset Connected but No Sound: Check Output and Mic"
seo_description: "Fix Windows 11 Bluetooth headset connected but no sound by checking the output device and microphone settings. Step-by-step diagnosis and verification."
keywords:
  - "Windows Bluetooth Headset Connected but No Sound: Check Output and Mic"
date: 2026-11-22T12:11:28+08:00
publishDate: 2026-11-22T12:11:28+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent.

## Check the active output device

Open Settings > System > Sound. Under Output, confirm your Bluetooth headset is selected, not your speakers or monitor. If it is not listed, click the arrow next to the current device and choose the headset. Result: if the headset appears and is selected but still silent, continue. If it does not appear, remove the device in Settings > Bluetooth & devices, then pair it again.

## Check the microphone input

Still in Sound, scroll to Input. Select your headset microphone. Speak and watch the input level bar. Result: a moving bar means the mic is live; a flat bar means Windows is not receiving audio from the mic. This matters because some headsets expose separate output and input endpoints, and the wrong endpoint can leave both silent.

## Run a verification test

Open Sound settings and use the test tone under Output. If you hear it, playback works. Then open Voice Recorder and record a short clip; play it back to confirm the microphone. If the test tone is silent, go to Device properties for the headset and set it as the default device, then test again.

## Rollback and recovery

If changes made things worse, return to Sound and restore your previous default devices. In Device Manager, open the Bluetooth adapter and choose Roll Back Driver if a recent update caused the issue. Re-pair the headset only after the rollback, and note that removing the device clears its saved pairing.

For a focused **Windows Bluetooth Headset Connected but No Sound: Check Output and Mic** diagnosis, work through these checks in order. If the headset still stays silent after the verification test,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
