---
title: "Silent Bluetooth Headphones on Windows 11: When the Output Device Is Wrong"
description: "Windows 11 shows your Bluetooth headphones connected but silent? Check the output device, disable the headset profile, and verify with a test sound."
seo_title: "Windows 11 Bluetooth Headphones No Sound: Fix the Wrong Output Device"
seo_description: "Windows 11 shows your Bluetooth headphones connected but silent? Check the output device, disable the headset profile, and verify with a test sound."
keywords:
  - "windows 11 bluetooth headphones no sound"
date: 2026-11-26T08:09:22+08:00
publishDate: 2026-11-26T08:09:22+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You connected your Bluetooth headset to your Windows 11 PC, but the output stays silent even though Windows shows it as connected. This is the classic **windows 11 bluetooth headphones no sound** situation, and it usually comes down to the wrong playback device being selected. Let's fix that one issue.

## Check the active output device

Open Settings > System > Sound. Under Output, confirm your Bluetooth headset is selected. If it is not, choose it from the list. Then look at the volume slider for that device: if it sits at zero or is muted, raise it. Also click the device entry and check that the format is not set to something unusual; the default is fine.

## Disable the headset profile

In the same Sound settings, open More sound settings (or right-click the speaker icon and choose Sounds). On the Playback tab, find two entries for your headset: one labeled Headphones and one labeled Headset. Right-click the Headset entry and choose Disable. The Headset profile is for calls and often takes over output, leaving media silent. Keep Headphones enabled and set as Default Device.

## Verification test

Play a short local audio file or use the Test button in Sound settings. If you hear sound, the output path is fixed. If not, go back and confirm Headphones is still the default and the volume is up.

## Rollback note

If disabling the Headset profile causes your microphone to stop working in calls, re-enable it and instead set Headphones as the default playback device while leaving Headset for communication. You can reverse any change here at any time.

If the device still stays silent after these checks,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) and we will walk through the next diagnostic step.
