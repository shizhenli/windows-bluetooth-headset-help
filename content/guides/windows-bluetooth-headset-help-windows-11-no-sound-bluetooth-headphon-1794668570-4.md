---
title: "Windows 11 No Sound Bluetooth Headphones: Fix the Connected but Silent Output"
description: "Windows 11 shows your Bluetooth headphones connected but no sound plays. Follow these focused checks to restore audio output and verify the fix."
seo_title: "Windows 11 No Sound Bluetooth Headphones: Connected but Silent Fix"
seo_description: "Windows 11 shows your Bluetooth headphones connected but no sound plays. Follow these focused checks to restore audio output and verify the fix."
keywords:
  - "windows 11 no sound bluetooth headphones"
date: 2026-11-23T12:11:10+08:00
publishDate: 2026-11-23T12:11:10+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Bluetooth headset shows as connected in Windows 11, but the output device stays silent and you haven't yet run a controlled diagnosis.

## Confirm the active output device
Open Settings > System > Sound. Under Output, select your Bluetooth headset explicitly. If Windows lists two entries for the same headset (for example, "Headphones" and "Headset"), choose the stereo Headphones entry for playback. Result interpretation: if the volume meter moves during playback but you hear nothing, the device selection is likely wrong or muted; if the meter stays flat, the audio stream isn't reaching the device.

## Check volume and mute state
In the same Sound settings, click your headset and ensure the volume slider is above zero and the mute icon is not active. Also check the physical volume wheel on the headset itself. Result interpretation: a muted system slider or zero headset volume will produce silence even when connected.

## Run the audio troubleshooter
Go to Settings > System > Sound > Troubleshoot common sound problems and run the troubleshooter with the headset selected. Result interpretation: if it reports a driver or service issue, apply the suggested fix and retest; if it finds nothing, move to the verification test below.

## Verification test
Play a short local audio file and watch the volume meter in Sound settings. Then open the Sound Control Panel > Playback tab, confirm the headset is set as Default Device, and click Test. You should hear the test tone in both ears. If the tone plays but apps remain silent, check per-app volume in Volume Mixer.

## Rollback and recovery
If you recently changed the Bluetooth driver or installed an update, open Device Manager > Bluetooth, right-click the adapter, choose Properties > Driver > Roll back driver. If no rollback is available, unpair the headset, restart the PC, and pair it again. For persistent **windows 11 no sound bluetooth headphones** issues,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) before making further changes.
