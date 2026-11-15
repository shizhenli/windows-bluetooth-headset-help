---
title: "Windows 11 Bluetooth Headphones Connected but No Sound: Fix the Silent Output"
description: "Fix Windows 11 Bluetooth headphones that show connected but produce no sound. Step-by-step checks for output device, services, and a verification test."
seo_title: "Windows 11 Bluetooth Headphones No Sound: Connected but Silent Fix"
seo_description: "Fix Windows 11 Bluetooth headphones that show connected but produce no sound. Step-by-step checks for output device, services, and a verification test."
keywords:
  - "windows 11 bluetooth headphones no sound"
date: 2026-11-15T19:14:59+08:00
publishDate: 2026-11-15T19:14:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent, and you want to restore sound without guessing. This is the classic **windows 11 bluetooth headphones no sound** situation, and it usually comes down to the wrong output device or a stopped audio service.

## Confirm the active output device

Open Settings > System > Sound. Under Output, check which device is selected. If you see your headset listed but not selected, click it and test again. If it is selected and still silent, click the device and look at its volume slider—raise it if it is at zero. Also open the volume mixer from the taskbar and confirm the headset is not muted there.

## Check the Bluetooth audio services

Press Win+R, type services.msc, and press Enter. Find Bluetooth Audio Gateway Service and Bluetooth Support Service. Both should show Running. If either is stopped, right-click it, choose Start, then set Startup type to Automatic. Restart the PC and reconnect the headset.

## Run a verification test

Play a short local audio file or use the Windows sound test under Settings > System > Sound > More sound settings > Playback. Select the headset, click Test, and listen. If you hear the chime, the output path is working. If not, remove the headset under Settings > Bluetooth & devices, then pair it again.

## Rollback note

If sound breaks after a driver or Windows update, open Device Manager > Audio inputs and outputs, right-click the headset, choose Properties > Driver > Roll Back Driver. If no rollback is available, uninstall the device and restart so Windows reinstalls it.

If these steps do not restore audio,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact device names and what the test produced.
