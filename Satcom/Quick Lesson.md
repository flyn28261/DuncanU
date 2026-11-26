------------------------------------------------------------------------------------------------------------
# Satellite Communications (SATCOM)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

SATCOM provides voice or data connectivity through satellites beyond normal terrestrial radio coverage, depending on system and service availability.

## Operation

A satellite data unit or modem processes traffic. An antenna and RF electronics establish the external radio link; the ground network routes calls or data. L-band safety-service installations and broadband passenger connectivity can use different architectures. Satellite coverage, antenna visibility and network registration affect availability.

## Signal Flow

```text
Crew voice/data or cabin network --> satellite terminal <--> antenna <--> satellite network <--> ground network.
```

## Testing

Separate local voice or network functionality from satellite acquisition, registration, service provisioning and RF path integrity. Never assume passenger broadband provides approved operational safety communications.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

What is the difference between a local network connection and a satellite link?

<details><summary>Answer</summary>

A local connection reaches onboard equipment; a satellite link connects that equipment to the external network.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
