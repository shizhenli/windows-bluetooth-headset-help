---
title: "Bluetooth Headset Mic Not Detected: Fix the 'Microphone Is Not Available' Error on Windows 11"
description: "Apps can't select your Bluetooth headset microphone even though audio output works. Follow these focused checks to fix the 'microphone is not available' error on Windows 11."
seo_title: "Bluetooth Headset Mic Not Detected on Windows 11: Fix 'Microphone Is Not Available'"
seo_description: "Apps can't select your Bluetooth headset microphone even though audio output works. Follow these focused checks to fix the 'microphone is not available' error on Windows 11."
keywords:
  - "bluetooth headset mic not detected"
date: 2026-11-21T16:38:53+08:00
publishDate: 2026-11-21T16:38:53+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but apps show 'microphone is not available' and won't let you pick the headset mic. Let's walk through a controlled diagnosis so you can restore the expected outcome: the microphone is not available error should disappear and apps should list your headset mic.

## Check the input device and privacy settings

First, open Settings > System > Sound. Under Input, confirm your Bluetooth headset is listed and selected. If it's missing, click Add device and pair it again. Next, go to Settings > Privacy & security > Microphone and make sure Microphone access and Let apps access your microphone are on. Scroll down and verify the specific app you're using is allowed. If the headset appears but shows 'Not plugged in' or 'Disabled', right-click it in Sound settings and choose Enable.

## Verify the correct Bluetooth profile

Windows often exposes two entries for a headset: one for output (stereo) and one for input (hands-free). In Device Manager, expand Audio inputs and outputs and look for your headset's microphone entry. If it has a yellow warning, right-click and update the driver. Also, in Settings > Bluetooth & devices > Devices, select your headset and check that the microphone is enabled under its properties. This is where a **bluetooth headset mic not detected** issue usually becomes visible.

## Run a verification test

Open Settings > System > Sound > Input and speak into the mic. The test bar should move. Then open Voice Recorder and record a short clip; play it back to confirm your voice is captured. If the bar stays flat, proceed to the rollback note below.

## Rollback and recovery

If you recently changed drivers or privacy settings, use Device Manager to roll back the audio driver (right-click > Properties > Driver > Roll back). If that's unavailable, unpair the headset, restart Windows, and pair it again. For persistent cases,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact Sound settings screenshot.
