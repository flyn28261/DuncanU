------------------------------------------------------------------------------------------------------------
# Attitude and Heading Reference Systems (AHRS)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Solid-state AHRS provides attitude and heading information to flight displays and guidance systems.

## Operation

Gyros sense rotation and accelerometers sense specific force. Sensor fusion estimates pitch, roll and heading; magnetic or other heading references may aid the estimate depending on architecture. Older mechanical gyros and flux valves are useful background, but modern installations commonly use solid-state sensors and digital outputs.

## Signal Flow

```text
Gyros + accelerometers + heading reference --> AHRS --> displays and flight guidance.
```

## Testing

Compare validity flags, alignment status, power, data bus outputs and independent sources. A magnetic heading error does not automatically indicate an attitude sensor fault.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

What is the purpose of combining several sensor types?

<details><summary>Answer</summary>

Their complementary measurements help estimate orientation and reduce the effect of individual sensor errors.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
