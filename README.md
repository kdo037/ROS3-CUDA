# ROS3-CUDA
1. Compile CUDA Fortran from NVIDIA SDK
2. Build based CMAQ CCTM
3. Replace Makefile, rbsolver.F, and rbsolverkernel.cuf in BLD_CCTM folder
4. Rebuild using make command
5. rbsolverkernel.cuf will replace 4 subroutines: rbsolver.F, rbdecomp.F, rbfeval.F, and rbsolve.F
