# Day 1: Network Basics

# Definitions
- **Computer Network:** is a digital telecommunications network which allows nodes to share resources
- **Client:** is a device that acceesses a service made available by a server
- **Server:** is a device that provides functions or services for client
- **Switch:** is designed to connect many end hosts in the same LAN together
- **Router:** is a device that is designed to connect and forward network traffic between multiple networks
- **Firewalls:** are network security devices that control network traffic entering and exiting your network
- **Network Firewalls:** are hardware devices that filter traffic between networks
- **Host-Based Firewall:** are software applications that filters traffic entering and exiting a host machine, like a PC
- **Protocol:** the set of rules computers use to talk. it is their shared language
  ## TCP/IP MODEL
  1. Application Layer: The software you use (like a web browser) to create data
  2. Transport Layer: Manages the communication (like TCP) between apps on different devices
  3. nternet Layer: Handles routing data across different networks using IP addresses
  4. Local Network Layer: Moves data hop-to-hop within a single local network using MAC addresses
  5. Local Network Layer: Moves data hop-to-hop within a single local network using MAC addresses

 ## Data Units (PDUs)
 - **Segment (Layer 4):** The message at Transport layer
 - **Packet (Layer 3):** The message at the internet layer
 - **Frame (Layer 2):** The final'package' sent over the physical wires

 ## Layer Interaction
 - **Adjacent Layer:** Layer only talk to the layer directly above or below them
 - **Same Layer:** The application layer on your computer talks directly to  the application layer on the server
 - **Modularity:** Because layers are separate, you can swap out a protocol(like changing  from ethernet to Wi-Fi) without rebuilding the whole network

##LAB
Successfully downdloaded cicso packet tracker
