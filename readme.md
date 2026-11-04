# Virtual Pinball Table

**A custom 3-screen virtual pinball cabinet project**

---

## Contents

1. [Introduction](#1-introduction)
2. [Cabinet](#2-cabinet)
3. [Cabinet parts](#3-cabinet-parts)
4. [Construction](#4-construction)
5. [PC](#5-pc)
6. [Cabinet electronics](#6-cabinet-electronics)
7. [Audio subsystem](#7-audio-subsystem)
8. [Video subsystem](#8-video-subsystem)
9. [Addressable LEDs](#9-addressable-leds)
10. [Miscellaneous](#10-miscellaneous)
11. [Wiring](#11-wiring)
12. [Software](#12-software)

# 1. Introduction
This virtual pinball table started as a project in Dec 2025. Parts were first ordered then for the cabinet.

# 2. Cabinet

The cabinet used for the build was a [Tukkari Widebody Virtual Pinball Cabinet](https://www.tukkari.com/p/widebody-virtual-pinball-cabinet-vpin-flat-pack-kit) flat pack.

![cabinet](images/Tukkari-widebody-cabinet.png)

# 3. Cabinet Parts

| Date ordered | Part |
|---|---|
| Jan 3, 2026 | [Tukkari Widebody Virtual Pinball Cabinet with optional black-powder coated siderails and lockdown bar](https://www.tukkari.com/p/widebody-virtual-pinball-cabinet-vpin-flat-pack-kit) |
| Feb 12, 2026 | [30.5" Premium Mirror Polished Chrome Ribbed Legs](https://www.pinballlife.com/jjpstern-premium-chrome-legs-set-of-4.html) |
|  Feb 12, 2026 | [Williams/Bally Leg Bracket](https://www.pinballlife.com/williamsbally-leg-bracket.html) |
|  Feb 12, 2026 | [Heavy Duty Leg Leveler With Nut](https://www.pinballlife.com/4INCH_LEG_LEVELER_HEAVY_DUTY?) |
|  Feb 12, 2026 | [Extended Silver Leg Bolt - 2-3/4"](https://www.pinballlife.com/williamsbally-extended-chrome-leg-bolt-2-34.html) |
|  Feb 12, 2026 | ['Snap-On Happy Sliders™ For Carpeting - Set of 4](https://www.pinballlife.com/snap-in-leg-leveler-slider.html) |
|  Feb 12, 2026 | [Metal Cabinet Protectors (set of 4)](https://www.pinballlife.com/metal-cabinet-protectors-set-of-4.html) |
|  Feb 21, 2026 | [Inlet Module Plug 3D Printer Arcade Power Switch](https://www.amazon.com/dp/B09DRLYD2Z?ref=ppx_yo2ov_dt_b_fed_asin_title) |
|  Feb 24, 2026 | [Outwater Industries 25 Foot Black 3/4 Inch Center Barb Tee Moulding](https://www.amazon.com/dp/B07M8DBTST?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) |
|  Feb 28, 2026 | [IRWIN Marples Forstner Bit, Wood Drilling, 1-1/8-Inch](https://www.amazon.com/dp/B01JIKAIY0?ref=ppx_yo2ov_dt_b_fed_asin_title) |
|  Feb 28, 2026 | [Iot Relay - Enclosed High-power Power Relay](https://www.amazon.com/dp/B00WV7GMA2?ref=ppx_yo2ov_dt_b_fed_asin_title) |

# 4. Construction

Notes:
The Tukkari cabinet assumes pinball buttons (1" (25.4 mm) diameter) while the CSD buttons are arcade buttons ( 1-1/8" (30 mm) diameter). A Forstner bit was purchased to drill out all of the button holes so the CSD buttons would fit.

A T-moulding with a 3/32" barb had to be used with the Tukkari cabinet backbox. The 1/8" barb one didn't fit.

An IoT relay power strip was purchased so that when the PC is powered on, its USB port signals this power strip to turn on other devices (or keep them powered at all times). It currently is not in use as it wasn't determined what to make switched/non-switched until it was too late to be able to reach in the back of the cabinet (the playfield monitor is in the way). Perhaps it will be used later.

| | | |
| :---: | :---: | :---: |
| ![](images/Flat-pack-delivery-in-garage.jpg) | ![](images/Flat-pack-delivery-in-garage2.jpg) | ![](images/Unboxing-in-media-room.jpg) |
| *Flat pack* | *Flat pack2* | *Unboxing* |

| | | |
| :---: | :---: | :---: |
| ![](images/Base-box-glued-together.jpg) | ![](images/Backbox-assembled.jpg) | ![](images/Legs-and-backbox-attached.jpg)
| *Base box glued together* | *Backbox assembled* | *Legs and backbox attached*

| | | |
| :---: | :---: | :---: |
| ![](images/Fans-and-cable-raceways-installed.jpg) | ![](images/Fans-and-cable-raceways-installed2.jpg) | ![](images/Speakers-installed.jpg)
| *Fans and cable raceways installed* | *Fans and cable raceways installed2* | *Speakers installed*

| | | |
| :---: | :---: | :---: |
| ![](images/Speaker-installed2.jpg) | ![](images/Coin-door-installed.jpg) | ![](images/Power-strips-pc-mount-installed.jpg)
| *Speakers installed2* | *Coin door, power strips, backbox monitor installed* | *Power strips, PC mount installed*

| | | |
| :---: | :---: | :---: |
| ![](images/Power-strips-pc-mount-installed2.jpg) | ![](images/Power-switch-installed.jpg) | ![](images/Backbox-cover.jpg)
| *Power strips, PC mount installed2* | *Power switch installed* | *Backbox cover*

| | | |
| :---: | :---: | :---: |
| ![](images/DMD-monitor-installed.jpg) | ![](images/DMD-monitor-installed2.jpg) | ![](images/Coin-door-internals.jpg)
| *DMD monitor installed* | *DMD monitor installed2* | *Coin door internals*

| | | |
| :---: | :---: | :---: |
| ![](images/Playfield-holder-and-cabinet-braces-installed.jpg) | ![](images/Flipper-buttons-and-plunger-installed.jpg) | ![](images/Flipper-buttons-and-plunger-installed2.jpg)
| *Playfield holder, cabinet braces, flipper buttons and plunger installed* | *Flipper buttons and plunger installed* | *Flipper buttons and plunger installed2*

| | | |
| :---: | :---: | :---: |
| ![](images/Flipper-buttons-and-plunger-installed3.jpg) | ![](images/Subwoofer-bass-shaker-installed.jpg) | ![](images/Subwoofer-bass-shaker-installed3.jpg)
| *Flipper buttons and plunger installed3* | *Subwoofer and bass shaker installed* | *Subwoofer and bass shaker installed3*

| | | |
| :---: | :---: | :---: |
| ![](images/Playfield-holder-up.jpg) | ![](images/Playfield-holder-up2.jpg) | ![](images/Subwoofer-bass-shaker-installed2.jpg)
| *Playfield holder up* | *Playfield holder up2* | *Subwoofer and bass shaker installed2* 

| | | |
| :---: | :---: | :---: |
| ![](images/Internal-electronics-installed.jpg) | ![](images/Internal-electronics-installed2.jpg) | ![](images/Internal-electronics-installed3.jpg)
| *Internal electronics installed* | *Internal electronics installed2* | *Internal electronics installed3* 

| | | |
| :---: | :---: | :---: |
| ![](images/Internal-electronics-installed4.jpg) | ![](images/Internal-electronics-installed5.jpg) | ![](images/Internal-electronics-installed6.jpg)
| *Internal electronics installed4* | *Internal electronics installed5* | *Internal electronics installed6* 

| | | |
| :---: | :---: | :---: |
| ![](images/Internal-electronics-installed7.jpg) | ![](images/Internal-electronics-installed8.jpg) | ![](images/Internal-electronics-installed9.jpg)
| *Internal electronics installed7* | *Internal electronics installed8* | *Internal electronics installed9* 

| | | |
| :---: | :---: | :---: |
| ![](images/Internal-electronics-installed10.jpg) | ![](images/Internal-electronics-installed11.jpg) | ![](images/Internal-electronics-installed12.jpg)
| *Internal electronics installed10* | *Internal electronics installed11* | *Internal electronics installed12* 

| | | |
| :---: | :---: | :---: |
| ![](images/Internal-electronics-installed13.jpg) | ![](images/Internal-electronics-installed14.jpg) | ![](images/Internal-electronics-installed15.jpg)
| *Internal electronics installed13* | *Internal electronics installed14* | *Internal electronics installed15* 

| | | |
| :---: | :---: | :---: |
| ![](images/Internal-electronics-installed16.jpg) | ![](images/Internal-electronics-installed17.jpg) | ![](images/Internal-electronics-installed18.jpg)
| *Internal electronics installed16* | *Internal electronics installed17* | *Internal electronics installed18* 

| | | |
| :---: | :---: | :---: |
| ![](images/Backglass-monitor-mount.jpg) | ![](images/Backglass-dmd-connection.jpg) | ![](images/Rear-fans.jpg)
| *Backglass monitor mount* | *Backglass dmd connection* | *Rear fans* 

| | | |
| :---: | :---: | :---: |
| ![](images/Addressable-RGB-LEDs-controller.jpg) 
| *Addressable RGB LEDs controller on back of top of playfield angled board* 

# 5. PC

The PC ([MSI® Z370-A PRO](https://www.msi.com/Motherboard/z370-a-pro/Specification)) is an old, repurposed computer with a new high end graphics card and a higher-powered power supply added. The motherboard was removed from its PC case and put into an open chassis since the fans are installed into the pinball cabinet itself.
- Operating System: Windows 11 Home 64-bit
- CPU: Intel Core i7 8700 @ 3.20GHz, Coffee Lake 14nm Technology
- RAM: 16GB Dual-Channel DDR4 @ 1333MHz (19-19-19-43)
- Motherboard: Micro-Star International Co., Ltd. Z370-A PRO (MS-7B48) (U3E1)
- Graphics: Intel UHD Graphics 630 (MSI)
- Storage: 232GB NVMe Samsung SSD 970
- Audio: Realtek 7.1 High Definition Audio
- [Manual](diagrams/PC.pdf)

| Date ordered | Part |
|---|---|
| Dec 10, 2025 | [GIGABYTE GeForce RTX 5070 Gaming OC 12G Graphics Card](https://www.amazon.com/dp/B0DTR3JK3Y?th=1) |
| Dec 10, 2025 | [CORSAIR RM850x ATX 3.1 PCIe 5.1 750W Power Supply](https://www.amazon.com/dp/B0DJ1JL3MK) |
| Feb 21, 2026 | [AL01 Open Frame Computer case ](https://www.amazon.com/dp/B0C59W6JKD) |
| Feb 21, 2026 | [USB 3.0 PCIE Card 5-Port] (https://www.amazon.com/dp/B09MFPGMH5?ref=ppx_yo2ov_dt_b_fed_asin_title) |

# 6. Cabinet electronics

#### [Cleveland Software Designs Virtual Pinball Builders Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-builders-kit)
As the main controller, the Cleveland Software Designs PinOne is used along with its accessories. The virtual pinball builders kit includes this controller along with its accessories. It includes the following: 
- [PinOne Controller](https://www.clevelandsoftwaredesign.com/pinball-parts/p/pinone-main-virtual-pinball-connection-board)
- [4x True Leaf Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-true-leaf-button) 
- [RGB LED Button](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button)
- [2x Red LED Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee)
- [2x Blue LED Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee)
- [2x Green LED Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee)
- [1x White LED Button](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee)
- [10x Solenoids](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-quality-solenoid)
- [2x 2 Position Solenoid Life Extenders](https://www.clevelandsoftwaredesign.com/pinball-parts/p/style-01-j6jmp)
- [2x 2 Position Solenoid Life Extenders](https://www.clevelandsoftwaredesign.com/pinball-parts/p/style-01-j6jmpv)
- [Button Board and 2x Flipper Button Boards](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-button-hookup-kit)
- [Williams Style Plunger](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-plunger-attachment)
- [Service Board](https://www.clevelandsoftwaredesign.com/pinball-parts/p/expansion-breakout-board-zx5y6) 
- [Shaker motor](https://www.clevelandsoftwaredesign.com/pinball-parts/p/ultimate-pinball-shaker-motor)

| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Virtual Pinball Builders Kit (medium/large) from Cleveland Software Designs](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-builders-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

# 7. Audio subsystem

 ### [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) 
 For the audio subsystem, the Cleveland Software Designs SSF Kit is used. It includes the following: 
- [Amplifier](https://www.clevelandsoftwaredesign.com/pinball-parts/p/ssf-extra-amplifier)
- [Bass shaker](https://www.clevelandsoftwaredesign.com/pinball-parts/p/bass-shaker-speaker)
- [4x Exciter speakers](https://www.clevelandsoftwaredesign.com/pinball-parts/p/replacement-exciter-speaker)

### Amplifier
The CSD amplifier is set to 7.1 mode and is connected to the PC's 7.1 audio output jacks using 3 3.5mm multi-channel audio wires. 

| PC audio output | CSD amplifier input |
|---|---|
| Green (Front L/R) | Speaker L/R In |
| Black (Rear surround) | Back L/R In |
| Gray/White (Side surround) | Front L/R In |

The PC Orange (Subwoofer and Center ) output is not used. The CSD amplifier creates its own subwoofer output from the other audio inputs.

| Date ordered | Part |
|---|---|
| Mar 24, 2026 | [AUX Cord for Car, 6 Pack 3.5mm Auxiliary Audio Cable](https://www.amazon.com/dp/B07N3YKBDY?ref=ppx_yo2ov_dt_b_fed_asin_title) |

The amplifier's physical volume is turned up to the max and the table volumes are managed through the windows and the [PinVol](http://mjrnet.org/pinscape/PinVol.html) app. The CSD surround sound card is not used.
| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) |

### Bass Shaker
The CSD Bass Shaker is connected to the amplifier on its Shaker connector. It is mounted to the floor of the cabinet so that it can shake the whole cabinet.
| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) |

### 4x Exciter Speakers
Four CSD exciter speakers are connected to the amplifier on its Front Left/Front Right and Back Left/Back Right connectors. They are mounted on the side walls of the cabinet with the front exciters near the front of the cabinet and the back exciters nearer the middle/back of the cabinet.
| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) |

### Backbox speakers
The backbox speakers are standard 5 1/4" car stereo speakers connected to the amplifier on its Speaker Left and Speaker Right connectors. 

| Date ordered | Part |
|---|---|
| Feb 21, 2026 | [Pioneer TS-501M 5.25" 4-Way Coaxial Car Speakers](https://www.amazon.com/dp/B0DYLCVGQ7) |

### Subwoofer
The subwoofer speaker is a standard 6 1/2" car stereo subwoofer and is connected to the amplifier on its Sub connector. It is mounted to the cabinet's floor in the subwoofer hole. A speaker grill is mounted on the outside bottom of the cabinet to protect the subwoofer.

| Date ordered | Part |
|---|---|
| Feb 27, 2026 | [Skar Audio EVL-65 D4 6.5" 400 Watt Max Power Dual 4 Ohm Car Subwoofer](https://www.amazon.com/dp/B019WYPLIA) |
| MAr  1, 2026 | [DS18 PRO-GRILL6MS/BK PRO 6.5" Slim Metal Mesh Speaker Grill](https://www.amazon.com/dp/B0CFYSX56H?ref=ppx_yo2ov_dt_b_fed_asin_title) |

# 8. Video subsystem

### Playfield monitor
The playfield monitor is set to 4K, 120Hz, 100% scaling and HDR in windows display settings. The monitor is mounted to the Tukkari playfield mount and angled down in the "classic" (not flat) position. A 4K certified cable was used to connect it to the GPU using an HDMI port. 

!["Classic" lowered position"](images/Playfield-monitor-position.jpg)

| Date ordered | Part |
|---|---|
| Dec 13, 2025 | [LG 42-Inch Class 4K OLED C4 TV from Amazon](https://www.amazon.com/dp/B0CVRXN6XZ?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| Dec 25, 2025 | [Highwings 8K@60 HDMI Cable 10FT](https://www.amazon.com/dp/B08KSY32VR?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Backfield monitor
The backfield monitor is mounted in the backbox using the Tukkari mount and is set to 1080P, 60Hz and 100% scaling in windows display settings. The monitor has an unsually thick rear cover, so much so that it pushes the monitor forward and you are unable to use the Tukkari supplied plexiglass cover in front of the monitor. Someday I may try the trick of mounting the brackets backwards so that the monitor shift back and the plexiglass may be installed. It is connected to a Display Port on the GPU.

| Date ordered | Part |
|---|---|
| Dec 18, 2025 | [Samsung 32-Inch Odyssey G3 (G30D) Series FHD Gaming Monitor](https://www.amazon.com/dp/B0D5Z565D5?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### DMD monitor
The DMD monitor is set to 1080P 60Hz in windows and is mounted to the Tukkari metal speaker panel. Two pieces of aluminum strap were bent and tapped so that they can be used as mounting brackets. Two 90 degree angled adapters (one mini-HDMI and one USB-C) were used to provide power and signal to the monitor in the very tight space. It is connected to an HDMI port on the GPU.

| Date ordered | Part |
|---|---|
| Dec 18, 2025 | [KYY Portable Monitor 15.6" 1080P Computer Monitor](https://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_titlehttps://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_titlehttps://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| Feb 25, 2026 | [AreMe 90 Degree USB-C Male to Female Adapter 2 Pack](https://www.amazon.com/dp/B0B2NJ3P3L)
| Feb 25, 2026 | [90 Degree Mini HDMI to HDMI Adapter 2 Pack](https://www.amazon.com/dp/B0DXP8G1M7)

# 9. Addressable LEDs

Addressable LEDs were added to three different parts of the table -
- Playfield side lights (on both sides of the playfield display). It uses 137 LEDs for each side. The wires run out of the top of playfield to the controller. These LEDs were placed inside a smoke black LED strip panel to soften the lights.
- RGB matrix (at the top of the playfield display). 6-16x16 CSD RGB panels were used for a total display matrix of 96x16 RGB LEDs. A Matrix Display Board and Plexiglass was ordered but the slotted backing board part was not used. The Tukkari backboard was used instead to mount the matrix panels. The smoked plexiglass panel was used to cover the panels and soften the lights. The plexiglass panel uses velcro buttons to attach it so that it can be easily removed.
- Speaker ring lights (left and right speakers in the backbox). It uses 57 LEDs for each speaker. The LEDs were mounted inside the pre-routed Tukkari slots around each speaker.

The LEDs are controlled by a separate [CSD WEMOS S2 mini controller](https://www.clevelandsoftwaredesign.com/pinball-parts/p/addressable-led-controller) connected with USB to the PC. This controller is mounted to the backside of the playfield backboard. A hole was drilled through the backboard to connect to the matrix panels on the other side. `The [DOF software](https://configtool.vpuniverse.com/app/home) uses this controller to manage the LEDs. The CSD PinOne controller is not used for the LEDs.

| Date ordered | Part |
|---|---|
| Jun  2, 2026 | [Cleveland Software Designs Addressable LEDs](https://www.clevelandsoftwaredesign.com/pinball-parts/p/addressable-led-plug-and-play-kit?utm_medium=email&utm_source=customer_notification) |
| Jun  2, 2026 | [Matrix Display Board and Plexi glass](https://pinballcabinet.com/products/matrix-display-board-and-plexi-glass?_pos=1&_psq=Matrix+Display+Board+and+Plexi+glass+%C3%97+1&_psid=175819946&_ss=e&_su_rec=_LF1zME-2TKjNRA2qCVkx76eoBRy1DQVqyRocdSSjbh_dNJZRK7G9QU9ZUUBw1F4msSCpbx28rpIwXdamk-ZNus4tzgtUHHnVmoETgvqy5kameCwqw4HYOEzQx-cde56WJhI68bPAgros-TAn5lOhsiW5g8r0wZiRcbyGf-VRXMd6J0vVkWpw1LuLyNKSjtfM2guT5dObopG7d4GNDChhwEFKnRBLqxAi_OsVz1cTjYo7X3Ee8b9WjaeitRhIZaNUis_QedeYdFG4ACb4vPgapZgnT1CqQ2btk_Wr73zGG-0QluqQKCTXzqo5_PxSfQg3lcIdR3r9vrNhpOtw6e0Q0xe-BsR58oK0wBqAIUFGKBGDnNFYHTF9i5wIH46tl0t4k5cv5PKz9lg_gB2DTdumGSie7tItcU&_su_rec_id=09b31051-c94a-442a-bfe6-7143a7d115ed-1793803758)
| Jun 12, 2026 | [BTF-LIGHTING WS2812B IC RGB LED Strip](https://www.amazon.com/dp/B01CDTEJR0) |
| Jun 11, 2026 | [Muzata 6Pack 3.3FT Black LED Strip Channel with Smoky Cover](https://www.amazon.com/dp/B07KBYQ3JR) |

# 10. Miscellaneous

### Knocker
The knocker is used to make a loud "knock" noise when a player has won a game. It is mounted on the left inside wall of the backbox at the top (so it can have a loud knock). It is connected to the PinOne controller's Knocker terminals.  

| Date ordered | Part |
|---|---|
| May 4, 2026 | [Cleveland Software Designs 12v to 24v knocker circuit conversion kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/12v-to-24v-knocker-circuit-conversion-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### Shaker motor
The [shaker motor](https://www.clevelandsoftwaredesign.com/pinball-parts/p/ultimate-pinball-shaker-motor) was bolted through the cabinet floor since it needs a very secure mount so that it doesn't shake itself apart and cause damage. It is connected to the CSD PinOne using the shaker connector.

| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Virtual Pinball Builders Kit (medium/large) from Cleveland Software Designs](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-builders-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### Coin door
This is a coin door used in real pinball Wililams-style tables. It mounts in the pre-cut hole in the front of the cabinet using supplied bolts. The coin insert slots are fully functional since the have switches connected to the coin door harness. In addition, micro-switches were epoxied glued to the *coin reject* buttons and wired in parallel with the coin insert switches in order to use the reject buttons as coin insert buttons.

In addition another microswitch was mounted to the cabinet to be used as a custom coin door open (tilt) switch. 

| Date ordered | Part |
|---|---|
| Feb 21, 2026 | [Williams/Bally Coin Door with wiring harness](https://www.pinballlife.com/williamsbally-coin-door.html?) |
| Feb 21, 2026 | [1/4-20 x 1-1/4" Black Carriage Bolt](https://www.pinballlife.com/search.html?Search=231-5003-00)
| Feb 21, 2026 | [1/4-20 Coin Door Whiz Flange Locknut](https://www.pinballlife.com/14-20-coin-door-whiz-flange-locknut.html?)
| Mar  9, 2026 | [Micro Limit Switch 3 Pin SPDT 1NO 1NC Snap Action](https://www.amazon.com/dp/B09SWCJ8FF)

### Coin door adapter
This allows you to use the service board connector on the CSD PinOne board to directly plug into a Williams coin door. This will map the slam tilt, both coin switches and the 4 service buttons to the CSD inputs and the 5v outputs will power the coin lights built into the door.

| Date ordered | Part |
|---|---|
| Feb 22, 2026 | [Cleveland Software Designs Williams Coin Door Adapter](https://www.clevelandsoftwaredesign.com/pinball-parts/p/williams-coin-door-adapter?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### Chime box
A 3-note chime box was added inside the pinball table box. Since the chime coils require a high current, high current controller outputs must be used. One of the note coils uses the CSD PinOne controller high current output (since it was the last one) and the other two are interfaced to the PinOne through a [CSD Simple two output board](https://www.clevelandsoftwaredesign.com/pinball-parts/p/simple-two-output-board) to convert two CSD PinOne low current (signal) outputs to high current. Those two coils are powered by the PC's power supply (12V) not the CSD PinOne. This is done by attaching the PC power to the CSD Simple two output board.

In addition, 3 diodes are used across the coil terminals to keep the coil flyback voltage from damaging the controller circuits.

| Date ordered | Part |
|---|---|
| Sep 15, 2026 | [Intense Arcade Three Note Chime box](https://intensearcade.com/three-note-chime-unit) |
| Sep 15, 2026 | [CSD Simple two output board](https://www.clevelandsoftwaredesign.com/pinball-parts/p/simple-two-output-board) |

### External HDMI & USB connector
An external HDMI and USB connector was installed in the left rear hole of the bottom cabinet panel and plugged into the PC. This allows the user to connect a monitor and a keyboard physically to the PC in order to change BIOS settings (since wireless connections won't work with this PC's BIOS).
| Date ordered | Part |
|---|---|
| Feb 28, 2026 | [USB 3.0 & HDMI Male to Female AUX Dash Car Flush Mount Cable 3ft](https://www.amazon.com/dp/B073HZ4STM) |

### External LAN connector
An external LAN connector was installed in the right rear hole of the bottom cabinet panel and plugged into the PC's ethernet port. This allows the user to much higher LAN speeds when transferring files or backing up the PC.
| Date ordered | Part |
|---|---|
| Jun 21, 2026 | [RJ45 CAT6 Panel Mount Adapter Female-Female Ethernet Pass-Through Connector](https://www.amazon.com/dp/B0CPZX5B3G) |

### Wireless keyboard/trackpad
A wireless keyboard/trackpad combo is used to configure the PC & pinball tables as needed. 
| Date ordered | Part |
|---|---|
|  Mar 18, 2026 | [RJ45 CAT6 Panel Mount Adapter Female-Female Ethernet Pass-Through Connector](https://www.amazon.com/dp/B0CPZX5B3G) |

### Wireless game controller
A wireless game controller is used to play arcade games on the pinball table. The adapter is plugged into a PC USB port. The top keys were configured as F1-F12 functions keys since the pinball games use those quite extensively.

| Date ordered | Part |
|---|---|
| Mar 18, 2026 | [Logitech K400 Plus Wireless Touch TV Keyboard ](https://www.amazon.com/dp/B014EUQOGK?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Ground cable
A flat braid cable was used to ground all of electronics and the exposed metal surfaces in case someone walked up to the cabinet and had a static discharge though an exposed metal surface.

| Date ordered | Part |
|---|---|
| Feb 16, 2026 | [Tinned Flat Copper Braid Cable,4mm Flat Copper Braided Ground Strap Wire ](https://www.amazon.com/dp/B0CB3Z86HV?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Cabinet button labels
The under cabinet input buttons were labeled on the outside of the cabinet so the user knows which button to press. In addition, buttons themselves were labeled on the inside using 1 1/2" circular cut regular printer paper. The buttons were disassembled and the circular paper placed inside and reassembled. 

| Date ordered | Part |
|---|---|
| Mar 10, 2026 | [15 Sheet Small Letter Stickers - 1/2 Inch White Vinyl Self Adhesive Alphabet Number Stickers](https://www.amazon.com/dp/B0CYTT6JTY?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Cable management
Cables inside the cabinet were placed inside raceways to cover the cables and keep them neat.  

| Date ordered | Part |
|---|---|
| Mar 5, 2026 | [Cable Raceway 77in Wire Covers Under Desk Cable Management 5-Pack](https://www.amazon.com/dp/B08R75RMQT?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Fans
One incoming PC fan and two outgoing PC fans are used to keep the cabinet cool. The incoming fan was mounted on the bottom of the cabinet to bring in cool air and the outgoing fans were mounted on the back panel of the cabinet to exhaust hot air.

| Date ordered | Part |
|---|---|
| Feb 21, 2026 | [CORSAIR RS120 120mm PWM Fans ](https://www.amazon.com/dp/B0D49QX74S?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| Mar 19, 2026 | [Black 2 Pack PC Fan Grill](https://www.amazon.com/dp/B0CYHB7J9H?ref=ppx_yo2ov_dt_b_fed_asin_title) |

# 11. Wiring diagrams

###  Inputs
![Inputs](./images/Pinball-cabinet-Inputs.png)

###  Outputs
![Outputs](./images/Pinball-cabinet-Outputs.png)

###  Audio/Video
![Audio/Video](./images/Pinball-cabinet-Audio-Video.png)

###  Lights
![Lights](./images/Pinball-cabinet-Lights.png)

# 12. Software

## Virtual pinball emulator apps (windows versions)

### Visual Pinball X (VPX) emulator tables
Mostly VPX 10.8.0 tables are used in this cabinet. They are downloaded from [VPUniverse](https://vpuniverse.com/) and [VPForums](https://www.vpforums.org/). I am experimenting with pre-releases of the new [VPX 10.8.1 emulator](https://github.com/vpinball/vpinball) using these tables. The current results look good.  

#### TODO How I find and add a VPX table, make adjustments, add media, etc.

### Future Pinball emulator tables
In addition, some Future Pinball tables are used in this cabinet. They are also downloaded from [VPUniverse](https://vpuniverse.com/) and [VPForums](https://www.vpforums.org/). 

### Pinball FX (Steam) emulator tables
A few Steam Pinball FX emulator based tables were bought and are used in this cabinet. They are downloaded from [Pinball FX](https://www.pinballfx.com/). The steam emulator is installed and started upon windows boot.

### Pinup Popper frontend
[Pinup Popper](https://nailbuster.com/wikipinup/doku.php?id=start) is used as the frontend to select which table to load and run. It was installed and the cabinet software setup using [Baller Installer](https://nailbuster.com/wikipinup/doku.php?id=baller_installer).
#### PinUpMenu.exe TODO
#### PinUpMenuSetup.exe TODO
#### TODO how are the buttons configured?
#### TODO how are playlists managed?

#### TODO How to select, add coins and start a table

### DOF
TODO

### DOFLinx
TODO

### Steam
TODO

### Startup folder, scripts

### PinVol
[PinVol](http://mjrnet.org/pinscape/PinVol.html) is a windows background app that adjusts the volume of a table when it starts up (since tables tend to have different volume levels). It allows you to use the CSD buttons at the bottom of the cabinet to adjust the volume of a table and it will remember it for the next time the table is run. 

### JoyToKey
[JoyToKey](https://joytokey.net/en/) is a windows background app that is used to enhance the CSD button usage by doing - 

| Button | Context | Action |
|---|---|---|
| CSD Start | Windows desktop | Start the Pinup Popper frontend |
| CSD Pause | VPX emulator | Pause the table (enter the 'P' key) |
| ??? | Pinball FX (Steam) emulator | ??? |

### PinAffinity
[PinAffinity](http://mjrnet.org/pinscape/PinAffinity.html) is a windows background app that adjusts the Windows process affinity executables to give the pinball emualtors higher priority (and other processes lower) hence making the emulator run smoother. 

### FanControl
[FanControl](https://getfancontrol.com/) is a windows background app that adjusts the fan speed better than the PC BIOS does, thus producing less fan noise while keeping the electronics cooler. 

## Misc software

### RustDesk
[RustDesk](https://rustdesk.com/) is used as a remote desktop app so that I can use my PC to remotely control the cabinet (in Windows, in an emulator, etc.). It can remotely show all three displays (playfield, backglass, DMD). 

### VPin Studio

- Install/Manage/Remove tables
[VPin Studio](https://github.com/syd711/vpin-studio) is used to intelligently manage the pinball table emulators, software, associated files and settings over the LAN. It is a client/server design where the pinball cabinet has a server running in background and my main PC has the client running that talks to that server. The client is also installed on the pinball cabinet itself so that you can use it there too with the wireless keypad/trackpad. I normally use it remotely since I can do that from my office and I have a better keyboard/mouse/monitor setup there.      

- Backup/Restore tables
It also will backup individual tables to my NAS over the LAN. This allows me to experiment with a new version of a table and, if needed, delete the table and restore it from a good backup on the NAS. It also allows me to experiment with a table to see if I want to keep it or not and I decide not to keep it, backup it up to see if I will miss it later and restore it.  

### HDP PC Agent
[HDP PC Agent](https://www.qnap.com/en-us/software/hdp-pc-agent) is a background app that the QNAP NAS uses for backup. The entire cabinet software (including Windows) is periodically backed up in case of catastrophic storage failure. 

- NVidia app settings?
- MAME TODO