------------------------------------------------------------------------------------------------------------
# HF Communications

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

HF communications support long-range voice and some digital links beyond normal VHF line-of-sight coverage.

## Operation

HF occupies 3–30 MHz; aeronautical assignments use portions of this range and nearby frequencies. Ionospheric propagation varies with frequency, time and solar conditions. Aeronautical HF voice commonly uses single-sideband modulation. An antenna coupler matches the electrically short aircraft antenna to the transceiver over its operating range.

## Signal Flow

```text
Audio or data --> HF transceiver --> antenna coupler --> aircraft antenna --> ionospheric path.
```

## Testing

Separate propagation limitations from coupler faults, bonding, antenna path and audio interface problems. Tuning failure can originate in the antenna installation. Observe high RF voltage and transmission safety precautions.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why is an antenna coupler commonly required on an aircraft HF system?

<details><summary>Answer</summary>

The aircraft antenna is electrically short relative to HF wavelengths and requires impedance matching across frequencies.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
