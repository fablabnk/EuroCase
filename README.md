Two projects

1. Maker Trophy Base

Walkthough: https://github.com/fablabnk/MakerTrophy/blob/main/CNCMilling/SimulationScreencast.webm

2. Eurorack Case

For each:
- Operations: profiles, pockets and "dogboning"

# Tool Notes

We are using: 3mm_Endmill_doubleFlute

- Feed
	(taken from here: https://www.upload.sorotec.de/doku/manuals/Manual_Router_Set_HL.pdf)
	- Horiz Feed: 1200mm/min
	- Vert Feed: 500mm/min

- Specs
	(taken from here: https://www.sorotec.de/shop/END-Mill-Z2---3-mm-2-Flute-Fishtail-Sorotec-Edition-10886.htm)
	- Cutting Edge Height: 10mm
	- Diameter: 3mm
	- Flutes: was set to 0!
	- Length: 38mm
	- Shank diameter: 3.17mm

# To Do
- Check correct tool is used and settings are correct
- Triple check dimensions, that we're cutting the right thing compared to Patrick's real case
- Remill from scratch in CAM Workbench (see noToolpaths file)
	- Layout according to stock we have
	- Explore new Tool Library and how portable it is
	- Remember each profile needs dress-up dogbone
- Our material thickness
	- same as in file?
- Export sanity check
- Export .nc file, check for tool changes within it
- Submit to lab Google Drive flow
