# Mesh Topology

## What is Mesh Topology?
- Mesh topology is a network design where every device is connected to every other device directly. This creates multiple paths for data to travel, ensuring high redundancy and reliability.
- The nodes are connected to each other completely via a dedicated link during which information travels from nodes to nodes.
- If a mesh network has N nodes, then there are N(N-1)/2 links. Each computer not only sends its signals but also transfer data from other computers.
- The connections within the mesh are often wired or wireless.

## Types of Mesh
- Full Mesh: Every device is connected to all other devices.
- Partial Mesh: Some devices are fully connected, others are partially connected.

## How It Works
- Data can take multiple routes to reach its destination.
- If one link fails, data can still travel through other links.
- Common in WANs and mission-critical networks.

## Technical Example
- Imagine 4 routers in a WAN:
  - Each router has a direct link to every other router.
  - If Router A wants to send data to Router D, it can go directly or via B or C.

## Real-Life Analogy
- Think of airline routes between major cities:
  - Big cities have direct flights to each other (full mesh).
  - Smaller cities may have fewer direct flights (partial mesh).

## Advantages
- High reliability and fault tolerance.
- Multiple paths reduce congestion.

## Disadvantages
- Very expensive (lots of cables and ports).
- Complex to set up and maintain.

## Steps to Implement Mesh Topology in Cisco Packet Tracer
- Open Cisco Packet Tracer.
- Add Devices:
  - Drag and drop 4–6 PCs or routers.
- Connect Devices:
  - For full mesh, connect every device to every other device using Copper Straight-Through cables.
- Assign IP Addresses:
  - Each link needs its own IP subnet if using routers.
  - For PCs, assign IPs in the same subnet for simplicity.
- Test Connectivity:
  - Use Ping between all devices.
- Optional:
  - Simulate link failure and observe alternate paths.
