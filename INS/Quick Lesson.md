------------------------------------------------------------------------------------------------------------
# Inertial Reference Systems (IRS / IRU)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Modern inertial reference units use gyroscopes and accelerometers to estimate aircraft attitude, heading, velocity and position. They are important when external navigation signals are unavailable.

## Operation

Ring laser or fiber-optic gyros and other solid-state technologies sense angular motion. Accelerometers sense specific force. Integration of sensor measurements and alignment estimates produces inertial outputs. Position error accumulates over time; GNSS aiding can help limit drift. Alignment and input requirements vary by installation.

## Signal Flow

```text
Gyros + accelerometers --> inertial processing --> attitude, heading and position --> FMS and displays.
```

## Testing

Distinguish alignment problems, invalid attitude/heading, and gradual navigation drift. Compare redundant reference units and GNSS status. A disagreement does not establish which source is wrong.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why can inertial position drift even though the aircraft receives valid attitude information?

<details><summary>Answer</summary>

Small sensor and alignment errors accumulate when acceleration is integrated into velocity and position.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
