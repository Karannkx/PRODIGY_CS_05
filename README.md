```
# Network Packet Analyzer

This Python script uses the `scapy` library to sniff packets on a specified network interface.

## Usage

1. Ensure you have the necessary permissions to sniff packets on the chosen interface.
2. Modify the `interface` variable in the script to specify the network interface you want to sniff packets on.
3. Run the script in a Python environment.
4. The script will display information about captured packets, including source IP, destination IP, protocol, and payload (if available).

## Dependencies

- `scapy`: Install via pip if not already installed:
  ```
  pip install scapy
  ```


## Security Note

Packet sniffing can intercept sensitive information. Ensure that you have appropriate permissions and only use this script for authorized purposes.
```
