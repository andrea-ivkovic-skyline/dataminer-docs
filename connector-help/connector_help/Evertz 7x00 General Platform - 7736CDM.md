---
uid: Connector_help_Evertz_7x00_General_Platform_-_7736CDM
---

# Evertz 7x00 General Platform - 7736CDM

This driver is used to monitor an Evertz 7736CDM card. The 7736CDM card is a composite analog-to-serial digital video converter. For more information, see <http://www.evertz.com/products/7736CEM>.

The following card types are supported: 7736CDM-A4 and 7736CDM-AES.

## About

This driver is automatically generated by the parent driver [Evertz 7x00 General Platform](xref:Connector_help_Evertz_7x00_General_Platform).

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.x          | v3.03 Build 1 (Tested)      |

## Installation and configuration

### Creation

The element using this driver is automatically exported from the **Evertz 7x00 General Platform** driver. The configuration of the element must be done in this parent driver.

## Usage

### General

This page displays the **Card Type** and the **Slot Instance** of the card.

### Audio

This page displays general information about the audio stream, such as **Destination**, **Channels**, etc.

### Video

This page displays general information about the video stream, such as **Video Standard**, **Lock**, etc.

### Alarms

This page lists the status of all possible alarms. For each alarm, the **Send Trap** parameter allows you to enable/disable traps for that fault.

The fault conditions can be configured via the **Alarms Condition** page button.