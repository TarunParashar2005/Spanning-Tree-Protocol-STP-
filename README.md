Spanning-Tree-Protocol(STP):-

Description:-
             This lab demonstrates the configuration and working of Spanning Tree Protocol (STP) to prevent                 loops in a switched network. With multiple switches connected in a redundant topology, STP                     ensures a loop-free logical path while maintaining redundancy for fault tolerance.

Topology:
>3 Switches (2960-24TT)
>2 PCs (PC0, PC1)
>Redundant links between switches forming a looped topology.

Steps:-
1.Connect three switches and PCs in a triangular topology.
2.Configure switch basic settings (hostname, VLAN, interfaces).
3.Enable STP (default on Cisco switches).
4.Observe how STP blocks redundant ports to avoid loops.
5.Test connectivity with ping between PC0 and PC1.
6.Shut down one active link to see STP automatically re-enable a previously blocked port.

Outcomes & Learnings:-
- Understand how STP avoids broadcast storms caused by loops.
- Learn how switches elect a Root Bridge.
- Observe how redundant paths provide fault tolerance.
- Gain hands-on experience with loop prevention in LAN design.

Benefits:-
- Provides network stability by avoiding loops.
- Ensures automatic failover in case of link failure.
- Essential knowledge for real-world LAN deployment.
