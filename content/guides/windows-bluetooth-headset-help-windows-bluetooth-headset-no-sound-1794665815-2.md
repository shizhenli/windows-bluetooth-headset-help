---
title: "Windows Bluetooth Headset No Sound: Fix the Connected but Silent Output"
description: "Fix Windows 11 Bluetooth headset connected but no sound by checking the active output device, disabling the hands-free profile, and running a verification test."
seo_title: "Windows Bluetooth Headset No Sound: Connected but Silent Fix"
seo_description: "Fix Windows 11 Bluetooth headset connected but no sound by checking the active output device, disabling the hands-free profile, and running a verification test."
keywords:
  - "windows bluetooth headset no sound"
date: 2026-11-21T16:38:53+08:00
publishDate: 2026-11-21T16:38:53+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent and you need to restore normal audio.

## Confirm the active output device

Open Settings > System > Sound. Under Output, select your Bluetooth headset, not the hands-free or headset microphone entry. If Windows lists two entries for the same device, choose the stereo one. Then play a short system sound and watch the volume meter next to the device. If the meter moves but you hear nothing, the headset is muted or at zero volume. If the meter does not move, Windows is still routing audio elsewhere, which is the usual cause of **windows bluetooth headset no sound**.

## Remove the hands-free profile conflict

Open Control Panel > Hardware and Sound > Devices and Printers. Right-click the headset, choose Properties, and open the Services tab. Clear the Hands-free Telephony checkbox, click Apply, then reconnect the headset. This stops Windows from switching to the low-quality call profile that can silence playback.

## Verify with a controlled test

Set the headset as the default output device, play a local audio file for ten seconds, and confirm sound comes through the headset while the Sound meter responds. Then open a video call app and check that its own audio settings also point to the headset.

## Rollback if needed

If the headset still stays silent, return to the Services tab and re-enable Hands-free Telephony, then remove and re-pair the headset. If the problem persists,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your device model and the Sound panel result.
