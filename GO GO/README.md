------------------------------------------------------------------------------------------------------------
# GO GO

[Operation](#operation)

[System Components](#system-components)

[Aircraft Connectivity](#aircraft-connectivity)

[Troubleshooting Concepts](#troubleshooting-concepts)

[More Reading](#more-reading)

[Videos](#videos)

------------------------------------------------------------------------------------------------------------

## Operation

Gogo provides in-flight connectivity for business aircraft. Traditional air-to-ground (ATG) installations communicate with a network of terrestrial radio stations. The onboard equipment connects passenger devices to the internet through the aircraft cabin network. Coverage depends on the network, aircraft location, installed equipment and service plan. Satellite-capable configurations can provide connectivity beyond terrestrial coverage.

## System Components

- **ATG antennas:** Provide the radio link to the ground network.
- **Connectivity LRU:** Contains the modem and network processing functions; the exact configuration varies by model.
- **Cabin wireless access points:** Provide Wi-Fi coverage for passenger devices; some systems integrate this function.
- **Aircraft interfaces:** Depending on the installation, supply power, configuration inputs and network connections.

## Aircraft Connectivity

```mermaid
flowchart LR
 A[Passenger device] <--> B[Cabin Wi-Fi]
 B <--> C[Connectivity LRU]
 C <--> D[ATG antenna]
 D <--> E[Ground network]
 E <--> F[Internet]
```
The AVANCE platform supports several connectivity configurations. A cabin Wi-Fi connection alone does not establish that the aircraft has an active internet connection. ATG and satellite connectivity use different external links even when passengers connect to the same cabin network.

## Troubleshooting Concepts

When investigating a reported connectivity issue, distinguish between cabin Wi-Fi availability, the external radio link and the service provider's network. Consider equipment status, network coverage, provisioning, power and antenna or cable condition. Record the operating conditions and fault indications. Use the applicable approved aircraft and equipment maintenance documentation for actual testing; this lesson does not establish test procedures or acceptance limits.

### More Reading

[Gogo AVANCE](https://www.gogoair.com/solutions/avance)

[Gogo ATG Network](https://www.gogoair.com/solutions/atg-network)

[Duncan Aviation — Gogo Wi-Fi equipment information](https://www.duncanaviation.aero/intelligence/important-information-about-your-gogo-wi-fi-system)

[Related lesson: Satcom](../Satcom/README.md)

### Videos

Video resources have not yet been selected.

