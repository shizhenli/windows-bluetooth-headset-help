---
title: "Windows 11 Bluetooth Headset: Fix 'Microphone Not Available' When Audio Output Works"
description: "Step-by-step fix for Windows 11 when your Bluetooth headset microphone is not available in apps, even though audio output works. Includes checks, verification, and rollback."
seo_title: "Windows Microphone Not Working Bluetooth: Fix 'Microphone Not Available'"
seo_description: "Step-by-step fix for Windows 11 when your Bluetooth headset microphone is not available in apps, even though audio output works. Includes checks, verification, and rollback."
keywords:
  - "windows microphone not working bluetooth"
date: 2026-11-25T09:11:03+08:00
publishDate: 2026-11-25T09:11:03+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You're on a Windows 11 PC with a Bluetooth headset, audio output works fine, but apps can't select the headset microphone—you're stuck at 'microphone is not available' before any controlled diagnosis. This focused fix addresses that specific failure.

## Check the input device and privacy settings

Open Settings > System > Sound. Under Input, confirm your headset appears and is selected. If it's missing, click Add device and pair it again. Next, go to Settings > Privacy & security > Microphone and ensure Microphone access is on and Let apps access your microphone is on. Under Let apps access your microphone, verify the specific app (e.g., Voice Recorder) is allowed. If the headset shows as 'Not plugged in' or 'Disabled', right-click it in Sound settings and choose Enable. This is the most common cause of **windows microphone not working bluetooth** when output is fine.

## Verify with a controlled test

Open Voice Recorder (or Sound Recorder) and record 5 seconds. Play it back. If you hear your voice, the microphone path works. If the app shows 'No microphone found', return to Sound settings and set the headset as the default input device. Also check Device Manager > Audio inputs and outputs: if the headset microphone has a yellow warning, right-click and Update driver, then restart.

## Rollback and recovery

If changes made things worse, use Settings > System > Sound > Manage sound devices to reset to your previous default input. In Device Manager, right-click the headset microphone and choose Properties > Driver > Roll Back Driver if available. If not, uninstall the device and restart to let Windows reinstall it.

If the microphone still isn't available after these steps,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for a guided diagnosis.
