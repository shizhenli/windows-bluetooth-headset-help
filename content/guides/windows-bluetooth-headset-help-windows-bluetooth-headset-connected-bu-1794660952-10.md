---
title: "Windows 11: Bluetooth Headset Shows Connected but Plays No Sound — Output and Mic Check"
description: "Windows 11 shows your Bluetooth headset connected but silent? Check the output device and microphone with this focused, step-by-step diagnosis and verification test."
seo_title: "Windows Bluetooth Headset Connected but No Sound: Check Output and Mic"
seo_description: "Windows 11 shows your Bluetooth headset connected but silent? Check the output device and microphone with this focused, step-by-step diagnosis and verification test."
keywords:
  - "Windows Bluetooth Headset Connected but No Sound: Check Output and Mic"
date: 2026-11-17T10:10:41+08:00
publishDate: 2026-11-17T10:10:41+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC lists the Bluetooth headset as connected, yet no audio comes out of it. That usually means Windows is sending sound to a different endpoint or the headset's output profile is not active. Work through this **Windows Bluetooth Headset Connected but No Sound: Check Output and Mic** sequence before changing drivers.

## Confirm the active output device
Open Settings > System > Sound. Under Output, confirm the headset is selected, not your monitor or speakers. If two entries exist (for example, Headset and Headphones), choose the one labeled Headset for calls or the stereo entry for media. Play a short system sound. If the volume meter moves but you hear nothing, the endpoint is wrong; if the meter stays flat, the app is muted or routed elsewhere.

## Check the microphone side
Still in Sound, open Input and select the headset microphone. Speak and watch the input meter. A flat meter means Windows is not receiving audio from the mic; a moving meter means the mic works and the problem is output-only.

## Verify with a controlled test
Open Sound > More sound settings > Playback, select the headset, click Test, and listen for the chime. Then use the Recording tab to listen to the microphone. This separates a device fault from an app routing issue.

## Rollback and recovery
If you recently changed default devices, right-click the previous device in Playback and choose Set as Default Device to restore it. If the headset disappears entirely, remove it in Settings > Bluetooth & devices, then pair it again.

If the meter still stays flat after these checks,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your Sound panel screenshots.
