# molecularstats
This project came out from a simple requirement to calculate Molecular Weight and number of atoms in a mulecule for >1000 different compounds. I didn't get any good implementation of same and decided to make one based on pure python which also supports brackets.

The program can:
1. Calculate Molecular Weight and Number of Molecules for any given string with molecular formula in standard format without spacing and subscripts.
2. Both 2 string and single single string Chemical Symbol Supported
3. Number supported only upto 2 digits currently. I plan to make it generalized irrespective of number of digits.
4. Any bracket combination is supported. 

Future work:
1. Adding general support for other molecular symbols like bonds (Basically to eliminate them)
2. Making Number of Elements generalized and not restricted to 2 digits.

Usage:

	from molstats.molstats import Molecule
	f1=Molecule('CH3CH4')
	f1.getMolecularWeight()
	31.07698
	f1.getNumElements()
	9
