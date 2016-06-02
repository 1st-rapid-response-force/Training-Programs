Tactical Reports
================

This chapter covers all of the standardized radio reports used in the Unit.

It does not include Aviation reports which can be found in the Tactical Air Controller and Air Trafic Controller training programs.

Troops in Contact Report
-------------------------

The troops in contact report is a basic report sent to signal that an element has taken contact. It is short and designed to be made during or immediately after contact.

- *"(RX), this is (TX), break, break, PRIORITY - Contact - in vicinity GRID 000000, OVER"*
- *"(TX), this is (RX), COPY Contact - in vicinity GRID 000000, OVER."*
- *"(RX), this is (TX), NOTHING FOLLOWS, OUT"*


Front Line Trace ( POSREP )
---------------------------

Front Line Traces provide the location of the element - normally they will use a grid but they can also use a location such as "The Eastern Hangar".

-	*“(RX), this is (TX), Location GRID 1234 5678, OVER”*
-	*“(TX), this is (RX), COPY, Location GRID 1234 5678, OUT”*

SALUTE Report ( SPOTREP )
-------------------------

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
--------------------

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
---------------------------

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
