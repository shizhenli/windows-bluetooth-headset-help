---
title: "Windows Microphone Not Working with Bluetooth Headset: Fix the 'Microphone Not Available' Error"
description: "Apps can't select your Bluetooth headset microphone on Windows 11 even though audio output works? Follow these exact checks to restore the microphone."
seo_title: "Windows Microphone Not Working Bluetooth: Fix Headset Mic Not Available"
seo_description: "Apps can't select your Bluetooth headset microphone on Windows 11 even though audio output works? Follow these exact checks to restore the microphone."
keywords:
  - "windows microphone not working bluetooth"
date: 2026-11-14T19:55:49+08:00
publishDate: 2026-11-14T19:55:49+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but apps show the microphone as not available and won't let you select it. This is a common **windows microphone not working bluetooth** issue, and it usually comes down to the headset being stuck in the wrong Bluetooth profile or the microphone being disabled at the system level.

## Check the Bluetooth profile and default input

Open Settings > Bluetooth & devices > Devices. Find your headset and click it. Under Audio, you should see two entries: one for output (stereo) and one for input (hands-free). If the input entry is missing, remove the headset and pair it again. Next, go to System > Sound > Input. Select your headset microphone from the list. If it's not listed, click Manage sound devices and enable it. If it shows as unavailable, that confirms the profile isn't active.

## Verify the microphone in Sound settings

Still in System > Sound, under Input, speak into the mic and watch the input level bar. If it stays flat while the headset is selected, the microphone is muted or the wrong device is active. Click the device and check the volume slider and mute button. Also open Device Manager, expand Audio inputs and outputs, right-click your headset microphone, and choose Enable device if available.

## Run a verification test

Open Voice Recorder and record a short clip. Play it back. If you hear your voice, the microphone is working. If not, return to Sound settings and confirm the input device is set as default for both input and communications.

## Rollback note

If you recently changed privacy settings, go to Settings > Privacy & security > Microphone and turn on microphone access for apps. If the issue started after a driver update, roll back the Bluetooth driver in Device Manager. For a guided diagnosis,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
