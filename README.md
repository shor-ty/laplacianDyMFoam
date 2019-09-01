### README ###

* This solver is used for a tutorial that Holzmann CFD made namely ACMIBoundaryWithHeatTransfer

* The solver was derived from the basic laplacianFoam by Nico Speelman

* Holzmann CFD did not re-check the solver but everything seems to work fine

### OpenFOAM Version ###
* 4.x
* 5.x
* 6.x

### Compilation ###

* Load your OpenFOAM environment
* Go to your solver folder and into basic
> cd $FOAM\_SOLVERS/basic
* Clone the repository
> git clone https://shor-ty@bitbucket.org/shor-ty/laplaciandymfoam.git laplacianDyMFoam
* Enter to the repository
> cd laplacianDyMFoam
* Switch to your version; (X) stands for your version
> git checkout OpenFOAM-(X).x
* Build the solver
> wmake
* Done
