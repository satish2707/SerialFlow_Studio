# SerialFlow Studio

**Version:** v1.0.1  
**Platform:** Windows  
**Author:** Satish Kanawade

SerialFlow Studio is a professional USB-to-serial communication tool for firmware debugging, command testing, terminal monitoring, and serial data logging.

## What Is Included

| File | Description |
|---|---|
| `SerialFlow_Studio.exe` | Windows application |
| `SerialFlow_Studio_User_Guide.pdf` | Complete setup and usage guide |
| `SHA256SUMS.txt` | Checksums for file verification |

## Key Features

- Auto-detect available COM ports
- Select common baud rates such as 9600, 115200, and 921600
- Connect and disconnect from USB-to-serial devices
- View incoming serial data in a terminal-style window
- Send commands to the connected serial device
- Enable optional timestamps for received data
- Record serial logs to a text file
- Detect disconnected USB serial devices and update status safely

## Quick Start

1. Download `SerialFlow_Studio.exe`.
2. Connect your USB-to-serial adapter or target board.
3. Open SerialFlow Studio.
4. Select the COM port.
5. Select the baud rate used by your device.
6. Click **Connect**.
7. Use the terminal window to monitor data, send commands, and record logs.

For detailed instructions, open:

`SerialFlow_Studio_User_Guide.pdf`

## System Requirements

- Windows 10 or later
- USB-to-serial adapter or target device
- Correct Windows driver installed for the USB-to-serial chip
- Available COM port

## File Verification

Use `SHA256SUMS.txt` to verify that downloaded files match the published checksums.

PowerShell example:

```powershell
Get-FileHash .\SerialFlow_Studio.exe -Algorithm SHA256
```

Compare the result with the checksum listed in `SHA256SUMS.txt`.

## Notes

- This repository contains the public release package only.
- Source code is not included in this public repository.
- If Windows shows a security prompt, confirm that you downloaded the file from this repository before running it.

## License

Copyright (c) Satish Kanawade. All rights reserved.
