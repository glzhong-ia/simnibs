# SimNIBS

The main goal of SimNIBS is to calculate electric fields caused by Transcranial Electrical Stimulation (TES) and Transcranial Magnetic Stimulation (TMS).
The pipeline is divided in two parts:
1. Automatic segmentation of MRI images and meshing to create individualized head models
2. Calculation of electric fields through the Finite Element Method (FEM) and post-processing of results

## Build Status
<table>
  <tr>
  <td>Windows</td>
    <td>
    <a href="https://dev.azure.com/simnibs/simnibs/_build/latest?definitionId=771&branchName=test_release">
      <img src="https://dev.azure.com/simnibs/simnibs/_apis/build/status/Tests%20Windows?branchName=test_release" alt="variant">
    </a>
    </td>
  </tr>
  <tr>
  <td>Linux</td>
    <td>
    <a href="https://dev.azure.com/simnibs/simnibs/_build/latest?definitionId=771&branchName=test_release">
      <img src="https://dev.azure.com/simnibs/simnibs/_apis/build/status/Tests%20Linux?branchName=test_release" alt="variant">
      </a>
    </td>
  </tr>
  <td>OSX</td>
    <td>
    <img src="https://img.shields.io/badge/OSX-disabled-lightgrey.svg" alt="OSX disabled">
    </td>
  </tr>
</table>


## Getting Started
 
SimNIBS runs on 64bit Windows, Linux and OSX machines.
Please visit [the SimNIBS website](www.simnibs.org) for instructions into how to download and install SimNIBS.


## Authors
Please see [the SimNIBS website](www.simnibs.org) for a complete list of contributors.

## 3rd Party Files
We have included code or binaries from the following project to this repository:
* [Gmsh](www.gmsh.info)
* [meshfix](https://github.com/MarcoAttene/MeshFix-V2.1)
* [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/)
* [CAT12](http://www.neuro.uni-jena.de/cat/)
* [PETSc](https://www.mcs.anl.gov/petsc/)
* [HYPRE](https://www.mcs.anl.gov/petsc://computation.llnl.gov/projects/hypre-scalable-linear-solvers-multigrid-methods)
* [MPICH](https://www.mpich.org/)
* [MSMPI](https://github.com/Microsoft/Microsoft-MPI)
* [CYGWIN](https://www.cygwin.com/)
* [pygpc](https://github.com/konstantinweise/pygpc)

For a full list of files and licenses, please see the 3RD-PARTY.md file

## Contributing

Contributions with new Python or MATLAB functionality or examples are welcome

### Documentation

- Please document *ALL* python functions, classes and modules following the [NumPy Standards](https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt)
- Please document *ALL* MATLAB functions

### Testing

- Please write [Pytest](http://pytest.org/latest/) unit tests for all new functions.

### Style

- Please try to follow [PEP8](https://www.python.org/dev/peps/pep-0008/). Linters on your IDE are there to help, as well as tools such as [flake8](https://flake8.readthedocs.io/en/latest/)