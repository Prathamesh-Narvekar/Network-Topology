# Hybrid Topology

## What is Hybrid Topology?
- Hybrid topology is a combination of two or more different topologies (like star, bus, ring, mesh) to form a complex network that meets specific requirements.
- Hybrid Topology is used when the nodes are free to take any form. It means these can be individuals such as Ring or Star topology or can be a combination of various types of topologies
- It’s widely used in large networks because it offers flexibility and scalability.

## How It Works
- Different sections of the network use different topologies.
- For example, one department might use star, another uses ring, and both connect to a bus backbone.
- This allows organizations to design networks based on their needs.

## Technical Example
- Imagine a university network:
  - The main backbone uses bus topology.
  - Each building uses star topology for its internal network.
  - The library uses ring topology for its specialized systems.

## Real-Life Analogy
- Think of a transport system:
  - Highways (bus) connect cities.
  - Inside each city, roads form a star pattern.
  - Some areas have circular routes (ring).

## Advantages
- Flexible and scalable.
- Can be optimized for performance and cost.
- Fault isolation is easier compared to pure topologies.

## Disadvantages
- Complex to design and maintain.
- Higher cost due to mixed hardware and cabling.

## Applications
- Large Enterprises: Where different departments have different needs.
- Universities and Campuses: Combining star for labs and ring for specialized systems.
- Data Centers: Using mesh for critical servers and star for user access.

## Steps to Implement Hybrid Topology in Cisco Packet Tracer
- Open Cisco Packet Tracer.
- Add Devices:
  - Create one section with star topology (switch + PCs).
  - Another section with ring topology (PCs connected in a loop).
  - Connect both sections using a router or backbone switch.
- Assign IP Addresses:
  - Use different subnets for each section.
- Test Connectivity:
  - Ping across sections to ensure routing works.
