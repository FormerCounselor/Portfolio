# 3D Printer Primer

This topic explains the basics of 3D printing, it is for those unfamiliar with the field.

### General Printer Terms

The type of 3D printer that will best suit your needs depends on the model being made. Models, commonly called prints, are the object that the printer creates. The terms model and print may be used interchangeably in the document.

Printers use a program called a slicer. A slicer program takes the print, converts it into hundreds of tiny layers, and creates one of two types of instruction files that the printer can understand. The height of those layers is dependent on the resolution of the printer.

Resolution is just like it is in pictures and video, only there is an added third dimension. Instead of pixels, resolution is typically measured in micrometers (microns). One millimeter contains 1000 microns. 

The Z resolution is the layer height, but think of it as just the height. The XY resolution determines how small details on the print can be, and XY can be compared to length and width. 

A model is constructed on a build plate. A build plate is a flat surface, made with durable material, the dimensions of which represent the printer’s build volume. The build volume also includes the Z, or vertical dimension, which is unique to the printer. Build volumes are measured in millimeters. The build plate sits on top of the printer’s bed. The bed is an adjustable platform that moves during construction. 
 
Supports are used by both types of printers. Supports are just what they sound like: they help stabilize the print during the 3D printing process, ensuring the print is constructed accurately. The important thing to know is that sometimes supports are necessary for a print. However,  determining if supports are necessary is beyond the scope of this document.  

#### Consumer Level Printers

Two Types of Printers of 3D printers available to consumers. They are Fused Filament Fabrication (FFF) and Stereolithography (SLA). FFF is commonly known as FDM, but that term is trademarked.

## Fused Filament Fabrication

FFF printers use filament to create the model. Filament is a cord formed from plastic that is stored on a reel. The filament is melted and pushed through a nozzle. Nozzles have different sized openings at the tip, but are interchangeable. The size of the opening at the tip limits the amount of filament that can pass. Nozzles also conduct heat provided by a heater block. The heater block receives heat from a heater cartridge. A heater cartridge is a small cylinder that makes heat through electricity. This heat is regulated by a thermistor. Heat allows the nozzle to melt the filament to the temperature that the filament is malleable. The rate at which the filament is pushed through the nozzle is controlled by a motor called an extruder. 

<img src="https://github.com/FormerCounselor/Portfolio/blob/main/images/Ender%203.png" alt="Typical Fused Filament Fabrication Printer" width="905" height="1119">

#### How it Works
Filament is fed into the extruder, and exits into flexible plastic tubing called a Bowden Tube. The Bowden Tube guides the filament into the heat sink, through the heat break, and exits the nozzle. The heat break is similar to an hourglass shape, and is designed to isolate the heat used to melt the filament. The melted filament is then expelled onto the build plate in the shape of the model. 

<img src="https://github.com/FormerCounselor/Portfolio/blob/main/images/FFF%20Hotend%20Cutaway.png" alt="FFF Hotend Cutaway" width="927" height="1038">

#### Unboxing and Assembly

FFF printers come partially assembled. Partially assembled means that the printer comes as several individual pieces, and assembly must be completed after purchase. All needed tools are included. For additional assistance beyond the instructions, there is a large 3D printing community on YouTube. Assembly and how to maintain printers are popular topics. The specifics of assembling a printer is beyond the scope of this document.

#### Preparation - Before Printing

Place your model’s file into the slicer software of your choice, orient the model as desired, then slice the file. The slicer generates an instruction file. Load the sliced file onto an SD card, and insert that card into the printer. Clean the build plate with Isopropyl alcohol, commonly known as IPA, and wipe it with a clean, lint-free cloth. Pre-heat the nozzle to the manufacturer’s recommended temperature for the filament, and preheat the build plate to the recommended temperature so that the print will stick to the surface. 

Level the build plate. It is important to level the build plate AFTER it is at printing temperature, as leveling before heat expansion can result in a flawed print. A build plate must be leveled with respect to the printer’s frame, not the surface the printer is resting on. Select the model’s instruction file loaded onto the SD card from earlier, then print.

#### Troubleshooting

Keep your FFF printer unmodified is the best way to minimize the chance things can go wrong. Ensure you follow all steps in the FFF Prep section. Solutions to advanced issues are beyond the scope of this document. Find a 3D printing community, provide as much information about the problem as you can, and other enthusiasts will help.


#### Post-process

Post-process, or simply post, is very simple with FFF printers. Remove the print from the build plate with a scraper, and avoid scratching the surface of the build plate while doing so. Remove any supports that were also created for the proper construction of your print. 

## Stereolithography

SLA printers use UV resin and a UV LED panel to construct the model. UV resin, commonly known as just resin, hardens when exposed to UV light. SLA printers invert the model, with the build plate rising out of the vat as each layer is constructed. A vat is a wide, shallow container that holds the UV resin, with a FEP sheet as a transparent bottom that allows light to pass through a glass bottom, and cure the UV resin. A FEP sheet is a specially engineered sheet of plastic specifically for resin printers.

<img src="https://github.com/FormerCounselor/Portfolio/blob/main/images/SLA%20Illustration.png" alt="Typical Stereolithography Printer" width="927" height="1038">

#### How it Works

The build plate submerges itself in the resin, stopping one layer’s width above the FEP sheet. The high resolution UV LED turns on, projecting an image shaped exactly how the first layer looks. The area from the build plate to the FEP sheet is cured in a shape identical to the image projected. The newly cured layer attaches itself to the build plate during this process. The printer lifts the build plate and partially printed model a few centimeters out of the resin. The bottom of the most recently printed layer serves as the new build plate, and the process repeats until the model is finished.

<img src="https://github.com/FormerCounselor/Portfolio/blob/main/images/SLA%20Build%20Process.png" alt="How SLA printers construct the model" width="980" height="1386">

#### Unboxing and Assembly
Attach the vat on top of the transparent glass panel. Attach the build plate to the build arm. Pour UV resin into the vat.

#### Safety with SLA

UV resin is petroleum based, and is toxic. Use a respirator. A respirator is a half-face or full-face breathing apparatus for humans. A respirator that uses organic vapor filter cartridges is required. Organic vapors are petroleum based. 

Wear nitrile gloves, and change gloves each time resin is handled. Latex gloves provide no protection. Repeated exposure will create an allergy to the resin, resulting in headaches, dizziness, vomiting, rashes at the site of exposure, and other unwanted effects.

#### Environmental Safety

When resin is exposed to UV light, it quickly hardens. Do not pour uncured resin down the drain, and do not throw away objects contaminated with uncured resin. Items with uncured resin on them, and solutions with uncured resin in them, should be placed in the sun for a minimum of one hour.

#### Printer Placement

Choose a room with no sunlight, the printer should also be placed in a well ventilated area, either outside or inside with ventilation.

#### Preparation - Before Printing

Place your model’s file into the slicer software of your choice, orient the model as desired, then slice the file. The slicer generates an instruction file. Load the sliced file onto an SD card, and insert that card into the printer. Clean the build plate with Isopropyl alcohol, and wipe it with a clean, lint-free cloth. Resin printers have a bed that also functions as a build plate, and it does not need to be leveled unless you suspect it has been disturbed during removal of a previous print. 

#### Troubleshooting

Keep your SLA printer unmodified. This reduces the number of issues created.  Ensure you follow all steps in the SLA Prep section, and ensure you have selected a spot away from any sunlight. Solutions to advanced issues are beyond the scope of this document. 

#### Post-Process

Remove the print from the build plate with a scraper, and avoid scratching the build plate while doing so. Remove any supports on the print. Place the print in a solution of IPA inside of an ultrasonic cleaner. An ultrasonic cleaner uses ultrasounds at a very low frequency to agitate a fluid, with a cleaning effect. Fully cure the print by exposing it to a UV LED panel for 10-15 minutes, depending on size. This post-cure consists of exposing the print to 10-15 minutes of additional UV light. Do not skip the post-cure process.
