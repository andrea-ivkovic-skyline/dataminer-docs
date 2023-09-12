---
uid: Connector_help_CEFD_MCDD-100_SNMP
---

# CEFD MCDD-100 SNMP

The Comtech EF Data's MCDD-100 MetaCarrier Detection Device is a carrier identification product that uses spread spectrum technology to decode an embedded unique carrier identification sequence for a transmission carrier.

## About

The CEFD MCDD-100 SNMP driver is used to monitor and control a CEFD MCDD-100 device. The information is displayed in different pages regarding a certain category and there is the possibility to modify some settings. This driver uses SNMP communication to retrieve and configure the device's data.

### Ranges of the driver

| **Driver Range** | **Description** | **DCF Integration** | **Cassandra Compliant** |
|------------------|-----------------|---------------------|-------------------------|
| 1.0.0.x          | Initial Version | No                  | Yes                     |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.x          | Unknown                     |

## Installation and configuration

### Creation

#### SNMP Main Connection

This driver uses a Simple Network Management Protocol (SNMP) connection and requires the following input during element creation:

SNMP CONNECTION:

- **IP address/host**: 10.15.1.11.

SNMP Settings:

- **IP port**: 161
- **Get community string**: public
- **Set community string**: private

## Usage

### General

The **General** page displays the **System** **Information** and **Demodulator Status** information.

### Admin - Firmware

The **Admin - Firmware** page displays the **Firmware** **Table** containing information about each slot. **Bootrom** **version** is displayed and there is the possibility to set the **BOOT From** a specific slot. **Reboot** button is also accessible for **System** **Reboot**.

### Config

This page contains information about the **Demodulator.** The **Rx** **Frequency**, **Symbol Rate** and **Sweep** **Width** are displayed and can be also set within a prefixed range. Rx Symbol Rate can be set also to zero through a checkbox.

### Configuration - Interface

This page contains information about the **Management** **Interface**, including **MAC** **address**, **IP** **address** and **Gateway**. The IP addresses can be set and a pop up window will show up in case the inserted values are not valid.

### Status - Monitor

This page contains information about the **Unit Temperature**, **Demodulator Status** and **Carrier ID**.

### Status - Alarms

This page contains **Alarm/Faults** and **Events** tables, where detailed alarm information and events generated by the device can be monitored. The fault type on "temperature" faults can be set (to info or masked).

### Utility

This page contains the **Serial** **Number** of the unit along with editable information regarding the system, including **Contact** and **Location**, **Date** and **Time**. A **Monitor** of **BER** and **PER** is also displayed, containing information about **Total** **Bits** and **Packets** **errors**.

### Webinterface

To access the embedded device's web interface, the client machine has to be able to access the device.