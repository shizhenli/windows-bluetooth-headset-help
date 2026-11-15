---
title: "Bluetooth Headphones Connected but No Sound on Windows 11: A Focused Fix"
description: "Windows 11 shows your Bluetooth headset connected but silent? Follow these focused checks to restore audio output without reinstalling drivers."
seo_title: "Bluetooth Headphones Connected but No Sound Windows 11"
seo_description: "Windows 11 shows your Bluetooth headset connected but silent? Follow these focused checks to restore audio output without reinstalling drivers."
keywords:
  - "bluetooth headphones connected but no sound windows 11"
date: 2026-11-15T19:14:59+08:00
publishDate: 2026-11-15T19:14:59+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Windows 11 PC shows the Bluetooth headset connected, but the output device stays silent. Let's walk through a controlled diagnosis to fix **bluetooth headphones connected but no sound windows 11**.

## Check the active output device

Right-click the speaker icon in the taskbar and choose Sound settings. Under Output, confirm your headset is selected. If it is not listed, click Add device and pair it again. If it is listed but marked as Disabled, click it and choose Enable. Result interpretation: if the headset appears only under Input, Windows is treating it as a microphone-only device; proceed to the next check.

## Verify the correct playback endpoint

In Sound settings, click your headset and open its properties. Under the Advanced tab, note the default format. If it is set to a format the headset does not support, such as 24-bit/192000 Hz, change it to 16-bit/48000 Hz and click Test. You should hear a chime from the headset. If you hear nothing, continue.

## Disable exclusive mode and enhancements

On the same properties page, open the Advanced tab and uncheck Allow applications to take exclusive control of this device. Then open the Enhancements tab and check Disable all enhancements. Click Apply. This resolves cases where an app holds the audio stream silently.

## Run the built-in audio test

Open Settings > System > Sound > Troubleshoot. Select your headset as the device and run the troubleshooter. If it reports that the device is not set as default, apply the fix. Then play a short local audio file. You should hear sound through the headset.

## Rollback note

If audio still fails, return to Sound settings, select your previous output device, and set it as default. Then remove the headset from Bluetooth devices and pair it again. This restores your prior working state before further changes.

If these steps do not restore sound,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult) with your exact device name and Windows build.
