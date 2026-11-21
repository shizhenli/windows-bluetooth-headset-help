---
title: "Windows 11 Bluetooth Headset Connected but Silent: Resolve the Output Device Conflict"
description: "Your Bluetooth headset shows connected in Windows 11 but stays silent. Follow these focused checks to resolve the output device conflict and restore sound."
seo_title: "Windows 11 No Sound Bluetooth Headphones: Fix Connected but Silent"
seo_description: "Your Bluetooth headset shows connected in Windows 11 but stays silent. Follow these focused checks to resolve the output device conflict and restore sound."
keywords:
  - "windows 11 no sound bluetooth headphones"
date: 2026-11-21T16:44:59+08:00
publishDate: 2026-11-21T16:44:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You've paired your Bluetooth headset, Windows 11 says it's connected, but no audio comes through—this usually means the wrong playback device is selected or the headset's audio service is stuck.

## Check the active output device

Open Settings > System > Sound. Under Output, confirm your headset is selected. If it's not listed, click the arrow next to your current device and choose your headset. If it appears as "Headset" but still silent, proceed to the next check.

## Verify the correct profile is active

In the same Sound settings, click your headset and look at the format. Windows may list two entries: "Headset" (stereo audio) and "Headphones" (hands-free). Select the stereo option. If only "Hands-Free AG Audio" is available, the stereo profile may be disabled—right-click the volume icon, choose Sounds, go to Playback, right-click your headset, and select "Set as Default Device." Then click "Configure" and ensure "Stereo" is chosen.

## Restart the Bluetooth audio service

Press Windows + R, type services.msc, and press Enter. Find "Bluetooth Audio Gateway Service" and "Bluetooth Support Service." Right-click each and select Restart. If they're stopped, start them. This clears a common stuck state causing **windows 11 no sound bluetooth headphones**.

## Verification test

Play a short audio clip (e.g., a system sound). You should hear it through the headset. If still silent, disconnect and reconnect the headset in Settings > Bluetooth & devices. As a rollback, if you changed any default device settings, you can revert by selecting your previous output device in Sound settings.

If the issue persists,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for a guided diagnosis.
