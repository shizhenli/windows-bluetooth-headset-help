---
title: "Bluetooth Headset Microphone Not Working Windows 11: Fix the Microphone Not Available Error"
description: "Step-by-step fix when your Bluetooth headset microphone is not available in Windows 11, even though audio output works. Diagnose the mic selection issue and restore your headset microphone."
seo_title: "Bluetooth Headset Microphone Not Working Windows 11: Fix Mic Not Available"
seo_description: "Step-by-step fix when your Bluetooth headset microphone is not available in Windows 11, even though audio output works. Diagnose the mic selection issue and restore your headset microphone."
keywords:
  - "bluetooth headset microphone not working windows 11"
date: 2026-11-23T09:10:53+08:00
publishDate: 2026-11-23T09:10:53+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio plays fine, but apps can't select the headset microphone—it shows as not available. This is a common **bluetooth headset microphone not working windows 11** symptom, and it usually means Windows is treating the headset as an output-only device or the microphone endpoint is disabled.

## Check the microphone endpoint in Sound settings

Open Settings > System > Sound > All sound devices. Find your headset under Input devices. If it's missing, click View all devices and look for it under Disabled or Disconnected. If it appears but says Not plugged in, the headset's mic profile isn't active—proceed to the next check. If it's listed and enabled, skip to the verification test.

## Re-enable the headset microphone

Right-click the Start button, choose Device Manager, and expand Audio inputs and outputs. Look for your headset microphone. If it has a down-arrow icon, right-click and select Enable device. Then return to Sound settings and confirm the input device now shows as Ready. If it still shows Not plugged in, go to Settings > Bluetooth & devices > Devices, remove the headset, and pair it again—this refreshes the Hands-Free profile that carries microphone audio.

## Verification test

Open Settings > System > Sound > All sound devices > your headset microphone and speak while watching the input level bar. A moving bar confirms the mic is live. Then test in an app: open Voice Recorder and record a short clip; playback should contain your voice. If the bar stays flat, the headset may be in a mode that disables its mic—check the headset's own mute switch or companion app.

## Rollback note

If re-pairing or enabling the device causes audio output to stop, return to Device Manager, disable the microphone endpoint again, and re-pair the headset once more. This restores the previous output-only state so you can retry the steps in order.

If the microphone still isn't available after these checks,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your device details.
