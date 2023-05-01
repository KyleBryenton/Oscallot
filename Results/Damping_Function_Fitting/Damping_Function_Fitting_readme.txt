Kyle Bryenton 2022-07-28 

All .xyz files obtained from Johnson Group Wiki in KB65 dataset on 2022-07-26

For TS and MBD, results are given as a beta value, followed by dispersion energies for Ar-Ar, He-Ar, He-He, He-Ne, Ne-Ar, Ne-Ne. 
For XDM-C6, the Rsep, C6, and critical damping radius from the BJ damping function for Ar-Ar, He-Ar, He-He, He-Ne, Ne-Ar, Ne-Ne. 

The dispersion corrections' energies is combined with a PW86PBE energy to get the total energy, then the RMSPE is compared to the refdata.
Full XDM was already previously fit in another work using similar methodology, so those results are omitted.

PW86PBEenergy = {-85.2, -19.1, -9.2, -9.0, -21.5, -15.3};
REFenergy = {454., 93.7, 34.8, 66.0, 211., 134.};

TS and MBD were fitted by fine-scanning beta values to get the lowest RMSPE.
XDM was fitted by writing the RMSPE as a function of a1 and a2, assuming a1,a2>0, and solving for the global minimum.

--------
Results Summary:

MBDrsSCS:

Beta = 0.62     RMSPE = 6.75605%
System	PW86PBE	MBD		Sum		Ref
He-He	-9.2	45.1206	35.9206	34.8
He-Ne	-9.0	80.5168	71.5168	66.
He-Ar	-19.1	111.219	92.119	93.7
Ne-Ne	-15.3	153.383	138.083	134.
Ne-Ar	-21.5	233.167	211.667	211.
Ar-Ar	-85.2	478.054	392.854	454.


TS:

Beta = 0.86     RMSPE = 7.32626%
System	PW86PBE	TS		Sum		Ref
He-He	-9.2	45.9646	36.7646	34.8
He-Ne	-9.0	82.0392	73.0392	66.
He-Ar	-19.1	113.249	94.1494	93.7
Ne-Ne	-15.3	155.414	140.114	134.
Ne-Ar	-21.5	237.038	215.538	211.
Ar-Ar	-85.2	483.457	398.257	454.



XDM-C6:

a1=0    a2=2.3024 Å    RMSPE = 11.73%
System	PW86PBE	XDM-C6	Sum		Ref
He-He	-9.2	45.5425	36.3425	34.8
He-Ne	-9.0	80.1802	71.1802	66.
He-Ar	-19.1	105.329	86.2293	93.7
Ne-Ne	-15.3	149.113	133.813	134.
Ne-Ar	-21.5	214.817	193.317	211.
Ar-Ar	-85.2	427.059	341.859	454.