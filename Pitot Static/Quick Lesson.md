------------------------------------------------------------------------------------------------------------
# Pitot-Static Systems

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Pitot-static systems supply total and static pressure to air data computers and standby instruments.

## Operation

Pitot probes face the airflow to sense total pressure; static ports sense ambient pressure. Their difference is impact pressure used in airspeed calculation. Static pressure also supports altitude and vertical speed. Probe heating helps prevent ice accumulation. Separate pressure paths may serve redundant systems.

## Signal Flow

```text
Pitot probe + static ports --> air data computer --> PFD, flight guidance and surveillance.
```

## Testing

A blocked static source can affect altitude, vertical speed and airspeed; a pitot blockage can primarily affect airspeed. A pneumatic leak and a digital data failure are different fault domains. Use aircraft-specific test connections and safe pressure limits; incorrect pressure can damage instruments.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Which pressure input is common to airspeed and altitude?

<details><summary>Answer</summary>

Static pressure.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](Readme.md)

[Back to DuncanU](../README.md)
