---
title: "Windows Bluetooth Headset Connected but No Audio: Fix the Silent Output"
description: "Step-by-step fix for when your Windows 11 Bluetooth headset shows connected but produces no sound. Check output device, disable enhancements, and verify audio."
seo_title: "Windows Bluetooth Headset Connected but No Audio: Fix the Silent Output"
seo_description: "Step-by-step fix for when your Windows 11 Bluetooth headset shows connected but produces no sound. Check output device, disable enhancements, and verify audio."
keywords:
  - "windows bluetooth headset connected but no audio"
date: 2026-11-21T16:44:59+08:00
publishDate: 2026-11-21T16:44:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent, and you want to restore sound without a full reinstall.

## Confirm the active output device
Open Settings > System > Sound. Under Output, select your Bluetooth headset. If it appears twice (for example, "Headset" and "Headphones"), choose the one labeled Headset for calls or Headphones for media. Click the device and check that its volume is not muted and is above zero. Then play a short local audio file. If the level meter moves but you hear nothing, the device is selected but audio is not reaching it; continue below.

## Disable audio enhancements and exclusive mode
In the same Sound settings, click your headset, then Advanced. Uncheck "Enable audio enhancements" and "Allow applications to take exclusive control." Apply, then test again. If sound returns, the enhancement driver was blocking output; you can re-enable one option at a time to identify the culprit.

## Restart the Bluetooth audio service
Press Windows + R, type services.msc, and open it. Find Bluetooth Audio Gateway Service and Bluetooth Support Service; right-click each and choose Restart. Reconnect the headset from Settings > Bluetooth & devices. This clears a stuck audio route that can cause **windows bluetooth headset connected but no audio**.

## Verification test
Play a system sound and a video. Confirm the meter in Sound settings responds and audio is audible. Then open Voice Recorder and record a few seconds to confirm the microphone still works.

## Rollback note
If changes made things worse, return to Advanced and re-enable audio enhancements and exclusive mode, then restart the Bluetooth services again. For guided diagnosis,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
