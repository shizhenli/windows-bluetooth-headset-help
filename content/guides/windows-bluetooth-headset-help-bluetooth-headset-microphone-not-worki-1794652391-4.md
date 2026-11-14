---
title: "Bluetooth Headset Microphone Not Working on Windows 11: Fix the 'Microphone Not Available' Error"
description: "Apps can't select your Bluetooth headset microphone on Windows 11 even though audio output works? Follow these steps to fix the 'microphone not available' error."
seo_title: "Bluetooth Headset Microphone Not Working Windows 11: Fix 'Microphone Not Available'"
seo_description: "Apps can't select your Bluetooth headset microphone on Windows 11 even though audio output works? Follow these steps to fix the 'microphone not available' error."
keywords:
  - "bluetooth headset microphone not working windows 11"
date: 2026-11-14T19:55:49+08:00
publishDate: 2026-11-14T19:55:49+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but apps show the microphone as not available and won't let you select it. This points to a specific handshake failure between Windows and the headset's mic profile, not a dead microphone.

## Check the microphone privacy and device state

Open Settings > Privacy & security > Microphone. Make sure Microphone access is on and that the specific app you're using is allowed. Then go to Settings > Bluetooth & devices > Devices and click your headset. Under Input devices, confirm the microphone is listed and not marked as disabled. If it's missing entirely, remove the headset (Unpair) and pair it again. After re-pairing, wait 10 seconds before opening any app.

## Force the correct input profile

Windows sometimes keeps the headset on the high-quality output profile and never switches to the headset profile that carries mic audio. Open Sound settings > More sound settings > Recording tab. If your headset mic appears but is greyed out, right-click it and choose Enable. Then right-click again and Set as Default Device. Click Apply. If it doesn't appear, right-click in the empty area and tick Show Disabled Devices and Show Disconnected Devices.

## Verification test

Open Voice Recorder and record five seconds. Play it back. If you hear your voice, the mic path is restored. Also return to your meeting or chat app and confirm the headset microphone now appears in its device list and can be selected.

## Rollback note

If the mic still doesn't appear after re-pairing, roll back the Bluetooth driver: Device Manager > Bluetooth > your adapter > Properties > Driver > Roll Back Driver. If no rollback is available, uninstall the device and restart so Windows reinstalls it.

If the **bluetooth headset microphone not working windows 11** symptom persists after these checks, the profile switch may be blocked by firmware or a conflicting audio service.

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact device model and Windows build for a targeted diagnosis.
