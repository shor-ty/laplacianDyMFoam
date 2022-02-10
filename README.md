### README ###

* This solver is used for a tutorial created by Tobias Holzmann namely _ACMIHeatTransfer_

* The solver was derived from the basic laplacianFoam by Nico Speelman

* Tobias did not re-check the solver but everything seems to work fine

### OpenFOAM Version ###
* The application is built and tested for the OpenFOAM Foundation versions:
  * 4.x
  * 5.x
  * 6.x
  * 7.x
  * v8
  * v9
  * v2106
  * v2112

* The master branch contains the actual version (7.x)

### Compilation ###

* Load your OpenFOAM environment
* Go to your solver folder and into basic

```bash
cd $FOAM_SOLVERS/basic
```

* Clone the repository

```bash
git clone git@github.com:shor-ty/laplacianDyMFoam.git
```

* Enter to the repository

```bash
cd laplacianDyMFoam
```

* Switch to the version of your OpenFOAM installation:

```bash
git checkout OpenFOAM <TAB> <TAB>
```

* Build the solver

```bash
wmake
```

* Done
