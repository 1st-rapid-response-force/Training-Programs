Basics of Radio Transmission
============================

Messages are constructed of a Wrapper and a Message.

The Wrapper
------------

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
-----------

The intended transmission contents is then placed inside the wrapper to ensure delivery of the information. Message types and formats will be covered in the next chapters.
