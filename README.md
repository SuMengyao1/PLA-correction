The code is used to correct the distortion of CBED patterns caused by projector lens aberration.

The code includes four python notebooks. 

The first one “GetCenters” is to fit the center of the Bragg disks in the position averaged CBED pattern of reference data. 

A corresponding code “RefineOvalCenters” can be used to refine the positions of centers. 

The second one “FitZernikeModel” is used to fit the distortion field into Zernike Model at certain camera length. 

The third one “CorrectEntireDataset” is used to correct all 4D-STEM data collected at the same camera length.
