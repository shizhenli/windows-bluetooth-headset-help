---
title: "Windows 11 Bluetooth Headphones No Sound: Fix the Connected but Silent Issue"
description: "Fix Windows 11 Bluetooth headphones that show connected but produce no sound. Step-by-step checks for output device, services, and driver rollback."
seo_title: "Windows 11 Bluetooth Headphones No Sound: Connected but Silent Fix"
seo_description: "Fix Windows 11 Bluetooth headphones that show connected but produce no sound. Step-by-step checks for output device, services, and driver rollback."
keywords:
  - "windows 11 bluetooth headphones no sound"
date: 2026-11-21T16:44:59+08:00
publishDate: 2026-11-21T16:44:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset and microphone, and the headset shows as connected, but the output stays silent. This is a common **windows 11 bluetooth headphones no sound** problem, and it's usually fixable with a few focused checks.

## Check the Output Device

Open Settings > System > Sound. Under Output, confirm your Bluetooth headset is selected. If it's not listed, click the arrow next to the current device and choose the headset. If it is listed but still silent, click it and check the volume slider—make sure it's not at zero or muted. Also click the headset entry and verify the format isn't set to an unsupported sample rate; try 16-bit, 44100 Hz.

## Verify the Bluetooth Services

Press Win+R, type services.msc, and press Enter. Find Bluetooth Support Service. If its status isn't Running, right-click and choose Start. Double-click it and set Startup type to Automatic. Then restart the Bluetooth Audio Gateway Service if present. After that, go to Settings > Bluetooth & devices > Devices, remove the headset, and pair it again. This clears stale connection data.

## Test with a Known Audio Source

Play a local audio file or a system sound (Settings > System > Sound > More sound settings > Sounds tab). If you hear the test sound, the issue was the previous app or its output selection. If not, continue.

## Roll Back the Bluetooth Driver

Open Device Manager, expand Bluetooth, right-click your adapter, and choose Properties > Driver. If Roll Back Driver is available, use it. Otherwise, uninstall the device (do not delete the driver) and restart—Windows will reinstall it. This is your recovery step if a recent update caused the silence.

If these steps don't restore sound,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact adapter model and Windows build.
