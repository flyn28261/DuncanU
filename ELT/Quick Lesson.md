------------------------------------------------------------------------------------------------------------
# Emergency Locator Transmitter (ELT)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

An ELT transmits a distress signal following activation, enabling search and rescue services to locate an aircraft.

## Operation

Modern satellite-alerting ELTs transmit digitally coded distress bursts on 406 MHz; many also provide a 121.5 MHz homing signal. Some receive GNSS position or encode position from an integrated receiver. Components may include a battery, crash sensor, remote switch, antenna and coax. Satellite alerts on 121.5 MHz alone are legacy technology.

## Signal Flow

```text
Crash sensor or manual command --> ELT --> antenna --> search-and-rescue satellite; homing signal --> rescue receiver.
```

## Testing

Distinguish remote-switch, battery, antenna and transmitter issues. Use manufacturer-approved self-tests and RF precautions; do not transmit an unintended distress alert.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

What is the role of 406 MHz compared with 121.5 MHz?

<details><summary>Answer</summary>

406 MHz supports satellite distress alerting; 121.5 MHz commonly supports local homing.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
