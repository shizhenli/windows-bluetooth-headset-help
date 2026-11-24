---
title: "Bluetooth Microphone Not Working Windows: Fix 'Microphone Is Not Available'"
description: "Fix the Windows 11 error where apps cannot select your Bluetooth headset microphone even though audio output works. Step-by-step diagnosis and recovery."
seo_title: "Bluetooth Microphone Not Working Windows: Fix 'Microphone Is Not Available'"
seo_description: "Fix the Windows 11 error where apps cannot select your Bluetooth headset microphone even though audio output works. Step-by-step diagnosis and recovery."
keywords:
  - "bluetooth microphone not working windows"
date: 2026-11-24T08:11:00+08:00
publishDate: 2026-11-24T08:11:00+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You are on a Windows 11 PC with a Bluetooth headset, audio output works, but apps cannot select the headset microphone and show "microphone is not available."

## Confirm the headset exposes a microphone endpoint

Open Settings > System > Sound > All sound devices. Under Input devices, look for your headset name. If it appears but is disabled, click it and set it to Allow. If it does not appear at all, the headset is connected only in playback mode; proceed to the next section. If it appears and is enabled, skip to the verification test.

## Force the hands-free profile

Open Control Panel > Hardware and Sound > Devices and Printers. Right-click your headset and choose Properties > Services. Confirm Hands-Free Telephony is checked. If it is not, check it, click Apply, then disconnect and reconnect the headset. Interpretation: after reconnecting, the Input devices list should now show a second endpoint labeled Hands-Free AG Audio. If it still does not, remove the device from Settings > Bluetooth & devices, then pair it again.

## Verification test

Open Settings > System > Sound > All sound devices > your headset microphone > Test your microphone. Speak normally. A moving input level confirms the endpoint is live. Then open the app that failed, select the Hands-Free AG Audio microphone, and test again. If the meter moves in Settings but not in the app, the app is holding a stale device list; restart the app.

## Rollback and recovery

Before changing Services or re-pairing, note your original settings. If the microphone stops working after a driver or Windows update, open Device Manager > Bluetooth, right-click the adapter, choose Properties > Driver > Roll Back Driver. If rollback is unavailable, re-pair the headset to restore the previous working state.

If the input endpoint never appears after re-pairing, this is a deeper **bluetooth microphone not working windows** issue that needs a focused diagnostic.

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
