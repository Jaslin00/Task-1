Nmap Tool:
Nmap is a tool used for network scanning.
It is used in this task to find the different ports. That includes the SYN-ACK and RSK.

1. Installed the Nmap tool from Google.
2. Using the command ipconfig in command prompt found the IP address.
3. Run nmap -sS -Pn 192.168.218.0/24 command in Nmap tool.
4. Finf different ports.
5. Stop

Wireshark:
Wireshark is the network packet capturing tool.
It is used to in this to find the different packets on running the Nmap.

1. Installed the Wireshark from Google.
2. Choose either Wifi or Ethernet on your device connected.
3. On terminal run the Nmap and capture the packets on applying filter tcp.flags.syn == 1 and tcp.flags.ack == 0 in the filter option.
4. Found different Nmap related traffic packets.
5. Stop

6. Uses:
You can watch live how Nmap sends packets
Learn how computers communicate (TCP SYN, ACK, RST)
