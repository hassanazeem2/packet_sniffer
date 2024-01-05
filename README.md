**Packet Sniffer**

Overview:
This Python script serves as a basic packet sniffer using the Scapy library, capturing HTTP requests on a specified network interface.

**Prerequisites:**
Ensure that Scapy is installed (pip install scapy).
Usage:
Modify the network interface in the sniff function call (e.g., sniff("eth0")) to match your network setup.
Run the script (python your_script_name.py).

**Features:**
Monitors HTTP traffic.
Extracts URLs from HTTP requests.
Identifies potential sensitive information (e.g., usernames and passwords) using predefined keywords.
