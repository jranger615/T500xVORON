<h2>This is a modificed Voron build using Trist0ne initial configurations but with less complexity. This uses the T500 stock breakout board and will mostly rely on Configuration Changes and Soldering wires/Changing ends for your stealthburner to fit.</h2>


## Things to Buy
* If you cant Print ABS or Dont want to print your StealthBurner - https://www.etsy.com/listing/1220054510/voron-stealthburner-clockwork-2
You will have to talk to the guy and ask him to print all the seperate parts (Board Spacer, PCB Specific PCB Door, Cable Chain stuff,)

* Optionally you can also use craftcloud.com to have things like the Bed Spacers and T500 Adapter printed in ABS. My Prefered Vendor is 3D Pros 

* BMG Hardened Extruder Parts:
https://west3d.com/products/bmg-components-kit-by-trianglelab?_pos=3&_psq=bm&_ss=e&_v=1.0

* Pancake Motor:
https://west3d.com/products/ldo-nema14-36mm-pancake-stepper-motor-ldo-36sth20-1004ahg

* Bambu Labs Hotend:
https://us.store.bambulab.com/products/complete-hotend-assembly-x1-series?variant=40475104280712

* Hardware/FANS/Extruder/Motor Kit: (Use instead of Separate Bolts) (Based on Reviews i dont trust the LEDs or Extruder Parts)
https://a.co/d/hCeWtaP

* 1 Pc RGBW Mini Button PCB LED: (Will need wire extensions to MCU)
https://www.amazon.com/dp/B075L8Y8V1/?coliid=I1FMQTNQJ0O444&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_JF21D1ZD5WGFT2YJCZDS

* CHAOTICLAB Voron Tap V2.0:
https://www.amazon.com/dp/B0CJV1QK1N/?coliid=I20A3SCCWK9XCS&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_B5HRK3VTWEEB0CD1SH8E

* 3D Printing Soldering Iron
https://www.amazon.com/dp/B0CN6LQXYD/?coliid=I1IMXZO5S24SAN&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_B5HRK3VTWEEB0CD1SH8E

* Printing Brass Nuts:
https://www.amazon.com/dp/B09MCWTBCC/?coliid=I34NRO9I6WL8EN&colid=3IIJXA0HSD0NW&psc=1&ref_=cm_sw_r_cp_ud_lstpd_B5HRK3VTWEEB0CD1SH8E

  * If you use a Bambu Labs hotend, [this](https://www.printables.com/model/322091-voron-stealthburner-printhead-for-bambu-x1cx1-hote) adapter for the StealthBurner works well!
  * A few extra parts you will need:
  * 4x M3 5x4mm heat set inserts (same ones that VORONs use)
  * 8x M4x40mmm Socket Heat Cap Screws (Or whatever style M4x40mm screws you would like, SHCS's are just the easiest to tighten during the build)
  * A small length of PTFE tubing for the Stealthburner hotend mount


## Things to Print
**THESE MUST ALL BE PRINTED FROM ABS OR ASA. THEY ARE DESIGNED FOR ABS. OTHER MATERIALS ARE NOT SUITABLE EITHER DUE TO THEIR TEMPERATURE RESISTANCE OR STRUCTURE CREEP OVER TIME; YOU HAVE BEEN WARNED**
* [1x Complete Voron Stealthburner Assembly](https://github.com/VoronDesign/Voron-Stealthburner/tree/main)
  * Optionally [but highly reccomended!] use the inline filament runout sensor located [here](https://www.printables.com/model/292186-stealthburner-clockwork-2-filament-sensor/files). This replaces the main_body of the CW2 extruder.
  *  Optionally Bambu Labs hotend, [this](https://www.printables.com/model/322091-voron-stealthburner-printhead-for-bambu-x1cx1-hote) adapter for the StealthBurner works well!
  * Ensure you use the Cable_Cover_for_PCB and the toolhead T500 spacer!
  * You do not need to print the gantry mount or TAP mount; the extruder and toolhead cover screw directly into the CNC TAP
* [2x Bed Spacers](https://github.com/Trist0ne/T500xVORON/blob/main/STL/Bed%20Spacer%20T500%20v3.stl). Ensure these print perfectly flat with no warping, or it will throw off your bed level!
* [1x CW2 Cable Bridge](https://github.com/bigtreetech/EBB/blob/master/EBB%20SB2240_2209%20CAN/STL/CW2%20Cable%20Bridge.STL)


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

### Mounting the Toolhead
1. Start by inserting {4x} M3 5x4mm heat set inserts into the adapter plate. Take care to ensure they are perfectly level with the surface of the plastic.
![image](https://github.com/jranger615/T500xVORON/blob/main/photos/20250123_115149.jpg)
(Ignore the very bottom two holes in the picture; they didn't make it into the final design)

3. Unclip the stock toolhead umbilical and drag chain mount, and move them out of the way. Unmount the stock T500 toolhead and drag chain plate. There are 4 screws around the outside of the plastic casing (keep these!), several screws holding the drag chain plate to the rail. You should be left with a metal rectangular sliding rail.
![image](https://github.com/jranger615/T500xVORON/blob/main/photos/20250123_115523.jpg)


4. Using the 4 casing screws from the stock toolhead, attach the Adapter Plate to the rectangular sliding rail. Check to ensure the rail still slides back and forth. 
![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/f67d71d7-87a8-44ed-b62f-64451ad39fc4)


5. Attach the ChaoticLabs CNC TAP to the Adapter Plate
   * The attachment process is the same as the one located in the [CNC TAP build guide](https://github.com/Chaoticlab/CNC-Tap-for-Voron/blob/master/Manual/CNC_Voron_Tap_V2_Build_Guide_20231013.pdf)

6. Attach the Stealthburner assembly to the CNC TAP. Check to make sure the whole assembly can slide up and down (the 'TAP' function)
   * The attachment process for the Stealthburner is the same as the one located in the [CNC TAP build guide](https://github.com/Chaoticlab/CNC-Tap-for-Voron/blob/master/Manual/CNC_Voron_Tap_V2_Build_Guide_20231013.pdf)
   * Ensure you attach the cable bridge shown at the end of the build guide. We will not use the steel wire, but the bridge will provide strain relief and stability to the CANBUS cable port.
![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/4ad1ae06-10eb-4e5d-9737-56c6c2a6584a)

 
7. Check clearences, and appreciate how nice the Stealthburner looks mounted on the T500

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

### Wiring Wiring Wiring
Thankfully for the most part we are SIMPLIFYING the wiring rather than making it more complicated. It should go without saying that your printer should be **fully powered off and unplugged** for the next few steps especially.
# Motor Wiring
 * Cut your Stock Wiring Harness and the LDO Wiring Harness from each Motor
 * Match LDO Wires to Stock Wire Harness Below
   * Blue to Blue
   * Yellow to RED
   * Green to Green
   * Red to Black



#### LED Wiring
* ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/6f1cea17-c823-405f-b56b-fb6b61758521)


### Software Configuration

#### Initial Startup
1. SSH into your printer. The username is **mks**, and the password is **makerbase**. Install KAMP on your printer, located [here](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)
2. Access your printers web-ui. In the machine tab, delete ALL the config files.
3. Download the Klipper Configurations folder from this Github ([here](https://github.com/Trist0ne/T500xVORON/tree/main/Klipper%20Configurations)), and upload them ALL to the printer's config section.
* ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/258b8037-95a2-4bea-b8ea-d8ef3a9e6b04)
3. Configure the annotated sections of **printer.cfg**, **toolboard.cfg**, and **u2c.cfg**. You will need to fill in the canbus_uuid sections to to tell your printer the CAN addresses of your U2C and SB2209, as well as configuring your sensorless homing (info below)
4. Save and click 'firmware restart'; resolve any errors that Klipper may throw, if any (the error message will tell you what the configuration issue is).

#### Z Endstop Check
**DO THIS BEFORE ATTEMPTING TO HOME THE PRINTER**
1. Once Klipper has successfully loaded and can interface with the U2C and SB2209, navigate to the machine page of the web UI and press 'sync endstops'
2. Endstop Z should be 'OPEN'
3. By hand, move the toolhead up to the top of it's travel to trigger the CNC TAP sensor. Hold it in place and click the 'sync enstops' button. Endstop Z should now be marked as 'CLOSED'
4. Additionally, there should be a blue light on the rear of the TAP sensor that turns red when triggered. If this doesn't happen, you've either wired the sensor wrong or it is faulty.

#### Sensorless Homing Configuration
**DO THIS BEFORE ATTEMPTING TO HOME THE PRINTER**
1. Follow the guide located [here](https://docs.vorondesign.com/community/howto/clee/sensorless_xy_homing.html) to calibrate the sensorless homing.
* The default configurations are made to work with sensorless homing, and are largely preconfigured. You can start from "Finding the right StallGuard threshold". You do not need to add sensorless homing macros, I built them in. Ensure that your sensitivity numbers are high enough that you do not damage the printer, but low enough that the machine is consistently able to home itself.

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
* Your X axis now has a built in accelerometer. You will still need to plug in the included accelerometer and mount it on the Y axis, the same way you would do on the stock T500.
* I use the SHAPER_CALIBRATE macro for automatic calibration. It will measure both X and Y sequentially and apply the best settings automatically. 

6. Retune your Pressure Advance
* Follow [this guide](https://github.com/SoftFever/OrcaSlicer/wiki/Calibration) from the Orca Slicer wiki. You shold set this number in the Orca Slicer filament profile settings, rather than setting it in the Klipper configs. It will be different for every filament and between brands. 
7. Pat yourself on the back for a job well done! Edit your slicer settings as shown below, and then do a test print!

### Slicer Configuration
1. Edit your printer settings "Machine G-code" tab as follows:
* PRINT_START EXTRUDER=[nozzle_temperature_initial_layer] BED=[bed_temperature_initial_layer_single] CHAMBER=[chamber_temperature]
* PRINT_END
* ![image](https://github.com/Trist0ne/T500xVORON/assets/41755299/38245c9d-8e7e-4014-8cb4-d94785227172)
2. In the 'Quality' tab, enable Arc Fitting
3. In the 'Others' tab, enable
* Label Objects
* Exclude Objects

### Troubleshooting Notes
There are two errors you may see in your console when starting a print:
1. Unknown command:"SAVE_LAST_FILE"
2. Error evaluating 'gcode_macro PRINT_START:gcode': jinja2.exceptions.UndefinedError: 'dict object' has no attribute 'BED'
These are caused by the non-standard version of klipperscreen that comes built into the T500, and makes calls to incorrectly labeled markers. **Thankfully, they don't actually impede the printing, so you can ignore them!** You can resolve this by installing the standard version of KlipperScreen using [KIAUH](https://github.com/dw-0/kiauh), which comes built into the T500

