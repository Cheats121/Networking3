# Networking3
RIP Routing
--------------------
# Lab 3: Static & RIP Routing

### Overview
Configured both static routes and RIP across three routers to enable end-to-end connectivity.

### Topology
- **Networks:**  
  - 192.168.1.0/24 (PC1)  
  - 10.0.2.0/24 (PC2)  
  - 200.0.0.0/24 (PC3)  
- **Routers:** R1, R2, R3

### Tasks & Results
1. **Static Routing**  
   - Added IP route entries on each router
   - verified PC1↔PC3.

2. **Default Route Alternative**  
   - Demonstrated use of `0.0.0.0/0` next-hop.

3. **RIP Implementation**  
   - Enabled RIP v2 on all routers; dynamic route exchange observed via Wireshark.

### Lessons Learned
- Manual vs. dynamic routing trade‐offs.
- RIP update and convergence behaviour.

