---
title: "Windows Microphone Not Working Bluetooth: Fix Apps That Can't Select the Headset Mic"
description: "Fix the Windows 11 Bluetooth headset microphone not available error when apps cannot select the mic even though audio output works. Step-by-step checks and verification."
seo_title: "Windows Microphone Not Working Bluetooth: Fix Apps Can't Select Headset Mic"
seo_description: "Fix the Windows 11 Bluetooth headset microphone not available error when apps cannot select the mic even though audio output works. Step-by-step checks and verification."
keywords:
  - "windows microphone not working bluetooth"
date: 2026-11-21T16:41:56+08:00
publishDate: 2026-11-21T16:41:56+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works, but apps show the microphone as not available and won't let you select it. Let's walk through a controlled diagnosis.

## Check the input device in Windows
Open Settings > System > Sound. Under Input, confirm your headset appears. If it doesn't, go to Bluetooth & devices and remove then re-pair the headset. If it appears but is disabled, click it and select Set as default. Result interpretation: if the device is listed but grayed out, the driver or privacy setting is blocking it.

## Verify microphone privacy and app permissions
Go to Settings > Privacy & security > Microphone. Ensure Microphone access is on and Let apps access your microphone is on. Under Let desktop apps access your microphone, confirm the toggle is on. Then scroll to the specific app and enable it. If the app is missing, it may be a desktop app that relies on the global toggle.

## Check the sound control panel
Right-click the speaker icon and choose Sounds > Recording. If your headset mic is absent, right-click and select Show Disabled Devices. If it appears disabled, right-click and Enable. Then open Properties > Levels and confirm the mic isn't muted and the level is above zero. This is a common cause of **windows microphone not working bluetooth** symptoms.

## Run a verification test
Open Settings > System > Sound > Input and speak; the test bar should move. Then test in the app that failed. If the bar moves in Settings but not in the app, the app's own audio settings need the headset mic selected.

## Rollback note
If you recently changed drivers or privacy settings, reverse the last change: re-enable the previous default input or reinstall the Bluetooth driver from Device Manager. If the mic remains unavailable,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your device model and the exact app name.
