Communications with the ATC
=====================================

The 1st RRF employs the use of an Air Traffic Controller to enhance realism and our capabilities. As such aircraft will need to know how to properly communicate with each other and the air traffic controller.

This manual is intended to break down all types of communication required when communicating with the ATC.

Standard Frequencies
--------
The following frequencies are standard for all 1st RRF aircraft.

+--------------------------+----------------------+-------------------------------------------+
| GROCON                   | AIRCON               | TRACON                                    |
+==========================+======================+===========================================+
| 33 Mhz                   | 35Mhz                | 37Mhz                                     |
+--------------------------+----------------------+-------------------------------------------+

For all uncontrolled airspace use AIRCON frequency.

Airframe Start-Up
--------
    1. File a flight plan on the 1st Rapid Response Force Website (https://1st-rrf.com/paperwork/aviation/flight-plan)
    2. Crosscheck Flight Plan designator with ATC for Mission.
    3. Conduct visual inspection of aircraft and conduct control service check.
    4. Crosscheck monitoring systems, weapons control systems and FLIR systems for damage and operations.
    5. Crosscheck Radio Frequencies are programmed and monitored for Air Traffic Control, Squadron communications, and internal communications.

Each section will include a communication snippet:

Communication Snippet:
    - **Aircraft**: "GROCON, this is [Call Sign] (PHANTOM ONE), Checks complete - requesting startup for RRF-FP-[id] (04) from [parking position] (Hotel 3)"
    - **ATC**: “[Call sign] (PHANTOM ONE), this is GROCON, Startup authorized for RRF-FP-[id] (04)”
    - **Aircraft**: “GROCON, this is [Call sign] (PHANTOM ONE), Startup authorized for RRF-FP-[id] (04)"

Airframe Pushback
--------
If your aircraft is positioned in a manner where you cannot simply taxi out, you will need to obtain approval for a pushback from GROCON.

Communication Snippet:
    - **Aircraft**: “GROCON, this is [Call sign] (PHANTOM ONE), [parked position] (Hotel 2), request push-back”
    - **ATC**: “[Call sign] (PHANTOM ONE), this is GROCON, push-back approved”
    - **Aircraft**: “GROCON, this is [Callsign] (PHANTOM ONE), push back approved”

Airframe Taxi
--------
After push-back, or, if you are parked in a position from which you can taxi you will need to request taxi instructions to get to the runway.

Communication Snippet:
    - **Aircraft**: “GROCON, this is [Callsign] (PHANTOM ONE), [parked position] (Hotel 2), request take off clearance”
    - **ATC**: “[Callsign] (PHANTOM ONE), this is GROCON, [Runway] (runway 22), cleared for take-off.”
    - **Aircraft**: “GROCON, this is [Call sign] (PHANTOM ONE), taxiing to [holding point] (holding point runway 22), via [taxi route] (Golf and Alpha)”

Airframe Take-off clearance
--------
Before turning onto an active runway and taking off, request clearance.

Once you have taken off, switch to AIRCON Frequency.

Communication Snippet:
    - **Aircraft**: “GROCON, this is [Call sign] (PHANTOM ONE), [parked position] (Hotel 2), request taxi”
    - **ATC**: “[Call sign] (PHANTOM ONE), this is GROCON, taxi to [holding point] (holding point runway 22), via [taxi route] (Golf and Alpha)”
    - **Aircraft**: “GROCON, this is [Callsign] (PHANTOM ONE), cleared for take-off [Runway] (runway 22)”

Departure and Climb
--------
Once you are in the air:
    1. Check in with AIRCON (provide with current altitude)
.. note::

  Angels is a method of expressing altitude in hundreds of meters. Angels One Five would be 1500 meters whilst Angels Fifteen would be 15000 meters.

  Note – This has been modified for its original definition for ARMA.  

Communication Snippet:
    - **Aircraft**: “AIRCON, this is [Callsign] (PHANTOM ONE), [Altitude] (angels eight), climbing to [new altitude] (angels one five)”
    - **ATC**: “[Call sign] (PHANTOM ONE), this is AIRCON, identified, climb to [new altitude] (angels two zero).”
    - **Aircraft**: “AIRCON, this is [Call sign] (PHANTOM ONE), climb to [new altitude] (angels two zero).”

Proceed Direct To
--------
The air traffic controller at times may direct aircraft to a certain waypoint.

Communication Snippet:
    - **ATC**: “[Call sign] (PHANTOM ONE), this is AIRCON, proceed direct to [Grid] (1032 1231)”
    - **Aircraft**: “AIRCON, this is [Call sign] (PHANTOM ONE), proceeding direct to [Grid] (1032 1231).”

Headings and Vectors
--------
The ATC may direct aircraft to change direction, they will do this by providing a vector.

Communication Snippet:
    - **ATC**: “[Call sign] (PHANTOM ONE), this is AIRCON, turn [instructions with vector] (right heading 180)”
    - **Aircraft**: “AIRCON, this is [Call sign] (PHANTOM ONE),turning [instructions with vector] (right heading 180).”

Descend
--------
When returning to a friendly airbase, you will typically want to begin descending slowly, you should do this in conjunction with the ATC instructions.

Communication Snippet:
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), ready to descent (or request descent)”
    - **ATC**: “[Call sign] (PHANTOM ONE), descent to [altitude] (angels zero five)”
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), descending to [altitude] (angels zero five)”

Holdings
--------
For ARMA we have simplified holding patterns, all aircraft entering a holding pattern will follow a clockwise pattern holding at 500 meters until they are instructed to land. Holding can be waived if ATC instructs the pilot that there is no delay.

Communication Snippet:
    - **ATC**: “[Call sign] (PHANTOM ONE), enter holding pattern”
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), entering holding pattern”

Approach
--------
When arriving to the airbase, you will want to contact TRACON and requesting instructions on which runway you will be using and approaching.

Communication Snippet:
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), on approach, requesting instructions”
    - **ATC**: “[Call sign] (PHANTOM ONE), cleared for ILS approach on [runway] (runway 22L)”
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), cleared for ILS approach on runway 22L”

Landing Clearance
--------
When arriving to the airbase, you will want to contact TRACON and requesting instructions on which runway you will be using and approaching.

Communication Snippet:
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), on approach to [runway] (runway 22L), requesting landing clearance on [runway] (runway 22L)”
    - **ATC**: “[Call sign] (PHANTOM ONE), cleared to land on [runway] (runway 22L)”

Go Around
--------
There are times when the pilot must abort their landing attempt or the ATC instructs the pilot to abort.

In this case, they will want your aircraft to go around.

Communication Snippet:
    - **Aircraft - Abort**: “TRACON, this is [Call sign] (PHANTOM ONE), going around”
    - **ATC**: “[Call sign] (PHANTOM ONE), follow missed approach as published”
or 
    - **ATC - Abort**: “[Call sign] (PHANTOM ONE), go around, I say again, go around. [Vector] (Maintain runway heading), climb [altitude] (angels one seven)”
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), going around. [Vector] (Maintain runway heading), climb [altitude] (angels one seven)”

Standard missed approach process is to join go into holding pattern and request approach and landing instructions from TRACON

Taxi To Gate
--------
After the aircraft, has landed and they are no longer on the runway. The pilot should request taxi instructions back to parking or gate.

Communication Snippet:
    - **ATC**: “[Call sign] (PHANTOM ONE), this is TRACON, taxi to [parking location] (hanger 1) via [taxi route] (Alpha Bravo)”
    - **Aircraft**: “TRACON, this is [Call sign] (PHANTOM ONE), taxiing to [parking location] (hanger 1) via [taxi route] (Alpha Bravo)”

Emergencies
--------
During an emergency, you will contact the ATC and send the following distress call.

Communication Snippet:
    - **Aircraft**: “Mayday, Mayday, Mayday, [Call sign] (PHANTOM ONE) declaring an emergency”

Reporting a Downed Aircraft
~~~~~~~~~~
If an aircraft that was flying in formation or aircraft has crashed. The following message should be broadcasted to the ATC.

Communication Snippet:
    - **Aircraft**: “AIRCON, [Call sign] (PHANTOM ONE), fallen angel [downed callsign]( PHANTOM TWO) at [grid] (10321041), [surviors] (survivors visible at this time).