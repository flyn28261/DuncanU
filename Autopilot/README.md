------------------------------------------------------------------------------------------------------------
# Autopilot 

More Reading

Videos 

------------------------------------------------------------------------------------------------------------

# Automatic Pilot Systems

An [aircraft automatic pilot system](https://en.wikipedia.org/wiki/Autopilot) controls the aircraft without the pilot directly maneuvering the controls. The autopilot maintains the aircraft’s attitude and/or direction and returns the aircraft to that condition when it is displaced from it. Automatic pilot systems are capable of keeping aircraft stabilized laterally, vertically, and longitudinally.

The primary purpose of an autopilot system is to reduce the work strain and fatigue of controlling the aircraft during long flights. Most autopilots have both manual and automatic modes of operation. In the manual mode, the pilot selects each maneuver and makes small inputs into an autopilot controller. The autopilot system moves the control surfaces of the aircraft to perform the maneuver. In automatic mode, the pilot selects the attitude and direction desired for a flight segment. The autopilot then moves the control surfaces to attain and maintain these parameters.

Autopilot systems provide for one-, two-, or three-axis control of an aircraft. Those that manage the aircraft around only one axis control the ailerons. They are single-axis autopilots, known as wing leveler systems, usually found on light aircraft. [Figure 10-107]

Other autopilots are two-axis systems that control the ailerons and elevators. Three-axis autopilots control the ailerons, elevators, and the rudder. Two-and three axis autopilot systems can be found on aircraft of all sizes.

There are many autopilot systems available. They feature a wide range of capabilities and complexity. Light aircraft typically have autopilots with fewer capabilities than high performance and transport category aircraft. Integration of navigation functions is common, even on light aircraft autopilots. As autopilots increase in complexity, they not only manipulate the flight control surfaces, but other flight parameters as well.

Some modern small aircraft, high-performance, and transport category aircraft have very elaborate autopilot systems known as automatic flight control systems (AFCS). These three-axis systems go far beyond steering the airplane. They control the aircraft during climbs, descents, cruise, and approach to landing. Some even integrate an auto-throttle function that automatically controls engine thrust that makes auto landings possible.

For further automatic control, flight management systems have been developed. Through the use of computers, an entire flight profile can be programmed ahead of time allowing the pilot to supervise its execution. An FMS computer coordinates nearly every aspect of a flight, including the autopilot and auto throttle systems, navigation route selection, fuel management schemes, and more.

## Basis for Autopilot Operation

The basis for autopilot system operation is error correction. When an aircraft fails to meet the conditions selected, an error is said to have occurred. The autopilot system automatically corrects that error and restores the aircraft to the flight attitude desired by the pilot. There are two basic ways modern autopilot systems do this. One is [position based](https://en.wikipedia.org/wiki/Position-based_navigation) and the other is [rate based](https://en.wikipedia.org/wiki/Rate-based_navigation). 

A position based autopilot manipulates the aircraft’s controls so that any deviation from the desired attitude of the aircraft is corrected. This is done by memorizing the desired aircraft attitude and moving the control surfaces so that the aircraft returns to that attitude. Rate based autopilots use information about the rate of movement of the aircraft and move control surfaces to counter the rate of change that causes the error. Most large aircraft use rate-based autopilot systems. Small aircraft may use either.

## Autopilot Components

Most autopilot systems consist of four basic components, plus various switches and auxiliary units. The four basic components are:

1. **Sensing Elements**: The attitude and directional gyros, the turn coordinator, and an altitude control are the autopilot sensing elements. These units sense the movements of the aircraft. They generate electric signals that are used by the autopilot to automatically take the required corrective action needed to keep the aircraft flying as intended. The sensing gyros can be located in the cockpit mounted instruments. They can also be remotely mounted. Remote gyro sensors drive the servo displays in the cockpit panel, as well as provide the input signals to the autopilot computer.

2. **Computer and Amplifier**: The computing element of an autopilot may be analog or digital. Its function is to interpret the sensing element data, integrate commands and navigational input, and send signals to the output elements to move the flight controls as required to control the aircraft. An amplifier is used to strengthen the signal for processing, if needed, and for use by the output devices, such as servo motors. The amplifier and associated circuitry is the computer of an analog autopilot system. Information is handled in channels corresponding to the axis of control for which the signals are intended (i.e., pitch channel, roll channel, or yaw channel). Digital systems use solid state microprocessor computer technology and typically only amplify signals sent to the output elements.

3. **Output Elements**: The output elements of an autopilot system are the servos that cause actuation of the flight control surfaces. They are independent devices for each of the control channels that integrate into the regular flight control system. Autopilot servo designs vary widely depending on the method of actuation of the flight controls. Cable-actuated systems typically utilize electric servo motors or electro-pneumatic servos. Hydraulic actuated flight control systems use electro-hydraulic autopilot servos. Digital fly-by-wire aircraft utilize the same actuators for carrying out manual and autopilot maneuvers. When the autopilot is engaged, the actuators respond to commands from the autopilot rather than exclusively from the pilot. Regardless, autopilot servos must allow unimpeded control surface movement when the autopilot is not operating.

4. **Command Elements**: The command unit, called a flight controller, is the human interface of the autopilot. It allows the pilot to tell the autopilot what to do. Flight controllers vary with the complexity of the autopilot system. By pressing the desired function buttons, the pilot causes the controller to send instruction signals to the autopilot computer, enabling it to activate the proper servos to carry out the command(s). Level flight, climbs, descents, turning to a heading, or flying a desired heading are some of the choices available on most autopilots. Many aircraft make use of a multitude of radio navigational aids. These can be selected to issue commands directly to the autopilot computer.

In addition to an on/off switch on the autopilot controller, most autopilots have a disconnect switch located on the control wheel(s). This switch, operated by thumb pressure, can be used to disengage the autopilot system should a malfunction occur in the system or any time the pilot wishes to take manual control of the aircraft.

### Feedback or Follow-up Element

As an autopilot maneuvers the flight controls to attain a desired flight attitude, it must reduce control surface correction as the desired attitude is nearly attained so the controls and aircraft come to rest on course. Without doing so, the system would continuously overcorrect. Surface deflection would occur until the desired attitude is attained. But movement would still occur as the surface(s) returned to pre-error position. The attitude sensor would once again detect an error and begin the correction process all over again. Various electric feedback, or follow-up signals, are generated to progressively reduce the error message in the autopilot so that continuous over correction does not take place. This is typically done with transducers on the surface actuators or in the autopilot servo units.

A rate system receives error signals from a rate gyro that are of a certain polarity and magnitude that cause the control surfaces to be moved. As the control surfaces counteract the error and move to correct it, follow-up signals of opposite polarity and increasing magnitude counter the error signal until the aircraft’s correct attitude is restored. A displacement follow-up system uses control surface pickups to cancel the error message when the surface has been moved to the correct position.

## Autopilot Functions

The following autopilot system description is presented to show the function of a simple analog autopilot. Most autopilots are far more sophisticated; however, many of the operating fundamentals are similar.

The automatic pilot system flies the aircraft by using electrical signals developed in gyro-sensing units. These units are connected to flight instruments that indicate direction, rate of turn, bank, or pitch. If the flight attitude or magnetic heading is changed, electrical signals are developed in the gyros. These signals are sent to the autopilot computer/ amplifier and are used to control the operation of servo units.

A servo for each of the three control channels converts electrical signals into mechanical force, which moves the control surface in response to corrective signals or pilot commands. The rudder channel receives two signals that determine when and how much the rudder moves. The first signal is a course signal derived from a compass system. As long as the aircraft remains on the magnetic heading it was on when the autopilot was engaged, no signal develops. But, any deviation causes the compass system to send a signal to the rudder channel that is proportional to the angular displacement of the aircraft from the preset heading.

The second signal received by the rudder channel is the rate signal that provides information anytime the aircraft is turning about the vertical axis. This information is provided by the turn-and-bank indicator gyro. When the aircraft attempts to turn off course, the rate gyro develops a signal proportional to the rate of turn, and the course gyro develops a signal proportional to the amount of displacement. The two signals are sent to the rudder channel of the amplifier, where they are combined, and their strength is increased. The amplified signal is then sent to the rudder servo. The servo turns the rudder in the proper direction to return the aircraft to the selected magnetic heading.

As the rudder surface moves, a follow-up signal is developed that opposes the input signal. When the two signals are equal in magnitude, the servo stops moving. As the aircraft arrives on course, the course signal reaches a zero value, and the rudder is returned to the streamline position by the follow-up signal.

The aileron channel receives its input signal from a transmitter located in the gyro horizon indicator. Any movement of the aircraft about its longitudinal axis causes the gyro-sensing unit to develop a signal to correct for the movement. This signal is amplified, phase detected, and sent to the aileron servo, which moves the aileron control surfaces to correct for the error. As the aileron surfaces move, a follow-up signal builds up in opposition to the input signal. When the two signals are equal in magnitude, the servo stops moving. Since the ailerons are displaced from the streamline, the aircraft now starts moving back toward level flight with the input signal becoming smaller and the follow-up signal driving the control surfaces back toward the streamline position. When the aircraft has returned to level flight roll attitude, the input signal is again zero. At the same time, the control surfaces are streamlined, and the follow-up signal is zero.

The elevator channel circuits are similar to those of the aileron channel, with the exception that the elevator channel detects and corrects changes in pitch attitude of the aircraft. For altitude control, a remotely mounted unit containing an altitude pressure diaphragm is used. Similar to the attitude and directional gyros, the altitude unit generates error signals when the aircraft has moved from a preselected altitude. This is known as an altitude hold function. The signals control the pitch servos, which move to correct the error. An altitude select function causes the signals to continuously be sent to the pitch servos until a preselected altitude has been reached. The aircraft then maintains the preselected altitude using altitude hold signals.

### Yaw Dampening

Many aircraft have a tendency to oscillate around their vertical axis while flying a fixed heading. Near continuous rudder input is needed to counteract this effect. A [yaw damper](https://en.wikipedia.org/wiki/Yaw_damper) is used to correct this motion. It can be part of an autopilot system or a completely independent unit. A yaw damper receives error signals from the turn coordinator rate gyro. Oscillating yaw motion is counteracted by rudder movement, which is made automatically by the rudder servo(s) in response to the polarity and magnitude of the error signal.

## Automatic Flight Control System (AFCS)

An aircraft autopilot with many features and various autopilot related systems integrated into a single system is called an automatic flight control system (AFCS). These were formerly found only on high-performance aircraft. Currently, due to advances in digital technology for aircraft, modern aircraft of any size may have AFCS.

AFCS capabilities vary from system to system. Some of the advances beyond ordinary autopilot systems are the extent of programmability, the level of integration of navigational aids, the integration of flight director and autothrottle systems, and combining of the command elements of these various systems into a single integrated flight control human interface.

It is at the AFCS level of integration that an autothrottle system is integrated into the flight director and autopilot systems with glide scope modes so that auto landings are possible. Small general aviation aircraft being produced with AFCS may lack the throttle-dependent features.

Modern general aviation AFCS are fully integrated with digital attitude heading and reference systems (AHRS) and navigational aids including glideslope. They also contain modern computer architecture for the autopilot (and flight director systems) that is slightly different than described above for analog autopilot systems. Functionality is distributed across a number of interrelated computers and includes the use of intelligent servos that handle some of the error correction calculations. The servos communicate with





More Reading

Videos
