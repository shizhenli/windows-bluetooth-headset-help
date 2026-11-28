---
title: "Headset Shows Connected in Windows 11 but Plays No Audio: Resolve the Silent Output"
description: "Windows 11 shows your Bluetooth headset connected but no sound plays. Follow these focused checks to restore audio output and verify the fix."
seo_title: "Windows Bluetooth Headset Connected but No Audio: Fix Silent Output"
seo_description: "Windows 11 shows your Bluetooth headset connected but no sound plays. Follow these focused checks to restore audio output and verify the fix."
keywords:
  - "windows bluetooth headset connected but no audio"
date: 2026-11-28T22:00:22+08:00
publishDate: 2026-11-28T22:00:22+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You see your Bluetooth headset listed as connected in Windows 11, yet no sound comes through it. This is a common **windows bluetooth headset connected but no audio** situation, and it usually comes down to the output device selection or a stale Bluetooth link. Let's work through it step by step.

## Check the active output device

Open Settings > System > Sound. Under Output, confirm your headset is selected. If it shows as an option but is not active, click it. Then look at the volume slider—make sure it is not at zero or muted. If the headset is not listed at all, click the arrow next to the current output to see more devices.

## Verify the correct profile

Bluetooth headsets often expose two profiles: Stereo (high-quality playback) and Hands-Free (for calls). If you are playing music, select the Stereo option. If only Hands-Free appears, audio may route to the mono call channel and sound wrong or silent. Switch to Stereo if available.

## Reconnect the headset

Go to Settings > Bluetooth & devices. Find your headset, click the three dots, and choose Remove device. Then put the headset in pairing mode and add it again. This clears a stuck connection state that can leave the output silent.

## Run a verification test

Play a short audio clip or use the Windows sound test in Settings > System > Sound > More sound settings > Playback. Select your headset, click Properties, then Test. You should hear the test tone in both ears. If you do, the issue is resolved.

## Rollback note

If audio still fails after re-pairing, open Device Manager, expand Bluetooth, right-click your headset adapter, and choose Properties > Driver > Roll Back Driver. This reverts to the previous driver if a recent update caused the silence.

If these steps do not restore sound,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact device details.
