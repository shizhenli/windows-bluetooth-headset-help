---
title: "Bluetooth Headset Mic Not Detected: Fix Apps That Can't See the Microphone"
description: "Apps can't select your Bluetooth headset microphone even though audio output works? Follow these focused checks to restore the microphone on Windows 11."
seo_title: "Bluetooth Headset Mic Not Detected on Windows 11: Practical Fix"
seo_description: "Apps can't select your Bluetooth headset microphone even though audio output works? Follow these focused checks to restore the microphone on Windows 11."
keywords:
  - "bluetooth headset mic not detected"
date: 2026-11-16T11:10:42+08:00
publishDate: 2026-11-16T11:10:42+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, sound plays fine, but apps can't select the microphone at all. Start by opening Settings > System > Sound > All sound devices and confirm your headset appears under both Output and Input. If it's missing from Input, the PC isn't exposing the hands-free profile, which is the usual reason for a **bluetooth headset mic not detected** state. Next, open Device Manager > Audio inputs and outputs and check for a microphone entry matching your headset. A downward arrow means disabled: right-click and enable it. A yellow warning means driver trouble: right-click, uninstall, then restart so Windows reinstalls it.

## Check the headset's own mic mode

Many headsets expose two Bluetooth profiles: high-quality stereo output (no mic) and hands-free (mic plus lower-quality audio). In Settings > Bluetooth & devices > Devices, open your headset and confirm hands-free telephony is enabled. Then, in Sound > Input, set the headset microphone as the default input device. If the input list still shows only the laptop mic, the headset isn't offering the mic profile and Windows can't detect it.

## Verify with a clean test

Open Settings > System > Sound > Input and speak while watching the input level meter. Then use Voice Recorder to record ten seconds and play it back. If the meter moves and the recording contains your voice, the microphone is working and the problem is app-specific: check the app's own audio settings and Windows microphone privacy permissions.

## Rollback and recovery

If changes made things worse, return to Device Manager, right-click the headset's audio entries, and choose Properties > Driver > Roll Back Driver. Re-pair the headset only after that, since removing it first can discard the rollback option.

If the input device never appears,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your Device Manager and Sound settings details.
