------------------------------------------------------------------------------------------------------------
# Attitude Indicators — Legacy and Modern Standby

**Core lesson: approximately 3 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

An attitude indicator shows aircraft pitch and roll relative to a reference horizon. Modern electronic flight displays and standby units provide this information without traditional spinning-gyro instruments in many installations.

## Operation

Traditional attitude instruments used mechanical gyroscopes. Modern AHRS and integrated standby instruments use solid-state sensors and processing. An independent standby unit may have its own power and pressure inputs depending on configuration. Its independence is important when a main display or shared attitude source fails.

## Signal Flow

```text
Solid-state attitude sensors --> attitude processing --> primary or independent standby display.
```

## Testing

Distinguish a display failure from invalid attitude data. Compare independent indications and source status; the primary and standby systems may have different power and sensor arrangements.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why is an independent standby attitude source useful?

<details><summary>Answer</summary>

It can retain essential attitude information when the primary avionics source or display fails.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
