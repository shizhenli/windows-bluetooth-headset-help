---
title: "Bluetooth Headphones No Sound Windows 11: Fix the Connected but Silent Issue"
description: "Windows 11 shows your Bluetooth headphones connected but no sound? Follow these step-by-step checks to restore audio output and verify the fix."
seo_title: "Bluetooth Headphones No Sound Windows 11: Connected but Silent Fix"
seo_description: "Windows 11 shows your Bluetooth headphones connected but no sound? Follow these step-by-step checks to restore audio output and verify the fix."
keywords:
  - "bluetooth headphones no sound windows 11"
date: 2026-11-14T19:55:49+08:00
publishDate: 2026-11-14T19:55:49+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent, leaving you stuck before any controlled diagnosis. Let's walk through this together.

## Check the active output device

Right-click the speaker icon in the taskbar and choose Sound settings. Under Output, confirm your headset is selected. If it is not listed, click Add device and pair it again. If it is listed but marked as not plugged in or disconnected, proceed to the next check.

## Restart the Bluetooth service

Open Services (press Windows+R, type services.msc). Find Bluetooth Support Service, right-click it, and select Restart. Wait 10 seconds, then reconnect the headset. If the service was stopped, set its startup type to Automatic and start it.

## Run the audio troubleshooter

Go to Settings > System > Sound > Troubleshoot common sound problems. Select your headset when prompted. If the troubleshooter reports that the audio device is disabled, enable it in Device Manager under Sound, video and game controllers.

## Verify with a test sound

Play a short audio clip or use the Test button under Sound settings. If you hear sound, the issue is resolved. If not, right-click the headset in Sound settings, choose Properties, and under Advanced, uncheck Enable audio enhancements. Test again.

## Rollback if needed

If changes made things worse, return to Sound settings and set the previous output device as default. In Device Manager, right-click the headset and choose Properties > Driver > Roll Back Driver. This restores the prior driver state.

If the **bluetooth headphones no sound windows 11** problem persists after these steps, the cause may be a corrupted pairing profile. Remove the headset from Settings > Bluetooth & devices, restart the PC, and pair it fresh. Still stuck?

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) and we'll diagnose further.
