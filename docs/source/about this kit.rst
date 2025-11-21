.. __about_this_kit:

About_this_kit
====================

Preface
-------------------------------

We first need to understand what an POE HAT is. The illustration below shows an POE HAT.

.. figure:: ./Tutorial/img/LB004_A4.jpg
   :align: center
   :width: 70%
   
.. figure:: ./Tutorial/img/LB004_A8_V2.jpg
   :align: center
   :width: 80%

Our PoE HAT is a Power over Ethernet expansion board compatible with Raspberry Pi 3B+/4B/5. Compliant with the IEEE 802.3af/at network standard, it draws power directly from a PoE switch using only a single network cable. It features two independent DC output interfaces: 12V/2A and 5V/4.5A, providing ample power to the Raspberry Pi and peripherals.

Componen List
-------------------------------

1. POE HAT x1
2. 2×2P PoE adapter header x2
3. M2.5×18 brass standoffs x4
4. M2.5×8 black countersunk screws x8
5. Pi5 heatsink kit x1
6. Cross-head screwdriver x1

   .. image:: /Tutorial/img/LB004_A1_V3.jpg

Note
-------------------------------

.. Note::
   1. **Do NOT power the Pi via USB-C while the PoE HAT is connected** — board damage will occur.  
   
   2. **PoE HAT fits Pi 3B+, 4B, 5**; official Pi 5 cooler works **only** on Pi 5.  
   
   3. **Keep total continuous power below 25 W; if peripherals draw high power, use a switch that supports 802.3at and can provide at least 30 W with a 20 % margin.**


Product Features
================

Strong Compatibility
--------------------
Supports Raspberry Pi 3B+/4B/5; switching between models is achieved instantly through a single **2.54 mm 2×P connector socket**.

Rich Interfaces
---------------
- Standard **40-pin GPIO header** is retained for easy stacking of other Raspberry Pi expansion boards.  
- Additional **12 V / 2 A** and **5 V / 4.5 A** external power connectors are provided to supply power to external devices directly.

Easy to Use
-----------
Snap on the **PoE HAT** and plug in the **2×2P connector**, then the board works immediately—no extra setup required.

Mechanical Friendly
-------------------
- Reserved mounting space for active cooling fans.  
- Every cable terminal has a top exit slot for effortless wire routing.