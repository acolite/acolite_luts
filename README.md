# ACOLITE-LUTs
This repository contains the generic LUTs for ACOLITE, as well as the LUTs resampled to specific sensors that can be used in ACOLITE. The LUTs are retrieved automatically by ACOLITE when not yet present in the local installation.

They can be also obtained manually from this repository and should then be placed in the appropriate acolite/data/LUT folders. For example, the S2A_MSI folders from this repository:

    ACOLITE-LUT-202102-Reverse/S2A_MSI
    ACOLITE-LUT-202102/S2A_MSI
    RSKY-202102/S2A_MSI

can be placed in the data/LUT directory from the main repository (note that the ACOLITE-LUT-202102-Reverse directory needs to be created):

    acolite/data/LUT/ACOLITE-LUT-202102-Reverse/S2A_MSI
    acolite/data/LUT/ACOLITE-LUT-202102/S2A_MSI
    acolite/data/LUT/RSKY-202102/S2A_MSI
