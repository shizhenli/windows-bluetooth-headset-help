---
title: "Windows 11 Bluetooth Headset Connected but No Audio: Fix the Silent Output"
description: "Step-by-step fix for Windows 11 Bluetooth headset connected but no audio. Check output device, test sound, and recover if needed."
seo_title: "Windows 11 Bluetooth Headset Connected but No Audio: Fix Silent Output"
seo_description: "Step-by-step fix for Windows 11 Bluetooth headset connected but no audio. Check output device, test sound, and recover if needed."
keywords:
  - "windows bluetooth headset connected but no audio"
date: 2026-11-24T10:10:59+08:00
publishDate: 2026-11-24T10:10:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent, so you need a controlled way to restore sound.

## Confirm the active output device

Open Settings > System > Sound. Under Output, select your Bluetooth headset. If it is not listed, click Add device and pair it again. When selected, the volume slider should be active and the mute icon should not show a slash. If the headset appears twice, choose the one labeled Headphones, not Headset, for playback.

## Disconnect and reconnect cleanly

Go to Settings > Bluetooth & devices. Remove the headset, then pair it again. After reconnecting, return to Sound and confirm the headset is still the default output. If Windows switches back to speakers, set the headset as default manually.

## Run the audio test

In Sound settings, click the headset, then Test. You should hear a tone in both ears. If the test is silent, open the volume mixer and confirm the headset is not muted and its level is above zero. Also check that no app is holding exclusive control: in Sound > More sound settings > Playback, open the headset properties, Advanced tab, and clear Allow applications to take exclusive control.

## Rollback and recovery

If sound worked before a recent driver or Windows update, open Device Manager > Bluetooth, right-click the headset adapter, and choose Properties > Driver > Roll Back Driver. If rollback is unavailable, restart the Bluetooth Support Service and test again. This reverses the last change without removing your pairing.

If the headset still connects but has no sound after these checks, the issue is likely a driver or profile conflict. For a guided diagnosis of **windows bluetooth headset connected but no audio**,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
