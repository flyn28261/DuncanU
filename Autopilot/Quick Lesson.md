------------------------------------------------------------------------------------------------------------
# Digital Autopilot Systems

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

An autopilot commands aircraft controls to maintain selected flight conditions or follow computed guidance.

## Operation

Flight guidance combines attitude, air data, navigation and selected modes to compute commands. Servos or flight-control computers apply commands to the controls. Feedback and monitoring detect disagreement; disengagement and mode interlocks protect against certain failures. The flight director displays commands even when the autopilot is not engaged.

## Signal Flow

```text
Aircraft state + selected modes --> guidance computer --> servos or flight-control computer --> feedback.
```

## Testing

Distinguish mode refusal, missing sensor inputs, servo faults and control feedback problems. Observe control movement hazards during approved ground testing.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

How does a flight director differ from an autopilot?

<details><summary>Answer</summary>

A flight director displays guidance commands; an engaged autopilot can apply commands to the controls.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
