------------------------------------------------------------------------------------------------------------
# Mode S Transponder and ADS-B

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

A transponder replies to surveillance interrogations. ADS-B Out broadcasts aircraft identification, position and other data independently of interrogation. Mode S and 1090 MHz extended squitter are common on business jets.

## Operation

Mode S supports selective addressing. A transponder generally receives interrogations at 1030 MHz and replies at 1090 MHz. ADS-B Out obtains position and integrity information from an approved navigation source, plus altitude and aircraft identity data. ADS-B In receives traffic and other supported broadcasts; it is a separate capability. Mode A/C-only equipment is legacy background. UAT uses 978 MHz; US Class A airspace generally requires compliant 1090ES unless otherwise authorized. ADS-R translates between links; TIS-B is ground surveillance-derived traffic; FIS-B provides supported information on UAT. NIC, NACp, NACv, SIL and SDA indicate containment, accuracy, integrity and design assurance. Barometric and geometric altitude are distinct.

## Signal Flow

```text
GNSS + altitude + identity --> Mode S / ADS-B transmitter --> antenna --> surveillance; ADS-B In --> traffic display.
```

## Testing

An ADS-B position-quality fault may originate in the navigation source or data interface even if transponder replies are normal. Check status and use approved surveillance test equipment and controlled RF test conditions.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why can a working Mode S transponder still produce invalid ADS-B Out?

<details><summary>Answer</summary>

ADS-B also depends on valid position, integrity, identity and other input data.

</details>

### More Reading — Optional

[FAA AIM — surveillance](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/chap4_section_5.html)

[Full existing lesson, images and resources](readme.md)

[Back to DuncanU](../README.md)
