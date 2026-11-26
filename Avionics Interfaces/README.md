------------------------------------------------------------------------------------------------------------
# Serial, Analog, Discrete and Position Interfaces

[Operation](#operation)

[System Diagram](#system-diagram)

[Testing](#testing)

[More Reading](#more-reading)

------------------------------------------------------------------------------------------------------------

Aircraft avionics exchange information using serial links and electrical signals as well as packet networks. Understanding the interface type is essential before selecting test equipment.

## Operation

| Interface | Operating principle |
| --- | --- |
| RS-232 | Single-ended serial signaling |
| RS-422 | Differential serial signaling, generally one driver per pair |
| RS-485 | Differential signaling supporting multipoint configurations |
| Discrete | Open/ground or voltage state, depending on design |
| Analog | Continuous voltage, current or resistance |
| Resolver | Excited angular sensor with sine/cosine outputs |
| ARINC 708 | Radar display interface; commonly 1 Mbit/s Manchester encoded, 1600-bit messages |
| ARINC 717 | Recorder stream of 12-bit words; four one-second subframes per frame |

On ARINC 708, the radar display message includes status/header and range-bin data; control may use a separate interface. On ARINC 717, the parameter is identified by its assigned frame position rather than an ARINC 429-style label. Word rate and encoding depend on the installation. Neither interface should be tested using an assumed universal pinout.

Serial physical standards do not define every application protocol. A valid electrical signal may still contain the wrong message format. A resolver angle depends on relative signal amplitudes and phase/reference conventions.

## System Diagram

```mermaid
flowchart TD
 A[Sensor or transmitting LRU] --> I[Electrical interface]
 I --> R[Receiving LRU]
 R --> P[Decoded parameter or state]
```

Conceptual signal flow; individual aircraft configurations vary.

## Testing

Use aircraft-specific signal definitions and appropriate high-impedance or isolated measurements. Never assume an open discrete is logic high, or inject a voltage into an unknown input. Verify reference ground, excitation and loading where applicable.

Training theory only; use applicable aircraft and equipment maintenance instructions for live tests and limits.

### More Reading

[Astronics Ballard — avionics databus tutorials](https://www.astronics.com/avionics-databus-tutorials)

[FAA Aviation Maintenance Technician Handbook – Airframe, Chapter 11](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/FAA-H-8083-31B_Aviation_Maintenance_Technician_Handbook.pdf) — foundational reference; modern system details are supplementary training theory.

[Related lesson: ARINC 429](../ARINC%20429/README.md)

[Back to DuncanU](../README.md)
