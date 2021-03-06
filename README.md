
[![TravisCI](https://img.shields.io/travis/com/srmani/UCG-GFRD/master)](https://travis-ci.org/github/srmani/UCG-GFRD)
<img alt="GitHub commit merge status" src="https://img.shields.io/github/commit-status/srmani/UCG-GFRD/master/f5fc36c1acbec2009593c9bc730246ed407c4382">
[![Language grade: C++](https://img.shields.io/lgtm/grade/c++/g/srmani/UCG-GFRD.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/srmani/UCG-GFRD//context:C++)
[![codecov](https://codecov.io/gh/Andrew-AbiMansour/PyGranSim/branch/master/graph/badge.svg)](https://codecov.io/gh/Andrew-AbiMansour/PyGranSim/branch/master)

This is a LAMMPS fix implementing Ultra-Coarse-Graining (UCG) and Green's Function Reaction Dynamics (GFRD) for simulating
biochemical reaction network systems (ex: actin cytoskeletal networks with regulatory proteins)

Refer to the following journal articles to understand the UCG and GFRD technique:
1) The Theory of Ultra-Coarse-Graining. 1. General Principles
[![DOI for Citing UCG1](https://img.shields.io/badge/DOI%3A-https%3A%2F%2Fdoi.org%2F10.1021%2Fct4000444-green)](https://doi.org/10.1021/ct4000444)

2) The Theory of Ultra-Coarse-Graining. 2. Numerical Implementation
[![DOI for Citing UCG2](https://img.shields.io/badge/DOI%3A%20-%20https%3A%2F%2Fdoi.org%2F10.1021%2Fct500834t-brightgreen)](https://doi.org/10.1021/ct500834t)

3) Green's Function Reaction Dynamics: A Particle-Based Approach for Simulating Biochemical Networks in Time and Space
[![DOI for Citing GFRD1](https://img.shields.io/badge/DOI%3A%20-%20https%3A%2F%2Fdoi.org%2F10.1063%F1.2137716-blue)](https://doi.org/10.1063/1.2137716)

4) Combining Molecular Dynamics with Mesoscopic Green's Function Reaction Dynamics Simulations
[![DOI for Citing GFRD2](https://img.shields.io/badge/DOI%3A%20-%20https%3A%2F%2Fdoi.org%2F10.1063%F1.4936254-green)](https://doi.org/10.1063/1.4936254)

The repository includes the following files and directory

README: self-explanatory
src: folder containing the *.cpp and *.h fix files for the UCG-GFRD scheme
doc: documentation
examples: folder with simple examples demonstrating the application of the technique
test: files for testing


Compilation procedure
------------------------

Step 1: download LAMMPS tarball and unzip it
Step 2: copy the *.cpp and *.h files from src directory into corresponding LAMMPS/src/ folder
Step 3: follow the usual procedure of LAMMPS compilation (https://lammps.sandia.gov/)
