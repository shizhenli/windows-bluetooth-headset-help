---
title: "Bluetooth Headset Microphone Not Working on Windows 11: Fix 'Microphone Not Available'"
description: "Fix the 'microphone is not available' error when your Bluetooth headset microphone won't appear in Windows 11 apps, even though audio output works."
seo_title: "Bluetooth Headset Microphone Not Working Windows 11: Fix 'Microphone Not Available'"
seo_description: "Fix the 'microphone is not available' error when your Bluetooth headset microphone won't appear in Windows 11 apps, even though audio output works."
keywords:
  - "bluetooth headset microphone not working windows 11"
date: 2026-11-25T11:10:58+08:00
publishDate: 2026-11-25T11:10:58+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're in Windows 11 with a Bluetooth headset that plays audio fine, but when you open an app's microphone settings, the headset mic isn't listed or selectable.

## Check the input device and its status

Open Settings > System > Sound > Input. Confirm your Bluetooth headset appears in the list. If it does, click it and check that it isn't marked as disconnected or disabled. If it's missing entirely, go to Settings > Bluetooth & devices > Devices, find your headset, and remove it, then pair it again. After re-pairing, return to Sound > Input and see whether the headset now shows as an available microphone.

## Confirm the correct profile is active

In Sound > Input, select the headset and click Device properties. Under Audio enhancements, set them to Off temporarily. Then open the app that needs the mic (for example, Voice Recorder) and check its own audio settings. If the app lists the headset under microphones, select it. If it still shows "microphone is not available," close and reopen the app so it re-reads the device list.

## Run a verification test

Open Voice Recorder and record a short clip while speaking. Play it back. If you hear your voice, the microphone path is working. If the recording is silent, go back to Sound > Input and confirm the input level isn't at zero and that the headset isn't muted by a physical switch.

## Rollback note

If changes you made to enhancements or device properties didn't help, return those settings to their previous values before trying anything else, so you don't stack changes.

If the **bluetooth headset microphone not working windows 11** issue persists after these checks,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
