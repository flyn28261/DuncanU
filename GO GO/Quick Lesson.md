------------------------------------------------------------------------------------------------------------
# Gogo Aircraft Connectivity

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Gogo systems provide business aircraft passenger connectivity using supported air-to-ground (ATG) or satellite equipment.

## Operation

A cabin access point provides Wi-Fi. A router and modem connect the cabin network to an external provider. ATG antennas communicate with terrestrial sites; satellite configurations use a space segment. AVANCE equipment and supported networks vary by installed configuration. A visible Wi-Fi network does not prove internet access.

## Signal Flow

```text
Passenger device --> cabin Wi-Fi --> router and modem --> aircraft antenna --> provider network.
```

## Testing

If all devices lose internet but Wi-Fi remains available, consider modem status, coverage, service provisioning and RF path. If only one device is affected, investigate its connection and authentication first.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why can passengers connect to Wi-Fi without internet access?

<details><summary>Answer</summary>

The onboard wireless network can function independently of the external radio link.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
