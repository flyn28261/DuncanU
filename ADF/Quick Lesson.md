------------------------------------------------------------------------------------------------------------
# ADF / NDB — Legacy Navigation Background

**Core lesson: approximately 3 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

ADF equipment determines bearing to a nondirectional radio beacon. It is legacy background for the modern corporate avionics curriculum, not a recommended standalone installation.

## Operation

An ADF receiver and antenna system determine relative bearing to a selected NDB. Unlike GNSS, a single ADF bearing does not directly provide aircraft position. Legacy installations may feed an RMI or an electronic display. GNSS and supported conventional radio aids have displaced many ADF applications.

## Signal Flow

```text
NDB --> ADF antenna and receiver --> bearing display; modern equivalent context: GNSS --> FMS --> navigation display.
```

## Testing

Recognize the installed source and its limitations when working on an aircraft that retains ADF. Focus detailed training on GNSS, VOR and DME rather than legacy bench procedures.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

How does an ADF bearing differ from GNSS position?

<details><summary>Answer</summary>

ADF indicates direction to a beacon; GNSS estimates aircraft position from satellite measurements.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
