------------------------------------------------------------------------------------------------------------
# Radar Altimeter

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

A radar altimeter measures height above the reflecting surface beneath the aircraft, rather than altitude relative to sea level.

## Operation

Many civil radar altimeters operate in the 4.2–4.4 GHz band. Frequency-modulated continuous-wave designs determine range from the beat frequency between the current transmitted signal and its delayed return, using the known sweep slope. Other designs exist. Transmit and receive antennas, coax and the transceiver form the RF path. Outputs can support automatic flight control, TAWS and callouts.

## Signal Flow

```text
Radar altimeter --> transmit antenna --> terrain --> receive antenna --> radar altimeter --> dependent systems.
```

## Testing

An invalid height can affect several consumers simultaneously. Consider antenna condition, cable loss, mounting geometry, interference and transceiver status. Use approved test equipment and installation-specific limits.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why is radar altitude different from barometric altitude?

<details><summary>Answer</summary>

Radar altitude measures height above the reflecting surface, while barometric altitude derives from air pressure.

</details>

### More Reading — Optional

[FAA — radio altimeter interference and flight hazards](https://www.faa.gov/air_traffic/publications/aim_html/chap7_section_6.html)

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
