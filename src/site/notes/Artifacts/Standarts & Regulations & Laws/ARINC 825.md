---
{"dg-publish":true,"permalink":"/Artifacts/Standarts & Regulations & Laws/ARINC 825/","title":"ARINC 825","tags":["artifact/standard"]}
---

CANbus for aircraft

Automotive CAN is robust and cheap — but not deterministic enough or safety-controlled enough for aircraft.  
ARINC 825 adds the structure, timing rules, and safety layers needed for avionics.

Standard CAN is event-driven → collisions → arbitration → unpredictable delay.  
ARINC 825 defines:
- **Time-triggered messaging**
- **Priority rules**
- **Scheduling**

This makes it usable for safety-critical systems.

Great for:
- Landing gear systems
- ECS (environmental control systems)
- Actuators
- Sensors
- Engine subsystems.

great for _local subsystems_

used in
- UAVs
- Helicopters
- Regional aircraft
- Subsystems inside larger aircraft (non-critical zones)
- Electric actuators
- Power systems
- Sensors network
Used by [[Organizations/Airbus\|Airbus]] and many Tier-1 avionics suppliers in distributed subsystems