# Single ended to differential signal converter


Differential signaling is a method for electrically transmitting information using two complementary signals. The technique sends the same electrical signal as a differential pair of signals, each in its own conductor. The receiving circuit responds to the electrical difference between the two signals, rather than the difference between a single wire and ground.

Provided that the source and receiver impedances in a circuit are equal (it is balanced), external electromagnetic interference tends to affect both conductors identically. Since the receiving circuit only detects the difference between the wires, the technique resists electromagnetic noise compared to one conductor with an un-balanced reference.

Most of the SciCompiler supported board require fully differential signaling to correct operate.

This application notes include information and circuit to convert single ended signal from radiation detector to signal that can be easy digitalized with the DT5500 or R5560.

In docs folder you can find an Application Note on conversion circuit
In reference design folder you can find an Altium Design project as a reference design for Single Ended to Differential conversion for R5560 device

For more information on DT5550, 80MSps, 32 ch, 14 bit digitizer visit
[https://www.caen.it/products/dt5550/](https://www.caen.it/products/dt5550/)

For more information on R5560, 125MSps, 128 ch, 14 bit digitizer visit
[https://www.caen.it/products/r5560/](https://www.caen.it/products/r5560/)