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

The best resources I have found on how to build a virtual pinball table are -
- [Pinscape build guide](http://mjrnet.org/pinscape/BuildGuideV2/BuildGuide.php?sid=architecture)
- [Way of the Wrench youtube videos](https://www.youtube.com/@wayofthewrench). Especially the [Big Budget build videos](https://www.youtube.com/playlist?list=PLrqlHbqP7FINmGgJoszVvWOOyb8shdfUn). I used a different flat pack and a different controller, but there are many similarities.  

# 2. Cabinet

The cabinet used for the build was a [Tukkari Widebody Virtual Pinball Cabinet](https://www.tukkari.com/p/widebody-virtual-pinball-cabinet-vpin-flat-pack-kit) flat pack. Their [assembly guide](https://www.tukkari.com/advisor/assembly-guide-widebody-vpin-cabinet-premium-flat-pack) was used for construction.

![cabinet](images/Tukkari-widebody-cabinet.png)

# 3. Cabinet Parts

| Date ordered | Part |
|---|---|
| Jan 3, 2026 | [Tukkari Widebody Virtual Pinball Cabinet](https://www.tukkari.com/p/widebody-virtual-pinball-cabinet-vpin-flat-pack-kit) |
| Jan 3, 2026 | [Black powder-coated siderails ](https://www.pinballlife.com/47-316-williamsbally-wpc-stainless-steel-side-rails-set-of-2.html) |
| Jan 3, 2026 | [Black powder-coated lockdown bar](https://www.pinballlife.com/stern-dual-latch-lockdown-bar-with-action-button-hole.html) |
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
|  Mar  4, 2026 | [WIDEBODY Playfield Glass Rear Plastic Channel](https://www.pinballlife.com/widebody-playfield-glass-rear-plastic-channel.html) |
|  Mar  4, 2026 | [Playfield Glass Side Rail Plastic Channel](https://www.pinballlife.com/stern-extrusion-playfield-glass-sides-all-game.html) |
|  Mar 21, 2026 | [Cup Holder](https://www.marcospecialties.com/pinball-parts/77-PBY-GSK45) |

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
| ![](images/Addressable-RGB-LEDs-controller.jpg) | ![](images/Cup-holder.jpg) | ![](images/Lockdown-bar--latches-flipper-button-board-installed.jpg)
| *Addressable RGB LEDs controller on back of top of playfield angled board*  | *Cup holder* | *Lockdown-bar latches, flipper button boards installed* |

<img src="./images/Cabinet-bottom.jpg" alt="Description" width="40%" height="40%">\
*Cabinet bottom*

### Cabinet bolt sizes

| Part | Bolt size |
|---|---|
| PC board | M6x25mm |
| Upright braces | M6x10mm |
| Upright braces support board | M6x25mm |
| Backbox attachment | M6x35mm |


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

<img src="./images/PC-installed.jpg" alt="Description" width="40%" height="40%">\
*PC installed*

| Date ordered | Part |
|---|---|
| Dec 10, 2025 | [GIGABYTE GeForce RTX 5070 Gaming OC 12G Graphics Card](https://www.amazon.com/dp/B0DTR3JK3Y?th=1) |
| Dec 10, 2025 | [CORSAIR RM850x ATX 3.1 PCIe 5.1 750W Power Supply](https://www.amazon.com/dp/B0DJ1JL3MK) |
| Feb 21, 2026 | [AL01 Open Frame Computer case ](https://www.amazon.com/dp/B0C59W6JKD) |
| Feb 21, 2026 | [USB 3.0 PCIE Card 5-Port](https://www.amazon.com/dp/B09MFPGMH5?ref=ppx_yo2ov_dt_b_fed_asin_title) |

# 6. Cabinet electronics

#### [Cleveland Software Designs Virtual Pinball Builders Kit (medium/large)](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-builders-kit)
![](./images/CSD-Builders-Kit.png)

As the main controller, the Cleveland Software Designs PinOne is used along with its accessories. It is part of a virtual pinball builders kit.

| | | |
| :---: | :---: | :---: |
| ![](images/CSD-PinOne-installed.jpg) | ![](images/CSD-left-flippers.jpg) | ![](images/CSD-right-flippers.jpg)
| *PinOne installed* | *Left flippers* | *Right flippers* 


It includes the following: 
 
| Part | Usage |
|---|---|
| [PinOne Controller](https://www.clevelandsoftwaredesign.com/pinball-parts/p/pinone-main-virtual-pinball-connection-board) | Main controller |
| [4x True Leaf Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-true-leaf-button) | Flipper & Magna-save buttons |
| [RGB LED Button](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button) | Fire button |
| [2x Red LED Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee) | Power and Pause buttons |
| [2x Blue LED Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee) | Exit and Night Mode buttons |
| [2x Green LED Buttons](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee) | Vol-/Vol+ buttons |
| [1x White LED Button](https://www.clevelandsoftwaredesign.com/pinball-parts/p/rgb-leaf-button-3hwee) | Start button |
| [10x Solenoids](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-quality-solenoid) | 4 side solenoids, 3 middle bar and 3 back bar solenoids |
| [2x 2 Position Solenoid Life Extenders](https://www.clevelandsoftwaredesign.com/pinball-parts/p/style-01-j6jmp) | for side solenoids |
| [2x 3 Position Solenoid Life Extenders](https://www.clevelandsoftwaredesign.com/pinball-parts/p/style-01-j6jmpv) | for middle & back bar solenoids |
| [Button Board and 2x Flipper Button Boards](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-button-hookup-kit) | button interface to PinOne |
| [Williams Style Plunger](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-plunger-attachment) | |
| [Service Board](https://www.clevelandsoftwaredesign.com/pinball-parts/p/expansion-breakout-board-zx5y6) | not used, the one in the real coin door is used instead |
| [Shaker motor](https://www.clevelandsoftwaredesign.com/pinball-parts/p/ultimate-pinball-shaker-motor)

The various devices in the kit were connected based on this [CSD documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/category/builders-kits).

The [CSD PinOne Configuration documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/PinOne/) was used to configure the PinOne board and the devices (inputs, outputs, etc.). The [CSD PinOne Configuration app](https://pinball-docs.clevelandsoftwaredesign.com/docs/PinOne/Configuring/) is left installed on the cabinet desktop to make it easy to reconfigure the PinOne board. 

Night mode is enabled when the Night Mode button is pressed (button on the bottom of the cabinet behind right front leg). It works as an on/off toggle. The CSD PinOne board is configured to turn off solenoids, knocker and chimes when night mode is on.   

### Solenoids, outputs

| | | | |
| :---: | :---: | :---: | :---: |
| ![](images/Right-front-solenoid-installed.jpg) | ![](images/Left-front-solenoid-installed.jpg) | ![](images/Middle-bar-solenoids-installed.jpg) | ![](/images/Back-bar-solenoids-installed.jpg)
| *Right front solenoid installed* | *Left front solenoid installed* | *Middle bar solenoids installed* | *Back-bar-solenoids-installed*

### CSD Outputs config
<img src="./images/CSD outputs config.png">

| Outputs | Port | Connector |
|---|---|---|
| Solenoid front left | 1 | + 1 2 |
| Solenoid rear left | 2 | + 1 2 |
| Solenoid middle bar right | 3 | + 3 4 5 |
| Solenoid middle bar middle | 4 | + 3 4 5 |
| Solenoid middle bar left | 5 |  + 3 4 5 |
| Solenoid back right |6 | + 6 7 |
| Solenoid front right | 7 | + 6 7 |
| Solenoid back bar right | 8 | + 8 9 10 |
| Solenoid back bar middle | 9 | + 8 9 10 |
| Solenoid back bar left | 10 | + 8 9 10 |
| Chime low | 11 | 11 (Beacon) |
| Shaker motor | 12 | 12 (Shaker) |
| Knocker | 13 | 13 ( Knocker) |
| Chime high | 14 | 14 |
| Chime middle | 15 | 15 |
| IR emitter (?) | 24 | 24 |

### Buttons, inputs

| | | | |
| :---: | :---: | :---: | :---: |
| ![](images/CSD-button-board-installed.jpg) | ![](images/Left-flipper-button-board-installed.jpg) | ![](images/Right-flipper-button-board-installed.jpg) | ![](/images/CSD-bottom-buttons-installed.jpg)
| *CSD button board installed* | *Left flipper button board installed* | *Right flipper button board installed* | *Bottom buttons installed*

### CSD Inputs config
<img src="./images/CSD inputs config.png">

| Button inputs | Port | Button board |
|---|---|---|
| Flipper right | 1 | (right flipper board) B1 |
| Magna-save right | 2 | (right flipper board) B2 |
| Flipper left | 3 | (left flipper board) B1 |
| Magna-save left | 4 | (left flipper board) B2|
| Night mode | 5 | B5 |
| (unused) | 6 | B6 |
| Pause | 7 | B7 |
| (unused) | 8 | B8 |
| Fire | 9 | B9 (Fire) |
| Vol+ | 10 | B10 |
| Vol- | 11 | B11 |
| Exit | 12 | B12 |
| Start | 13 | B13 |
| Coin door open | 14 | B14 |
| Tilt | 16 | (accelerometer) |
| Coin left | 17 | (coin door adapter) |
| Coin right | 18 | (coin door adapter) |
| Escape | 19 | (coin door adapter) |
| Test mode | 20 | (coin door adapter) |
| Function | 21 | (coin door adapter) |
| Enter | 22 | (coin door adapter) |
| Coin door tilt | 23 | (coin door adapter) |
| Plunger launch | 24 | (plunger) |

### CSD Button outputs config
<img src="./images/CSD button outputs config.png">

Note: individual Magna-save buttons can be set to different colors (left vs right). The Fire button can also be set to any color. The left & right flippers can be set to any color, but they both have to be the same color. The other buttons are a static color (as defined by their plastic color) .

Note: the power button is lit though a port but its button switch is sent to the PC power-on motherboard connector not to the PinOne controller.

| Button outputs (LEDs) | Port | Button board |
|---|---|---|
| Flippers red | 16 | (left/right flipper board) B1 |
| Flippers green | 17 | (left/right flipper board) B1 |
| Flippers blue | 18 | (left/right flipper board) B1 |
| Magna right red | 19 | (right flipper board) B2 |
| Magna right green | 20 | (right flipper board) B2 |
| Magna right blue | 21 | (right flipper board) B2 |
| Magna left red | 22 | (left flipper board) B2 |
| Magna left green | 23 | (left flipper board) B2 |
| Magna left blue | 24 | (left flipper board) B2 |
| Night Mode| 25 | B5 |
| Power | 26 | B6 |
| Pause | 27 | B7 |
| (unused) | 28 | B8 |
| (unused) | | B9 |
| Vol+ | (always on) | B10 |
| Vol- | (always on)  | B11  |
| Exit | (always on)  | B12  |
| Start | (always on)  | B13  |
| (unused) | (always on) | B14 |
| Fire red | 29 | Fire LED |
| Fire green | 30 | Fire LED |
| Fire blue | 31 | Fire LED |

**VPX 10.8 Button/key config**

<img src="./images/VPX10.8-button-config.png" width="100%" height="100%">

### CSD Plunger

The CSD plunger was installed and configured per the [documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/PinOne/Configuring/plunger). 

<img src="./images/CSD-plunger-installed.jpg" width="40%" height="40%">

### CSD Plunger config
<img src="./images/CSD plunger config.png">

| Plunger setting | Value |
|---|---|
| Average Readings | 10 |
| Plunger Launch Button | 24 |
| Plunger Min Position | 15 |
| Plunger Max Position | 859 |
| Plunger Resting Position | 166 |
| Plunger Dead Zone | 255 |
| Plunger Quick Release Delay | 150 |
| Push Button On Min | off |
| Push Button On Max | off |
| Disable Plunger When Not Moving | off |
| Disable Accelerometer On Plunger Move | on |

### CSD Accelerometer

The CSD PinOne has an internal accelerometer that is used for nudging. It is configured per the [documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/PinOne/Configuring/accelerometer). 

### CSD Accelerometer config
<img src="./images/CSD accelerometer config.png">

| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Virtual Pinball Builders Kit (medium/large) from Cleveland Software Designs](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-builders-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### CSD Settings config

Miscellaneous CSD PinOne board settings. 

<img src="./images/CSD settings config.png">

# 7. Audio subsystem

 ### [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) 
![](./images/CSD-SSF-Kit.png)

 For the audio subsystem, the Cleveland Software Designs SSF Kit is used. It includes the following: 
- [Amplifier](https://www.clevelandsoftwaredesign.com/pinball-parts/p/ssf-extra-amplifier)
- [Bass shaker](https://www.clevelandsoftwaredesign.com/pinball-parts/p/bass-shaker-speaker)
- [4x Exciter speakers](https://www.clevelandsoftwaredesign.com/pinball-parts/p/replacement-exciter-speaker)

### Amplifier
<img src="./images/CSD-audio-amplifer-cabinet.jpg" width="40%" height="40%">

The CSD amplifier is set to 7.1 mode and is connected to the PC's 7.1 audio output jacks using 3-3.5mm multi-channel audio wires. 

| PC audio output | CSD amplifier input |
|---|---|
| Green (Front L/R) | Speaker L/R In |
| Black (Rear surround) | Back L/R In |
| Gray/White (Side surround) | Front L/R In |

The PC Orange (Subwoofer and Center ) output is not used. The CSD amplifier creates its own subwoofer output from the other audio inputs.

The amplifier's physical volume is turned up to the max and the table volumes are managed through the windows and the [PinVol](http://mjrnet.org/pinscape/PinVol.html) app. The CSD surround sound card is not used.

| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) |
| Mar 24, 2026 | [AUX Cord for Car, 6 Pack 3.5mm Auxiliary Audio Cable](https://www.amazon.com/dp/B07N3YKBDY?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Bass Shaker
The CSD Bass Shaker is connected to the amplifier on its Shaker connector. It is mounted to the floor of the cabinet so that it can shake the whole cabinet.

 <img src="./images/Bass-shaker-installed.jpg" width="40%">

| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) |

### Exciter Speakers
Four CSD exciter speakers are connected to the amplifier on its Front Left/Front Right and Back Left/Back Right connectors. They are mounted on the side walls of the cabinet with the front exciters near the front of the cabinet and the back exciters nearer the middle/back of the cabinet.

| | | | |
| :---: | :---: | :---: | :---: |
| ![](images/Left-front-exciter-speaker.jpg) | ![](images/Right-front-exciter-speaker.jpg) | ![](images/Left-rear-exciter-speaker.jpg) | ![](images/Right-rear-exciter-speaker.jpg) 
| *Exciter speaker left front installed* | *Exciter speaker right front installed* |  *Exciter speaker left rear installed* | *Exciter speaker right rear installed* |  

| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Cleveland Software Designs SSF Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/high-power-ssf-kit) |

### Backbox speakers
The backbox speakers are standard 5 1/4" car stereo speakers connected to the amplifier on its Speaker Left and Speaker Right connectors. 

| | |
| :---: | :---: |
| ![](images/Left-speaker-installed.jpg) | ![](images/Right-speaker-installed.jpg) 
| *Backbox speaker left installed* | *Backbox speaker right installed* |  


| Date ordered | Part |
|---|---|
| Feb 21, 2026 | [Pioneer TS-501M 5.25" 4-Way Coaxial Car Speakers](https://www.amazon.com/dp/B0DYLCVGQ7) |

### Subwoofer
The subwoofer speaker is a standard 6 1/2" car stereo subwoofer and is connected to the amplifier on its Sub connector. It is mounted to the cabinet's floor in the subwoofer hole. A speaker grill is mounted on the outside bottom of the cabinet to protect the subwoofer.

 <img src="./images/Subwoofer-installed.jpg" width="40%">

| Date ordered | Part |
|---|---|
| Feb 27, 2026 | [Skar Audio EVL-65 D4 6.5" 400 Watt Max Power Dual 4 Ohm Car Subwoofer](https://www.amazon.com/dp/B019WYPLIA) |
| Mar  1, 2026 | [DS18 PRO-GRILL6MS/BK PRO 6.5" Slim Metal Mesh Speaker Grill](https://www.amazon.com/dp/B0CFYSX56H?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Testing the audio subsystem 

#### Testing 7.1 audio
An audio file called "LPCM 7.1.wav" (on the desktop) is used to test the 7.1 audio subsystem. 

#### Testing the subwoofer 
An audio file called "40 Hz Tone.wav" (on the desktop) is used to test the subwoofer. 

# 8. Video subsystem

### Graphics card

A [GIGABYTE GeForce RTX 5070 ](https://www.amazon.com/dp/B0DTR3JK3Y?th=1) graphics card is used to drive all three monitors. 3 of the 4 ports are used (DPI, HDMI, HDMI). It is made for a more recent motherboard, but it works great in the older one that I am using.

![](./images/Graphics-card.png)

### Playfield monitor

For the playfield monitor, a [LG 42-Inch Class 4K OLED C4 TV](https://www.amazon.com/dp/B0CVRXN6XZ?ref=ppx_yo2ov_dt_b_fed_asin_title) is used. 

![](images/Playfield-monitor.png)

It is set to 4K, 120Hz, 100% scaling and HDR in windows display settings. The monitor is mounted to the Tukkari playfield mount and angled down in the "classic" (not flat) position. A 4K certified cable was used to connect it to the GPU using an HDMI port.

The TV itself was configured for gaming mode. It also goes into standby mode when the pinball table PC is shutdown so that it stays as the primary windows desktop and the pinball table software doesn't get confused about which monitor is used for what in the tables when the PC starts up.   

!["Classic" lowered position"](images/Playfield-monitor-position.jpg)

| Date ordered | Part |
|---|---|
| Dec 13, 2025 | [LG 42-Inch Class 4K OLED C4 TV](https://www.amazon.com/dp/B0CVRXN6XZ?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| Dec 25, 2025 | [Highwings 8K@60 HDMI Cable 10FT](https://www.amazon.com/dp/B08KSY32VR?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Backglass monitor

For the backglass monitor, a [Samsung 32-Inch Gaming Monitor](https://www.amazon.com/dp/B0D5Z565D5?ref=ppx_yo2ov_dt_b_fed_asin_title) is used. 

![](images/Backglass-monitor.png)

The backglass monitor is mounted in the backbox using the Tukkari mount and is set to 1080P, 60Hz and 100% scaling in windows display settings. The monitor has an unusually thick rear cover, so much so that it pushes the monitor forward and you are unable to use the Tukkari supplied plexiglass cover in front of the monitor. Someday I may try the trick of mounting the brackets backwards so that the monitor shifts back and the plexiglass may be installed. It is connected to a Display Port on the GPU.

| Date ordered | Part |
|---|---|
| Dec 18, 2025 | [Samsung 32-Inch Odyssey G3 (G30D) Series FHD Gaming Monitor](https://www.amazon.com/dp/B0D5Z565D5?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### DMD monitor

For the DMD monitor, a [KYY Portable Monitor 15.6" 1080P Computer Monitor](https://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_titlehttps://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_titlehttps://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_title) is used. 

![](images/DMD-monitor.png)

The DMD monitor is set to 1080P 60Hz in windows and is mounted to the Tukkari metal speaker panel. Two pieces of aluminum strap were bent and tapped so that they can be used as mounting brackets. Two 90 degree angled adapters (one mini-HDMI and one USB-C) were used to provide power and signal to the monitor in the very tight space. It is connected to an HDMI port on the GPU.

| Date ordered | Part |
|---|---|
| Dec 18, 2025 | [KYY Portable Monitor 15.6" 1080P Computer Monitor](https://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_titlehttps://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_titlehttps://www.amazon.com/dp/B088D8JG3L?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| Feb 25, 2026 | [AreMe 90 Degree USB-C Male to Female Adapter 2 Pack](https://www.amazon.com/dp/B0B2NJ3P3L)
| Feb 25, 2026 | [90 Degree Mini HDMI to HDMI Adapter 2 Pack](https://www.amazon.com/dp/B0DXP8G1M7)

**VPX 10.8 Video/graphics config**

<img src="./images/VPX10.8-video-graphics-options.png" width="100%" height="100%">

# 9. Addressable LEDs

 For the LEDs, the [Cleveland Software Designs Addressable LED Kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/addressable-led-plug-and-play-kit) is used. 

 ![](./images/CSD-Addressable-LED-Kit.png)

Addressable LEDs were added to three different parts of the table -
- Playfield side lights (on both sides of the playfield display). The wires run out of the top of playfield to the controller. These LEDs were placed inside a smoke black LED strip panel to soften the lights.
- RGB matrix (at the top of the playfield display). 6-16x16 CSD RGB panels were used for a total display matrix of 96x16 RGB LEDs. A [Matrix Display Board and Plexiglass kit](https://pinballcabinet.com/products/matrix-display-board-and-plexi-glass?_pos=1&_psq=Matrix+Display+Board+and+Plexi+glass+%C3%97+1&_psid=175819946&_ss=e&_su_rec=_LF1zME-2TKjNRA2qCVkx76eoBRy1DQVqyRocdSSjbh_dNJZRK7G9QU9ZUUBw1F4msSCpbx28rpIwXdamk-ZNus4tzgtUHHnVmoETgvqy5kameCwqw4HYOEzQx-cde56WJhI68bPAgros-TAn5lOhsiW5g8r0wZiRcbyGf-VRXMd6J0vVkWpw1LuLyNKSjtfM2guT5dObopG7d4GNDChhwEFKnRBLqxAi_OsVz1cTjYo7X3Ee8b9WjaeitRhIZaNUis_QedeYdFG4ACb4vPgapZgnT1CqQ2btk_Wr73zGG-0QluqQKCTXzqo5_PxSfQg3lcIdR3r9vrNhpOtw6e0Q0xe-BsR58oK0wBqAIUFGKBGDnNFYHTF9i5wIH46tl0t4k5cv5PKz9lg_gB2DTdumGSie7tItcU&_su_rec_id=09b31051-c94a-442a-bfe6-7143a7d115ed-1793803758) was ordered but the slotted backing board part was not used. The Tukkari backboard was used instead to mount the matrix panels. But portions of the Matrix Display Board and Plexiglass kit were used to mount the matrix panels - the two 1/2" mounting boards are on the top and bottom of the matrix panels and the smoked plexiglass cover was used to cover the panels and soften the lights. It is attached with velcro "dots" so that it can easily be removed. 
- Speaker ring lights (left and right speakers in the backbox). The LEDs were mounted inside the pre-routed Tukkari slots around each speaker.

 <img src="./images/Addressable-RGB-LEDs.jpg" width="40%">


The LEDs are controlled by a separate [CSD WEMOS S2 mini controller](https://www.clevelandsoftwaredesign.com/pinball-parts/p/addressable-led-controller) connected with USB (COM port 5) to the PC. This controller is mounted to the backside of the playfield backboard and is configured using this documentation [CSD Addressable LEDs configuration](https://pinball-docs.clevelandsoftwaredesign.com/docs/AddressableLED/). A hole was drilled through the backboard to connect to the matrix panels on the other side. `The [DOF software](https://configtool.vpuniverse.com/app/home) uses this controller to manage the LEDs. The main CSD PinOne controller is not used for the LEDs.

| Location | #LEDs | WEMOS S2 port |
|---|---|---|
| RGB Matrix right right  | 256 | 1 |
| RGB Matrix right center  | 256 | 2 |
| RGB Matrix right left  | 256 | 3 |
| RGB Matrix left right  | 256 | 4 |
| RGB Matrix left center  | 256 | 5 |
| RGB Matrix left left  | 256 | 6 |
| Playfield left | 137 | 7 |
| Playfield right | 137 | 8 |
| Speaker left | 57 | 9 |
| Speaker left | 57 | 10 |

The [CSDAddressableControllerTool.exe app](https://pinball-docs.clevelandsoftwaredesign.com/docs/AddressableLED/configuring) was initially used to test the LEDs. 

![](./images/CSDAddressableControllerTool.exe.png)
 
 The online [CSD cabinet file generator](https://pinball-docs.clevelandsoftwaredesign.com/docs/AddressableLED/cabinetGenerator) was used to create the c:\DirectOutput\config.cabinet.xml file to configure the lights for the cabinet.

| Date ordered | Part |
|---|---|
| Jun  2, 2026 | [Cleveland Software Designs Addressable LEDs](https://www.clevelandsoftwaredesign.com/pinball-parts/p/addressable-led-plug-and-play-kit?utm_medium=email&utm_source=customer_notification) |
| Jun  2, 2026 | [Matrix Display Board and Plexiglass](https://pinballcabinet.com/products/matrix-display-board-and-plexi-glass?_pos=1&_psq=Matrix+Display+Board+and+Plexi+glass+%C3%97+1&_psid=175819946&_ss=e&_su_rec=_LF1zME-2TKjNRA2qCVkx76eoBRy1DQVqyRocdSSjbh_dNJZRK7G9QU9ZUUBw1F4msSCpbx28rpIwXdamk-ZNus4tzgtUHHnVmoETgvqy5kameCwqw4HYOEzQx-cde56WJhI68bPAgros-TAn5lOhsiW5g8r0wZiRcbyGf-VRXMd6J0vVkWpw1LuLyNKSjtfM2guT5dObopG7d4GNDChhwEFKnRBLqxAi_OsVz1cTjYo7X3Ee8b9WjaeitRhIZaNUis_QedeYdFG4ACb4vPgapZgnT1CqQ2btk_Wr73zGG-0QluqQKCTXzqo5_PxSfQg3lcIdR3r9vrNhpOtw6e0Q0xe-BsR58oK0wBqAIUFGKBGDnNFYHTF9i5wIH46tl0t4k5cv5PKz9lg_gB2DTdumGSie7tItcU&_su_rec_id=09b31051-c94a-442a-bfe6-7143a7d115ed-1793803758)
| Jun 12, 2026 | [BTF-LIGHTING WS2812B IC RGB LED Strip](https://www.amazon.com/dp/B01CDTEJR0) |
| Jun 11, 2026 | [Muzata 6Pack 3.3FT Black LED Strip Channel with Smoky Cover](https://www.amazon.com/dp/B07KBYQ3JR) |

# 10. Miscellaneous

### Knocker

For the knocker, the [Cleveland Software Designs Knocker kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/12v-to-24v-knocker-circuit-conversion-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) is used. 

![](./images/CSD-Knocker-Kit.png)

The knocker is used to make a loud "knock" noise when a player has won a game. It is mounted on the left inside wall of the backbox at the top (so it can have a loud knock). It is connected to the PinOne controller's Knocker terminals.  

<img src="./images/Knocker-installed.jpg" alt="Description" width="40%" height="40%">\
*Knocker installed*

<img src="./images/CSD-knocker-adapter-installed.jpg" alt="Description" width="40%" height="40%">\
*Knocker adapter installed*

| Date ordered | Part |
|---|---|
| May 4, 2026 | [Cleveland Software Designs 12v to 24v knocker circuit conversion kit](https://www.clevelandsoftwaredesign.com/pinball-parts/p/12v-to-24v-knocker-circuit-conversion-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### Shaker motor

For the shaker motor, the [Cleveland Software Designs Shaker motor](https://www.clevelandsoftwaredesign.com/pinball-parts/p/ultimate-pinball-shaker-motor) is used. 

![](./images/CSD-Shaker-Motor.png)

It is bolted through the cabinet floor since it needs a very secure mount so that it doesn't shake itself apart and cause damage. It is connected to the CSD PinOne using the shaker connector pins.

<img src="./images/CSD-shaker-motor-installed.jpg" alt="Description" width="40%" height="40%">\
*Shaker motor installed*


| Date ordered | Part |
|---|---|
| Feb 20, 2026 | [Virtual Pinball Builders Kit (medium/large) from Cleveland Software Designs](https://www.clevelandsoftwaredesign.com/pinball-parts/p/virtual-pinball-builders-kit?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### Coin door

For the coin door, the [Williams/Bally Coin Door with wiring harness](https://www.pinballlife.com/williamsbally-coin-door.html?) is used. 

![](./images/Williams-Coin-Door-With-Wiring-Harness.png)

This is a coin door used in real pinball Williams-style tables. It mounts in the pre-cut hole in the front of the cabinet using supplied bolts. The coin insert slots are fully functional since they have switches connected to the coin door harness. 

In addition, micro-switches were epoxied glued to the *coin reject* buttons and wired in parallel with the coin insert switches in order to use the reject buttons as coin insert buttons. Another microswitch was mounted to the inside of the front panel of the cabinet to be used as a custom coin door open switch. 

| | | |
| :---: | :---: | :---: |
| ![](images/Coin-reject-switch-custom.jpg) | ![](images/Coin-door%20switch-custom.jpg) |![](images/Coin-door-switch-custom-internal.jpg) |
| *Coin reject switch (custom)*  | *Coin door step bracket (w/extra padding)* | *Coin door switch internal (custom)* |
 

| Date ordered | Part |
|---|---|
| Feb 21, 2026 | [Williams/Bally Coin Door with wiring harness](https://www.pinballlife.com/williamsbally-coin-door.html?) |
| Feb 21, 2026 | [1/4-20 x 1-1/4" Black Carriage Bolt](https://www.pinballlife.com/search.html?Search=231-5003-00)
| Feb 21, 2026 | [1/4-20 Coin Door Whiz Flange Locknut](https://www.pinballlife.com/14-20-coin-door-whiz-flange-locknut.html?)
| Mar  9, 2026 | [Micro Limit Switch 3 Pin SPDT 1NO 1NC Snap Action](https://www.amazon.com/dp/B09SWCJ8FF)

### Coin door adapter
This allows you to use the service board connector on the CSD PinOne board to directly plug into a Williams coin door. This will map the coin door slam tilt, both coin switches and the 4 service buttons to the CSD inputs and the 5v outputs will power the coin lights built into the door.

<img src="./images/Coin-door-adapter-installed.jpg" width="40%" height="40%">

| Date ordered | Part |
|---|---|
| Feb 22, 2026 | [Cleveland Software Designs Williams Coin Door Adapter](https://www.clevelandsoftwaredesign.com/pinball-parts/p/williams-coin-door-adapter?utm_medium=order-summary&utm_source=order-status&utm_content=name) |

### Chime box
For the chime box, the [Intense Arcade Three Note Chime box](https://intensearcade.com/three-note-chime-unit) is used. 

<img src="./images/Intense-Arcade-Three-Note-Chime-Unit.png" alt="Description" width="40%" height="40%">\
*Chime unit*

A 3-note chime box was added inside the pinball table box. Since the chime coils require a high current, high current controller outputs must be used. One of the note coils uses the CSD PinOne controller high current output (since it was the last one) and the other two are interfaced to the PinOne through a [CSD Simple two output board](https://www.clevelandsoftwaredesign.com/pinball-parts/p/simple-two-output-board) to convert two CSD PinOne low current (signal) outputs to high current outputs. Those two coils are powered by the PC's power supply (12V) not the CSD PinOne. This is done by attaching a PC power connector to the CSD Simple two output board.

In addition, 3 diodes are used across the coil terminals to keep the coil flyback voltage from damaging the controller circuits.

<img src="./images/Chime-unit-installed.jpg" alt="Description" width="40%" height="40%">\
*Chime unit installed*

| Date ordered | Part |
|---|---|
| Sep 15, 2026 | [Intense Arcade Three Note Chime box](https://intensearcade.com/three-note-chime-unit) |
| Sep 15, 2026 | [CSD Simple two output board](https://www.clevelandsoftwaredesign.com/pinball-parts/p/simple-two-output-board) |

### External HDMI & USB connector
An external HDMI and USB connector was installed in the left rear hole of the bottom cabinet panel and plugged into the PC. This allows the user to connect a monitor and a keyboard physically to the PC in order to change BIOS settings (since wireless connections won't work with this PC's BIOS).

<img src="./images/External-hdmi-usb-installed.jpg" alt="Description" width="40%" height="40%">\
*External HDMI/USB port installed*

| Date ordered | Part |
|---|---|
| Feb 28, 2026 | [USB 3.0 & HDMI Male to Female AUX Dash Car Flush Mount Cable 3ft](https://www.amazon.com/dp/B073HZ4STM) |

### External LAN connector
An external LAN connector was installed in the right rear hole of the bottom cabinet panel and plugged into the PC's ethernet port. This allows the user to much higher LAN speeds when transferring files or backing up the PC.

<img src="./images/External-LAN-installed.jpg" alt="Description" width="40%" height="40%">\
*External LAN port installed*

| Date ordered | Part |
|---|---|
| Jun 21, 2026 | [RJ45 CAT6 Panel Mount Adapter Female-Female Ethernet Pass-Through Connector](https://www.amazon.com/dp/B0CPZX5B3G) |

### Wireless keyboard/trackpad
A wireless keyboard/trackpad combo is used to locally configure the PC & pinball tables as needed. It includes a USB adapter plugged into the PC.

<img src="./images/Wireless-keyboard-trackpad.png" alt="Description" width="40%" height="40%">\
*Wireless keyboard/trackpad*

| Date ordered | Part |
|---|---|
|  Mar 18, 2026 | [Logitech K400 Plus Wireless Touch TV Keyboard](https://www.amazon.com/dp/B014EUQOGK?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Wireless game controller

A wireless game controller is used to play arcade games on the pinball table. The controller's adapter is plugged into a PC USB port. To observe its properties, type **(Windows key)-R joy.cpl** and then click on **Properties**. This should show the windows joystick properties. Clicking on buttons and moving the joystick on the controller should highlight various buttons and joystick movements on the Test screen. 

<img src="./images/Wireless-game-controller.png" alt="Description" width="40%" height="40%">\
*Wireless game controller*

<img src="./images/Joystick properties.png" alt="Description" width="40%" height="40%">\
*Wireless game controller properties*

### Wireless game controller config
| Input  | Description |
|---|---|
| Stick 1 | left analog stick |
| Stick 2 | right analog stick |
| POV | dpad
| Button 1 | A |
| Button 2 | B |
| Button 3 | X |
| Button 4 | Y |
| Button 5 | LB |
| Button 6 | RB |
| Button 7 | back |
| Button 8 | start |
| Button 9 | left analog stick center pushed in |
| Button 10 | right analog stick center pushed in |
| Button 11 | left trigger |
| Button 12 | right trigger |
| Button 13 | X silver guide button |

| Date ordered | Part |
|---|---|
| Mar 18, 2026 | [AceGamer Aurora II 2.4G Wireless Bluetooth Controller for PC ](https://www.amazon.com/dp/B0FJRTNTHQ?th=1) |

### Ground strap
A flat braid cable was wrapped around the inside of the cabinet and is used to ground all of electronics and the exposed metal surfaces in case someone walked up to the cabinet and had a static discharge though an exposed metal surface.

<img src="./images/Ground-strap-installed.jpg" alt="Description" width="40%" height="40%">\
*Ground strap installed*

| Date ordered | Part |
|---|---|
| Feb 16, 2026 | [Tinned Flat Copper Braid Cable,4mm Flat Copper Braided Ground Strap Wire ](https://www.amazon.com/dp/B0CB3Z86HV?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Cabinet button labels
The under cabinet buttons were labeled on the outside front of the cabinet so the user knows which button to press. In addition, buttons themselves were labeled on the inside using 1 1/2" circular cut regular printer paper. The buttons were disassembled and the circular paper placed inside and reassembled. 

<img src="./images/Button-labels.jpg" width="40%" height="40%">

| Date ordered | Part |
|---|---|
| Mar 10, 2026 | [15 Sheet Small Letter Stickers - 1/2 Inch White Vinyl Self Adhesive Alphabet Number Stickers](https://www.amazon.com/dp/B0CYTT6JTY?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Cable management
Cables inside the cabinet were placed inside raceways to cover the cables and keep them neat.  

<img src="./images/Cable-raceway.png" width="40%" height="40%">

| Date ordered | Part |
|---|---|
| Mar 5, 2026 | [Cable Raceway 77in Wire Covers Under Desk Cable Management 5-Pack](https://www.amazon.com/dp/B08R75RMQT?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Fans
One incoming PC fan and two outgoing PC fans are used to keep the cabinet cool. The incoming fan was mounted on the bottom of the cabinet to bring in cool air and the outgoing fans were mounted on the back panel of the cabinet to exhaust hot air. The outgoing fans are daisy chained together and connected to one of the PC's fan connector.

<img src="./images/Fans.png" width="40%" height="40%">

| Date ordered | Part |
|---|---|
| Feb 21, 2026 | [CORSAIR RS120 120mm PWM Fans ](https://www.amazon.com/dp/B0D49QX74S?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| Mar 19, 2026 | [Black 2 Pack PC Fan Grill](https://www.amazon.com/dp/B0CYHB7J9H?ref=ppx_yo2ov_dt_b_fed_asin_title) |

### Playfield glass
Glass to cover the playfield was sourced from a local vendor - Miller's Glass & Glazing. It is a 43"x23-3/4" 3/16" tempered glass panel, no logo.

| Date ordered | Part |
|---|---|
| Mar 10, 2026 | Glass panel |

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

[BallerInstaller](https://www.nailbuster.com/wikipinup/doku.php?id=baller_installer) was the first software run in order to configure windows, install table emulators, PinupPopper front end and a couple of demo games. It is the software starting point.   

### DOF

*Installation folder: c:\DirectOutput\\*

Direct Output Framework (DOF) controls the various toys (buttons, solenoids, shaker, coins, LEDs, etc.) for VPX tables and is installed and configured per [CSD DOF documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/DOF/). It uses the [Online DOF config tool](https://configtool.vpuniverse.com/app/home).

[DOF Wiki](https://github.com/dekay/vpinball-wiki/wiki/DOF-%E2%80%90-The-Direct-Output-Framework)

### DOFLinx

*Installation folder: c:\DOFLinx\\*

DOFLinx controls the various toys (buttons, solenoids, shaker, coins, LEDs, etc.) for non-VPX (i.e. FuturePinball, Steams's Pinball FX, etc) tables. It was installed and configured per [CSD DOFLink documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/DOFLinx/). 

## Virtual pinball emulator apps

The root of the virtual pinball software is located in *c:\vPinball\\*. 

### Visual Pinball X emulator (VPX 10.8.0) and tables

*Installation folder: c:\vPinball\VisualPinball\\*

Mostly VPX 10.8.0 tables are used in this cabinet. They are downloaded from [VPUniverse](https://vpuniverse.com/) and [VPForums](https://www.vpforums.org/).   

### Visual Pinball X (VPX 10.8.1) emulator

*Installation folder: c:\vPinball\VPX10.8.1\\*

I am experimenting with pre-releases of the new [VPX 10.8.1 emulator](https://github.com/vpinball/vpinball) using the VPX 10.8.0 tables. The current results look good.

### Future Pinball (FP) emulator tables

*Installation folder: C:\vPinball\FuturePinball\\*

In addition, some Future Pinball tables are used in this cabinet. They are also downloaded from [VPUniverse](https://vpuniverse.com/) and [VPForums](https://www.vpforums.org/). 

### Pinball FX (Steam) emulator tables

A few Steam Pinball FX emulator based tables were bought and are used in this cabinet. They are downloaded from [Pinball FX](https://www.pinballfx.com/). The steam emulator is installed and started upon windows boot.

### Pinup Popper frontend

*Installation folder: c:\vPinball\PinUPSystem\\*

- Install/manage/remove tables and playlists, graphic front end to load and run tables

[Pinup Popper frontend](https://www.nailbuster.com/wikipinup/doku.php?id=popper_themes) is used as the frontend to allow the user to select which table to load and run. It was installed in the cabinet and setup using [Baller Installer](https://nailbuster.com/wikipinup/doku.php?id=baller_installer).

PinUpMenu.exe is the main frontend executable file for PinUP Popper. PinUpMenuSetup.exe is the configuration app to install table, create playlists, etc. Shortcuts to both of these app are placed on the desktop since the are used quite often.

#### Pinup Popper emulator scripts

These are the scripts that Pinup Popper uses to start/stop itself and various emulators.

- [Pinup Popper startup script](scripts/pinup%20popper%20startup%20script.txt)
- [Pinup Popper closing script](scripts/pinup%20popper%20closing%20script.txt)
- [Pinup Popper custom options](scripts/pinup%20popper%20custom%20options.txt)
- [Pinup Popper Future Pinball startup script](scripts/pinup%20popper%20Future%20Pinball%20startup%20script.txt)
- [Pinup Popper Future Pinball closing script](scripts/pinup%20popper%20Future%20Pinball%20close%20script.txt)
- [Pinup Popper MAME startup script](scripts/pinup%20popper%20MAME%20startup%20script.txt)
- [Pinup Popper MAME closing script](scripts/pinup%20popper%20MAME%20close%20script.txt)
- [Pinup Popper Pinball FX startup script](scripts/pinup%20popper%20Pinball%20FX%20startup%20script.txt)
- [Pinup Popper Pinball FX closing script](scripts/pinup%20popper%20Pinball%20FX%20close%20script.txt)
- [Pinup Popper Visual Pinball startup script](scripts/pinup%20popper%20Visual%20Pinball%20X%20startup%20script.txt)
- [Pinup Popper Visual Pinball closing script](scripts/pinup%20popper%20Visual%20Pinball%20X%20close%20script.txt)

#### Pinup Popper screen settings

<img src="./images/Pinup Popper screen settings.png" alt="Description" width="60%" height="60%">\

### VPin Studio

*Installation folder on cabinet: C:\vPinball\Vpin-Studio\\*

- Alternative to Pinup Popper used for installing/managing/removing tables and playlists

[VPin Studio](https://github.com/syd711/vpin-studio) is used to intelligently manage the pinball table emulators, software, associated files and settings over the LAN. It is a client/server design where the pinball cabinet has a server running in background and my main PC has the client running that talks to that server. The client is also installed on the pinball cabinet itself so that you can use it there too with the wireless keypad/trackpad. I normally use it remotely since I can do that from my office and I have a better keyboard/mouse/monitor setup there.      

It also will backup individual tables to the NAS over the LAN. This allows me to experiment with a new version of a table and, if needed, delete the table and restore it from a good backup on the NAS. It also allows me to experiment with a table to see if I want to keep it or not and if I decide not to keep it, it is backed up and I can restore it later.  

[Vpin Studio Wiki](https://github.com/syd711/vpin-studio/wiki)


## How to find and add a VPX/FP table, add Pinup Popper media, etc.

1. Find a table on [Virtual Pinball Spreadsheet](https://virtualpinballspreadsheet.github.io/games)
2. Download the table xxx.vpx file (and perhaps others). Follow the directions.
3. Download the backglass .directb2s file (I usually prefer the 3 Screen or FullDMD versions by authors such as HauntFreaks) 
4. Download the rom xxx.zip file (if the table has a rom file). Usually late '70s/80s/90s/2000s tables have ROM files/ Older EM (electromechanical) tables do not (as they didn't have a microprocessor in them.) Also newer, original tables (not a recreation of a physical table) usually don't have a ROM either. Leave the ROM file in .zip form.
5. Run the VPin Studio client app on the your PC and connect to the cabinet by IP address and open the main Tables list window. Or use the cabinet PC by exiting to windows and running the VPin Studio client app using the wireless keyboard.
6. 
7. Drag the xxx.vpx, xxx.directb2s and rom.zip files to the Table list. VPin studio will ask if you want to add a new table. Select yes and fill out any extra data as needed.    
8.  Use VPin Studio app on your PC (or cabinet PC) to add Pinup Popper Table Media. I usually just add a Wheel icon, Playfield video, Backglass video, Apron/FullDMD graphic or video and Help graphic or video.

## How playlists are created/managed/deleted, etc.

Playlists are like a folder of games in the frontend UI that can be created and managed by either VPinStudio or Pinup Popper config app. Refer to their documentation for managing the playlists. This allows playlists to contain Kid's tables or Sports tables, etc. 

## How to select, add coins, start, play and exit a table

### Turning on the pinball machine
---

<img src="images/Power-switch.jpg" width="200" alt="First Image"> <img src="images/Power-button.jpg" width="200" alt="Second Image"> <img src="images/Pinup-popper-all-tables.png" alt="Third Image"> 

1. Make sure the back power switch is turned on 
2. Use the front Power button (located at the far right under the front of the cabinet) to turn on the machine.
3. Wait until the Pinup Popper menu is showing 

### Select a table
---

<img src="./images/Pinup-popper-controls.png" alt="Description" width="60%" height="60%">\
*PinupPopper controls*

1. Start Pinup Popper by booting up the cabinet PC (Pinup Popper autostarts after Windows boots) or double-clicking the ***PinUP Popper FrontEnd*** shortcut from the Windows desktop.  
2. Use the left/right flipper buttons to move left/right in the Pinup Popper scrolling menu.
3. Use the right **back** flipper button to select (or go into) an icon
4. Use the left **back** flipper button to exit (or go out of) a selection
5. Once you have scrolled to the table you want to play, use the right back (magna-save) flipper button to select it and then again to play it. Or you can use the Start button to start it. 

### Start a table
---

<img src="images/Coin-reject-buttons.jpg" width="200" alt="First Image"> <img src="images/Start-button.jpg" width="200" alt="Second Image">

1. Once the table is loaded, use the Coin Reject buttons to "Insert" coins. Both buttons work, but the right one simulates a single coin and always works. The left one simulates inserting a dollar/multiple coins which some games support and others do not (especially the older tables). You should hear the sound of coins dropping into the machine to determine if it is working or not.  
2. Use the Start button to start playing the table 

### Play a table
---

<img src="images/Plunger-pull.jpg" width="200" alt="First Image"> <img src="images/Fire-button.jpg" width="200" alt="Second Image">

1. Once a pinball table has been loaded, either pull back and release the physical plunger or, if the Fire button is lit or blinking, hit the Fire button to launch the ball. It depends on the table. 
2. Use the left/right flipper buttons to hit the ball. 
3. Most newer tables have 3 balls/game. Older tables ('70s and earlier) have 5 balls/game.  
4. Once the game is over you will need to use the Start button again to restart it. If you are out of credits, you will need to "insert" more coins and hit the Start button again.

### Exit a table
---

<img src="images/Exit-button.jpg" width="200" alt="First Image"> 

1. Once the game is over, you can use the Exit button (located at the far left under the front of the cabinet) to exit the game. This will take you back to the Pinup Popper scroll bar. 
2. Repeat selecting and playing another table.

### Exit back to windows (usually not needed)
---
<img src="images/Exit-button.jpg" width="200" alt="First Image"> <img src="images//System_exit.png" width="200" alt="First Image"> 

1. Once you are back to the scrolling Pinup Popper menu, use the right under cabinet Exit button, then the right magna-save twice to go back to windows. 

## Steam
Steam (Pinball FX) tables are configured using the [CSD documentation](https://pinball-docs.clevelandsoftwaredesign.com/docs/PinOne/Configuring/steam). Pinball FX tables are purchased and downloaded from [here](https://store.steampowered.com/app/2328760/Pinball_FX/). I bought a few just to try them out. There is a shortcut to this app on the desktop.

## Startup folder
These apps were installed and they are launched from the Windows startup folder. 

### PinVol
[PinVol](http://mjrnet.org/pinscape/PinVol.html) is a windows background app that adjusts the volume of a table when it starts up (since tables tend to have different volume levels). It allows you to use the CSD buttons at the bottom of the cabinet to adjust the volume of a table and it will remember it for the next time the table is run. 

### JoyToKey
[JoyToKey](https://joytokey.net/en/) is a windows background app that is used to enhance the CSD button usage by doing - 

| Button | Context | Action |
|---|---|---|
| Start | Windows desktop | Start the Pinup Popper frontend |
| Pause | VPX emulator | Pause the table (enter the 'P' key) |
| ??? | Pinball FX (Steam) emulator | ??? |

### PinAffinity
[PinAffinity](http://mjrnet.org/pinscape/PinAffinity.html) is a windows background app that adjusts the Windows process affinity executables to give the pinball emulators higher priority (and other processes lower) hence making the emulator run smoother. 

### FanControl
[FanControl](https://getfancontrol.com/) is a windows background app that adjusts the fan speed better than the PC BIOS does, thus producing less fan noise while keeping the electronics cooler. 

## Misc software

### RustDesk
[RustDesk](https://rustdesk.com/) is used as a remote desktop app so that I can use my PC to remotely control the cabinet (in Windows, in an emulator, etc.). It can remotely show all three displays (playfield, backglass, DMD). 

### HDP PC Agent

[HDP PC Agent](https://www.qnap.com/en-us/software/hdp-pc-agent) is a background app that the QNAP NAS uses for backup. The entire cabinet software (including Windows) is periodically backed up with this app in case of catastrophic storage failure. There is a shortcut to this app on the desktop.

### NVidia control panel 3d settings

Individual pinball emulator Windows executables were configured to modify various NVidia GPU control panel 3D settings different than the global settings. 

| Emulator app | Setting | Value |
|---|---|---|
| vpinballx64.exe (10.8.0) | Low Latency Mode | Ultra |
|  | Max Frame Rate | Off |
|  | Power management modeMax | Prefer maximum performance |
|  | Vertical sync | Use the 3D application setting |
| vpinballx_bgfx64.exe (10.8.1) | Low Latency Mode | Ultra |
|  | Max Frame Rate | Off |
|  | Power management modeMax | Prefer maximum performance |
|  | Vertical sync | Use the 3D application setting |

### MAME (v0.287)

*Installation folder on cabinet: C:\MAME\\*

[MAME](https://www.mamedev.org/) is a multi-arcade game emulator used to run old video arcade games. The games are played using the [AceGamer Aurora II 2.4G Wireless Bluetooth Controller for PC](https://www.amazon.com/dp/B0FJRTNTHQ?th=1) joystick controller. The arcade monitor is configured the same as the pinball table's such that it is turned 90 degrees (portrait mode). PinupPopper is configured to have a playlist for running installed arcade games. 

### vPinBackManager

*Installation folder on cabinet: C:\vPinball\vPinBackupManager\\*

[vPinBackupManager](https://vpuniverse.com/files/file/19155-virtual-pinball-backup-manager-vpbm-v21/) is used for backing up pinball tables. Since VPinStudio already backs up VPX tables to the NAS and it doesn't backup FuturePinball (FP) tables, vPinBackupManager is only for backing up FP tables.

## Windows desktop apps & scripts
- _Restore ScreenRes.bat_, _ScreenRes.txt_: restore the screenres.txt file so the monitors are displaying the correct screens again
- _Restore VPinballX.ini.bat_, _VPinballX.ini_": restore the VPinballX.ini file for experimental VPX 10.8/1 emulator

## Windows startup apps & scripts
These apps and scripts are started in background by Windows when it boots up.

### Startup apps
- DOFLinx.exe
- JoyToKey.exe
- PinAffinity.exe
- PinUpPopper.exe
- PinVol.exe

### Startup scripts
- [vpx-monitor-config.bat](scripts/vpx-monitor-config.bat)

# Notes/fixes

Tables being displayed on wrong screens
---
Use pixel position instead of device id position

1) Run B2S_ScreenResIdentifier.exe
2) Select 3 monitor
3) 100% full screen, set coordinates

Performance
---
Run Backglass as .EXE solves most problems

VPX 10.8.1 DMD fix
---
1) Display Settings > ScoreViewVPX 10.8.1 Display > B2S Backglass & FullDMD = 1  (global setting) 
2) Plugin Settings > B2S > Modify Backglass Edit xxx.directb2s >  Add DMD Display > Show on ScoreView, then click on Detect Position (per table setting)
3) Save (with F12 menu)

Fire button not working in tables, but CSD config app sees it
---
In VPinballX.ini, set JoyPlungerKey = 9

### Common Default Keyboard Assignments (VPX/Pinscape)
| Pinball | Keyboard |
|---|---|
| Left Flipper | Left Shift |
| Right Flipper | Right Shift |
| Left Nudge | Z |
| Right Nudge | / |
| Center Nudge | Spacebar |
| Plunger/Ball Launch | Enter |
| Start Game | 1 |
| Insert Coin | 3 or 5 |
| Exit | Esc |
| Left MagnaSave | Left Control |
| Right MagnaSave | Right Control |
| Service Menu (Inside Coin Door) | 7, 8, 9, 0 |
