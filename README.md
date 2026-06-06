# OPAutoClicker

A free, lightweight auto-clicker for Windows that automates mouse clicks at user-defined intervals.

## Features

- Adjustable click interval (hours, minutes, seconds, milliseconds)
- Single click, double click, or triple click options
- Left, middle, or right mouse button support
- Repeat a fixed number of times or click until stopped
- Click at the current cursor position or a fixed location
- Customizable global hotkeys for start/stop
- Lightweight with minimal system resource usage

## Installation

1. Download the latest release from the [Releases](../../releases) page.
2. Extract the archive to a folder of your choice.
3. Run `OPAutoClicker.exe`.

No installation is required — the application is portable.

### Requirements

- Windows 7 or later
- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework) (if not bundled)

## Usage

1. Set your desired **click interval**.
2. Choose the **click type** (single/double) and **mouse button**.
3. Select **click repeat** behavior (repeat N times or repeat until stopped).
4. Set the **cursor position** (current location or a fixed point).
5. Press the start hotkey (default `F6`) to begin, and the same hotkey to stop.

### Default Hotkey

| Action | Key |
|--------|-----|
| Start / Stop | `F6` |

You can change the hotkey under **Settings → Hotkey setting**.

## Building from Source

```bash
git clone https://github.com/yourusername/opautoclicker.git
cd opautoclicker
```

Open the solution file in **Visual Studio** and build the project (Release configuration recommended).

## Contributing

Contributions are welcome. Please fork the repository, create a feature branch, and open a pull request. For major changes, open an issue first to discuss what you would like to change.

## License

This project is released under the [MIT License](LICENSE).

## Disclaimer

This tool is intended for legitimate automation tasks. Use of auto-clickers may violate the terms of service of some applications and games. Use responsibly and at your own risk.
