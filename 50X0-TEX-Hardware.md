

                               50X0-TEX
                   OpiThin Embedded x86 AMD 64-bit
                             Hardware Guide


                                [image1]


50X0-TEX OpiThin Embedded x86
  Strong. Compact. Affordable
  High-performance embeddable PC
  Windows 10 IoT, Linux/Ubuntu Core, and Linux/OpenWRT


Copyright © Opiware Solutions. All Rights Reserved. | Version: 0.1  2020 Nov.


                                                        50X0-TEX Hardware Guide
-------------------------------------------------------------------------------

Trademarks
The Opiware logo is a registered trademark of Opiware Solutions. All other trademarks or registered marks in this manual belong to their respective manufacturers.

Disclaimer
Information in this document is subject to change without notice and does not represent a commitment on the part of Opiware.

Opiware provides this document as is, without warranty of any kind, either expressed or implied, including, but not limited to, its particular purpose. Opiware reserves the right to make improvements and/or changes to this manual, or to the products and/or the programs described in this manual, at any time.

Information provided in this manual is intended to be accurate and reliable. However, Opiware assumes no responsibility for its use, or for any infringements on the rights of third parties that may result from its use.

This product might include unintentional technical or typographical errors. Changes are periodically made to the information herein to correct such errors, and these changes are incorporated into new editions of the publication

Operation is subject to the following two conditions:
1. This device may not cause interference and
2. This device must accept any interference. Including interference that may cause undesired operation of the device.


                                                        50X0-TEX Hardware Guide
-------------------------------------------------------------------------------

Safety information

ATTENTION: Before Connecting the device to DC power input, make sure the DC power source voltage is stable.

ATTENTION: This product is intended to be mounted to a well-grounded mounting surface, such as a metal panel.

This Metal surface can be very hot when operating in high temperature. To avoid  injure, please do not touch the metal surface.


                                                        50X0-TEX Hardware Guide
-------------------------------------------------------------------------------

                         Document Amendment History
Revision    Date         Remark
V 0.1       2020 Nov.    Initial Doc


                                                        50X0-TEX Hardware Guide
-------------------------------------------------------------------------------

                             Table of Contents
1. Introduction ............................................................. 5
1.1 Features ............................................................... 10
1.2 Specifications (Hardware) .............................................. 15
1.3 Specifications (Linux/Ubuntu Core Software) ............................ 20
1.4 Ordering Information ................................................... 25


                                                        50X0-TEX Hardware Guide
-------------------------------------------------------------------------------

1. Introduction

50X0-TEX OpiThin Embedded x86
Powerful, compact, highly efficient quad core.
The Opiware 50X0 x86 series is a highly efficient and powerful embeddable PC platform for wide range of dedicated applications and virtual desktop environments. It is available with Windows 10 IoT, Linux/Ubuntu Core, and Linux/OpenWRT. With its extremely compact size and high performance, it’s a versatile embedded device.

1.1 Features
* Strong. Compact. Affordable.
* High-performance multimedia.
* Highly scalable, easy to operate and manage.
* Environmentally conscious computing.

1.2 Specifications (Hardware)

Model Name

Operating system
  Windows 10 IoT
  Linux/Ubuntu Core
  Linux/OpenWRT

CPU
5010-TE1
  AMD G-Series T48E Dual Core 1.4GHz
5020-TE2
  Quad-core AMD G-Series SoC 1.5 GHz

Memory
  32GB SSD Flash / 4GB, 2GB RAM DDR3
  16GB SSD Flash / 4GB, 2GB RAM DDR3
  Higher SSD storage also supported

Graphics
5010-TE1
  Radeon HD 6250 graphics (integrated with APU)
5020-TE2
  AMD Radeon HD 8330E graphics (integrated with APU)

Networking
  10/100/1000 Gigabit Ethernet
  Optional dual band 802.11 a/b/g/n wireless
  Optional SFP Module support for Fiber NIC network connectivity
  Optional Bluetooth connectivity

I/O peripheral support
5010-TE1
  1 x DisplayPort. (Optional DisplayPort to DVI-I adapter available)
  1 x One DVI-I port. DVI to VGA (DB-15) adapter included
  4 x USB 2.0 ports (two front, two rear)
5020-TE2
  1 x DisplayPort. (Optional DisplayPort to DVI-I adapter available)
  1 x One DVI-I port. DVI to VGA (DB-15) adapter included
  4 x USB 2.0 ports (two front, two rear)
  2 x SuperSpeed USB 3.0 ports on rear (backwards compatible with USB 2.0)

Resolution
  VESA monitor support with Display Data Control (DDC) for automatic setting
  of resolution and refresh rate
  DisplayPort: 2560 x 1600 at 32bpp / DVI-I: 1920 x 1200 at 32bpp
  Dual display: 1920 x 1200 at 32bpp / Supports dual digital high-resolution displays

Audio
  Composite audio jack: 1/8-inch mini, 16-bit stereo / Internal mono speaker

Dimensions
  Height: 6.7 inches (170 mm) / Width: 1.6 inches (40 mm) /Depth: 7.3 inches (185 mm)

Weight
  2.05 lbs. (0.93 kg)

Mountings
  Vertical feet, standard
  Optional VESA mounting bracket for mounting to flat surfaces, such as walls
  Please note: 50X0 series cannot mount directly to the backs of monitors
  Optional Ergotron mounting stand for mounting with monitors

Device security
5010-TE1
  Built-in Kensington security slot (cable sold separately)
5020-TE2
  Data: WE8S and Win10 IoT Trusted Platform Module (TPM) 1.2
  Device: Builtand -in Kensington security slot (cable sold separately)

Power
  Worldwide auto-sensing 100-240 VAC, 50/60 Hz 65W, 19V DC
  Energy Star V.5.2 Phase V external and EuP compliant power adapter

Temperature range
  Operating, vertical position: 32° to 104° F (10° to 40° C)
  Storage: 14° to 140° F (-10° to 60° C)

Humidity
  20% to 80% condensing. 10% to 95% non-condensing

Safety certifications
5010-TE1
  Ergonomics: German EKI-ITB 2000, ISO 9241-3/-8
  Safety: cULus 60950, TÜV-GS, EN 60950
  RF Interference: FCC Class B, CE, VCCI, C-Tick
  Environmental: WEEE, RoHS Compliant
  Energy Star®, EPEAT Silver listed
5020-TE2
  Ergonomics: German EKI-ITB 2000, ISO 9241-3/-8
  Safety: cULus 60950, TÜV-GS, EN 60950
  RF Interference: FCC Class B, CE, VCCI, C-Tick
  Environmental: WEEE, RoHS Compliant

Warranty
  One-year hardware warranty

1.3 Specifications (Linux/Ubuntu Core Software)

Operation Systems
• Linux/Ubuntu Core
• Supports bootup from SSD
• Support Backup/Restore USB
• Boot Loader : GRUB/LILO
• File System : ETX4

Software Development
• Toolchain: gcc + glibc/uclibc/musl
• Supports remote C/C++ compilation

Package Management
• Package repository: Opiware self-
maintained repository
• Command: Standard apt, apt-get

Popular Packages
• Web server: Apache/Lighttpd
• Database: MySQL/SQLite3
• Scripting: PHP/Node.JS/Node-RED
• Text editor: vim/nano/sed
• Administration: WebRDS

Software Documentation and Utility
Please refer to “50X0-TEX” repository for software documentation and utility at following: http://www.github.com/Opiware/

1.4 Ordering Information

• 5010-TE1
OpiThin Embedded x86 AMD 64-bit, Dual Core
with 32GB, 16GB SSD Flash / 4GB, 2GB RAM DDR3

• 5020-TE2
OpiThin Embedded x86 AMD 64-bit, Quad Core
with 32GB, 16GB SSD Flash / 4GB, 2GB RAM DDR3
