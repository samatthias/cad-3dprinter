# cad-3dprinter

## Context

This repository contains files of my 3dprinter cad model created with freecad version 1.0.0 and with the default assembly workspace (onsdel solver). The design is inspired by the Voron 2.4 and ratrig 4.

Major specification details:

- Core XY kinematics
- Heated chamber 
- Motors are completely outside of the heated chamber
- Z axis has 3 motors
- Z axis works with belts instead of lead screws, and has no mechanical breaks 
	- I will later add a cheap 24v battery to the printer to prevent serious damage if there is an unplanned main ac power loss
- Relatively large build volume 400mm x 400mm
- LDO Motors for x,y and z axis
- 9mm GT2 belts
- 30x30 aluminium extrusions

To be decided:
- Print head


## Notes

- Aluminium extrusion profile is simplified to speed up load times of assembly. I do not use "heavy" aluminium extrusions, instead I use the "light" version with groove width 6mm (usually it's 8mm).
- Most of the time I use M5 or smaller screws


