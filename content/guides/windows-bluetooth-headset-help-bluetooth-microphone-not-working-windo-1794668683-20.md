---
title: "Bluetooth Microphone Not Working Windows: Fix 'Microphone Not Available' Before Diagnosing Further"
description: "Stuck at 'microphone is not available' on Windows 11? Follow these focused steps to restore your Bluetooth headset microphone when apps can't select it."
seo_title: "Bluetooth Microphone Not Working Windows: Fix 'Microphone Not Available' Error"
seo_description: "Stuck at 'microphone is not available' on Windows 11? Follow these focused steps to restore your Bluetooth headset microphone when apps can't select it."
keywords:
  - "bluetooth microphone not working windows"
date: 2026-11-26T10:09:17+08:00
publishDate: 2026-11-26T10:09:17+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works, but apps show the microphone is not available and won't let you select the headset mic. This is a common **bluetooth microphone not working windows** symptom, and it usually means Windows hasn't enabled the headset's microphone endpoint or an app is holding it exclusively.

## Check the microphone endpoint

Open Settings > System > Sound. Under Input, click your Bluetooth headset. If it's missing, click Manage sound devices and look under Disabled. If the headset mic appears but is disabled, enable it. If it's enabled but shows no input level when you speak, proceed to the next check.

## Verify app permissions and exclusive mode

Go to Settings > Privacy & security > Microphone. Make sure Microphone access is on and the specific app is allowed. Then in Sound settings, select the headset mic, click Device properties > Additional device properties > Advanced. Uncheck Allow applications to take exclusive control of this device, click Apply. This often resolves apps that can't select the mic.

## Restart the Bluetooth service

Press Win+R, type services.msc, and press Enter. Find Bluetooth Support Service, right-click and choose Restart. If it's stopped, start it. Then disconnect and reconnect the headset.

## Verification test

Open Voice Recorder and record a short clip. Play it back. If you hear your voice, the mic is working. Also check Sound settings > Input and confirm the level meter moves when you speak. If it does, the issue is app-specific.

## Rollback note

If you changed exclusive mode or permissions and the mic stops working elsewhere, reverse the last change. If the problem persists,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for a guided diagnosis.
