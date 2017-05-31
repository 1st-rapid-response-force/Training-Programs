Advanced Infantry Radio Manual
========================================

An Introduction to Radio Networks in the 1st RRF
--------------

Radio networks are designed to relay time sensitive critical information vertically to command and control elements and horizontally to the adjacent units in order to facilitate the flow of situational awareness and coordinated control of operations.

What is a Radio Network?
~~~~~~~~~~~

A Radio Network in the 1st RRF is defined as a radio frequency on which official radio doctrine is used and there is an expectation of brevity and purpose to each transmission.

.. note:: Squad / Element radio frequencies are not counted as Radio Networks under official doctrine. Element leaders will determine the procedures used on these "uncontrolled" networks.

Concepts of Transmission
~~~~~~~~~~~

Transmissions on a Radio Network should be CLEAR and CONCISE with clearly stated receiving and sending callsigns in order to accurately convey information to any receiving element in a standardized way. On a Radio Network air time is everything so the shorter you can make your transmission - the better the communication will be.

Radio Networks are single TX ( Transmitter ), multiple RX ( Receiver ) networks - this means that only one person can speak on the network and that voices cannot be seperated or tuned on a given network. This is important as it means that any time you are speaking on a network you are actively preventing anyone else from transmitting on that network.

If elements fail to follow correct radio procedures on a Radio Network they will severely negatively impact the flow of the operations by impeding efficient communication.

Transmission Accuracy is extremely important to tactical radio communication and you should take time to prepare the statements you intend to transmit prior to beginning your broadcast on a given network. By clearly defining your message ahead of time you will use less air time and are less likely to make mistakes during transmission.

Speak Clearly - Radio Networks air time is precious but if you have to say your entire transmission twice then you will use even more of it. This is particularly important for members with heavy regional accents who may need to speak more slowly in order to be understood. Take your time to clearly state your transmission so that you will not need to say it again.

Layered Networks
~~~~~~~~~~~

In the 1st RRF we use a layered set of networks to mesh a large number of assets concurrently. This means that an individual may be listening to and communicating on multiple radio frequencies.

The resulting layers of frequencies is referred to as the Network Composition which is a complete listing of each channel that will be in use, it's intended purpose and which callsigns are expected to operate on it.

Command will plan the Network Composition in advance around any present hostile threats or friendly assets that may have overlapping utilization. Whilst this course will teach how to operate in a multi layer radio environment it will not cover how to plan a Composition.


Basic Principles of Radio Communication
----------------------------

Radio usage in the 1st Rapid Response Force is a complex and disciplined task - however this complexity mainly comes from the amount of communication and not the complexity of individual tasks. At their core radio usage is very simple. Below you will find the major principles explained.

Frequency
~~~~~~~~~~~~~~

A Frequency forms the base of any radio communication. Radio's work - at a very basic level - by emitting electromagnetic waves which have different oscillation frequencies. By tuning to a frequency the radio is able to receive and transmit on the specified frequency.

.. note::
  Military grade radios are significantly more complicated than this and use cryptography and advanced frequency manipulation - however that is not simulated in the game.

Frequencies with very similar wavelengths or certain mathematical relationships between them can interfere with each other so a good comm plan will ensure that frequencies are not overlapping or interfering with each other.

Only one Radio Network can operate per Frequency.

Channels
~~~~~~~~~~~~~~

A Channel is a preprogrammed channel on a radio device that allows for rapid switching to preprogrammed networks. Examples are that Channel 1 might be tuned to 50 and Channel 2 might be tuned to 51. By switching between Channel 1 and Channel 2 the user will be able to change between 50 and 51 faster than typing in the frequency.

**Alternate Channels**

Some radios in the unit will allow for the allocation of an Alternate Channel. An Alternate Channel is a channel that can be operated in addition to the primary channel. This would allow an operator to RX and TX at the same time on two channels from the same radio unit.

Network
~~~~~~~~~~~~~~

A defined use of a given Frequency that is used by a set of Callsigns to communicate with one and other for a designated purpose. For example you might have a command net for communication of High level orders to execution elements, or a fires net for communication with Artillery or IDF elements.

Radio
~~~~~~~~~~~~~~

A Radio is an electronic Transceiver that allows for the RX and TX of communications of one or more specified frequencies.

Radio's come with different length of Atenna and Power Output that will affect their maximum transmission range and the extent to which they are effected by terrain or meteoroligcal interferance. Some radios will also feature advanced functionality such as GPS positioning, Multiple Frequencies ( Alternate Frequency Programming ), Speakers, Stereo Audio Assignment and backlights for operation in low light conditions.

Radio's in the 1st RRF come in three ratings:

**SCOM Rated**

SCOM ( Short Comm ) rated radio's are rated for a transmission range of 5KM operating between 50 and 512 MHz with a frequency resolution of 0.1 MHz.

**LCOM Rated**

LCOM ( Long Comm ) rated radio's are rated for a transmission range of 20 KM and operate between 30 and 87 MHz with a frequency resolution of 0.1MHz.

**AVCOM Rated**

AVCOM ( Aviation Comm ) rated radio's are rated for a transmission range of 40 KM and can operate between 30 and 87MHz with a frequency resolution of 0.1 MHz.


When provided with a radio by the unit you will always be given its COM rating as well as it's feature list. If you are not given this information a full list of our radios, their ratings and features can be found in Appendix C - Radio Equipment.

Transmission
~~~~~~~~~~~~~~

A Transmission is a burst of communication sent from one callsign to another on a Frequency. A transmission occurs on a frequency and contains the sender and intended recipient in alongside a corresponding end word - either "Over" or "Out" but never both.

Message
~~~~~~~~~~~~~~

A Message is the contents of a transmission that conveys particular components of information.

Call Sign
~~~~~~~~~~~~~~

A Callsign is a keyword designed to uniquely identify a radio operator on a Network. Callsigns also provide increased OPSEC in the event that communications are compromised as they mask the identity or capabilities of an element.

.. note::
  In the 1st RRF we assume that communications are secure at all times and cannot be jeaprodised. This is so that we do not have to deal with cryptographic and frequency rekeys in the event of a radio being lost.

  All radios should still be recovered or destroyed in the gamespace so as to prevent their aquisition by hostile forces - however the 57A team is forbidden from using this to directly listen to or intefere with blufor comms.

Callsigns are assigned in advance by command and will usually follow the unit SOP for radio callsigns found as Appendix A - SOP Call Card.

Basics of Radio Transmission
-------------------------------

Messages are constructed of a Wrapper and a Message.

The Wrapper
~~~~~~~~~~~~~~

The Wrapper refers to the standard prefix and suffix to any Message that correctly addresses and ends the communication.

A Wrapper follows the following structure:

*"(RX), this is (TX), MESSAGE { Over | Out }"*

Breaking this down by component:

**RX**

RX refers to the intended recipient callsign. This can include multiple callsigns - for example, Archer 1, Archer 2 and Archer 3 - or address all callsigns on the net using "ALCON".

**TX**

TX refers to the transmitting callsign. This should be the callsign of the radio operator sending the transmission.

**Terminator**

The Terminator is the ending word of a transmission. You should never use Over and Out together as this is a misconception and often representative of a poor understanding of radio SOP.

**Over** Signals that this transmission has ended but a response or acknowledgment is expected to the communication.

**Out** Signals that the transmission has ended AND that no further response is expected.

.. warning::
  Some radio operators have been known to make liberal use of the Out terminator when their transmission still requires acknowledgment of receipt.

  Ensure that you use Out only when all necessary acknowledgments have been sent.

The Message
~~~~~~~~~~~~~~

The intended transmission contents is then placed inside the wrapper to ensure delivery of the information. Message types and formats will be covered in the next chapters.

Message Protocols
--------------------

There are many formats for messages - the standards for which are laid out on this page. This page starts with the more basic information - such as the NATO phonetic alphabet - and eventually develops into more complex multi transmission messages.

Tactical Reports and Requests will be covered in the next chapters.

The NATO Phonetic Alphabet
~~~~~~~~~~~~~~

The NATO Phoentic Alphabet is used when an alphanumeric character needs to be expressed over the network.

.. image:: ../_static/NATO_alphabet.png
    :align: center


Brevity Codes
~~~~~~~~~~~~~~

Prowords - also often referred to as Brevity Codes - are specially defined words that have predefined special meanings.

**ALL AFTER** – Reference portion of the message after

**AFFIRM** – True or correct

**ALL BEFORE** – Reference portion of the message before

**BREAK** – Indication of separation from other parts of the message

**CALL SIGN** – Group that follows is a call sign

**CORRECT** – What you have transmitted is correct

**COPY** – Information received as follows - information will then be restated for confirmation.

**CORRECTION** – Indicates correction to previous message

**DISREGARD** – Transmission is in error, disregard

**NOTHING FOLLOWS** – Do not respond to the following transmission

**I SAY AGAIN** – Indicates transmission or portion of a message will be repeated

**INTEROGATIVE** – What follows is a question which should be answered

**MORE TO FOLLOW** – More information will follow the current transmission

**NEGATIVE** – Transmission not acknowledged or cannot comply

**OUT** – Indicates the end of the transmission and no answer is required or expected

**OVER** – Indicates the end of the transmission and a response is necessary

**RELAY (TO)** – Transmit the following message to the indicated stations

**ROGER** – Transmission understood

**PRIORITY** - The following transmission is of elevated importance

**SAY AGAIN** – Request repeat of all or a portion of the last transmission

**THIS IS** – Transmission is originating from the call sign immediately following

**TIME** – Time that follows is the time of the message

**WAIT** – Transmission will pause for a few seconds

**WAIT-OUT** – Transmission will pause for longer than a few seconds

Basic Messages
~~~~~~~~~~~~~~

A Basic Message is used when there is no official SOP for the communication or it is out of routine scope.

- *"RX, this is TX, MESSAGE, OVER"*
- *"TX, this is RX, SEND TRAFFIC, OVER"*
- *"RX, this is TX, MESSAGE blah blah blah, OVER"*
- *"TX, this is RX, ROGER OVER"*

Net Calls
~~~~~~~~~~~~~~

A Netcall is used by a leader - in this example Archer 6 - to establish that his elements are on the network.

- *“All stations this net, this is Archer 6, respond in sequence, radio check, OVER”*
- *"This is Archer 1-1, OVER”*
- *“This is Archer 1-2, OVER”*
- *“This is Archer 1-3, OVER”*
- *“All stations this net, this is Archer 6, ROGER, OUT”*

Radio Check
~~~~~~~~~~~~~~

A Radio Check is used to conduct a check of communication between one or more indicated stations on the net

-	“(RX), this is (TX), radio check on FREQUENCY, OVER”
-	“(TX), this is (RX), ROGER on FREQUENCY, OVER”
-	“(RX), this is (TX), ROGER, OUT”

Tactical Reports
------------------

This chapter covers all of the standardized radio reports used in the Unit.

It does not include Aviation reports which can be found in the Tactical Air Controller and Air Trafic Controller training programs.

Troops in Contact Report
~~~~~~~~~~~~~~

The troops in contact report is a basic report sent to signal that an element has taken contact. It is short and designed to be made during or immediately after contact.

- *"(RX), this is (TX), break, break, PRIORITY - Contact - in vicinity GRID 000000, OVER"*
- *"(TX), this is (RX), COPY Contact - in vicinity GRID 000000, OVER."*
- *"(RX), this is (TX), NOTHING FOLLOWS, OUT"*


Front Line Trace ( POSREP )
~~~~~~~~~~~~~~

Front Line Traces provide the location of the element - normally they will use a grid but they can also use a location such as "The Eastern Hangar".

-	*“(RX), this is (TX), Location GRID 1234 5678, OVER”*
-	*“(TX), this is (RX), COPY, Location GRID 1234 5678, OUT”*

SALUTE Report ( SPOTREP )
~~~~~~~~~~~~~~

SALUTE Reports are used to transmit information regarding contact or observation of hostile or targeted elements in the battle space.

SALUTE stands for Size, Activity, Location, Unit, Time and Equipment. This format is used so that when you transmit the information can be sent without pause. SALUTE reports should be employed either before or after contact - but should not be used during contact. During contact a Troops in Contact report should be sent instead.

If you have multiple contacts to report you should send multiple SALUTEs - one for each element.

**Step 1 - Announce you will send a report and wait for the RX to acknowledge they are ready**

-	*“(RX), this is (TX), SALUTE report to follow, OVER”*
-	*“(TX), this is (RX), ROGER, OVER”*

**Step 2 - Send the SALUTE**

-	*“(RX), this is (TX), SIERRA, 1 dismounted patrol in the open, BREAK”* - Size of the element
-	*“ALPHA, Setting up fighting positions, BREAK”* - Activity that the element is performing
-	*“LIMA, grid 1234 5678, BREAK”* - Location of the element
-	*“UNIFORM, CSAT SF, BREAK”* - The type of unit that you believe the element to be ( for example an AA team )
-	*“TANGO – 0730 hours, BREAK”* - The time that the unit was at this location
-	*“ECHO – 1 RPK, 4 AK-47, 2 static HMG, OVER”* - The Equipment that the unit has
-	*“(TX), this is (RX), ROGER, OUT”*

Status Report (ACE)
~~~~~~~~~~~~~~

ACE Reports are used to indicate the combat effectveness of an element based on their equipment for the purposes of resupply or pre planned engagement. The components of an ACE report are Ammunition, Casualties and Equipment.

Ammunition is expressed as a color, perecentage of initial load or an absolute value. If using a color - it should use the standard thresholds defined in early training. If using an absolute value it should use the total number of each type of rounds. For example a 200 rnd box mag would be counted as 200 whilst a 30 rnd magazine would be counted as 30. This would give a total of 230.

Casualties are expressed as either a colour representing total combat effectiveness from casualties or as a series of MEDSTAT reports - the format and definitions for which can be found in the TC3 program.

Equipment can be expressed as the absolute number of available equipment pieces or as a color indicating mission readiness.

When transmitting an ACE report to a higher station the report combines all of those from the elements below it - a platoon report is made up by combining the squads, a squad is made up by combining the fireteams and so on.

**Step 1 - Announce you will send a report and await confimration from the RX**

-	*“(RX), this is (TX), ACE report to follow, OVER”*
-	*“(TX), this is (RX), ROGER, OVER”*

**Step 2 - Send the ACE report to the callsign**

-	*“(RX), this is (TX), ALPHA, 100 5.56, BREAK”* - Ammunition
-	*“CHARLIE, 1 Whsikey - Red, Red, Green, 2 Kilo BREAK”* - Casualties
-	*“ECHO, 1 AT-4, 2 explosive charges, black on claymores, OVER”* - Equipment
-	*“(TX), this is (RX), ROGER, OUT”*

Vehicle Report (DEFREP)
~~~~~~~~~~~~~~

A DEFREP is a specialized report used to report the status of vehicles in use by the element.

.. note::
  This report has been created by the 1st RRF and is not an authentic military report.

Vehicle Reports contains three components: Damage - Reported by exception, i.e only report problems , Equipment ( such as spare tires or radios ) - reported by color code and Fuel - reported by color code.

**Step 1 - Announce you will send a report and await confimration from the RX**

-	*“(RX), this is (TX), DEFREP report to follow, OVER”*
-	*“(TX), this is (RX), ROGER, OVER”*

**Step 2 - Send the ACE report to the callsign**

-	*“(RX), this is (TX), DELTA, no damage, BREAK”* - Damage
-	*ECHO, Green BREAK”* - Equipment
-	*FOXTROT, Red OVER”* - Fuel
-	*“(TX), this is (RX), ROGER, OUT”*
