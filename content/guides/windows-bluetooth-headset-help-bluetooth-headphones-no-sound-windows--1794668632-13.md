---
title: "Bluetooth Headphones Connected but No Sound on Windows 11: A Practical Fix"
description: "Windows 11 shows your Bluetooth headphones connected but no sound plays. Follow these focused steps to verify the output device, test audio, and restore sound."
seo_title: "Bluetooth Headphones No Sound Windows 11: Fix Connected but Silent"
seo_description: "Windows 11 shows your Bluetooth headphones connected but no sound plays. Follow these focused steps to verify the output device, test audio, and restore sound."
keywords:
  - "bluetooth headphones no sound windows 11"
date: 2026-11-25T10:10:56+08:00
publishDate: 2026-11-25T10:10:56+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC, your Bluetooth headset shows Connected, but the output device stays silent—no music, no system sounds.

## Confirm the active output device
Open Settings > System > Sound. Under Output, select your Bluetooth headset explicitly. If Windows lists two entries for the same headset (for example, "Headphones" and "Headset"), choose the one labeled Headphones for playback. Result to expect: the volume slider responds when you press the headset buttons. If the slider stays grayed out, the device is not truly active—continue below.

## Run the built-in audio test
Still in Sound settings, click your headset under Output, then use the Test button. You should hear a tone in both ears. If you hear nothing, open Device Manager, expand Audio inputs and outputs, right-click your headset, and choose Update driver. Then restart the PC once. This clears the common **bluetooth headphones no sound windows 11** state where the endpoint is connected but not bound to the audio engine.

## Check the app-level output
Right-click the speaker icon in the taskbar, open Volume mixer, and confirm your headset is selected for the app you are testing. Some apps hold their own output choice and ignore the system default.

## Verification test
Play a short local audio file. If sound comes through the headset, the fix holds. If it does not, go to Settings > Bluetooth & devices, remove the headset, then pair it again. That re-creates the audio endpoints cleanly.

## Rollback note
If re-pairing makes things worse, open Device Manager, right-click the headset, choose Properties > Driver, and select Roll Back Driver. If that option is unavailable, uninstall the device and restart so Windows reinstalls it.

If the headset still connects silently after these checks,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your Windows build and headset model.
