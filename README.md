The Labcyte / Beckman Coulter Echo acoustic liquid handler is able to use any fully-skirted SLAS-footprint plate with a height of up to 16 mm as a destination plate for liquid transfers. Many PCR plates, however, are not fully skirted, and many PCR machines cannot accept fully-skirted plates.

This model adapts the Applied Biosciences MicroAmp EnduraPlate Optical 96-Well Fast reaction plate, a 0.1 mL qPCR plate, to be usable as a destination plate. (AB catalogue numbers A36930, 4483485, 4483494.)

We use this adapter in an Echo 525 (500-series, 25 nL droplet size) machine.  While we're not aware of any reason it wouldn't work in a 600-series (2.5 nL droplet size) machine, we have not tested it.

Transferring water, in initial tests, we have done single-shot transfers with volumes up to 48 µL from a 6RES source plate without gravity causing catastrophic drops from the destination plate.  However, you should test this yourself, especially if you are using liquids with different properties.

This model is licensed CC-BY-SA 4.0.  We would in particular like to draw your attention to the disclaimer of any warranty or liability in the licence.  While a Labcyte employee initially recommended this approach to us, you are ultimately using a 3d printed item from a downloaded model in a fragile and six-figure-purchase-price machine. We are not liable if it damages your machine or lab, causes any problems in your research, or causes your building to burn down.  Please exercise care in using this model, and test it first.

We are using semantic versioning for the model, with versions formatted as X.Y.Z:

 - A change in X means that the model breaks compatibility with versions with different values of X, for example, in this case, requires different labware definition parameters.
 - A change in Y means that the model or other files has been improved in some manner, or the features of the model have changed, without breaking compatibility.
 - A change in Z means that a problem in the model or other files has been addressed, without breaking compatibility or making improvements or non-problem-related changes to the model.

# Printing recommendations

We have printed this adapter in both PLA and PETG.  PETG is likely to be preferable, both for the durability of the clips, and the ease of attaching and detaching the adapter.

# Recommended Echo destination labware parameters

These parameters are also available in the ELW and ELWX files in the labware-definitions zip file.

    Rows: 8
    Columns: 12
    A1 X Offset: 14.380 mm.
    A1 Y Offset: 11.240 mm.
    X Center Spacing: 9.000 mm.
    Y Center Spacing: 9.000 mm.
    Plate Height: 16.000 mm.
    Flange Height: 2.410 mm.
    Well Width: 3.80 mm. (NB: full well diameter is 5.49mm±0.05mm per AB specs, and the rounded well bottom has a diameter of 2.6mm, based on the plate technical drawings.  A 3.80 mm well width and height shoult ensure that any allowed offset value is within the well.)
    Well Height: 3.80 mm.
    Well Capacity: 80 µL. (NB: well nominal capacity is 100 µL.)

# Changelog

- 1.0.0: Initial tested version.  Note that unfortunately, the original SCAD file to this version has been lost, and will need to be reconstructed at some point if any changes are needed.