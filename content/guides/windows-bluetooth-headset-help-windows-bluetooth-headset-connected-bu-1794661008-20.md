---
title: "Windows 11 Bluetooth Headset Connected but No Audio: A Focused Fix"
description: "Your Bluetooth headset shows connected in Windows 11 but stays silent. Follow these focused checks to restore audio output without reinstalling Windows."
seo_title: "Windows 11 Bluetooth Headset Connected but No Audio: Fix It Step by Step"
seo_description: "Your Bluetooth headset shows connected in Windows 11 but stays silent. Follow these focused checks to restore audio output without reinstalling Windows."
keywords:
  - "windows bluetooth headset connected but no audio"
date: 2026-11-21T16:38:53+08:00
publishDate: 2026-11-21T16:38:53+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC, your Bluetooth headset and microphone show as connected, but the output device stays silent. Let's walk through a controlled diagnosis.

## Confirm the active output device

Open Settings > System > Sound. Under Output, select your Bluetooth headset. If it's not listed, click the arrow next to the current device and choose it. Result: if the volume slider moves but you hear nothing, the device is selected but not receiving audio. If the headset isn't listed, skip to the reconnect step.

## Check the correct Bluetooth profile

Windows often exposes two entries: "Headset" (hands-free, low quality) and "Headphones" (stereo). Select the stereo "Headphones" entry. Result: if audio returns only on one profile, the other profile is being used by a call app. Close apps like Teams or Zoom, then reselect.

## Run the audio troubleshooter

Go to Settings > System > Sound > Troubleshoot. Let it detect and apply fixes. Result: if it reports "no issues found" but sound is still missing, continue to the next check.

## Reconnect the headset cleanly

Remove the device in Settings > Bluetooth & devices, turn the headset off and on, then pair again. This clears a stale connection state that commonly causes **windows bluetooth headset connected but no audio**. Result: if sound returns after re-pairing, the original pairing was corrupted.

## Verification test

Play a short local audio file and watch the volume meter in Sound settings. The meter should move and you should hear sound. If the meter moves but you hear nothing, check the headset's own volume wheel and mute button.

## Rollback note

If a recent driver update caused this, open Device Manager > Bluetooth, right-click the adapter, choose Properties > Driver > Roll Back Driver. If no rollback is available, note the current driver version before trying alternatives so you can reinstall it.

Still stuck after these steps?

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
