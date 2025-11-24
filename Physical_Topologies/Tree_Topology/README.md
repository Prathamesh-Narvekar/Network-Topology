# Tree Topology
<div align = center>
<img width="783" height="472" alt="Tree_Topology" src="https://github.com/user-attachments/assets/1aa1ee42-bc92-4c44-a7e1-f3d92bc23fbe" />
</div>

## What is Tree Topology?
- Tree topology is a hierarchical network structure that combines characteristics of star and bus topologies. 
- It looks like a tree:
  - A root node (often a main switch or hub) connects to multiple branches.
  - Each branch can have multiple nodes connected in a star-like fashion.

## How It Works
- The network starts with a central backbone cable (like bus topology).
  - Branches (sub-networks) are connected to this backbone.
  - Each branch can have its own star topology for devices.

## Technical Example
- Imagine a corporate network:
  - The main switch connects to departmental switches.
  - Each departmental switch connects to PCs in that department.

## Real-Life Analogy
- Think of a family tree:
  - The root (grandparent) connects to branches (parents).
  - Each branch has its own leaves (children).

## Advantages
- Easy to expand by adding branches.
- Hierarchical structure makes management easier.
- Supports large networks.

## Disadvantages
- If the backbone fails, the entire network is affected.
- More cabling and hardware than bus or star.

## Applications
- Large Organizations: Used in corporate networks with multiple departments.
- School Networks: Where labs and classrooms connect to a central backbone.
- ISPs: For hierarchical distribution of internet services.

## Steps to Implement Tree Topology in Cisco Packet Tracer
- Open Cisco Packet Tracer.
- Add Devices:
  - One main switch (root).
  - 2–3 secondary switches (branches).
  - Multiple PCs for each branch.
- Connect Devices:
  - Connect main switch to secondary switches using Copper Straight-Through cables.
  - Connect PCs to their respective secondary switches.
- Assign IP Addresses:
  - All devices in the same subnet for simplicity (e.g., 192.168.1.x).
- Test Connectivity:
  - Ping between PCs in different branches.
