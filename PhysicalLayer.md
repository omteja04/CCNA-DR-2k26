<!--
  Author: omteja04
  Created on: 10-07-2024 13:50:25
  Description: PhysicalLayer
-->

## Physical Layer

**End Device** &rarr; Device used by end user.

<!-- cSpell:disable -->

**devmgmt.msc** &rarr; command in windows to see the all the detals about the device (device manager).

**ncpa.cpl** &rarr; command to see the network connections in the windows device

> Ethernet Port &rarr; rj45 port (Registered Jack)

> Telephone Port &rarr; rj11 port

<!-- cSpell:enable -->

## Cables used in Networking

UTP &rarr; Unshielded Twisted Pair

STP &rarr; Shielded Twisted Pair

### UTP

- This is the most common type of networking cable.
- It consists of pairs of twisted copper wires, typically surrounded by an outer jacket.
- UTP cables are susceptible to electromagnetic interference (EMI) and radio frequency interference (RFI) but are cost-effective and suitable for most networking needs.

### STP

- STP cables have an extra layer of shielding (such as foil or braided shielding) around the twisted pairs of copper wires.
- This shielding helps to reduce electromagnetic interference and crosstalk between pairs.
- STP cables are more expensive than UTP cables but offer better protection against interference, making them suitable for environments with high interference levels or where data integrity is critical.

### Color of the wires in cables of Ethernet

Green 🟢 &rarr; Green, White Green

Orange 🟠 &rarr; Orange, White Orange

Blue 🔵 &rarr; Blue, White Blue

Brown 🟤 &rarr; Brown, White Brown

### Color Coding

**T568A**

**T568B**

![Color Coding](https://i2.wp.com/support.reolink.com/hc/article_attachments/360028763714/RJ45-pinout.jpg?strip=all)

`Pin No. 1 2 3 6 are the actual pins which are responsible for the transfer of data, remaining pins are for the support`

#### Straight Cables

T568A &larr;&rarr; T568A

T568B &larr;&rarr; T568B

#### Cross Cables

T568A &larr;&rarr; T568B

T568B &larr;&rarr; T568A

> Straight Cables are used when there are different type of devices at both ends of the cable.

> Cross Cables are used when there are same type of device at both ends of the cable.

**Layer 1 (Physical Layer) Devices:** Hubs & End Devices

### Hub - Layer 1 Device (Physical Layer)

- It is a Broadcasting Device
- Half Duplex Device (Both sending and receiving of data is not possible simultaneously)

### Repeater

-Recommended length for Ethernet is 100 mts.

- Repeaters are used when the length between source and destination is > 100 mts.
- Repeaters placed at every 100 mts distance, repeats the signals and sends further
- These are Layer 01 Devices
