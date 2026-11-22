---
title: "Stop Bluetooth Audio Dropouts on Windows 11 During Playback"
description: "Fix Bluetooth audio stuttering on Windows 11 when your headset stays connected but sound cuts in and out. Step-by-step checks and a verification test."
seo_title: "Windows Bluetooth Audio Stuttering: Fix Dropouts During Playback"
seo_description: "Fix Bluetooth audio stuttering on Windows 11 when your headset stays connected but sound cuts in and out. Step-by-step checks and a verification test."
keywords:
  - "windows bluetooth audio stuttering"
date: 2026-11-22T09:10:57+08:00
publishDate: 2026-11-22T09:10:57+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're playing music or a video on your Windows 11 PC, your Bluetooth headset stays connected, but the audio keeps cutting in and out.

## Check the audio format and disable enhancements

Open Settings > System > Sound > More sound settings. On the Playback tab, select your Bluetooth headset, click Properties, then the Advanced tab. Under Default Format, note the current selection, then choose a lower sample rate and bit depth, such as 16 bit, 44100 Hz (CD Quality). Click Apply. Next, open the Enhancements tab (or Spatial sound in Settings) and disable any audio enhancements. Result interpretation: if the dropouts become less frequent or disappear after applying a lower format, the headset or its codec was struggling with the higher bandwidth setting.

## Separate the headset's output and microphone roles

In the same Sound window, go to the Recording tab, select your headset's microphone, and click Properties. On the Listen tab, make sure Listen to this device is unchecked. Then open Settings > Bluetooth & devices > Devices and confirm the headset is not also set as the default communication device unless you need it. This addresses a common cause of **windows bluetooth audio stuttering** when Windows tries to run playback and microphone streams at once.

## Reduce wireless interference

Move the headset closer to the PC and away from USB 3.0 hubs, external drives, and Wi-Fi routers. If your PC has both 2.4 GHz and 5 GHz Wi-Fi, connect to 5 GHz. Also open Device Manager, expand Bluetooth, right-click your adapter, and update the driver if an update is offered.

## Verification test

Play a local audio file for two minutes with the microphone idle, then repeat while a voice call or recording app is open. If both runs are clean, the fix holds; if dropouts return only during microphone use, revisit the format and Listen settings above.

## Rollback note

If audio quality worsens after lowering the format, return to the previous Default Format value and re-enable enhancements. For further diagnosis,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
