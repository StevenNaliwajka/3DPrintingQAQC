# 3DPrintingQualityTesting
Running Repo: Collection of my 3D printing calibration and demo tests

My personal research and reasoning on the objective 'best way' to design my parts.

CAD (Computer Aided Design) dimensions to align with the real world after they have
been printed.

### TERMS:
Tolerance - acceptable error when machining  
Fit - Ideal size  
Clearance - Minimum gap size for a certain fit

### 3 Variables:
1) Intentional CAD Clearances.
- Clearances built into the 3D model to allow for different fits.
- IN THEORY: This should be modeled as the 'real world' true value.
- Given that everything after this point is custom to the user. The goal for uniformity should in theory occur here.
2) STL -> GCODE Slicer settings.
- Different slicer settings provide variations in print quality and performance.
--- Print speed, layer settings and temp settings are examples.
3) Unique Printer Setup and Accuracy.
- Differnt quality of printers provide different levels of accuracy. 
- Nozzle size and material type also influence the way prints turn out.

# CAD Clearance Conclusions
From research, the current 'best' way to design models is to design prints with clearances tuned to my machine.  
A custom test print will verify if the baked STL will function properly on the user's machine.  
I can provide the OG solidworks files and allow for the user to modify and change clearances if required.

With future research on my other machines I can continue to find the most 'universal' clearances for most machines.

------------------


## 3D Printing Quality
Documentation on what slicer and or slicer settings I use when printing different filaments at different qualities.

### Troubleshooting:
[SIMPLIFY3D](https://www.simplify3d.com/resources/print-quality-troubleshooting/): Great website for debugging issues.  
[ALL3DP](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/): Another good debug website.

### Working Printers:
- Elegoo Neptune 3 PRO, (On loan from [Maiikiru](https://github.com/Maiikiru)), Klipper integration
- Snapmaker J1s, Dual extrusion printer, Stock
### Various Stage of repair:
- Ender 3 V2, My OG Printer, 'broke' due to me half installing a klipper upgrade, I'll get to it.
- Ender 3, Bought Used, 'broke' due to a firmware misflash, I'll get to it.