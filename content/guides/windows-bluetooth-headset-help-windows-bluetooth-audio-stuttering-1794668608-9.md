---
title: "Windows 11 Bluetooth Headset Audio Cuts Out During Playback: Stop the Dropouts"
description: "Stop Bluetooth audio from cutting in and out on your Windows 11 PC while media plays. Follow these focused checks to fix windows bluetooth audio stuttering."
seo_title: "Windows 11 Bluetooth Audio Stuttering: Fix Audio Cutting Out During Playback"
seo_description: "Stop Bluetooth audio from cutting in and out on your Windows 11 PC while media plays. Follow these focused checks to fix windows bluetooth audio stuttering."
keywords:
  - "windows bluetooth audio stuttering"
date: 2026-11-24T12:13:20+08:00
publishDate: 2026-11-24T12:13:20+08:00
draft: false
categories:
  - "Audio Devices"
category_slug: "audio-devices"
---

Your Bluetooth headset stays connected, but the audio cuts in and out while media plays on your Windows 11 PC. This points to a link-timing or power issue, not a pairing failure.

## Check the 2.4 GHz neighborhood

Open Settings > System > Sound > More sound settings > Playback. Select your headset, click Properties > Advanced, and note the default format. If it is set to 24-bit or a high sample rate, change it to 16 bit, 44100 Hz (CD Quality), click Apply, then Test. If the test tone plays without gaps, keep that setting. Also move the headset and PC away from Wi-Fi routers, USB 3.0 hubs, and microwaves; these crowd the 2.4 GHz band and cause brief dropouts.

## Disable power saving on the radio

Open Device Manager, expand Bluetooth, right-click your adapter, and choose Properties > Power Management. Clear "Allow the computer to turn off this device to save power" and click OK. Then open Control Panel > Power Options > Change plan settings > Change advanced power settings > USB settings > USB selective suspend setting and set it to Disabled. This stops Windows from briefly parking the Bluetooth radio during playback, a common cause of **windows bluetooth audio stuttering**.

## Verification test

Play a local audio file for two minutes with the headset at normal volume. If the sound is continuous, the fix holds. If dropouts return, reconnect the headset once and repeat the test.

## Rollback note

If audio becomes unstable after changing the sample rate, return to the previous format in the same Properties > Advanced tab and click Restore Defaults. Power settings can be re-enabled the same way.

If dropouts persist,

![Windows sound settings showing a Bluetooth headset output and microphone](/images/service-detail-960.webp "Windows Bluetooth output and microphone check")

[Ask for help](/#consult).
