---
title: "Bluetooth Headset Mic Not Detected: Fix the 'Microphone Not Available' Error on Windows 11"
description: "Apps can't select your Bluetooth headset microphone even though audio output works? Follow these focused steps to fix the 'microphone not available' error on Windows 11."
seo_title: "Bluetooth Headset Mic Not Detected on Windows 11? Fix It Now"
seo_description: "Apps can't select your Bluetooth headset microphone even though audio output works? Follow these focused steps to fix the 'microphone not available' error on Windows 11."
keywords:
  - "bluetooth headset mic not detected"
date: 2026-11-24T11:11:11+08:00
publishDate: 2026-11-24T11:11:11+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but apps still can't select the headset microphone and show 'microphone not available.'

## Check the input device and its status

Open Settings > System > Sound > Input. Under 'Choose a device for speaking,' confirm your headset appears. If it doesn't, click Add device and pair it again. If it appears but is marked 'Not plugged in' or disabled, click it and select Enable. Then open Device Manager (Win+X > Device Manager), expand Audio inputs and outputs, and look for your headset mic. A downward arrow means disabled; right-click and choose Enable device. A yellow warning icon means a driver problem; right-click and choose Update driver > Search automatically.

## Confirm app-level access and permissions

Go to Settings > Privacy & security > Microphone. Turn on 'Microphone access' and 'Let apps access your microphone.' Under 'Let desktop apps access your microphone,' make sure the toggle is on. In the app itself (for example, Teams or Zoom), open its audio settings and select your Bluetooth headset as the microphone. If the app still shows 'microphone not available,' close and reopen it so it re-enumerates devices.

## Verify with a quick test

Open Settings > System > Sound > Input and speak into the mic. Watch the input level bar; it should move. If it stays flat, the **bluetooth headset mic not detected** issue persists. Also test with Voice Recorder to confirm the device works outside a single app.

## Rollback and recovery

If a recent driver or Windows update caused this, open Device Manager, right-click the headset mic, choose Properties > Driver > Roll Back Driver. If rollback is unavailable, uninstall the device and restart; Windows will reinstall it. Re-pair the headset afterward if needed.

If these steps don't restore the microphone,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your Sound settings and Device Manager details.
