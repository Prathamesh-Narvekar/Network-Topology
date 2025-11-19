# Star Topology

## What is Star Topology?
- Star topology is a network design where all devices are connected to a central device (usually a switch or hub). Each device has its own dedicated connection to the central point.
- The hub can be passive in nature i.e., not an intelligent hub such as broadcasting devices, at the same time the hub can be intelligent known as an active hub. Active hubs have repeaters in them.

## How It Works
- The central device acts as a controller for communication.
- When a computer sends data, it goes to the central hub/switch, which then forwards it to the destination device.
- If one device fails, the rest of the network remains unaffected (as long as the central device works).

## Technical Example
- Imagine a LAN in an office with 5 computers and a switch:
  - Each computer is connected to the switch using a separate cable.
  - If PC1 wants to send data to PC3, the switch receives the data and forwards it only to PC3.

## Real-Life Analogy
- Think of a telephone operator system:
  - All callers connect to the operator (central point).
  - The operator connects the caller to the right person.

## Advantages
- Easy to manage and troubleshoot.
- Failure of one device doesn’t affect others.
- High performance because each device has a dedicated link.

## Disadvantages
- If the central device fails, the entire network goes down.
- Requires more cable than bus topology.

## Steps to Implement Star Topology in Cisco Packet Tracer
- Open Cisco Packet Tracer.
- Add Devices:
  - Drag and drop 4–6 PCs.
  - Add one switch (central device).
- Connect Devices:
  - Use Copper Straight-Through cables.
  - Connect each PC to the switch.
- Assign IP Addresses:
  - Click each PC → Desktop → IP Configuration.
  - Assign IPs in the same subnet (e.g., 192.168.1.1, 192.168.1.2, etc.).
- Test Connectivity:
  -  Use Ping from one PC to another.
- Optional:
  - Add a router if you want to connect to another network or simulate internet.
