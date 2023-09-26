# DuncanU
DuncanU
This will be used as a location to house open source information to help teach new avionics techs.   


# Automatic direction finder 

An automatic direction finder (ADF) is a radio-navigation instrument that automatically and continuously displays the relative bearing from the aircraft to a suitable radio station. ADF receivers are normally tuned to aviation NDBs (Non-Directional Beacon) operating in the LW band between 190 – 535 kHz. Like RDF ([Radio Direction Finder](https://en.wikipedia.org/wiki/Direction_finding)) units, most ADF receivers can also receive medium wave (AM) broadcast stations, though these are less reliable for navigational purposes.

The operator tunes the ADF receiver to the correct frequency and verifies the identity of the beacon by listening to the Morse code signal transmitted by the NDB. On old ADF receivers used a motorized ferrite-bar antenna atop the unit (or remotely mounted) would rotate and lock when reaching the null of the desired station. See Loop Antenna on top of Amelia Earhart's Lockheed Model 10 Electra.
![](ADF/RDFAntenna.jpg)
A bearing indicator on the antenna unit would movie atop a compass rose indicated in degrees the bearing of the station. On aviation ADFs, the unit automatically moves a compass-like pointer ![RMI](ADF/RMI.jpg) to show the direction of the beacon. The pilot may use this pointer to home directly towards the beacon, or may also use the magnetic compass and calculate the direction from the beacon (the radial) at which their aircraft is located.

Unlike the RDF, the ADF operates without direct intervention, and continuously displays the direction of the tuned beacon. Initially, all ADF receivers contained a rotating loop or ferrite loopstick aerial driven by a motor which was controlled by the receiver. Like the RDF, a sense antenna verified the correct direction from its 180-degree opposite.![](ADF/adf_antenna.jpg)

Modern aviation ADFs contain a small array of fixed aerials and use electronic sensors to deduce the direction using the strength and phase of the signals from each aerial. The electronic sensors listen for the trough that occurs when the antenna is at right angles to the signal, and provide the heading to the station using a direction indicator. In flight, the ADF's RMI or direction indicator will always point to the broadcast station regardless of aircraft heading. Dip error is introduced, however, when the aircraft is in a banked attitude, as the needle dips down in the direction of the turn. This is the result of the loop itself banking with the aircraft and therefore being at a different angle to the beacon. For ease of visualisation, it can be useful to consider a 90° banked turn, with the wings vertical. The bearing of the beacon as seen from the ADF aerial will now be unrelated to the direction of the aircraft to the beacon.

ADF receivers can be used to determine current position, track inbound and outbound flight path, and intercept a desired bearing. These procedures are also used to execute holding patterns and non-precision instrument approaches.![](ADF/ndb_track.jpg)

## More Reading
[Pilots Handbook of Aeronautical Knowledge](ADF/Pilots%Handbook%of%Aeronautical%Knowledge.pdf)

## Videos
[Understanding ADF](https://youtu.be/QQitucLrC8U?si=UZUXvmXRAXL9OD61)

# Distance Musering Equipment 

In aviation, distance measuring equipment (DME) is a radio navigation technology that measures the slant range (distance) between an aircraft and a ground station by timing the propagation delay of radio signals in the frequency band between 960 and 1215 megahertz (MHz). Line-of-visibility between the aircraft and ground station is required. An interrogator (airborne) initiates an exchange by transmitting a pulse pair, on an assigned 'channel', to the transponder ground station. The channel assignment specifies the carrier frequency and the spacing between the pulses. After a known delay, the transponder replies by transmitting a pulse pair on a frequency that is offset from the interrogation frequency by 63 MHz and having specified separation.[1]

DME systems are used worldwide, using standards set by the International Civil Aviation Organization (ICAO),[1] RTCA,[2] the European Union Aviation Safety Agency (EASA)[3] and other bodies. Some countries require that aircraft operating under instrument flight rules (IFR) be equipped with a DME interrogator; in others, a DME interrogator is only required for conducting certain operations.

While stand-alone DME transponders are permitted, DME transponders are usually paired with an azimuth guidance system to provide aircraft with a two-dimensional navigation capability. A common combination is a DME colocated with a VHF omnidirectional range (VOR) transmitter in a single ground station. When this occurs, the frequencies of the VOR and DME equipment are paired.[1] Such a configuration enables an aircraft to determine its azimuth angle and distance from the station. A VORTAC (a VOR co-located with a TACAN) installation provides the same capabilities to civil aircraft but also provides 2-D navigation capabilities to military aircraft.

Low-power DME transponders are also associated with some instrument landing system (ILS), ILS localizer and microwave landing system (MLS) installations. In those situations, the DME transponder frequency/pulse spacing is also paired with the ILS, LOC or MLS frequency.

ICAO characterizes DME transmissions as ultra high frequency (UHF). The term L-band is also used.[4]

Developed in Australia, DME was invented by James "Gerry" Gerrand[5] under the supervision of Edward George "Taffy" Bowen while employed as Chief of the Division of Radiophysics of the Commonwealth Scientific and Industrial Research Organisation (CSIRO). Another engineered version of the system was deployed by Amalgamated Wireless Australasia Limited in the early 1950s operating in the 200 MHz VHF band. This Australian domestic version was referred to by the Federal Department of Civil Aviation as DME(D) (or DME Domestic), and the later international version adopted by ICAO as DME(I).

DME is similar in principle to secondary radar ranging function, except the roles of the equipment in the aircraft and on the ground are reversed. DME was a post-war development based on the identification friend or foe (IFF) systems of World War II. To maintain compatibility, DME is functionally identical to the distance measuring component of TACAN.

## Operation

In its first iteration, a DME-equipped airplane used the equipment to determine and display its distance from a land-based transponder by sending and receiving pulse pairs. The ground stations are typically collocated with VORs or VORTACs. A low-power DME can be collocated with an ILS or MLS where it provides an accurate distance to touchdown, similar to that otherwise provided by ILS marker beacons (and, in many instances, permitting removal of the latter).

A newer role for DMEs is DME/DME area navigation (RNAV).[6][7] Owing to the generally superior accuracy of DME relative to VOR, navigation using two DMEs (using trilateration/distance) permits operations that navigating with VOR/DME (using azimuth/distance) does not. However, it requires that the aircraft have RNAV capabilities, and some operations also require an inertial reference unit.

A typical DME ground transponder for en-route or terminal navigation will have a 1 kW peak pulse output on the assigned UHF channel.

## Hardware 

The DME system comprises a UHF (L-band) transmitter/receiver (interrogator) in the aircraft and a UHF (L-band) receiver/transmitter (transponder) on the ground.

## Timing

### Search mode
150 interrogation pulse-pairs per second. The aircraft interrogates the ground transponder with a series of pulse-pairs (interrogations) and, after a precise time delay (typically 50 microseconds), the ground station replies with an identical sequence of pulse-pairs. The DME receiver in the aircraft searches for reply pulse-pairs (X-mode = 12-microsecond spacing) with the correct interval and reply pattern to its original interrogation pattern. (Pulse-pairs that are not coincident with the individual aircraft's interrogation pattern e.g. not synchronous, are referred to as filler pulse-pairs, or squitter. Also, replies to other aircraft that are therefore non-synchronous also appear as squitter).

### Track mode
Less than 30 interrogation Pulse-pairs per second, as the average number of pulses in SEARCH and TRACK is limited to max 30 pulse pairs per second. The aircraft interrogator locks on to the DME ground station once it recognizes a particular reply pulse sequence has the same spacing as the original interrogation sequence. Once the receiver is locked on, it has a narrower window in which to look for the echoes and can retain lock.

## Distance calculation

A radio signal takes approximately 12.36 microseconds to travel 1 nautical mile (1,852 m) to the target and back. The time difference between interrogation and reply, minus the 50 microsecond ground transponder delay and the pulse width of the reply pulses (12 microseconds in X mode and 30 microseconds in Y mode), is measured by the interrogator's timing circuitry and converted to a distance measurement (slant range), in nautical miles, then displayed on the cockpit DME display.

The distance formula, distance = rate * time, is used by the DME receiver to calculate its distance from the DME ground station. The rate in the calculation is the velocity of the radio pulse, which is the speed of light (roughly 300,000,000 m/s or 186,000 mi/s). The time in the calculation is ½(total time − reply delay).

## Accuracy

The accuracy of DME ground stations is 185 m (±0.1 nmi).[8] It's important to understand that DME provides the physical distance between the aircraft antenna and the DME transponder antenna. This distance is often referred to as 'slant range' and depends trigonometrically upon the aircraft altitude above the transponder as well as the ground distance between them.

For example, an aircraft directly above the DME station at 6,076 ft (1 nmi) altitude would still show 1.0 nmi (1.9 km) on the DME readout. The aircraft is technically a mile away, just a mile straight up. Slant range error is most pronounced at high altitudes when close to the DME station.

Radio-navigation aids must keep a certain degree of accuracy, given by international standards, FAA,[9] EASA, ICAO, etc. To assure this is the case, flight inspection organizations check periodically critical parameters with properly equipped aircraft to calibrate and certify DME precision.

ICAO recommends accuracy of less than the sum of 0.25 nmi plus 1.25% of the distance measured.

## Specification

A typical DME ground-based responder beacon has a limit of 2700 interrogations per second (pulse pairs per second – pps). Thus it can provide distance information for up to 100 aircraft at a time—95% of transmissions for aircraft in tracking mode (typically 25 pps) and 5% in search mode (typically 150 pps). Above this limit the transponder avoids overload by limiting the sensitivity (gain) of the receiver. Replies to weaker (normally the more distant) interrogations are ignored to lower the transponder load.

## Radio frequency and modulation data

DME frequencies are paired to VOR frequencies and a DME interrogator is designed to automatically tune to the corresponding DME frequency when the associated VOR frequency is selected. An airplane's DME interrogator uses frequencies from 1025 to 1150 MHz. DME transponders transmit on a channel in the 962 to 1213 MHz range and receive on a corresponding channel between 1025 and 1150 MHz. The band is divided into 126 channels for interrogation and 126 channels for reply. The interrogation and reply frequencies always differ by 63 MHz. The spacing of all channels is 1 MHz with a signal spectrum width of 100 kHz.

Technical references to X and Y channels relate only to the spacing of the individual pulses in the DME pulse pair, 12 microsecond spacing for X channels and 30 microsecond spacing for Y channels.

DME facilities identify themselves with a 1,350 Hz Morse code three letter identity. If collocated with a VOR or ILS, it will have the same identity code as the parent facility. Additionally, the DME will identify itself between those of the parent facility. The DME identity is 1,350 Hz to differentiate itself from the 1,020 Hz tone of the VOR or the ILS localizer.

## DME transponder types

The U.S. FAA has installed three DME transponder types (not including those associated with a landing system): Terminal transponders (often installed at an airport) typically provide service to a minimum height above ground of 12,000 feet (3,700 m) and range of 25 nautical miles (46 km); Low altitude transponders typically provide service to a minimum height of 18,000 feet (5,500 m) and range of 40 nautical miles (74 km); and High altitude transponders, which typically provide service to a minimum height of 45,000 feet (14,000 m) and range of 130 nautical miles (240 km). However, many have operational restrictions largely based on line-of-sight blockage, and actual performance may be different.[10] The U.S. Aeronautical Information Manual states, presumably referring to high altitude DME transponders: "reliable signals may be received at distances up to 199 nautical miles [369 km] at line−of−sight altitude".

DME transponders associated with an ILS or other instrument approach are intended for use during an approach to a particular runway, either one or both ends. They are not authorized for general navigation; neither a minimum range nor height is specified.

## Frequency usage/channelization

DME frequency usage, channelization and pairing with other navaids (VOR, ILS, etc.) are defined by ICAO.[1] 252 DME channels are defined by the combination of their interrogation frequency, interrogation pulse spacing, reply frequency, and reply pulse spacing. These channels are labeled 1X, 1Y, 2X, 2Y, ... 126X, 126Y. X channels (which came first) have both interrogation and reply pulse pairs spaced by 12 microseconds. Y channels (which were added to increase capacity) have interrogation pulse pairs spaced by 36 microseconds and reply pulse pairs spaced by 30 microseconds.

A total of 252 frequencies are defined (but not all used) for DME interrogations and replies—specifically, 962, 963, ... 1213 megahertz. Interrogation frequencies are 1025, 1026, ... 1150 megahertz (126 total), and are the same for X and Y channels. For a given channel, the reply frequency is 63 megahertz below or above the interrogation frequency. The reply frequency is different for X and Y channels, and different for channels numbered 1-63 and 64-126.

Not all defined channels/frequencies are assigned. There are assignment 'holes' centered on 1030 and 1090 megahertz to provide protection for the secondary surveillance radar (SSR) system. In many countries, there is also an assignment 'hole' centered on 1176.45 megahertz to protect the GPS L5 frequency. These three 'holes' remove approximately 60 megahertz from the frequencies available for use.

Precision DME (DME/P), a component of the Microwave Landing System, is assigned to Z channels, which have a third set of interrogation and reply pulse spacings. The Z channels are multiplexed with the Y channels and do not materially affect the channel plan.

## Future

In 2020 one company presented its 'Fifth-Generation DME'. Although compatible with existing equipment, this iteration provides greater accuracy (down to 5 meters using DME/DME triangulation), with a further reduction to 3 meters using a further refinement. The 3-meter equipment is being considered as part of Europe's SESAR project, with possible deployment by 2023.

In the twenty-first century, aerial navigation has become increasingly reliant on satellite guidance. However, ground-based navigation will continue, for three reasons:[citation needed]

The satellite signal is extremely weak, can be spoofed, and is not always available;
A European Union rule requires member states to keep and maintain ground-based navigation aids;
A feeling of sovereignty, or control over a state's own navigational means. "Some states want navigation over their territory to rely on means they control. And not every country has its constellation like the U.S.' GPS or Europe's Galileo."[attribution needed]
One advantage of the fifth-generation equipment proposed in 2020 is its ability to be function-checked by drone flights, which will significantly reduce the expense and delays of previous manned certification flight tests.[11]




## More Reading

## Videos
[Distance Measuring Equipment](https://youtu.be/wMmooAYr9sw?si=bqWSsvgKMyMLXZvk)
[DME](https://youtu.be/CEpoCVGk1UQ?si=HjiNIj6QVjT1fCE7)
