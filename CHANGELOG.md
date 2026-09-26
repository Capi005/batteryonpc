# Changelog

Updates install automatically. Download: [batteryonpc.com](https://batteryonpc.com)

## 2.0.11 (September 26, 2026)

Over 280 supported models: 77 more in the list.

- **Headsets:** Logitech G930, HyperX Cloud III Wireless, Cloud III S Wireless, Cloud II Core Wireless and Cloud Stinger 2 Wireless, Sony INZONE H9 and INZONE H9 II, MCHOSE V9 Turbo+.
- **Mice:** Corsair Dark Core RGB and Dark Core RGB SE, SteelSeries Aerox 3 Wireless Gen 2, HyperX Pulsefire Dart and Pulsefire Saga Pro, Sony INZONE Mouse-A, ATK A9, Razer Lancehead, five more WLMOUSE mice (HUAN, Strider, Ying, Beast Mini, Beast Mini Pro) and 37 older Logitech mice (MX Master, MX Anywhere 2, Performance MX, MX Air, G700s and more).
- **Keyboards:** Corsair K63 Wireless and 18 older Logitech keyboards (K270, K400, K830, MK270 and more).

Also in this version:

- **A device that is off from the start now shows grey** instead of a "?", like any device that is off or out of range, and the help for unreadable devices no longer appears for it.
- **Razer Nari:** the app now waits for the headset's actual reply and no longer takes an empty reply for a level.
- **Sony INZONE H9 (first model):** read while INZONE Hub is closed, because INZONE Hub keeps the headset's connection to itself.

## 2.0.10 (September 25, 2026)

Devices that were misread or not read:

- **GameSir Cyclone 2:** Windows sees it as a wired Xbox controller with no battery. Its real level is now read from its 2.4 GHz dongle and shown on the controller icon.
- **MCHOSE X9 headset:** it no longer beeps every few seconds. The app now listens to the level the headset sends by itself, and only asks after 30 minutes without news.
- **VXE and Pulsar mice** are now read, with the same protocol as the ATK mice (same family of receivers).
- **Razer Viper V3 Pro:** fixed on PCs where it stayed at "?" because Windows keeps its main interface to itself.
- **First-generation DualShock 4** (CUH-ZCT1) is now recognized.
- **Fewer false anonymous reports:** a device is reported as unreadable only after 3 missed readings over at least one minute, no longer after a single miss (asleep, waking up).

New devices: WLMOUSE 8K mice (Beast MAX 8K, Beast X Pro 8K, Beast X 8K, Sword X 8K, Miao 8K), Audeze Maxwell 2, Flydigi Apex 6 and Apex 6 Pro, Jabra Evolve2 65 Flex over USB, more Corsair Void Wireless variants.

## 2.0.9 (September 24, 2026)

- **The window always fits on screen.** It opens inside the usable area of the screen under the mouse, whatever the resolution and scaling. Before, it could open partly off screen, for example on a 4K display at 300%.
- **"Fully charged" once per real charge.** A device that hovers between 90 and 100% no longer repeats the notification. A new one comes only after a real discharge (85% or less for at least 2 minutes), and at most once every 30 minutes per device.
- **New option for each device:** "Warn when the battery is fully charged", on by default, in its card of the Notifications tab.
- **New gear button in the Devices tab:** it opens the notification settings of that device.
- Clearer help text about the icon colors (red below 25%).

## 2.0.8 (September 21, 2026)

- In the Devices tab, each tracked device's icon now takes the color of its battery level.
- When a device is detected but cannot be read (a "?"), a help block explains why and what to do, and a help notification appears right after adding such a device.
