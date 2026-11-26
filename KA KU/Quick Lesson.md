------------------------------------------------------------------------------------------------------------
# Ka/Ku Satellite Connectivity

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Ka-band and Ku-band satellite systems provide broadband connectivity to business aircraft. Frequency band and satellite orbit are separate characteristics.

## Operation

The modem encodes data and RF electronics transmit it through a directional antenna. A receive chain recovers weak signals. Mechanically or electronically steered antennas maintain the link; radomes protect equipment where fitted. Ka and Ku systems operate at microwave frequencies; actual uplink and downlink assignments vary. GEO satellites appear nearly fixed from the ground, while LEO satellites require frequent tracking and handovers.

## Signal Flow

```text
Cabin network --> modem and RF electronics <--> aircraft antenna <--> satellite network <--> ground network.
```

## Testing

Consider cabin network status, modem registration, antenna tracking, radome condition, weather and provider coverage as distinct fault domains. Follow RF and moving-antenna safety precautions.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Does Ka-band necessarily mean a GEO satellite network?

<details><summary>Answer</summary>

No. Frequency band and orbital architecture are independent.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
