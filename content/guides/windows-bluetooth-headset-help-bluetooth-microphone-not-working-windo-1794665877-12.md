---
title: "Bluetooth Microphone Not Working Windows: Fix the 'Microphone Not Available' Step"
description: "Windows 11 can't select your Bluetooth headset microphone even though audio output works? Follow these focused steps to resolve the 'microphone is not available' error and restore mic access."
seo_title: "Bluetooth Microphone Not Working Windows: Fix 'Microphone Not Available'"
seo_description: "Windows 11 can't select your Bluetooth headset microphone even though audio output works? Follow these focused steps to resolve the 'microphone is not available' error and restore mic access."
keywords:
  - "bluetooth microphone not working windows"
date: 2026-11-21T16:44:59+08:00
publishDate: 2026-11-21T16:44:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on Windows 11 with a Bluetooth headset, audio plays fine, but apps show the microphone is not available and won't let you select the headset mic. This is a common **bluetooth microphone not working windows** issue, and it usually comes down to the headset being stuck in playback-only mode or the mic being disabled in Windows settings.

## Check the input device in Sound settings

Right-click the speaker icon in the taskbar and choose Sound settings. Under Input, see if your headset appears. If it's listed but marked as not plugged in or disabled, click it and select Set as default. If it doesn't appear at all, go to More sound settings > Recording tab, right-click in the empty area, and enable Show Disabled Devices. If your headset shows up greyed out, right-click and choose Enable.

## Verify the headset's microphone mode

Many Bluetooth headsets have two profiles: stereo playback (A2DP) and hands-free (HFP) with microphone. Windows sometimes keeps only the stereo profile active. In Sound settings, under Input, if you see a Hands-Free AG Audio entry, select it. Then test by speaking—the input level bar should move. If it stays flat, the headset may have a physical mute switch or the mic boom is flipped up.

## Run a quick verification test

Open Voice Recorder or Settings > System > Sound > Test your microphone. Speak normally. If the bar moves and you hear your recording, the mic is working. If not, proceed to the rollback step.

## Rollback and recovery

If changes made things worse, go to Settings > Bluetooth & devices > Devices, remove your headset, then pair it again. Also, in Device Manager under Sound, video and game controllers, right-click your Bluetooth audio device and choose Properties > Driver > Roll Back Driver if available. This restores the previous driver state.

Still stuck?

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for a focused diagnosis.
