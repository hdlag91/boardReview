## Board Review
Before sending out your project for fabrication, you want to go through an extensive board review. This is to help catch any errors
as well as make any improvements on the current design.
## Table of contents
[Schematic Document Review](#sdr)<br>
[PCB Document Review](#pcb)<br>
[Documentation Outputs (Smart PDFs)](#out)<br>
[Fabrication Outputs](#fab)<br>
[Report Outputs](#rep)<br>
[Validation Outputs](#valid)<br>
[References](#ref)<br>

<div id='sdr'>
  
## Schematic Document Review
 - Are all pins hooked up correctly on all IC's.
 - All grounds are routed.
 - If a net label GND is being used is it tied to a ground object somewhere.
 - Cloned resistors and capacitors have correct values.
 - Cloned resistors and capacitors have correct Digikey part numbers.
 - Cloned resistors and capacitors have correct footprints.
 - IC's have correct footprints for part ordered.
 - All parts are annotated.
 - All components used are in a project included library.
 - Compile Project.

<div id='pcb'>

## PCB Document Review
 - Import Changes from PCB Project.
 - Apply Design Rules (OSH Park) for hole size.
 - Apply Design Rules (OSH Park) for Minumum Annular Ring.
 - Apply Design Rules (OSH Park) for trace width.
 - Layer Stackup all layers visible.
 - No island polygons on PCB.
 - Ground pins of components aren't floating
 - Polygons with high voltage differences have adequete distance from each other.
 - USB lines are placed with differential routing tool.
 - All strings are 30mil text height.
 - All traces are 10mil w/ exception of differential usb lines.
 - Are via stitching groups down and polygons poured around them.
 - Ensure all polygons aren't shelved.
 - Design Rule Checks (Zero Errors)
 - No net antennas.
 - Double check silk screen to solder mask.
 - No unrouted nets.
 - Are decoupling capacitors and power cap arrays located as close to pins as possible?

<div id='out'>

## Documentation Outputs (Smart PDFs)
 - Schematic Prints.
 - PCB Prints.
 
 <div id='fab'>

## Fabrication Outputs
 - NC Drill Files.
 - Gerber Files.
 **Note: Do not use Gerber X2 Files.
 
 <div id='rep'>

## Report Outputs
 - Bill of Materials
 - Comment
 - Description
 - Designator
 - Footprint
 - Libref
 - Quantity
 - Supplier Part No
 - Value

<div id='valid'>

## Validation Outputs
 - Design Rules Check
 - Footprint Comparison Report

<div id='ref'>

## References
 - [OSHPARK design rules](https://docs.oshpark.com/design-tools/altium-designer/)
