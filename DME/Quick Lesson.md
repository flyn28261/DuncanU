------------------------------------------------------------------------------------------------------------
# Distance Measuring Equipment (DME)

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

DME measures slant-range distance between the aircraft and a ground transponder. It remains relevant to conventional navigation and some FMS position updating.

## Operation

The aircraft interrogator transmits paired pulses; a ground transponder replies after a known nominal delay (50 µs for DME/N X channels, 56 µs for Y channels). The receiver calculates distance from round-trip propagation time after accounting for that delay. DME operates in the 960–1215 MHz UHF allocation, with associated channels often selected through a VOR or ILS frequency. DME/DME position updating uses ranges from multiple stations.

## Signal Flow

```text
Aircraft DME interrogator <--> ground transponder; interrogator --> distance indication and FMS.
```

## Testing

A displayed distance greater than horizontal map distance near a station may be normal because DME measures slant range. Investigate coverage, antenna, channel selection, receiver and output validity if distance is absent or unstable.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why can DME indicate a nonzero distance directly over a station?

<details><summary>Answer</summary>

The measured range includes the aircraft's vertical separation from the station.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](readme.md)

[Back to DuncanU](../README.md)
