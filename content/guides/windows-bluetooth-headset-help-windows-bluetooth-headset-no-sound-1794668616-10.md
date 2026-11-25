---
title: "Windows 11 Bluetooth Headset Connected but Silent: Fix the No-Sound Output"
description: "Windows 11 shows your Bluetooth headset connected but no sound plays. Follow these focused checks to restore audio output without reinstalling drivers."
seo_title: "Windows Bluetooth Headset No Sound: Fix Connected but Silent"
seo_description: "Windows 11 shows your Bluetooth headset connected but no sound plays. Follow these focused checks to restore audio output without reinstalling drivers."
keywords:
  - "windows bluetooth headset no sound"
date: 2026-11-25T08:11:00+08:00
publishDate: 2026-11-25T08:11:00+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

You have a Bluetooth headset paired and connected on Windows 11, but the output stays silent, and you want to fix this **windows bluetooth headset no sound** issue without a full reinstall.

## Check the active output device

Open Settings > System > Sound. Under Output, confirm your headset is selected. If Windows shows two entries for the same headset (for example, "Headset" and "Headphones"), select the one labeled Headset. Play a short system sound. If you hear it, the issue was the wrong profile; stop here.

## Verify the Bluetooth profile

Go to Settings > Bluetooth & devices > Devices, select your headset, and open More Bluetooth options. In the Services tab, ensure Hands-free Telephony and Audio Sink are checked. If Audio Sink is unchecked, check it and click Apply. Then return to Sound settings and test again. No sound after this means the profile did not bind; continue.

## Restart the audio stack

Open Services (services.msc). Find Windows Audio and Windows Audio Endpoint Builder. Right-click each and choose Restart. Wait ten seconds, then play a test sound. If audio returns, the endpoint had stalled. If not, proceed to the verification test.

## Verification test

Disconnect the headset, wait five seconds, and reconnect. Open Sound settings and click Test next to the headset output. A tone should play. If it does not, right-click the speaker icon in the taskbar, choose Sound settings, and set the headset as both default device and default communication device.

## Rollback and recovery

If you changed the Bluetooth service settings, return to More Bluetooth options > Services and restore the previous checkboxes. If audio still fails, remove the headset under Bluetooth & devices, then pair it again. For hands-on diagnosis,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
