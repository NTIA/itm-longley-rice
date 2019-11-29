# ITS Irregular Terrain Model (Longley-Rice)

The ITS model of radio propagation for frequencies between 20 MHz and 20 GHz (the Longley-Rice model) (named for Anita Longley & Phil Rice, 1968) is a general purpose model that can be applied to a large variety of engineering problems. The model, which is based on electromagnetic theory and on statistical analyses of both terrain features and radio measurements, predicts the median attenuation of a radio signal as a function of distance and the variability of the signal in time and in space.

**Note**: This code base is the historical source that is available [here](https://www.its.bldrdoc.gov/resources/radio-propagation-software/itm/itm.aspx), and was migrated here for archival purposes.  These code bases correspond to ITM Version 1.2.2.  A new code base has been established [here](https://github.com/NTIA/itm).  This new code base was initially established as ITM Version 1.2.3, which is functionally identical to Version 1.2.2, with the only difference being updated error and warning handling.  While this code will continue to be supported, all future updates to ITM will only be applied to [the code base](https://github.com/NTIA/itm).

## Releases

A list of all available software releases can be viewed [here](https://github.com/NTIA/itm-longley-rice/releases).

### Fortran Source ###

* itm_man.txt - A manual for ITM. A straight ASCII file intended to aid the programmer in preparing a main program that involves the ITM.
* uarea.exe - An executable file for UAREA. Runs on a PC under DOS.
* uarea_man.txt - A manual for UAREA. A straight ASCII file.
* qkpflman.txt - A manual for QKPFL. A straight ASCII file.
* qkpfl.exe - An executable file for QKPFL. Runs on a PC under DOS.
* qkpfl32.exe- An executable file for QKPFL. Runs on a PC under DOS (in 32-bit mode).
    * You will need to put salflibc.dll into your C:\WINDOWS\SYSTEM directory for it to work.
* qkpflbat.txt, qkpfldat.txt, and qkpflanx.txt - A sample showing how to run QKPFL on a PC-a batch file which runs the program using QKPFL.DAT as input and writing output to QKPFL.ANS. When run, the latter may be compared with QKPFL.ANX. Files should be renamed to QKPFL.BAT, QKPFL.DAT, and QKPFL.ANX. The .txt suffix was used to make it possible to easily view the files before running them.

### C++ Source ###

* ITMsetup.exe - An executable file for ITM (C++ version) using the GLOBE terrain database (You must download this separately).
* To see more information about GLOBE, see our [GLOBE extraction routines](https://www.its.bldrdoc.gov/resources/radio-propagation-software/globe/globe-10-elevation-extraction-subroutines.aspx).

## References

* G.A. Hufford, A.G. Longley, W.A. Kissick, [A Guide to the Use of the ITS Irregular Terrain Model in the Area Prediction Mode](https://www.its.bldrdoc.gov/publications/details.aspx?pub=2091), NTIA Technical Report TR-82-100, April 1982.
* G.A. Hufford, [The ITS Irregular Terrain Model, version 1.2.2 Algorithm](https://www.its.bldrdoc.gov/media/50676/itm_alg.pdf).
* G.A. Hufford, [1985 ITM Memo](https://www.its.bldrdoc.gov/media/50675/Hufford_1985_Memo.pdf), Dr. George Hufford's 1985 Memo describing the changes to ITM version 1.2.1 (dated April, 1979) in ITM version 1.2.2 (dated September, 1984)
* G.A. Hufford, [The Irregular Terrain Model](https://www.its.bldrdoc.gov/media/50674/itm.pdf), The "definitive" representation of the ITS Irregular Terrain Model. It contains both the source code and a rather extensive documentation.
* A.G. Longley and P.L. Rice, [Prediction of Tropospheric Radio Transmission Loss Over Irregular Terrain: A Computer Method - 1968](https://www.its.bldrdoc.gov/publications/details.aspx?pub=2784), NTIA Technical Report ERL 79-ITS 67, July 1968.

## Contact

For technical questions about ITM, contact Paul McKenna, (303) 497-3474, pmckenna@ntia.gov.