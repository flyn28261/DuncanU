------------------------------------------------------------------------------------------------------------
# Traffic Alert and Collision Avoidance System (TCAS)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

TCAS II monitors nearby transponder-equipped aircraft and can issue traffic advisories (TAs) and vertical resolution advisories (RAs).

## Operation

The system interrogates compatible transponders and processes range, bearing, relative altitude and closure information. Directional antennas support bearing determination. TCAS II coordinates compatible resolution advisories using Mode S. Displays and aural alerts present advisories; inhibition logic depends on aircraft state.

## Signal Flow

```text
TCAS antennas <--> surrounding aircraft transponders; air data + aircraft state --> TCAS processor --> displays and alerts.
```

## Testing

Separate antenna, transponder coordination, altitude inputs and display interfaces. Use approved ramp test modes and precautions to avoid generating misleading traffic or alerts for nearby aircraft.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

How does a traffic advisory differ from a resolution advisory?

<details><summary>Answer</summary>

A TA draws attention to traffic; an RA provides vertical maneuver or restriction guidance.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](readme.md)

[Back to DuncanU](../README.md)
