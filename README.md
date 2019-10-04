This sample sketch make M5Stack working as a BLE(HID Over GATT Profile) mouse.

- It works on Windows PC and Android devices.
- I tried with iOS13(Assistive Touch), then it connects to iOS Device but reporting(cursol movement and button click) is not work. I don't know the reason why it doesn't work.

## Usage

1. After boot up, connect from BLECentral.
1. Left button recognize multiple clicks.
  1. Single click: Change direction, Up-Down mode <-> Right-Left mode.
  1. Double click: Emulates Mouse click(left button).
  1. Triple click: Emulates Mouse click(right button).
1. Middle button moves cursol to Up or Left.
1. Right button moves cursol to Down or Right.

## Development

If you change Report Map structure, you need to unpair M5Stack and BLECentral.

## Acknowledgment

This program is much inspired by [M5StackHIDCtrlAltDel](https://github.com/mhama/M5StackHIDCtrlAltDel).

## License

MIT
