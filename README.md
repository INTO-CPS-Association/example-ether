# Ether

## Overview
This example explores ways to model network communications between controllers. This involves passing messages —VDM values encoded as strings— from a model called Sender to a model called Receiver. This is either done directly, or via a third model called the Ether.

While this example demonstrates that direct connection is possible, for multi-models with large numbers of connected controllers (for example swarms or cooperative vehicles) it becomes unwieldy. This example includes an Ether model, which represents an abstract communication mechanism, that handles message passing between the Sender and Receiver. This Ether can be used in other models.

The introduction of a model of communications also permits a range of realistic and faulty behaviours to be introduced, such as message delay, duplication, and loss. The ether pattern which this example implements is described in greater detail in [Deliverable D3.2a](http://projects.au.dk/fileadmin/D3.2a_Method_Guidelines_2.pdf), which includes a discussion of realistic and faulty behaviour.

## Supported Features
This study supports the following INTO-CPS technologies:

* Multi-DE model
* VDM-RT (for FMU)
* Co-simulation Engine (COE)
* Test Automation
* Model Checking

## Additional Information
Additional Information about this case study can be found in the [Examples Compendium](http://projects.au.dk/fileadmin/D3.5_Examples_Compendium_2.pdf#page=54)

Alternatively, contact the case study owner, [Ken Pierce](mailto:kenneth.pierce@newcastle.ac.uk).
