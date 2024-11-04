## ARP Spoof Detector

A Python script to detect ARP spoofing attacks on a network by monitoring ARP responses and checking for mismatches in MAC addresses.

### Features

- Monitors network traffic for ARP responses
- Alerts if an ARP spoofing attack is detected by identifying MAC address inconsistencies

### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Daniel-Ikenna/arpspoof_detector
   ```

2. **Run the Script**:
   ```bash
   sudo python arp_spoof_detector.py
   ```

   The script will monitor the specified network interface and print an alert if a spoofing attempt is detected.

### Requirements

- Python 3.x
- `scapy` library (install via `pip install scapy`)
- Superuser privileges (use `sudo`)

### Important Note

This tool is intended for educational purposes and network security testing. Unauthorized use on networks is prohibited.

### Authors

- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
