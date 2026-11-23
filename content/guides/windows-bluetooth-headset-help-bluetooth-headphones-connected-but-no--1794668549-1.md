---
title: "Bluetooth Headset Connected but No Sound on Windows 11: Resolve the Silent Output"
description: "Windows 11 shows your Bluetooth headset connected but no sound plays. Follow these focused checks to restore audio output."
seo_title: "Bluetooth Headphones Connected but No Sound Windows 11: Fix Silent Output"
seo_description: "Windows 11 shows your Bluetooth headset connected but no sound plays. Follow these focused checks to restore audio output."
keywords:
  - "bluetooth headphones connected but no sound windows 11"
date: 2026-11-23T11:11:08+08:00
publishDate: 2026-11-23T11:11:08+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent, leaving you stuck before any controlled diagnosis. Here’s how to fix that specific failure.

## Check the active output device
Open Settings > System > Sound. Under Output, confirm your Bluetooth headset is selected. If it isn’t, click it and test sound. If it is selected but still silent, click the device and check its volume level—make sure it’s not at 0 or muted. Also, open the volume mixer (right-click the speaker icon) and verify the headset isn’t muted for individual apps.

## Disable exclusive mode and enhancements
In Sound settings, go to More sound settings > Playback tab. Right-click your headset > Properties > Advanced. Uncheck “Allow applications to take exclusive control of this device” and “Enable audio enhancements.” Click Apply. This often resolves the **bluetooth headphones connected but no sound windows 11** issue when the device is connected but silent.

## Run the audio troubleshooter
Go to Settings > System > Sound > Troubleshoot common sound problems. Select your headset when prompted and follow the results. If the troubleshooter finds and fixes an issue, test audio immediately.

## Verification test
Play a short audio file or use the Test button in Sound settings. You should hear sound through the headset. If you do, the fix worked.

## Rollback note
If changes cause new problems, return to the Properties > Advanced tab and re-enable exclusive mode and enhancements. Then restart the Bluetooth service: press Win+R, type services.msc, find Bluetooth Support Service, and restart it.

If the headset still stays silent after these steps,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) for a guided diagnosis.
