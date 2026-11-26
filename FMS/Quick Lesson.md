------------------------------------------------------------------------------------------------------------
# Flight Management System (FMS)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

An FMS integrates navigation sources, flight-plan data and aircraft performance information. It computes a desired path and distributes guidance to displays and flight control systems.

## Operation

GNSS, IRS and radio navigation inputs can be combined or selected according to the installed architecture. The navigation database provides coded procedures and waypoints; performance data and aircraft configuration influence predictions. A control display unit or integrated touchscreen allows selection and modification of the flight plan.

## Signal Flow

```text
GNSS and IRS --> FMS --> flight director and autopilot; navigation database --> FMS; FMS --> PFD and MFD.
```

## Testing

A valid position with incorrect course guidance can indicate flight-plan, database or mode selection issues rather than a failed position sensor. Compare independent navigation indications, source validity and the active flight plan.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

What is the difference between a navigation position source and a navigation database?

<details><summary>Answer</summary>

A position source determines where the aircraft is; the database describes routes, waypoints and procedures.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
