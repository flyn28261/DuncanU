------------------------------------------------------------------------------------------------------------
# FAA Avionics Performance and Testing Requirements

**Core lesson: approximately 6 minutes.** Optional references are outside the timed lesson.

[Operation](#operation)

[System Diagram](#system-diagram)

[Testing](#testing)

[Knowledge Check](#knowledge-check)

[More Reading](#more-reading)

------------------------------------------------------------------------------------------------------------

This technical lesson introduces selected United States Federal Aviation Regulations (14 CFR) relevant to installed corporate aircraft avionics. It covers equipment performance and physical testing only, not paperwork, recordkeeping or administrative processes.

## Operation

| Requirement | Technical purpose |
| --- | --- |
| 91.411 and Part 43 Appendix E | Static system integrity, altimeter accuracy and installed altitude reporting correspondence |
| 91.413 and Part 43 Appendix F | Transponder performance, including applicable RF and reply characteristics |
| 91.225 and 91.227 | ADS-B Out equipment and broadcast performance in applicable airspace |

**Altitude and transponder testing:** Sections 91.411 and 91.413 establish 24-calendar-month intervals where applicable. Certain static system openings or changes that may introduce altitude data correspondence errors require additional applicable testing. Appendix E addresses static integrity, altimeter characteristics and integrated altitude reporting; Appendix F addresses transponder characteristics such as frequency, sensitivity and RF output, as applicable to the equipment.

**ADS-B performance:** Section 91.227 specifies broadcast content, position and velocity accuracy, integrity, design assurance and latency. A functioning Mode S reply is not proof that ADS-B Out meets those requirements; position source validity and transmitted message content also matter.

## System Diagram

```mermaid
flowchart TD
  P[Static pressure and ADC] --> T[Transponder altitude input]
 G[GNSS position and integrity] --> T
 T --> R[RF transmission]
 R --> E[Approved surveillance test equipment]
```

Conceptual signal flow; aircraft installations vary.

## Testing

Use a suitable air data test set for applicable pneumatic and altitude checks, and approved surveillance test equipment for transponder and ADS-B measurements. Distinguish pressure-altitude accuracy, altitude correspondence and RF performance. Observe pressure limits, RF safety and test-mode restrictions. The regulation and aircraft-specific approved test instructions establish actual applicability, test points and limits; this overview is not a substitute for them.

## Knowledge Check

Does a satisfactory transponder RF output test establish correct ADS-B position and altitude reporting?

<details><summary>Answer</summary>

No. RF performance, altitude correspondence and ADS-B broadcast content and quality are separate checks.

</details>

### More Reading

[14 CFR 91.411 and 91.413 — official 2026 CFR text](https://www.govinfo.gov/content/pkg/CFR-2026-title14-vol2/xhtml/CFR-2026-title14-vol2-part91-subpartE.html)

[14 CFR Part 43 Appendix E and F](https://www.govinfo.gov/content/pkg/CFR-2025-title14-vol1/xhtml/CFR-2025-title14-vol1-part43.html)

[14 CFR 91.225](https://www.govinfo.gov/content/pkg/CFR-2026-title14-vol2/xhtml/CFR-2026-title14-vol2-sec91-225.html)

[14 CFR 91.227](https://www.govinfo.gov/content/pkg/CFR-2026-title14-vol2/xhtml/CFR-2026-title14-vol2-sec91-227.html)

[Related lesson: Transponder and ADS-B](../ATC/Quick%20Lesson.md)

[Back to DuncanU](../README.md)
