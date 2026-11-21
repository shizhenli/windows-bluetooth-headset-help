---
title: "Bluetooth Headset Microphone Not Working Windows 11: When Apps Can't Select the Mic"
description: "Apps can't select your Bluetooth headset microphone in Windows 11 even though audio output works? Follow these focused checks to restore the microphone."
seo_title: "Bluetooth Headset Microphone Not Working Windows 11: Fix 'Microphone Not Available'"
seo_description: "Apps can't select your Bluetooth headset microphone in Windows 11 even though audio output works? Follow these focused checks to restore the microphone."
keywords:
  - "bluetooth headset microphone not working windows 11"
date: 2026-11-21T16:41:56+08:00
publishDate: 2026-11-21T16:41:56+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but every app shows the microphone as not available and won't let you select it.

## Confirm the headset exposes a microphone profile

Open Settings > Bluetooth & devices > Devices and click your headset. Under Audio, check whether a Hands-Free or Headset entry appears alongside Stereo. If only Stereo is listed, Windows sees output only. Remove the device, put the headset in pairing mode, and re-add it. If the Hands-Free entry still doesn't appear, the headset's mic profile isn't being offered and the **bluetooth headset microphone not working windows 11** issue is at the device pairing level, not in your apps.

## Check the input device and its state

Go to Settings > System > Sound > Input. Select your headset's Hands-Free microphone from the list. If it's missing, click Manage sound devices and see whether it's listed as Disabled; enable it. If it appears but shows "Not plugged in," the Hands-Free profile didn't attach, so repeat the remove-and-repair step above.

## Set the default input and test

In the same Input screen, set the headset mic as default. Open Voice Recorder and record five seconds, then play it back. If you hear your voice, the mic path is working; return to your app and reselect the microphone. If the recording is silent, open Device Manager > Audio inputs and outputs, right-click the headset microphone, and choose Update driver.

## Recovery note

If changes make things worse, use Settings > System > Sound > Reset to restore default audio settings, then re-pair the headset. For a guided diagnosis,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
