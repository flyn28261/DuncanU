------------------------------------------------------------------------------------------------------------
# KA KU

[Operation](#operation)

[Frequency Bands](#frequency-bands)

[System Components](#system-components)

[Aircraft Connectivity](#aircraft-connectivity)

[Troubleshooting Concepts](#troubleshooting-concepts)

[More Reading](#more-reading)

[Videos](#videos)

------------------------------------------------------------------------------------------------------------

## Operation

Ka-band and Ku-band satellite communication systems provide broadband connectivity to aircraft. The aircraft communicates with a satellite, which relays traffic through a network to ground infrastructure or other satellites. These systems can support passenger internet and other services, depending on the installation and provider.

## Frequency Bands

| Band | Common IEEE nominal range | Characteristics |
| --- | --- | --- |
| Ku | 12–18 GHz | Widely used for satellite broadband; available bandwidth and coverage depend on the network. |
| Ka | 26.5–40 GHz | Can offer substantial bandwidth; propagation is more sensitive to atmospheric attenuation, including rain. |

These are nominal band definitions, not equipment operating frequencies. Actual satellite allocations and uplink/downlink frequencies vary.

## System Components

- **Satellite antenna:** Provides the radio link and may use mechanical or electronic beam steering.
- **Radome:** Where installed, protects the antenna while allowing RF energy to pass through.
- **Modem and RF electronics:** Process data and transmit or receive RF signals.
- **Antenna control functions:** Maintain the required pointing or beam tracking for the installed system.
- **Cabin network:** Distributes connectivity to passenger devices.

## Aircraft Connectivity

```mermaid
flowchart LR
 A[Passenger device] <--> B[Cabin network]
 B <--> C[Satellite modem and RF electronics]
 C <--> D[Aircraft antenna]
 D <--> E[Satellite network]
 E <--> F[Ground gateway and internet]
```
Geostationary (GEO) satellites appear nearly fixed relative to the ground, while low Earth orbit (LEO) satellites move across the sky and require network handovers. Frequency band and orbital architecture are separate characteristics.

## Troubleshooting Concepts

Distinguish cabin network faults from modem, antenna tracking, satellite coverage and service provisioning issues. Radome condition, RF path integrity, antenna blockage and weather can affect link performance. Follow applicable approved aircraft and equipment documentation, including RF exposure precautions, for all maintenance and testing.

### More Reading

[NBAA — Business Aircraft Connectivity](https://nbaa.org/aircraft-operations/communications-navigation-surveillance-cns/connectivity/special-report-business-aircraft-connectivity/)

[Related lesson: Satcom](../Satcom/README.md)

[Related lesson: Iridium](../Iridium/README.md)

### Videos

Video resources have not yet been selected.

