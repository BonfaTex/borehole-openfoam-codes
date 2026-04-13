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

If you are looking for the already-compiled versions, together with the `.foam` files:
```bash
cd v002-stationary // compiled version of v001-stationary
cd v002-timeDependent // compiled version of v001-timeDependent
```

Finally, for the stationary simulation a Grid Independence Study was performed. Referring to the compiled versions, the finer mesh is inside `v002-stationary`, instead:
```bash
cd gis/v003-stationary // for the mid mesh
cd gis/v004-stationary // for the coarse mesh
```

___ 

### To recap

* `v001-stationary` for the non-compiled stationary case (using fine mesh)
* `v002-stationary` for the compiled stationary case (using fine mesh)
* `v003-stationary` for the compiled stationary case (using mid mesh)
* `v004-stationary` for the compiled stationary case (using coarse mesh)

* `v001-timeDependent` for the non-compiled transient case (using fine mesh)
* `v002-timeDependent` for the compiled transient case (using fine mesh)


