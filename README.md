# borehole-openfoam-codes

CFD simulation of a borehole geotheral energy system using OpenFOAM.

To run the stationary simulation:
```bash
cd v001-stationary
./Allrun
./postP
```

To run the transient simulation:
```bash
cd v001-timeDependent
./Allrun
./postP
```

If you want to clean the folder:
```bash
./Allclean
```

If you are looking for the already-compiled codes, together with the `.foam` files:
```bash
cd v002-stationary
// or
cd v002-timeDependent
```
