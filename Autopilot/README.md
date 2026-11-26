------------------------------------------------------------------------------------------------------------
# Autopilot 

Foundations of autopilot Operation

More Reading

Videos 

------------------------------------------------------------------------------------------------------------

# autopilot Systems

An aircraft's **autopilot system** operates the aircraft without direct manual control from the pilot. The system is responsible for maintaining the aircraft's attitude and direction, correcting any deviations from the desired parameters. These autopilot systems are proficient at stabilizing the aircraft both laterally, vertically, and longitudinally.

The primary objective of an autopilot system is to alleviate the pilot's workload and fatigue during extended flights. Most autopilots offer both manual and automatic modes of operation. In manual mode, the pilot selects specific maneuvers and provides minor inputs to the autopilot controller, which then moves the aircraft's control surfaces accordingly. In automatic mode, the pilot chooses the desired attitude and direction for a specific flight segment, and the autopilot adjusts the control surfaces to achieve and maintain these parameters.

autopilot systems come in one-, two-, or three-axis control configurations. Single-axis autopilots handle aileron control and are often referred to as wing leveler systems, typically found on smaller aircraft. Two-axis systems manage aileron and elevator control, while three-axis autopilots handle aileron, elevator, and rudder control. Two- and three-axis autopilot systems can be found on aircraft of various sizes.

A wide variety of autopilot systems are available, featuring diverse capabilities and complexities. Light aircraft generally have simpler autopilots compared to high-performance and transport category aircraft. More advanced autopilots can also manipulate various flight parameters beyond control surfaces.

Some modern aircraft, including small planes, high-performance aircraft, and transport category aircraft, are equipped with sophisticated **automatic flight control systems (AFCS)**. These three-axis systems offer comprehensive control during climbs, descents, cruising, and landing approaches. Some even incorporate an auto-throttle feature, managing engine thrust and enabling automatic landings.

For more advanced automated control, **flight management systems** have been developed. These systems allow for the pre-programming of an entire flight profile, enabling the pilot to supervise its execution. Flight management systems coordinate various aspects of a flight, including the autopilot and auto-throttle systems, navigation route selection, fuel management, and more.

## Foundations of autopilot Operation

The core principle behind autopilot system operation is error correction. When an aircraft deviates from the selected conditions, an error occurs, prompting the autopilot system to make necessary corrections and restore the aircraft to the desired flight attitude. Modern digital control laws can combine attitude or position error, angular rate, navigation deviation and actuator feedback. The exact control laws and sensor sources are aircraft-specific.

## Components of autopilot Systems

Most autopilot systems consist of four primary components, along with various switches and auxiliary units. These core components include **sensing elements**, a **computing element**, **output elements**, and **command elements**. Closed-loop control relies on feedback from aircraft state; dedicated actuator position feedback hardware varies by design.

1. **Sensing Elements**: These elements, including attitude and directional gyros, turn coordinators, and altitude controls, detect aircraft movements and generate electrical signals used by the autopilot to make corrections. In modern digital systems, various sensors like MEMS gyros, solid-state accelerometers, and magnetometers may be used, and they communicate via a [digital data bus](https://en.wikipedia.org/wiki/Digital_data_bus).

2. **Computing Element**: The computing element interprets data from sensing elements, integrates navigational input, and sends signals to the output elements. It can be analog or digital, with amplifiers used to process signals, particularly in analog systems. Digital systems employ microprocessor technology.

3. **Output Elements**: Output elements are the servos responsible for moving control surfaces to enact corrections. These servos can be electric, electro-pneumatic, or electro-hydraulic, depending on the type of aircraft control system. They integrate into the regular flight control system.

4. **Command Elements**: The command unit, also known as a flight controller, allows the pilot to issue instructions to the autopilot. The pilot selects specific maneuvers or flight conditions via the flight controller, and the autopilot executes them. This interface may vary in complexity depending on the system.

5. **Feedback or Follow-up Element**: In systems that include this element, follow-up signals are generated to progressively reduce errors during correction, preventing continuous overcorrection. Rate systems, for example, use feedback signals to counteract initial error signals and bring the aircraft back to the desired attitude.

## autopilot Functions

Digital flight guidance computers use attitude, air data, navigation and mode selections to compute commands. Roll and pitch channels command servos or flight control computers; yaw damping may use a separate or integrated function. Feedback, engagement interlocks and monitoring vary with aircraft design.

**Yaw Dampening**

Many aircraft experience oscillations around their vertical axis while maintaining a fixed heading. A **yaw damper**, either integrated into the autopilot system or a standalone unit, corrects this motion. It uses yaw-rate and other relevant sensor data as designed to command rudder or other control action, damping Dutch-roll motion.

## Automatic Flight Control System (AFCS)

An advanced form of autopilot system, the **automatic flight control system (AFCS)**, integrates various features and systems into a single cohesive unit. AFCS systems are now available on aircraft of all sizes, thanks to advancements in digital technology.

AFCS capabilities differ across systems but often include extensive programmability, integration of navigational aids, flight director and autothrottle systems, and a unified flight control interface. In some cases, AFCS allows for auto-landings, particularly in conjunction with auto-throttle systems.

**Flight Director Systems**

A **flight director system**, a guidance function that displays computed commands, computes and displays the required aircraft attitude to achieve a specific flight condition. It provides command indications on the aircraft's attitude indicator, assisting the pilot in maneuvering the aircraft effectively. Flight director systems can be integrated into autopilot systems or exist independently, offering valuable guidance during instrument approaches and navigation.

The flight director information is displayed on an instrument like the attitude indicator, using a visual reference technique. The pilot follows commands displayed on the instrument panel to achieve the desired maneuvers. Flight director systems comprise sensing elements, a computer, and an interface panel, and their complexity and features can vary.

Overall, autopilot systems, whether basic or advanced AFCS, play a crucial role in modern aviation by enhancing flight safety, reducing pilot workload, and improving precision in controlling aircraft.



### More Reading

[FAA AMT Airframe handbook — automatic flight control](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/FAA-H-8083-31B_Aviation_Maintenance_Technician_Handbook.pdf)

[Related lesson: Flight Guidance](../Flight%20Guidance/README.md)
