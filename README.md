# Irregular Terrain Model (Longley-Rice)

The ITS Irregular Terrain Model (ITM) predicts long-distance terrestrial radio wave propagation for frequencies between 20 MHz and 20 GHz based on electromagnetic theory and empirical models developed by Anita Longley & Phil Rice.  Specifically, ITM predicts the attenuation of a radio signal as a function of distance based on transmitter and receiver heights, terrain features, climate and meteorological conditions, and variability parameters.

## History of Software Implementations

The Fortran and C++ implementations of ITM are both version 1.2.2 and are maintained here for historical purposes.  A new C++ implementation of ITM has been established [here](https://github.com/NTIA/itm).  This new C++ implementation, initially designated version 1.3, is functionally identical to the old 1.2.2 software, except for updated error and warning handling.  Most importantly, the new C++ code base will be where all future updates and improvements to ITM will be applied and versioned.

## Releases

A list and short description of all files part of the software release can be viewed [here](https://github.com/NTIA/itm-longley-rice/releases).

## References

* G.A. Hufford, A.G. Longley, W.A. Kissick, [A Guide to the Use of the ITS Irregular Terrain Model in the Area Prediction Mode](https://www.its.bldrdoc.gov/publications/details.aspx?pub=2091), NTIA Technical Report TR-82-100, April 1982.
* G.A. Hufford, [The ITS Irregular Terrain Model, version 1.2.2 Algorithm](https://www.its.bldrdoc.gov/media/50676/itm_alg.pdf).
* G.A. Hufford, [1985 ITM Memo](https://www.its.bldrdoc.gov/media/50675/Hufford_1985_Memo.pdf), Dr. George Hufford's 1985 Memo describing the changes to ITM version 1.2.1 (dated April, 1979) in ITM version 1.2.2 (dated September, 1984)
* G.A. Hufford, [The Irregular Terrain Model](https://www.its.bldrdoc.gov/media/50674/itm.pdf), The "definitive" representation of the ITS Irregular Terrain Model. It contains both the source code and a rather extensive documentation.
* A.G. Longley and P.L. Rice, [Prediction of Tropospheric Radio Transmission Loss Over Irregular Terrain: A Computer Method - 1968](https://www.its.bldrdoc.gov/publications/details.aspx?pub=2784), NTIA Technical Report ERL 79-ITS 67, July 1968.

## Contact

For technical questions about ITM, contact Paul McKenna, (303) 497-3474, pmckenna@ntia.gov.