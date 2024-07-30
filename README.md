# Q-SYS Plugin: Shure MXA310 (Unofficial)

## Overview
This unofficial Q-SYS plugin is designed to integrate and control the Shure MXA310 device. It includes features for almost all send commands and return commands, and managing device settings.
As you know, use this plugin at your own risk.

## Version History

### v1.0.2
- **Bug Fixes**:
  - Fixed Inc/Dec behavior of angles, especially from 345 to 00 and 00 to 345.
  - Fixed privacy behavior during conversion from mute to color.

### v1.0.1.1.3
- **Bug Fixes**:
  - Added touch feedback for the MXA310 unit.
  - Changed TX commands and mute LED feedback to the privacy button during mute to color mode conversion.
  - Added TX input pin (previously, TX was read-only and an output pin, now it directly sends the string written to TX).

### v1.0.1
- **New Features**:
  - Added Mute Control Function.
  - Added Convert Mute to Color function.
    - This feature is the Mute Control Function in Logic Out mode, and it only changes the appearance of the color from the touch of the MXA310 unit. The device itself will not be muted.

## Controls
The following controls are available in the plugin:

### Angles
- **Angle 1 (Coverage Angle 1)**: String
- **Angle 2 (Coverage Angle 2)**: String
- **Angle 3 (Coverage Angle 3)**: String
- **Angle 4 (Coverage Angle 4)**: String
- **Angle Dec 1 (Coverage Angle Gain Dec 1)**: Boolean
- **Angle Dec 2 (Coverage Angle Gain Dec 2)**: Boolean
- **Angle Dec 3 (Coverage Angle Gain Dec 3)**: Boolean
- **Angle Dec 4 (Coverage Angle Gain Dec 4)**: Boolean
- **Angle Inc 1 (Coverage Angle Gain Inc 1)**: Boolean
- **Angle Inc 2 (Coverage Angle Gain Inc 2)**: Boolean
- **Angle Inc 3 (Coverage Angle Gain Inc 3)**: Boolean
- **Angle Inc 4 (Coverage Angle Gain Inc 4)**: Boolean

### Audio Settings
- **Audio Gateway (Settings Audio Gateway)**: String
- **Audio IP Address (Settings Audio IP Address)**: String
- **Audio Subnet (Settings Audio Subnet Mask)**: String

### Automix
- **AutoMXR Dec 1 (Automix AutoMixer Gain Dec 1)**: Boolean
- **AutoMXR Dec 2 (Automix AutoMixer Gain Dec 2)**: Boolean
- **AutoMXR Dec 3 (Automix AutoMixer Gain Dec 3)**: Boolean
- **AutoMXR Dec 4 (Automix AutoMixer Gain Dec 4)**: Boolean
- **AutoMXR Gain 1 (Automix AutoMixer Gain 1)**: Float
- **AutoMXR Gain 2 (Automix AutoMixer Gain 2)**: Float
- **AutoMXR Gain 3 (Automix AutoMixer Gain 3)**: Float
- **AutoMXR Gain 4 (Automix AutoMixer Gain 4)**: Float
- **AutoMXR Gain Text 1 (Automix AutoMixer Gain Text 1)**: Float
- **AutoMXR Gain Text 2 (Automix AutoMixer Gain Text 2)**: Float
- **AutoMXR Gain Text 3 (Automix AutoMixer Gain Text 3)**: Float
- **AutoMXR Gain Text 4 (Automix AutoMixer Gain Text 4)**: Float
- **AutoMXR Inc 1 (Automix AutoMixer Gain Inc 1)**: Boolean
- **AutoMXR Inc 2 (Automix AutoMixer Gain Inc 2)**: Boolean
- **AutoMXR Inc 3 (Automix AutoMixer Gain Inc 3)**: Boolean
- **AutoMXR Inc 4 (Automix AutoMixer Gain Inc 4)**: Boolean
- **AutoMXR Label 1 (Channels Dante Out Name 1)**: String
- **AutoMXR Label 2 (Channels Dante Out Name 2)**: String
- **AutoMXR Label 3 (Channels Dante Out Name 3)**: String
- **AutoMXR Label 4 (Channels Dante Out Name 4)**: String
- **AutoMXR Label 5 (Channels Dante Out Name 5)**: String
- **AutoMXR LED 1 (Gate Out Status 1)**: Boolean
- **AutoMXR LED 2 (Gate Out Status 2)**: Boolean
- **AutoMXR LED 3 (Gate Out Status 3)**: Boolean
- **AutoMXR LED 4 (Gate Out Status 4)**: Boolean
- **AutoMXR Meter 1 (Automix AutoMixer Meter 1)**: Float
- **AutoMXR Meter 2 (Automix AutoMixer Meter 2)**: Float
- **AutoMXR Meter 3 (Automix AutoMixer Meter 3)**: Float
- **AutoMXR Meter 4 (Automix AutoMixer Meter 4)**: Float
- **AutoMXR Meter Rate (Automix AutoMixer Meter Rate)**: String
- **AutoMXR Solo 1 (Automix SOLO 1)**: Boolean
- **AutoMXR Solo 2 (Automix SOLO 2)**: Boolean
- **AutoMXR Solo 3 (Automix SOLO 3)**: Boolean
- **AutoMXR Solo 4 (Automix SOLO 4)**: Boolean

### Device Settings
- **Convert Mute to Color (Convert Mute to Color)**: Boolean
- **Device ID (Device Name)**: String
- **Device id (Settings Device Name)**: String
- **Device Mute (Device Mute)**: Boolean
- **Device Name (Settings Dante Device Name)**: String
- **Disable (Disable)**: Boolean
- **Discover (Settings Discover)**: Boolean
- **Firmware Ver (Settings Firmware Ver)**: String
- **Flash (Identify)**: Boolean
- **IP (Settings IP Address)**: String
- **IP List (Settings IP List)**: String
- **MAC Address (Settings MAC Address)**: String
- **Model (Settings Model)**: String
- **Reboot (Settings Reboot Device)**: Trigger
- **Serial Number (Settings Serial Number)**: String
- **Status (Settings Status)**: Status

### Channels
- **Dec 1 (Channels Gain Dec 1)**: Boolean
- **Dec 2 (Channels Gain Dec 2)**: Boolean
- **Dec 3 (Channels Gain Dec 3)**: Boolean
- **Dec 4 (Channels Gain Dec 4)**: Boolean
- **Dec 5 (Channels Gain Dec 5)**: Boolean
- **Gain 1 (Channels Gain 1)**: Float
- **Gain 2 (Channels Gain 2)**: Float
- **Gain 3 (Channels Gain 3)**: Float
- **Gain 4 (Channels Gain 4)**: Float
- **Gain 5 (Channels Gain 5)**: Float
- **Gain Text 1 (Channels Gain Text 1)**: Float
- **Gain Text 2 (Channels Gain Text 2)**: Float
- **Gain Text 3 (Channels Gain Text 3)**: Float
- **Gain Text 4 (Channels Gain Text 4)**: Float
- **Gain Text 5 (Channels Gain Text 5)**: Float
- **Inc 1 (Channels Gain Inc 1)**: Boolean
- **Inc 2 (Channels Gain Inc 2)**: Boolean
- **Inc 3 (Channels Gain Inc 3)**: Boolean
- **Inc 4 (Channels Gain Inc 4)**: Boolean
- **Inc 5 (Channels Gain Inc 5)**: Boolean
- **Label 1 (Input Channel Name 1)**: String
- **Label 2 (Input Channel Name 2)**: String
- **Label 3 (Input Channel Name 3)**: String
- **Label 4 (Input Channel Name 4)**: String
- **Label 5 (Input Channel Name 5)**: String
- **LED Brightness (Lights LED Brightness)**: Integer
- **LED Mute (Lights LED Mute Behavior)**: String
- **LED Mute Color (Lights LED Mute Color)**: String
- **LED Preview (Lights LED Preview)**: Boolean
- **LED Unmute (Lights LED Unmute Behavior)**: String
- **LED Unmute Color (Lights LED Unmute Color)**: String
- **Meter 1 (Channels Meter 1)**: Float
- **Meter 2 (Channels Meter 2)**: Float
- **Meter 3 (Channels Meter 3)**: Float
- **Meter 4 (Channels Meter 4)**: Float
- **Meter 5 (Channels Meter 5)**: Float
- **Meter Rate (Channels Meter Rate)**: String
- **Mute 1 (Channels Mute 1)**: Boolean
- **Mute 2 (Channels Mute 2)**: Boolean
- **Mute 3 (Channels Mute 3)**: Boolean
- **Mute 4 (Channels Mute 4)**: Boolean
- **Mute 5 (Channels Mute 5)**: Boolean
- **PEQ 1 (Channels PEQ 1)**: Boolean
- **PEQ 2 (Channels PEQ 2)**: Boolean
- **PEQ 3 (Channels PEQ 3)**: Boolean
- **PEQ 4 (Channels PEQ 4)**: Boolean
- **PEQ 5 (Channels PEQ 5)**: Boolean
- **Polar Block 1 (Automix AutoMixer Polar Block 1)**: Trigger
- **Polar Block 2 (Automix AutoMixer Polar Block 2)**: Trigger
- **Polar Block 3 (Automix AutoMixer Polar Block 3)**: Trigger
- **Polar Block 4 (Automix AutoMixer Polar Block 4)**: Trigger
- **Polar Pattern 1 (Coverage Polar Pattern 1)**: String
- **Polar Pattern 2 (Coverage Polar Pattern 2)**: String
- **Polar Pattern 3 (Coverage Polar Pattern 3)**: String
- **Polar Pattern 4 (Coverage Polar Pattern 4)**: String
- **Preset 1 (Presets Preset Recall 1)**: Boolean
- **Preset 2 (Presets Preset Recall 2)**: Boolean
- **Preset 3 (Presets Preset Recall 3)**: Boolean
- **Preset 4 (Presets Preset Recall 4)**: Boolean
- **Preset 5 (Presets Preset Recall 5)**: Boolean
- **Preset 6 (Presets Preset Recall 6)**: Boolean
- **Preset 7 (Presets Preset Recall 7)**: Boolean
- **Preset 8 (Presets Preset Recall 8)**: Boolean
- **Preset 9 (Presets Preset Recall 9)**: Boolean
- **Preset 10 (Presets Preset Recall 10)**: Boolean
- **Preset Label 1 (Presets Preset Name 1)**: String
- **Preset Label 2 (Presets Preset Name 2)**: String
- **Preset Label 3 (Presets Preset Name 3)**: String
- **Preset Label 4 (Presets Preset Name 4)**: String
- **Preset Label 5 (Presets Preset Name 5)**: String
- **Preset Label 6 (Presets Preset Name 6)**: String
- **Preset Label 7 (Presets Preset Name 7)**: String
- **Preset Label 8 (Presets Preset Name 8)**: String
- **Preset Label 9 (Presets Preset Name 9)**: String
- **Preset Label 10 (Presets Preset Name 10)**: String
- **Privacy (Lights Privacy Mode Toggle)**: Boolean
- **Privacy Flash (Lights Privacy Mode Flash Toggle)**: Boolean
- **Privacy Flash Tri 1 (Lights Privacy Mode Flash On)**: Trigger
- **Privacy Flash Tri 2 (Lights Privacy Mode Flash Off)**: Trigger
- **Privacy Tri 1 (Lights Privacy Mode On)**: Trigger
- **Privacy Tri 2 (Lights Privacy Mode Off)**: Trigger
- **Step (Channels Step)**: String
- **Tx (Settings Command String Tx)**: String
- **Rx (Settings Command String Rx)**: String

## Test Equipment
- **Shure MXA310**: ver 6.0.23 and 4.7.8.0
- **QDS**: ver 9.10.1
  - Note: Discover may not work with QDS v9.10.1 or lower. Additionally, it cannot search link-local-ip (DHCP Address) without a DHCP server.

![Alt text](/Capture/Shure-MXA310-Channels.png)
![Alt text](/Capture/Shure-MXA310-Automix.png)
![Alt text](/Capture/Shure-MXA310-Coverage.png)
![Alt text](/Capture/Shure-MXA310-Lights.png)
![Alt text](/Capture/Shure-MXA310-Presets.png)
![Alt text](/Capture/Shure-MXA310-Settings.png)
![Alt text](/Capture/Shure-MXA310-Plugin.gif)