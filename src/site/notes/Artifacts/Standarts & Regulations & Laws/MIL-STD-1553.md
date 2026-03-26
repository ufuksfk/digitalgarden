---
{"dg-publish":true,"permalink":"/Artifacts/Standarts & Regulations & Laws/MIL-STD-1553/","title":"Highlights","tags":["artifact/standard"]}
---

**Role:** Military avionics data bus  
**Type:** Command/response, dual-redundant  
**Speed:** 1 Mbps  
**Topology:** One _Bus Controller (BC)_ + many _Remote Terminals (RTs)_  , Bus Monitor (BM)
Only BC can initiates data transfer makes it very reliable.
**Introduced:** [[Calendar/Decades/1970s\|1970s]]

- **Deterministic timing** → very stable and predictable (military requirement).
- **Dual-redundancy** → two physical buses; one is backup.
- **Transformer-coupled stubs** → improve isolation and reliability.
- **Messages defined by the BC**, RTs only respond.
- Still used widely in fighters ([[Products/F-16\|F-16]], F-18, Gripen C/D) and missiles.
- Very robust to EMI, radiation, and harsh environments.

# Highlights
## From youtube videos
https://www.youtube.com/watch?v=tiim2adsLtA
One _Bus Controller (BC)_ + many _Remote Terminals (RTs)_  , Bus Monitor (BM)
2 sided bus, commonly labeled as A,B
fix set of commands
BC->RT : Fire a missile
RT->BC : Request, information from avionics instrument
RT->RT : 

Comes with scheduler, major frame and multiple minor frames
Manchester encoding!
Dual buses for redundancy
[[Artifacts/Standarts & Regulations & Laws/ARINC-708\|ARINC-708]] based on MIL-STD-1553 encoding. Developed for airborne weather radar, longer data words,  data transmits on both sides of the bus.

