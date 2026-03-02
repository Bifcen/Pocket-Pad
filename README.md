# PocketPad

Turn your Android handheld into a wireless Bluetooth HID gamepad. Windows and other devices will see it as a real game controller — no extra software needed on the host.

## Download

Head to [**Releases**](../../releases/latest) to grab the latest APK.

## Features

- **Bluetooth HID Gamepad** — Registers as a native game controller, no receiver app or drivers needed
- **Full Controller Support** — Buttons, analog sticks, triggers, D-pad, bumpers, thumbstick clicks
- **Low Latency** — Event-driven input pipeline, compact 8-byte HID reports
- **Screen Dim + OLED Black** — Dims screen on inactivity, optional full-black overlay for OLED panels
- **Hair Triggers** — Per-trigger option for instant full-press at minimal physical input
- **Configurable Deadzones** — Per-stick deadzone sliders (0–20%) with scaled output
- **Exclusive Button Mode** — Prevents gamepad buttons from navigating Android while active
- **Foreground Service** — Keeps Bluetooth connection alive when backgrounded

## Requirements

- Android 9+
- Bluetooth on both device and host
- Host that supports Bluetooth HID gamepads (Windows 10/11, etc.)

## How to Use

1. Install the APK and launch PocketPad
2. Tap **Start Gamepad** and allow Bluetooth discoverability
3. On your PC: Settings > Bluetooth > Add device > Select **PocketPad**
4. Pair and start gaming

## Author

Rob Jobse — [robjobse.com/rjlabs](https://robjobse.com/rjlabs)

## License

GNU General Public License v3.0