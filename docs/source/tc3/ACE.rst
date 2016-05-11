The ACE 3 Medical System
==================================

Medics are expected to fully understand the ACE medical system including all possible symptoms and side effects as well as being drilled in quickly providing the correct care to patients.

In order to facilitate this goal you should carefully read through the following details of the ACE medical system. This is somewhat unique to our group based on the settings we use so you should read this with even greater care if you believe you already understand the medical system.

You should also be advised that not all avenues of treatment are available to all personnel and as such the system may be more complicated than the "hit them with a PAK" method used in other groups.

.. note::
  You should thoroughly review the information on this page.

  In order to help you operate at the highest level you can download the Apendices at the end of this training program that provide printable cheat cards for reference during training and combat.

The Basics
-----------

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
-------

A MEDSTAT is essentially an ACE report for patients. It consists of Blood Volume then Pulse then Responsive State.

For example:

  RED - GREEN - BLACK is a non responsive casualty with a normal pulse and a low blood pressure.

MEDSTATs allow for rapid communication about the status of a casualty.

Injury Type
------------

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

..note::
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
-------------

Each injury type can come in a variety of sizes which increases or decreases the bleed rate of the wound.

Cardiac Arrest
--------------

A cardiac arrest is when the heart stops pumping. In game this is an extremely bad situation and means that the individual has to be MEDEVACd to a Level 2 facility.

A Cardiac Arrest is triggered when a patient fufills any of the following criteria:

  * A heart rate below 20
  * A heart rate above 200
  * A Systolic blood pressure above 260
  * A Diastolic blood pressure below 40 with a heart rate above 190
  * A Systolic blood pressure is above 145 and the heart rate is above 150

Once a patient enters cardiac arrest they cannot be recovered in the field. CPR will extend the time until they fully die - allowing enough time for them to reach a medical facility capable of restarting the heart.

Setting up ACE to be efficient
-------------------------------

ACE 3 is a matrix of complicated 3D menus and contrived custom keys. As such we have introduce additional tooling to make this process faster for medical personnel so they are able to act more efficiently.

Changing the Medical Menu to a 2D interface:
  1. Go to the ACE OPTIONS menu in the top left hand corner of your in game options menu.
  2. Navigate to the "Medical Menu" option
  3. Enable the Medical Menu

After enabling the medical menu you should be able to ACE interact and find the "Medical Menu" under interactions - this is in contrast to the usual 3D "Medical" setting that would be there. This allows you to access the 2D medical menu and access time critical information faster.

..note ::
  We also recommend setting your ACE interact and self interact key to a mouse hotkey if you have them available so that you are able to access these options faster.
