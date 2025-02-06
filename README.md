<h2>This is a modificed Voron build using Trist0ne initial configurations but with less complexity. This uses the T500 stock breakout board and will mostly rely on Configuration Changes and Soldering wires/Changing ends for your stealthburner to fit.</h2>

![image](https://github.com/jranger615/T500xVORON/blob/main/photos/T500Voron.jpg)


## Things to Buy
* If you cant Print ABS or Dont want to print your StealthBurner - [https://www.etsy.com](https://www.etsy.com/search?q=voron+stealthburner+clockwork+2&ref=auto-1&as_prefix=voron+s&dd_referrer=https%3A%2F%2Fwww.etsy.com%2F) and search for Voron StealthBurner. Make sure you get CW2 setup
You will have to talk to the seller and ask him to print all the seperate parts (Board Spacer, Cable Door in STLS, Cable Chain stuff,)

* Optionally you can also use craftcloud.com to have things like the Bed Spacers and T500 Adapter printed in ABS. My Prefered Vendor is 3D Pros 

* BMG Hardened Extruder Parts:
https://west3d.com/products/bmg-components-kit-by-trianglelab?_pos=3&_psq=bm&_ss=e&_v=1.0

* Pancake Motor:
https://west3d.com/products/ldo-nema14-36mm-pancake-stepper-motor-ldo-36sth20-1004ahg

* OPTIONAL Bambu Labs Hotend (Choose HotEnd of Your Choice to replace this) :
https://us.store.bambulab.com/products/bambu-hotend-x1c?variant=40475104313480&currency=USD

* OPTIONAL If Using the Recommended Filament Sensor CW2 you need:
  * [5MM Ball](https://www.amazon.com/dp/B0B5P9H3S2/)
  * [MicroSwitch](https://www.amazon.com/gp/product/B0B3DFJB6P)

* Hardware/FANS/Extruder/Motor Kit: (Use instead of Separate Bolts) (Based on Reviews i dont trust the LEDs or Extruder Parts)
https://a.co/d/hCeWtaP

* 1 Pc RGBW Mini Button PCB LED: (Will need wire extensions to MCU)
https://www.amazon.com/dp/B075L8Y8V1/?coliid=I1FMQTNQJ0O444&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_JF21D1ZD5WGFT2YJCZDS

* LED Connectors for MCU Conenctions https://www.amazon.com/gp/product/B07H1WDN3R/
 
* CHAOTICLAB Voron Tap V2.0:
https://www.amazon.com/dp/B0CJV1QK1N/?coliid=I20A3SCCWK9XCS&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_B5HRK3VTWEEB0CD1SH8E

* 3D Printing Soldering Iron
https://www.amazon.com/dp/B0CN6LQXYD/?coliid=I1IMXZO5S24SAN&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_B5HRK3VTWEEB0CD1SH8E

* Printing Brass Nuts:
https://www.amazon.com/dp/B09MCWTBCC/?coliid=I34NRO9I6WL8EN&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_B5HRK3VTWEEB0CD1SH8E

  * If you use a Bambu Labs hotend, [this](https://www.printables.com/model/588316-stealthburner-bambu-lab-x1cx1-hotend-mount/files) adapter for the StealthBurner works well!
  * A few extra parts you will need:
  * 8x M3 5x4mm heat set inserts (same ones that VORONs use)
  * 8x M4x40mmm Socket Heat Cap Screws (Or whatever style M4x40mm screws you would like, SHCS's are just the easiest to tighten during the build)
  * A small length of PTFE tubing for the Stealthburner hotend mount


## Things to Print
**THESE MUST ALL BE PRINTED FROM ABS OR ASA. THEY ARE DESIGNED FOR ABS. OTHER MATERIALS ARE NOT SUITABLE EITHER DUE TO THEIR TEMPERATURE RESISTANCE OR STRUCTURE CREEP OVER TIME; YOU HAVE BEEN WARNED**
* [1x Complete Voron Stealthburner Assembly](https://github.com/VoronDesign/Voron-Stealthburner/tree/main)
  * Optionally [but highly reccomended!] use the inline filament runout sensor located [here](https://www.printables.com/model/292186-stealthburner-clockwork-2-filament-sensor/files). This replaces the main_body of the CW2 extruder.
  *  Optionally Bambu Labs hotend, [this](https://www.printables.com/model/322091-voron-stealthburner-printhead-for-bambu-x1cx1-hote) adapter for the StealthBurner works well!
  * Ensure you use the [Custom Cable_Cover](https://github.com/jranger615/T500xVORON/blob/main/STL/cable_door_for_T500.stl)
  * [Toolhead T500 spacer](https://github.com/jranger615/T500xVORON/blob/main/STL/T500-Board-Adapter.stl.stl)(Requires 1 heat insert)
   * You do not need to print the gantry mount or TAP mount; the extruder and toolhead cover screw directly into the CNC TAP
* [T500 TAP Adapter](https://github.com/jranger615/T500xVORON/blob/main/STL/T500%20TAP%20Adapter.stl)
* [2x Bed Spacers](https://github.com/jranger615/T500xVORON/blob/main/STL/Bed%20Spacer%20T500%20v3.stl). Ensure these print perfectly flat with no warping, or it will throw off your bed level!
* Optional for Cable Management/Ribbon Cable Retainer [3 Hole Cable Bridge](https://github.com/VoronDesign/Voron-Stealthburner/blob/main/STLs/Clockwork2/chain_anchor_3hole_SW.stl) & [Retainer](https://github.com/jranger615/T500xVORON/blob/main/STL/T500%20Ribbon%20Cable%20Retainer%20%26%20Cable%20Connector.stl) (Retainer requires 2 heat inserts to attach cable chain)


Print Settings:
* Layer height: 0.2mm
* Extrusion width: 0.4mm, forced
* Infill percentage: 40%
* Infill type: grid, gyroid, honeycomb, triangle, or cubic
* Wall count: 4
* Solid top/bottom layers: 5
* Supports: NONE

## The Build
You can do the following sections in any order, they are just listed in the order I did them. **Some of the steps will be linked to other guides** for the non-T500 conversion specific parts as they cover them more in depth, and there's no need to reinvent the wheel.

### Prerequisites
* Assemble the VORON Stealthburner
  * Follow the build guide located [here](https://github.com/VoronDesign/Voron-Stealthburner/tree/main/Manual). This is a large step, and your toolhead will only function as well as you assemble it, so take your time.
  * this video is also helpful https://youtu.be/dOyYvnehLaI?si=HIRMF422sOZMZnhB

    
### Mounting the Toolhead
1. Start by inserting {4x} M3 5x4mm heat set inserts into the adapter plate. Take care to ensure they are perfectly level with the surface of the plastic.
![image](https://github.com/jranger615/T500xVORON/blob/main/photos/20250123_115149.jpg)


2. Unclip the stock toolhead umbilical and drag chain mount, and move them out of the way. Unmount the stock T500 toolhead and drag chain plate. There are 4 screws around the outside of the plastic casing (keep these!), several screws holding the drag chain plate to the rail. You should be left with a metal rectangular sliding rail.
![image](https://github.com/jranger615/T500xVORON/blob/main/photos/293424021-e83a2e70-2edc-46f8-97bc-da69bf9ecbf4.jpeg)


3. Using the 4 casing screws from the stock toolhead, attach the Adapter Plate to the rectangular sliding rail. Check to ensure the rail still slides back and forth. 
![image](https://github.com/jranger615/T500xVORON/blob/main/photos/20250123_115523.jpg)


4. Attach the ChaoticLabs CNC TAP to the Adapter Plate
   * The attachment process is the same as the one located in the [CNC TAP build guide](https://github.com/Chaoticlab/CNC-Tap-for-Voron/blob/master/Manual/CNC_Voron_Tap_Build_Guide.pdf)
   * 
![image](https://github.com/jranger615/T500xVORON/blob/main/photos/20250123_115725.jpg)

5. Attach the Stealthburner assembly to the CNC TAP. Check to make sure the whole assembly can slide up and down (the 'TAP' function)
   * The attachment process for the Stealthburner is the same as the one located in the [CNC TAP build guide](https://github.com/Chaoticlab/CNC-Tap-for-Voron/blob/master/Manual/CNC_Voron_Tap_V2_Build_Guide_20231013.pdf)
 
6. Check clearences, and appreciate how nice the Stealthburner looks mounted on the T500

#### X Endstop Move
**IF YOU DONT DO THIS, YOUR X Will not have an endstop setup and will crash**
 * The X End Stop is on the back of the X Axis. Remove the Screw and move it to the lower front bolt that holds the X Axis cover. (THis will requie a slightly logner m3 bolt)
 * Using washers, Center the X End Stop with the new Carriage assembly.
 * WIth the Machine Powered on, you should see the red light Turn off as the plastic extension passes into it.
 *![image](https://github.com/jranger615/T500xVORON/blob/main/photos/X-End%20Stop.jpg?raw=true)



### Raising the Bed
The stock T500 gantry and bed are mounted in such a way that the gantry cannot drop low enough to touch the nozzle to the bed. Obviously, this is problematic. Because of the way the gantry is designed, there is no easy way to gracefully drop the toolhead low enough; thus, we have to go the other direction and raise the bed!
* "Wont I lose Z height??"
  * Nope! In it's stock form, the T500 Z rails can raise the nozzle up to 550mm. With these spacers in place, you will still have 520mm of Z clearance (though it will still be software limited to 500mm), so there is no lost Z build height!
* "Wont these spacers melt so close to the bed? Are they strong enough?"
  * Nope! They're far enough from the bed that they are well within the longterm operating temperature limit of ABS. ABS also does not stress creep over time, and should remain durable for the life of the printer
 
1. Remove the print surface, and remove the 8x M4 socket head screws using the access holes
   * ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/ddf7ffba-6176-486a-8fc0-d5f8d951e9f6)

   * If you have a difficult time getting a tool to fit in those holes, you can unbolt every M4 countersunk screw and remove the headbed entirely.
   * If you remove the bed from the bed frame, remove the screws holding the bed drag chain to the bed frame
   * ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/622494c6-0444-4c62-af16-58f4166bf830)


2. Carefully raise the bed frame, and align the bed spacers to the long rectangular rails
   * Be very careful not to damage the heatbed wiring!
![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/49a9cc11-a071-44c6-a119-31e2612c8e6c)

   * Depending on how much your ABS print shrunk, you may need to slightly drill out the holes in the printed bed spacers; you'll never get them properly aligned unless the screws can slide through the spacers with only light resistance
![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/a1e1170f-3aea-4827-b9fe-b631b5aab490)


3. Using 8x M4x40mm screws, bolt the bed frame to the Y axis rails through the spacers. Ensure everything is very tight and does not have any play; you dont want your bed level changing or your bed flying off its rails!
![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/e2aad75b-baf5-4722-8da7-eb1707f60aba)

4. If you removed it in step 1, reattach the drag chain to the bed frame

5. Check to ensure the bed is able to slide **all** the way back and forth across its rails. If you did not use M4x40mm screws to attach the spacers, they may stick out from the rails and hit the Y Stepper drivers.

### Mounting PCB
* Mount your PCB Spacer using a m3x8 to the inner most heat insert. You may want to use a m3 bolt at the top to hold it in palce before you tighten it down.
  * ![image](https://github.com/jranger615/T500xVORON/blob/main/photos/PCB_Spacer.jpg)
* Use a small m3 bolt to mount the board to the spacer. Make sure its not too long or it may hit the gear
* Use a m3x10 (May be 12) to mount the top location of the board
  * ![image](https://github.com/jranger615/T500xVORON/blob/main/photos/Board-Mount.jpg)




### Wiring Wiring Wiring
Printer should be **fully powered off and unplugged** for the next few steps.
* I cut and soldered all connectors from the original hotend. I believe these are MINI JST Connectors but i am unsure so i just used what i had.

# Stock Breakout Board Connections
* ![image](https://github.com/jranger615/T500xVORON/blob/main/photos/Breakout%20Board.jpg)


# Motor Wiring
 * Cut your Stock Wiring Harness and the LDO Wiring Harness from each Motor
 * Match LDO Wires to Stock Wire Harness Below
   * A2 Blue > Blue 1B
   * A1 Yellow > RED 1A
   * B1 Green > Green 2B
   * B2 Red > Black 2B
     
# TAP Wiring
For Reference ONLY: Pull Up Indicator and Reverse Polarity indicator were needed for the TAP ^!PE8

 * Cut your Sensor Wire off the TAP and Off the Thermal Sensor
 * Match TAP Wires to Stock Wiring
   * Brown Wire > Red Wire
   * Blue Wire > Black Wire
   * Black Wire > Yellow Wire

  
 # RunOut Sensor
 For Reference ONLY: Reverse Polarity was needed for this function !PE9
 
 * The Runout sensor will only use 2 connections
   * Outside Connections(Button Side) To the Left Most Pin on the Breakout Board
   * Middle Connections to Ground or Middle Pin on the Breakout Board
 
 # FANS
 * Red/Black wires will all match for 24v Fans
 * Heatsink Fan is the middle Fan connector on the bottom 3
 * Cooling Fan can attach to any of the other 3 connectors

 # HotEnd
  * These wires you cant really wire wrong as long as you plug the right connection in.
  * The thermistor is usually the bare copper looking wire comming off the Hot End
  * Heat Cartidge is usually a thicker set of wires with insulation

# LED Wiring
 * You will need to access the mother board and run a long set of 3 wires to the mainboard.
 * Feed all the wires through the cable chain and amtch them to the length of the ribbon cable. I zipped tied them along it after exiting the cable chain,
 * See the below diagram to connect the wires
   * ![image](https://github.com/jranger615/T500xVORON/blob/main/photos/pinouts.jpg)
   * Connect the Middle DataWire to PB12 (Usually Blue),
   * Connect the 2 outside connections to the 2 bottom pins 5v and Ground as it shows on the LEDS.
  
# Ribbon Cable/Retainer
  * Attach the ribbon Cable to the breakout board
  * If you printed the retainer you can now install it to keep the ribbon cable from pulling free
  * Attach Cable Chain to Retainer. 

### Software Configuration

#### Initial Startup
1. SSH into your printer. The username is **mks**, and the password is **makerbase**. Install KAMP on your printer, located [here](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)
2. Access your printers web-ui. In the machine tab, delete ALL the follwing if present: filament.cfg, KAMP_Settings.cfg,macros.cfg, mainsail.cfg,moonraker.conf,printer.cfg,start.cfg,stealthburner_leds.cfg,temperature_led.cfg, and toolhead.cfg
3. Download the Klipper Configurations folder from this Github ([here](https://github.com/jranger615/T500xVORON/tree/main/configs)), and upload them ALL to the printer's config section.
* ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/258b8037-95a2-4bea-b8ea-d8ef3a9e6b04)
3. Configure the annotated sections of **toolboard.cfg**. Things like Nozzle Size, PID Tunning, Extruder Sensor Typer, and Rotation Distance need to be adjusted for your machine.
4. Save and click 'firmware restart'; resolve any errors that Klipper may throw, if any (the error message will tell you what the configuration issue is).

#### Z Offset Configuration
Update your Z offset
* Remember, with Tap, your nozzle IS the probe. You'll need to manually calibrate the probe's Z offset by using PROBE_CALIBRATE and your chosen leveling method (I use a sheet of paper)

### Final Checks
1. Ensure that your printer can reliably home X, Y, and Z.
2. Test that your Extruder, Hotend, Hotend Fan, Part Cooling Fan, and [optionally] the runout sensor all work as expected.
3. PID Calibrate your Hotend following [this guide](https://www.obico.io/blog/klipper-pid-tuning/)
4. Follow the [Ellis3dp print tuning guide](https://ellis3dp.com/Print-Tuning-Guide/articles/extruder_calibration.html) to dial in your Stealthburner
5. Configure Input Shaping on both X and Y
* You can reference [this guide](https://www.klipper3d.org/Measuring_Resonances.html#bed-slinger-printers) for help
* I use the SHAPER_CALIBRATE macro for automatic calibration. It will measure both X and Y sequentially and apply the best settings automatically. 

6. Retune your Pressure Advance
* Follow [this guide](https://github.com/SoftFever/OrcaSlicer/wiki/Calibration) from the Orca Slicer wiki. You shold set this number in the Orca Slicer filament profile settings, rather than setting it in the Klipper configs. It will be different for every filament and between brands. 
7. Pat yourself on the back for a job well done! Edit your slicer settings as shown below, and then do a test print!

### Slicer Configuration
1. Edit your printer settings "Machine G-code" tab as follows:
* PRINT_START EXTRUDER=[nozzle_temperature_initial_layer] BED=[bed_temperature_initial_layer_single] CHAMBER=[chamber_temperature]
* PRINT_END
* ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/38245c9d-8e7e-4014-8cb4-d94785227172)
3. In the 'Others' tab, enable
* Label Objects
* Exclude Objects

### Troubleshooting Notes
There are two errors you may see in your console when starting a print:
1. Unknown command:"SAVE_LAST_FILE"
2. Error evaluating 'gcode_macro PRINT_START:gcode': jinja2.exceptions.UndefinedError: 'dict object' has no attribute 'BED'
These are caused by the non-standard version of klipperscreen that comes built into the T500, and makes calls to incorrectly labeled markers. **Thankfully, they don't actually impede the printing, so you can ignore them!** You can resolve this by installing the standard version of KlipperScreen using [KIAUH](https://github.com/dw-0/kiauh), which comes built into the T500

