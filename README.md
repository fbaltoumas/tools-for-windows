# Tools for Windows
Compiled versions of popular Bioinformatics/Computational Biology and/or computational Biophysics tools for use in Windows.  

### GROMACS v. 2018.1
GROMACS v. 2018.1, compiled for 64-bit Windows. GROningen MAchine for Chemical Simulations (GROMACS) is a molecular dynamics package mainly designed for simulations of proteins, lipids, and nucleic acids. It was originally developed in the Biophysical Chemistry department of University of Groningen, and is now maintained by contributors in universities and research centers worldwide.  
Notes on this particular GROMACS implementation:  
* Single-precision build
* No MPI or GPU capabilities
* Fast-Fourier Transformation (FFT) library: FFTW
  
  
### HMMER v. 3.2b  
HMMER version 3.2b compiled for 64-bit Windows. HMMER is a package for the creation and manipulation of profile Hidden Markov Models (pHMMs) for biological data (protein and nucleic acid sequences).  
  
  
All tools have been compiled using the Cygwin compatibility layer, with all required compilers (gcc, g++, gfortran etc).  The relevant DLL libaries have also been included in the packages.  Therefore, users can run the tools straight from the Command Prompt (CMD) and/or PowerShell and do not need to install Cygwin (although it would be easier for them to do so).
