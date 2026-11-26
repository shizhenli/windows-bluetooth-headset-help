---
title: "Windows 11 Bluetooth Headphones Connected but Silent: Resolve the No-Sound State"
description: "Windows 11 shows your Bluetooth headphones connected but no sound plays. Follow these focused checks to restore audio output without reinstalling drivers."
seo_title: "Windows 11 No Sound Bluetooth Headphones: Fix Connected but Silent"
seo_description: "Windows 11 shows your Bluetooth headphones connected but no sound plays. Follow these focused checks to restore audio output without reinstalling drivers."
keywords:
  - "windows 11 no sound bluetooth headphones"
date: 2026-11-26T09:09:15+08:00
publishDate: 2026-11-26T09:09:15+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC, your Bluetooth headset shows connected, but the output stays silent—this is the classic **windows 11 no sound bluetooth headphones** state, and we'll walk through a controlled diagnosis.

## Confirm the active output device

Open Settings > System > Sound. Under Output, check which device is selected. If your headset appears but is not selected, click it. If it is selected and the volume slider is at zero or muted, raise it. Result interpretation: if the headset is selected and volume is up but still silent, move to the next check.

## Test with the Windows sound test

In the same Sound settings, click your headset, then click Test. You should hear a tone in each ear. If you hear nothing, the problem is likely the Bluetooth audio profile or the headset's own connection state. If you hear the tone, the issue is app-specific—check the app's own output device setting.

## Switch the Bluetooth audio profile

Windows sometimes connects the headset in Hands-Free (phone call) mode instead of Stereo. Open Settings > Bluetooth & devices > Devices, click your headset, and look for an audio profile selector. Choose Stereo or High Fidelity Playback. Then retest with the sound test.

## Rollback and recovery

If changes make things worse, return to Settings > System > Sound and reselect your previous output device. You can also remove the headset from Bluetooth & devices and pair it again; this restores default profiles without losing other settings.

## Verification

Play a short local audio file. If sound comes through both ears and the volume slider responds, the fix is confirmed. If silence persists,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact device name and Windows build.
