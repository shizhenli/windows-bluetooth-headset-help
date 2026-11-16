---
title: "Bluetooth Microphone Not Working Windows: Fix the 'Microphone Not Available' Error"
description: "Fix the Windows 11 'microphone not available' error when your Bluetooth headset mic won't appear in apps, even though audio output works."
seo_title: "Bluetooth Microphone Not Working Windows: Fix 'Microphone Not Available'"
seo_description: "Fix the Windows 11 'microphone not available' error when your Bluetooth headset mic won't appear in apps, even though audio output works."
keywords:
  - "bluetooth microphone not working windows"
date: 2026-11-16T08:10:37+08:00
publishDate: 2026-11-16T08:10:37+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio plays fine, but apps like Teams or Voice Recorder say the microphone is not available. This is a common **bluetooth microphone not working windows** issue, and it usually means Windows is using the wrong input device or the headset's mic profile isn't active.

## Check the input device in Sound settings

Right-click the speaker icon in the taskbar and choose Sound settings. Under Input, select your Bluetooth headset microphone. If it's not listed, click Manage sound devices and enable it. Then speak into the mic: the input level bar should move. If it stays flat, Windows isn't receiving audio from the headset.

## Verify the headset's microphone profile

Open Control Panel > Hardware and Sound > Sound > Recording. Look for your headset. If you only see a stereo output device, the headset may be connected in 'Headset' mode but not 'Hands-Free' mode. Disconnect and reconnect the headset, then check again. A working mic shows a green check and responds to speech.

## Run a quick verification test

Open Voice Recorder and record a short clip. Play it back. If you hear your voice, the mic works. If not, go to Settings > Privacy > Microphone and ensure microphone access is on for apps. Also, in Sound > Recording, double-click your headset mic, go to Levels, and raise the microphone level to 80.

## Rollback note

If you changed settings and the mic stops working entirely, return to Sound > Recording, right-click the headset, and choose Set as Default Device. If you installed a new audio driver, use Device Manager to roll it back.

Still stuck?

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) and we'll walk through your exact device.
