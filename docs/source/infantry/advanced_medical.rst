Infantry Medic Manual
=======================

The ACE 3 Medical System
---------------------------

Medics are expected to fully understand the ACE medical system including all possible symptoms and side effects as well as being drilled in quickly providing the correct care to patients.

In order to facilitate this goal you should carefully read through the following details of the ACE medical system. This is somewhat unique to our group based on the settings we use so you should read this with even greater care if you believe you already understand the medical system.

You should also be advised that not all avenues of treatment are available to all personnel and as such the system may be more complicated than the "hit them with a PAK" method used in other groups.

.. note::
  You should thoroughly review the information on this page.

  In order to help you operate at the highest level you can download the Apendices at the end of this training program that provide printable cheat cards for reference during training and combat.

The Basics
~~~~~~~~~~~~~~

In ACE the human body is represented as 6 distinct areas that can receive damage. Some of these areas have special abilities such as applying a tourniquet or using a variety of IV solutions.

Each living person in the battlespace has three key metrics which define their state of health. Every action you take will be to maintain or restore one of these metrics:

  * Blood Volume
  * Pulse
  * Responsive State ( Are they concious? )

**Blood Volume**

Blood volume is measured via blood pressure is measured by systolic and diastolic blood pressure - often expressed in the form ( systolic / diastolic ).

In ARMA you only need to pay attention to the systolic blood pressure to diagnose a condition. You can categorize blood pressure into colour categories as follows:

  * **BLACK** - No Pressure - 0-20 systolic
  * **RED** - Low Pressure - 20-100 systolic
  * **GREEN** - Normal Pressure - 100-160 systolic
  * **YELLOW** - High Pressure - 160 and above systolic

In the treatment section you will find out how to deal with these blood pressures.

**Pulse**

The Pulse - an indication of Heart Rate or Arterial Palpation - is the number of beats per minute that the patient's heart makes.

In ARMA we classify these into categories:

  * **BLACK** - No Pulse - 0 BPM
  * **RED** - Low Pulse - 45 BPM
  * **GREEN** - Normal Pulse - 46-119 BPM
  * **YELLOW** - High Pulse - 120 and above BPM

Blood pressure is affected by the patient's blood volume and administered medication.

**Responsive State**

If a patient's pulse or blood volume falls to low the patient will become unconcious ( non-responsive ). Unconcious states can also be prompted by sudden impacts such as car or helicopter crashes as well as being the result of chemical use such as morphine.

Responsiveness has two categories:

  * **BLACK** - Un Responsive
  * **GREEN** - Responsive

MEDSTAT
~~~~~~~~~~~~~~

A MEDSTAT is essentially an ACE report for patients. It consists of Blood Volume then Pulse then Responsive State.

For example:

  RED - GREEN - BLACK is a non responsive casualty with a normal pulse and a low blood pressure.

MEDSTATs allow for rapid communication about the status of a casualty.

Injury Type
~~~~~~~~~~~~~~

Each limb on the body can receive different types of injury. Each injury has a different level of pain and bleeding that it will inflict.

Each injury type also has a set of treatment procedures that are best suited for it - these will be laid out in the subsequent chapter about rendering aid.

The injury types are:

**Abrasions**

An Abrasion is a wound caused by friction. Examples include Vehicle Crashes and Rope Burn. This wound type has a **low** pain effect and an **extremely slow** bleed rate.

**Avulsions**

An Avulsion is when an entire structure is seperated from the body. Examples include lost teeth or an ear lobe. These are caused by explosions, shrapnel and any other situation which could sever a body part.

Avulsions have an **extremely high** pain effect with an **extremely fast** bleed rate.

**Contusions**

Contusions, commonly known as Bruises, are caused by traumas that injure an internal structure without breaking the skin. Blunt blows to areas such as the chest or head can cause contusions.

.. note::
  Due to poor modelling in ARMA contusions do not cause blood loss

**Lacerations**

Lacerations are wounds with ragged edges. They are produced by large forces exerted on the body.

Lacerations have a **light** pain effect with a **slow** bleed rate.

**Velocity Wound**

A Velocity wound is caused by objects entering the body at speed, such as shrapnel or bullets.

Velocity wounds have an **extremely high** pain effect with a **medium** bleed rate.

**Puncture Wounds**

A puncture wound is a narrow wound produced by a sharp object such as a knife.

Puncture wounds have a **light** pain effect with a **slow** bleed rate.

Injury Sizes
~~~~~~~~~~~~~~

Each injury type can come in a variety of sizes which increases or decreases the bleed rate of the wound.

Cardiac Arrest
~~~~~~~~~~~~~~

A cardiac arrest is when the heart stops pumping. In game this is an extremely bad situation and means that the individual has to be MEDEVACd to a Level 2 facility.

A Cardiac Arrest is triggered when a patient fufills any of the following criteria:

  * A heart rate below 20
  * A heart rate above 200
  * A Systolic blood pressure above 260
  * A Diastolic blood pressure below 40 with a heart rate above 190
  * A Systolic blood pressure is above 145 and the heart rate is above 150

Once a patient enters cardiac arrest they cannot be recovered in the field. CPR will extend the time until they fully die - allowing enough time for them to reach a medical facility capable of restarting the heart.

Setting up ACE to be efficient
~~~~~~~~~~~~~~

ACE 3 is a matrix of complicated 3D menus and contrived custom keys. As such we have introduce additional tooling to make this process faster for medical personnel so they are able to act more efficiently.

Changing the Medical Menu to a 2D interface:
  1. Go to the ACE OPTIONS menu in the top left hand corner of your in game options menu.
  2. Navigate to the "Medical Menu" option
  3. Enable the Medical Menu

After enabling the medical menu you should be able to ACE interact and find the "Medical Menu" under interactions - this is in contrast to the usual 3D "Medical" setting that would be there. This allows you to access the 2D medical menu and access time critical information faster.

.. note::
  We also recommend setting your ACE interact and self interact key to a mouse hotkey if you have them available so that you are able to access these options faster.

Conditions and Treatments
------------------

ACE adds a wide number of injury and treatment types to the game some of which were detailed in the ACE section of this program.

In this section we will explore the individual treatment options and the decision making tree of a medic.

Treatments
~~~~~~~~~~~~~

**Bandages**

ACE provides four different type of bandages - each with a different level of effectiveness on a given wound type.

.. image:: https://ace3mod.com/img/wiki/feature/medical1.jpg
    :align: center

Bandages are used to pack wounds to reduce bleeding and providing a surface for blood to clot against. Bandages are temporary solutions and wounds will require stitiching to repair permanently.

**Tourniquests**

Tourniquests are pressure devices used to prevent blood flowing into a limb. Due to the nature of the device they are highly effective at bleeding reduction in the limbs stopping bleeding entirely.

The downside of tourniquets is that they put the patient in a lot of pain if they are left on too long - sometimes to the point of rednering the patient unconcious.

**IVs**

ACE provides two types of intravenous bag that can be administered to patients. All IVs are used to help restore blood volume.

The first type is Saline which is used to rapidly provide blood volume to a patient. Saline is a double edged sword as it reduces blood clotting meaning that bleeding can be intesnified by overuse of saline IVs. It is useful for restoring patient's who have lost a little blood or stabilizing patients who are suffering  cardiac failure due to low blood pressure until MEDEVAC arrives.

The second type of IV is a blood transfusion. Blood transfusions restore blood volume and are used in cases of heavy blood loss. Blood transfusions do however require specialized refrigerated transport arrangements meaning that they are not carried by medics in the field and must be kept in vehicles.

.. note:: We do not simulate blood types in game.

**Injected Drugs**

ACE provides three types of Autoinjector for injecting drugs. Drugs are used to manipulate the pulse and to reduce pain levels.

The first and most common autoinjector is Morphine which reduces the pain experienced by the patient. It also has side effects of reducing the patient's blood pressure and heart rate, reducing it by around 20 BPM.

The second autoinjector is Epinephrine - more commonly known as Adrenaline. This drug solely affects the patient's pulse raising it by around 20 BPM.

The third autoinjector is Atropine - a muscle relaxant - which lowers the heart rate of the patient by approximately 20 BPM.

**Surgical Kits**

Surgical Kits allow the bearer ( assuming they are medic qualified ) to sew wounds closed to prevent them from reopening.

Surgical kits are available to all medics in the group - but do require that the user be inside a medical vehicle or facility.

**Personal Aid Kits**

The Personal Aid Kit is a one hit Jesus level wonder of modern medicine that instantly restores the user to full health in every way. This glorious and remarkable achievement can only be performed in a Level 2 medical facility.

Providing Aid to a Patient
~~~~~~~~~~~~~

The first priority in combat medicine is always to keep the blood inside the body. Bleeding control and management is more important that anything else because without it all other efforts will be wasted.

Therefore when dealing with a casualty you should follow the following process:

.. image:: ../_static/medical_flowchart.png
    :align: center

Medical Facility Levels and the Pipeline of Care
------------------------

.. danger:: Medical Facility Levels and the MEDEVAC policy is currently under strategic review. The following information may be out of date with the latest edge of combat training and doctrine within the unit.

In the RRF we split our medical pipeline into three distinct phases - Care under Fire, Level 1 and Level 2 care.

Below you will find an explanation of each level as well as the transfer between these levels.

Care under Fire
~~~~~~~~~~~~~~~~~~

Care under Fire is the actions undertaken by the squadmates of the injured personnel when a casualty is first injured. This phase revolves solely around bleeding control until such a time that the casualty can be transfered to a trained medical team at a Level 1 care facility.

All infantry personnel are extensively drilled on reacting to injury and the handoff procedures. At the end of the Care under Fire process injured personnel should have been tourniqued and bandaged to the best ability of the element that they belong to. Bleeds will not have been stitched and may reopen. Frontline infantry may have also administered morphine as a pain relief tool or epinehrine if the patient was suffering from a low heart rate.

Level 1 Medical Care
~~~~~~~~~~~~~~~~~~

Level 1 Medical Care begins when a casualty is received by a medical team at a CCP.

.. note::
  A CCP ( Casualty Collection Point ) is an area designated by a platoon leader where a medical detachment should prepare to receive casualties.

  CCPs will generally be somewhat set back from the frontline trace and will routinely be provided with a small security element.

  The purpose of a CCP is to provide a central location for all injured personnel to be triaged and treated by a trained medic or forwarded onto further care. It also serves as a location for collection of dead personnel by Logistics elements.

  When establishing a CCP at a given location medical teams should define a reception point where casualties are received and triaged as well as a treatment area where casualties are given aid.

  This information should then be marked on the map so that other elements know how to work efficiently with the medical team at the CCP.

Infantry personnel will hand over casualties at the designated triage area of the CCP and provide the medic with:

  * **Any aid rendered**
  * **Casualty Roster Number and Element**
  * **Cause of injury**
  * **Time of handoff (Local Time)**

**Medical personnel should then physically note this information in real life on paper as it is important to keep track of casualties who may be potentially MIA or non responsive.**

Once a casualty is received from the infantry the medic will triage the casualty into one of four categories:

  * **GREEN** Clear for discharge from the CCP. No active bleeds ( all have been stitched ) with a good blood volume and stable pulse. Able to effectively fight.

  * **YELLOW** Requires medical attention at a non life threatening level. All wounds have been bandaged but have not been stitched. May be low on fluid and attached to an IV. Not cleared for discharge but does not require active medical attention.

  * **RED** Requires urgent medical attention to stabilise and will require MEDEVAC. Casualty may have suffered cardiac arrest, severe bleeding and extreme loss of blood volume. The medical team will attempt to stabilize the casualty  for MEDEVAC.

  * **BLACK** The casualty is dead. All medical aid will cease and the casualty is treated as a logistical issue from this point forward.

.. danger::
  **WE DO NOT LEAVE BODIES BEHIND. DEAD PERSONNEL MUST ALL BE RECOVERED ALONGSIDE WOUNDED PERSONNEL.**

Medics will prioritize casualties based on their colour code dealing with the most severe first.

Medical teams have autonomy in the way that they run the CCP however the official recommendation is that one member of the team provides Triage whilst the other renders aid. This is because triage is a constant process of monitoring bleeding, Pulse and Blood Pressure for all personnel in the CCP in parrallel to the time intensive task of rendering aid is performed.

.. note::
  Medical personnel can request that teammates dropping off wounded personnel remain behind to render CPR if necessary. **Medical personnel should not commit to performing CPR themselves unless absoloutely necessary - always try to seek outside assistance**

Performing a MEDEVAC
~~~~~~~~~~~~~~~~~~

It is the sole decision of the senior medic if a casualty requires a MEDEVAC. If a MEDEVAC is called the medic should provide the necessary information for the five line to the platoon leader for relay.

The platoon RTO will then liase with command or follow preestablished guidelines for the evacuation of casualties. The leader will then relay this information back to the medical team as they receive it.

.. danger::
  **MEDICAL PERSONNEL SHOULD NOT CALL AIRCRAFT OR ASSETS DIRECTLY - THERE ARE OTHER ELEMENTS RESPONSIBLE FOR THESE TRANSMISSIONS AND ASSISGNMENTS**

At this stage the platoon RTO will advise if the MEDEVAC will be land or air based and any steps required to comply as well as an ETA.

Detailed below are the procedures to follow for a land and air based MEDEVAC.

**Land Based MEDEVAC**

A Land Based MEDEVAC is conducted by a medical team on the ground with an ambulance.

The Medical team at the CCP should prepare the casualty for transport. This might include ensuring that bleeding has been well controlled and that a fresh IV is in place if necessary.

The Medical team should then prepare to move the casualty if he is unconcious or clearly communicate the steps with the casualty if they are ambulatory.

Once the ambulance arrives the medic will dismount the MEDEVAC vehicle and conduct a handoff identical to that performed when receiving a casualty at the CCP. He will then load the casualty into the vehicle or provide them with instructions to board the vehicle.

Once all casualties are loaded the MEDEVAC vehicle will return to base. During the journey the medic on duty ( the one that is not driving the vehicle ) will constantly monitor all casualties and administer any aid possible. As this is a vehicle it will also be possible to perform a blood transfusion.

Once at base the ambulance will pull into the Level 2 facility and the casualty will be handed over.

.. note::
  In some cases the MEDEVAC team will act as the Level 2 facility. In this case they should take the casualty inside the facility and use a Personal Aid Kit.

**Air Based MEDEVAC**

An air based MEDEVAC is conducted by a medical team embedded within a transport airframe. Air based MEDEVACs are more complicated than land based MEDEVACs as they must comply with the additional complications of aviation cooperation.

Similar to a land based MEDEVAC the CCP team should prepare the casualty for MEDEVAC and get them moved to an area close to the HLZ.

Once the aircraft lands the flight medics will disembark and perform a handoff for each casualty. The Flight Medics alone will load the casualties into the helicopter. **Flight Medics are specially trained on loading casualties without damaging the aircraft - CCP personnel should not approach the aircraft.**

Once all casualties are loaded the Flight Medics will load up and give an all clear signal to the Airframe Crew who will then take off and begin a return flight to base.

.. note::
  MEDEVAC flights get the highest Air Traffic Control priority second only to MAYDAY calls so you should not spend a long time in flight in most cases.

During the flight the medical crew in the back of the aircraft will do their best to stabilize the patient's by providing blood transfusions and chemcial injections.

In some cases the flight crew may also assist with providing CPR to the casualties in flight.

Upon landing the patients will be handed over to Level 2 care as per the land based MEDEVAC.

Level 2 Medical Care
~~~~~~~~~~~~~~~~~~

Level 2 Medical Care in the 1st RRF is a facility equipped with basic surgical equipment. In the context of the game this means that Personal Aid Kits can be used within the building or vehicle which allows a wounded individual to be restored to full health.

Level 2 care is normally rendered inside the MEDEVAC helicopter by the MEDEVAC medic or back at base depending on the command intent in the region.
