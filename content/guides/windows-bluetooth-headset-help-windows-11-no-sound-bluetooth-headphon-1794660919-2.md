---
title: "Windows 11 No Sound Bluetooth Headphones: Fix the Connected but Silent Issue"
description: "Fix Windows 11 Bluetooth headphones that show connected but produce no sound. Step-by-step checks for output device, services, and verification."
seo_title: "Windows 11 No Sound Bluetooth Headphones: Connected but Silent Fix"
seo_description: "Fix Windows 11 Bluetooth headphones that show connected but produce no sound. Step-by-step checks for output device, services, and verification."
keywords:
  - "windows 11 no sound bluetooth headphones"
date: 2026-11-15T19:14:59+08:00
publishDate: 2026-11-15T19:14:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset as connected, but the output device stays silent. This is a common **windows 11 no sound bluetooth headphones** problem, and it usually comes down to the wrong output device being selected or the Bluetooth audio service not routing sound correctly. Let's walk through a controlled diagnosis.

## Check the active output device

Right-click the speaker icon in the taskbar and choose Sound settings. Under Output, confirm your Bluetooth headset is selected. If it shows as connected but not selected, click it and test again. Next, open the volume mixer and ensure the headset isn't muted and its slider is up. If the device appears but stays silent, proceed.

## Restart the Bluetooth audio services

Press Windows + R, type services.msc, and press Enter. Find Bluetooth Audio Gateway Service and Bluetooth Support Service. Right-click each and choose Restart. If they are stopped, start them. Set both to Automatic if they were manual. This refreshes the audio routing without unpairing.

## Re-pair the headset cleanly

Go to Settings > Bluetooth & devices. Remove the headset, then add it again. During pairing, wait for the second connected state (often labeled Voice, Music, or Stereo). Select the Stereo output in Sound settings, not the Hands-Free profile, which is for calls only.

## Verification test

Play a short local audio file and watch the volume meter in Sound settings. If the meter moves but you hear nothing, check the headset's own volume and mute button. If the meter stays flat, the output device is still wrong.

## Rollback note

If re-pairing makes things worse, return to Bluetooth & devices, remove the device, and re-add it. Your previous pairing is not recoverable, but this restores a clean state. If the issue persists after these steps,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact device names and Windows build.
