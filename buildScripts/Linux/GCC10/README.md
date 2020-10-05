To build the NGMS software stack in the current directory just run the Allmake script using `./Allmake`. The Allmake script will build all the dependencies from the compiler up. CMake is not currently included and the build has only been tested with CMake version 3.13.4. All source code is fetched from the websites and repositories for the official releases.  

Versions compiled using the script in this directory.  
- Compiler:  
  -  GCC             10.2.0  
- MPI Libraries:  
  -  MPICH           3.3.2  
  -  YAXT            0.9.0  
- IO Libraries:  
  -  HDF5            1.10.6  
  -  NETCDF4 C       4.7.3  
  -  NETCDF4 C++     4.3.1  
  -  NETCDF4 Fortran 4.5.2  
  -  XIOS            2.5  
- Unit Testing Library  
  -  pFUnit          3.3.3  
- Unit Testing Library  
  -  rosePicker      r24024  
