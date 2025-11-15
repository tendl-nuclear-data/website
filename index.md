# TENDL

TALYS-based evaluated nuclear data library

TENDL is a nuclear data library which provides the output of the [TALYS](https://nds.iaea.org/talys/) nuclear model code system for direct use in both basic physics and applications. 

TENDL is not a default or shadow library. Not a single neutron evaluation is based on default calculations. With the HFR approach, all resonances follow statistical hypothesis. For major isotopes, greater care was used during the evaluation process.

A set of tools, called T6, was used to produce it. T6 stands for TALYS, TEFAL, TASMAN, TARES, TAFIS and TANES. Each code produces a part of the library. Processing tools such as NJOY, CALENDF, PREPRO are also used in T6.
