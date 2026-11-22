---
title: "Windows 11 Bluetooth Headset: Apps Can't Select the Microphone"
description: "Apps can't select your Bluetooth headset microphone on Windows 11 even though audio output works. Follow these focused checks to restore microphone availability."
seo_title: "Windows Microphone Not Working Bluetooth: Fix App Selection"
seo_description: "Apps can't select your Bluetooth headset microphone on Windows 11 even though audio output works. Follow these focused checks to restore microphone availability."
keywords:
  - "windows microphone not working bluetooth"
date: 2026-11-22T11:11:11+08:00
publishDate: 2026-11-22T11:11:11+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works, but apps can't select the headset microphone—this points to a device-role or privacy issue rather than a dead mic.

## Check the microphone's device status

Open Settings > Bluetooth & devices > Devices. Find your headset and select it. Under Device settings, confirm the microphone is enabled. If you see "Microphone not available," the headset is connected only as an output device. Remove the headset, then re-pair it. During pairing, watch for two entries: one for audio output and one for the microphone (often labeled Hands-Free AG Audio). If only one appears, the headset's mic profile isn't loading—proceed to the next check.

## Verify app-level microphone permissions

Go to Settings > Privacy & security > Microphone. Ensure Microphone access is on and the specific app is allowed. In the app's own audio settings, select the headset microphone explicitly. If the app lists only the default device, set the headset mic as the system default input: Settings > System > Sound > Input, then choose your headset. This resolves the **windows microphone not working bluetooth** symptom where apps can't see the mic despite output working.

## Run a verification test

Open Sound Settings > Input and speak into the mic. The input level bar should move. If it stays flat, the mic isn't active. Test with Voice Recorder to confirm.

## Rollback note

If re-pairing or changing defaults breaks audio output, return to Settings > Bluetooth & devices > Devices, remove the headset, and re-pair it. Your previous audio device will remain available in Sound settings.

If the mic still doesn't appear after these steps, the headset's Hands-Free profile may be disabled at the driver level.

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for a guided diagnosis.
