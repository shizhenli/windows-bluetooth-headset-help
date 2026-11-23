---
title: "Windows 11 Bluetooth Headset Connected but No Sound: A Simple Output Fix"
description: "Windows 11 shows your Bluetooth headset connected but silent? Follow these practical steps to restore sound and verify the fix."
seo_title: "Bluetooth Headphones No Sound Windows 11: Fix Connected but Silent"
seo_description: "Windows 11 shows your Bluetooth headset connected but silent? Follow these practical steps to restore sound and verify the fix."
keywords:
  - "bluetooth headphones no sound windows 11"
date: 2026-11-23T08:10:57+08:00
publishDate: 2026-11-23T08:10:57+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You've paired your Bluetooth headset with your Windows 11 PC, and Windows says it's connected, but you hear nothing. This is a common **bluetooth headphones no sound windows 11** problem, and it's usually caused by the wrong output device being selected or a disabled audio service.

## Check the Output Device

Click the speaker icon in the system tray and make sure your headset is selected as the output device. If it's not listed, click the arrow to expand the list. If it is listed but still silent, open Settings > System > Sound. Under Output, select your headset. Then click the device to open its properties and ensure the volume is turned up and not muted. If the volume slider is at zero or the mute icon is active, adjust it and test again.

## Verify the Audio Service

Press Win + R, type services.msc, and press Enter. Scroll to Windows Audio and confirm its status is Running. If it's stopped, right-click and choose Start. Do the same for Windows Audio Endpoint Builder. If either service was stopped, starting it often restores sound immediately.

## Run the Audio Troubleshooter

Go to Settings > System > Sound > Troubleshoot. Select your headset when prompted and let the tool run. If it finds and fixes an issue, test the sound again.

## Verification Test

Play a short audio file or use the Test button in the sound settings. You should hear clear sound through the headset. If you still hear nothing, try disconnecting and reconnecting the headset.

## Rollback Note

If you changed any settings and the problem worsens, you can undo them by returning to the same screens and restoring the previous selections. For driver changes, use Device Manager to roll back the Bluetooth driver.

If these steps don't resolve it,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for further diagnosis.
