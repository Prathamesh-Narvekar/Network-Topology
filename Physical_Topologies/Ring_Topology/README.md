# Ring Topology

## What is Ring Topology?
- Ring topology is a network design where each device is connected to exactly two other devices, forming a circular path. Data travels in one direction (or sometimes both) around the ring until it reaches its destination.
- In-Ring Topology, the Token Ring Passing protocol is used by the workstations to transmit the data where, Token passing is a network access method in which a token is passed from one node to another node & Token is a frame that circulates around the network.

## How It Works
- Devices are arranged in a closed loop.
- Data moves from one device to the next in a ring-like fashion.
- Each device acts as a repeater, passing data along until it reaches the correct device.
- If one link breaks, the entire network can fail (unless it’s a dual ring).

## Technical Example
- Imagine 6 computers connected in a ring:
  - PC1 → PC2 → PC3 → PC4 → PC5 → PC6 → back to PC1.
  - If PC1 sends data to PC4, the data passes through PC2 and PC3 before reaching PC4.

## Real-Life Analogy
- Think of a relay race:
  - Each runner (device) passes the baton (data) to the next runner in a circle.
  - The baton keeps moving until it reaches the intended runner.

# Applications
- Token Ring Networks (IBM)
  - Historically used in LANs where data passed in a ring using tokens for access control.
- Metro Area Networks (MAN)
  - Fiber optic rings are used for redundancy in city-wide networks.
- Industrial Control Systems
  - Predictable data flow makes it suitable for factory automation and monitoring systems.

## Advantages
- Data flows in a predictable path.
- Good for small networks with limited traffic.

## Disadvantages
- If one device or link fails, the whole network can go down.
- Adding/removing devices is harder than in star topology.

## Steps to Implement Ring Topology in Cisco Packet Tracer
- Open Cisco Packet Tracer.
- Add Devices:
  - Drag and drop 4–6 PCs.
- Connect Devices in a Ring:
  - Use Copper Straight-Through cables.
  - Connect PC1 → PC2 → PC3 → PC4 → PC5 → PC6 → back to PC1.
- Assign IP Addresses:
  - Click each PC → Desktop → IP Configuration.
  - Assign IPs in the same subnet (e.g., 192.168.1.1, 192.168.1.2, etc.).
- Test Connectivity:
  - Use Ping from one PC to another.
- Optional:
  - Simulate failure by removing one link and observe connectivity loss.
