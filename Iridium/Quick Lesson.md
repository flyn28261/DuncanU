------------------------------------------------------------------------------------------------------------
# Iridium Satellite Communications

**Core lesson: approximately 5 minutes** (read, trace the signal path and answer the check). Optional references are not part of the timed lesson.

[Operation](#operation)

[Signal Flow](#signal-flow)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

------------------------------------------------------------------------------------------------------------

Iridium uses low Earth orbit satellites to provide voice and data services, including coverage in high-latitude regions.

## Operation

The terminal communicates with passing satellites through an L-band antenna. Satellite movement requires network-managed handovers. Aircraft equipment may connect to cockpit audio, cabin phones or data systems; supported services depend on the terminal and installation. Iridium voice/data services differ from high-throughput Ku-band LEO broadband.

## Signal Flow

```text
Aircraft handset or data interface --> Iridium terminal <--> L-band antenna <--> LEO satellite network.
```

## Testing

Check antenna visibility, cable condition, terminal status, registration and local audio or data interfaces. A successful local handset test does not prove satellite registration or call routing.

Use applicable aircraft and equipment instructions for actual tests and limits.

## Knowledge Check

Why does a LEO satellite network require handovers?

<details><summary>Answer</summary>

Satellites move relative to the aircraft, so the network must manage transitions between available links.

</details>

### More Reading — Optional

[Full existing lesson, images and resources](README.md)

[Back to DuncanU](../README.md)
