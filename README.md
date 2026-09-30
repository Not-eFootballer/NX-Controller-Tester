# Controller Tester — Nintendo Switch

**Joy-Con · DualShock 3 (PS3) · DualShock 4 (PS4) · DualSense (PS5) · PS1 / PS2 (via SuperBox 3)**

**By Not_eFootballer**

Nintendo Switch homebrew (`.nro`) to test your controllers in real time. It runs from the Homebrew Menu, needs no sysmodule, and changes nothing on the console.

## Features

- **Controller**: every button, the D-pad, the sticks (X/Y values and %), the triggers, the battery, rumble (left, right, both) and the motion sensors.
- **Drift**: stick trails, ×10 center zoom, 3-second resting measurement with a verdict, circularity test.
- **USB**: diagnostics for controllers plugged in over USB.

## Tested controllers

| Controller | Connection |
|---|---|
| Joy-Con | Bluetooth / rail |
| DualShock 3 (PS3) | USB cable |
| DualShock 4 (PS4) | USB cable |
| DualSense (PS5) | USB cable |
| PS1 / PS2 | **SuperBox 3** USB adapter |

### PS1 / PS2 controllers

PlayStation 1 and 2 controllers have no USB port, so you need an adapter. Plug the controller into a **SuperBox 3**, then plug the SuperBox 3 into the Switch (into the dock, or through a USB-C OTG adapter in handheld mode). The app detects it automatically and shows the controller with the PlayStation layout.

### PS3 / PS4 / PS5 controllers

Just plug them in with a USB cable: they work in the app right away, even though the Switch doesn't support them on its own.

## Installation

1. Download `NXControllerTester.nro` from the **Releases**.
2. Copy it to `sd:/switch/NXControllerTester/`.
3. Open the Homebrew Menu (ideally by holding **R** while launching a game) and start **Controller Tester**.

## Controls

Hold **+** (or **−**), then:

| Button | Action |
|---|---|
| L / R | Previous / next page |
| Up / Down | Choose the displayed controller |
| A | Full rumble test |
| ← / → | Left / right motor |
| X | Resting drift measurement |
| Y | Reset statistics |
| **B held for 1 s** | **Quit** (or press HOME twice) |

The touchscreen also works for the tabs, the controller list and rumble.

Tested on firmware 21.0.1 with Atmosphère 1.10.1.
