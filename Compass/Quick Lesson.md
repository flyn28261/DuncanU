------------------------------------------------------------------------------------------------------------
# Compass and Electronic Heading — Background

**Core lesson: approximately 3 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Modern flight decks use electronic heading sources, often within AHRS or inertial reference systems. Standby magnetic compasses can still provide an independent reference.

## Operation

A magnetic compass responds to Earth's magnetic field. Older remote heading systems may use a flux valve and slaved gyro; modern installations may use magnetometers, inertial sensors or other heading references. Magnetic heading and GNSS ground track describe different quantities and can differ in wind.

## Signal Flow

```text
Heading reference + attitude sensors --> AHRS or IRS --> heading indication and flight guidance.
```

## Testing

Consider magnetic interference, installation alignment and data validity when heading disagrees. Compare independent heading sources; do not use ground track as a universal substitute for heading.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why might GNSS track differ from aircraft heading?

<details><summary>Answer</summary>

Track describes movement over the ground; heading describes the direction the aircraft points.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](readme.md)

[Back to DuncanU](../README.md)
