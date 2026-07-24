# VPN
The process of designing, creating, and implementing my VPN into my copmuting environment

## Plan
- [ ] 1. Create a simple encrypted tunnel from my laptop to my network node.
- [ ] 2. Convert the network node into a VPN gateway so the laptop can reach the other nodes in the environment.
- [ ] 3. Implement access control and firewall.
- [ ] 4. Integrate field devices.
- [ ] 5. Add commercial VPN tunnel

## Conceptual Blueprint
                         REMOTE DEVICE
                      Laptop / Field Device
                              │
                              │
                    ┌─────────▼─────────┐
                    │   Encrypted VPN   │
                    │      Tunnel       │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │    NETWORK NODE   │
                    │                   │
                    │   VPN Endpoint    │
                    │   Firewall        │
                    │   Router          │
                    │   "BOUNCER"       │
                    └─────────┬─────────┘
                              │
                     ┌────────▼────────┐
                     │    Home LAN     │
                     └─────┬──┬──┬─────┘
                           │  │  │
                           ▼  ▼  ▼
                      Workstation
                           │
                      Compute Node
                           │
                      Storage Node
