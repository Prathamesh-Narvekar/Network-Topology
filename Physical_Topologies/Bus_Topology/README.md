# Bus Topology

## What is Bus Topology?
- Bus topology is a network setup where all devices are connected to a single central cable (called the bus or backbone). Data travels along this cable, and every device checks if the data is meant for it.It is bi-directional.
- It is a multi-point connection and a non-robust topology because if the backbone fails the topology crashes. In Bus Topology, various MAC (Media Access Control) protocols are followed by LAN ethernet connections like TDMA, Pure Aloha, CDMA, Slotted Aloha, etc.

## How It Works
- There is one main cable (the bus).
- All computers and devices are connected to this cable using connectors.
- When a device sends data, it travels across the bus, and all devices receive it.
- Only the intended recipient processes the data; others ignore it.
- Terminators are placed at both ends of the bus to prevent signal reflection.

## Technical Example
- Imagine a small LAN in an office with 5 computers:
  - All computers are connected to a single coaxial cable.
  - If Computer A sends a message to Computer D, the message travels through the bus, and D picks it up.

## Real-Life Analogy
- Think of a public announcement system in a train:
  - There’s one speaker line (the bus).
  - When the conductor speaks, the message goes to all speakers.
  - Every passenger hears it, but only those who need the info act on it.

## Applications
- Small LANs (Local Area Networks)
  - Used in early Ethernet networks where a single coaxial cable connected all computers. Ideal for small setups because it’s cheap and easy to install.
- Broadcast Networks
  - Perfect for situations where the same message needs to reach all devices, like announcements or alerts.
- Temporary Networks
  - Great for quick setups in labs or testing environments because it’s simple and requires minimal hardware.

## Advantages
- Easy to set up.
- Requires less cable than star topology.

## Disadvantages
- If the main cable fails, the entire network goes down.
- Performance decreases as more devices are added.


## Steps to Implement Bus Topology in Cisco Packet Tracer
- Open Cisco Packet Tracer.
- Add Devices:
  - Drag and drop 3–5 PCs from the device list.
- Add a Hub or Switch (optional for simulation, but pure bus uses a single cable).
- Connect Devices:
  - Use Coaxial Cable (or in Packet Tracer, use Copper Straight-Through cable).
  - Connect all PCs to the same hub (simulating the bus).
- Assign IP Addresses:
  - Click each PC → Desktop → IP Configuration.
  - Assign IPs in the same subnet (e.g., 192.168.1.1, 192.168.1.2, etc.).
- Test Connectivity:
  - Use the Ping command from one PC to another.
- Optional:
  - Remove the hub and connect PCs in a straight line for a pure bus representation.
