---
title: "Windows Bluetooth Headset Connected but No Sound: Fix the Silent Output"
description: "Your Bluetooth headset shows connected on Windows 11 but stays silent. Follow these focused checks to restore audio output without reinstalling drivers."
seo_title: "Windows Bluetooth Headset No Sound: Connected but Silent Fix"
seo_description: "Your Bluetooth headset shows connected on Windows 11 but stays silent. Follow these focused checks to restore audio output without reinstalling drivers."
keywords:
  - "windows bluetooth headset no sound"
date: 2026-11-22T10:11:06+08:00
publishDate: 2026-11-22T10:11:06+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC, your Bluetooth headset connects and the mic works, but playback stays silent. This is a common **windows bluetooth headset no sound** symptom, and it usually comes down to the output route or the hands-free profile being selected by mistake.

## Check the active output device

Open Settings > System > Sound. Under Output, confirm your headset is selected, not your monitor or speakers. Then click the headset entry and check the format. If it shows Hands-Free AG Audio, switch to Stereo. Result: if Stereo is available and selected, play a test sound; if the meter moves but you hear nothing, continue below.

## Disable the hands-free endpoint

Open Control Panel > Hardware and Sound > Sound > Playback. Right-click your headset's Hands-Free entry and choose Disable. Keep the Stereo entry enabled and set as Default Device. Result: Windows should now route media to the stereo endpoint. If the headset disappears entirely, re-enable it and move on.

## Run the audio troubleshooter

Go to Settings > System > Sound > Troubleshoot. Let it detect and apply fixes. Result: if it reports no issues but sound is still absent, restart the Bluetooth service: press Win+R, type services.msc, find Bluetooth Support Service, and restart it. This is your rollback point if later changes make things worse.

## Verification test

Play a short local audio file and watch the volume mixer. If the meter moves and you hear sound, the route is fixed. If the meter moves silently, test the headset on another device to isolate hardware.

If these steps don't restore audio,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your Sound panel screenshots.
