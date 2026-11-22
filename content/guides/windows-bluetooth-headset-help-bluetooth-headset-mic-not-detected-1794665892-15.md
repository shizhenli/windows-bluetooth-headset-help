---
title: "Bluetooth Headset Mic Not Detected in Windows 11: Fix the Unavailable Microphone"
description: "Apps can't find your Bluetooth headset microphone even though sound plays? Follow these focused checks to fix the bluetooth headset mic not detected error on Windows 11."
seo_title: "Bluetooth Headset Mic Not Detected on Windows 11: Step-by-Step Fix"
seo_description: "Apps can't find your Bluetooth headset microphone even though sound plays? Follow these focused checks to fix the bluetooth headset mic not detected error on Windows 11."
keywords:
  - "bluetooth headset mic not detected"
date: 2026-11-22T08:11:04+08:00
publishDate: 2026-11-22T08:11:04+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but apps still show the microphone as not available. Here's how to diagnose and fix the **bluetooth headset mic not detected** issue without guessing.

## Check the Bluetooth Profile and Default Input

Open Settings > Bluetooth & devices > Devices. Find your headset and click it. Under Audio, confirm both Music and Calls are enabled. If Calls is missing, remove the device and pair it again. Next, go to System > Sound. Under Input, select your headset microphone. If it doesn't appear, click Manage sound devices and check whether it's listed as disabled. A disabled entry means Windows sees the device but isn't exposing it to apps.

## Verify Microphone Privacy and Driver State

Open Settings > Privacy & security > Microphone. Ensure Microphone access is on and Let apps access your microphone is on. Then open Device Manager, expand Audio inputs and outputs, and look for your headset mic. A yellow warning icon indicates a driver problem; right-click and choose Update driver. If no warning appears, right-click the headset entry and select Uninstall device, then restart the PC so Windows reinstalls it.

## Run a Verification Test

Open Settings > System > Sound > Input and speak into the mic. The input level bar should move. If it stays flat, return to Manage sound devices and confirm the correct endpoint is set as default. Also test in Voice Recorder to rule out app-specific issues.

## Rollback and Recovery

If the mic worked before a driver update, open Device Manager, right-click the audio device, choose Properties > Driver > Roll Back Driver. If rollback is unavailable, use System Restore to return to a prior working state.

If these steps don't restore the microphone,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your device details.
