# Packet Capture Tool

This Python-based network packet capture tool leverages the `pyshark` library for real-time packet sniffing and pcap file analysis. It supports both Windows and Unix-like systems, offering users the ability to capture and analyze network traffic using a variety of interfaces.

## Features:
- **Live Capture**: Capture packets in real-time from selected network interfaces with a user-friendly interface.
- **File Capture**: Read and analyze captured packets from a `.pcap` file. Supports TCP and all packet types.
- **Color-Coded Output**: Enhanced visibility through color-coded packet data for easier analysis and troubleshooting.
- **Cross-Platform**: Compatible with both Windows and Unix-based systems, including Linux and macOS.

## Usage:
1. Choose the network interface (Windows, Unix/Mac OS, or specialized).
2. Select between live capture or file-based packet analysis (TCP or all packets).
3. View captured packet data in a clear, color-coded format for efficient network monitoring.

## Requirements:
- Python 3.x
- `pyshark` library: Install it using `pip install pyshark`

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing:
Feel free to fork this repository, create a branch, and submit a pull request. Contributions are welcome!

## Disclaimer:
This tool is intended for educational purposes only. Ensure you have the proper authorization before capturing network traffic.
