# OpenSBLI benchmark

To aid with standardisation across UK HPC systems, our OpenSBLI benchmark is identical to the "LARGE (1024)" one used by ARCHER, the UK national HPC service.

Details of how to build and run the benchmark may be found in the ARCHER repository here: https://github.com/hpc-uk/archer-benchmarks/tree/master/apps/OpenSBLI

# Results 

The follwoing results are from runs on a recently installed ARC cluster. 

OpenSBLI was built with Intel Compiler 2019 and Intel MPI 2019 - with HDF5 1.8.15-p1 

Single Node
```
------------------Simulation time-----------------------------------------
Total Wall time of the time iteration loop for 10 iterations, 305.233978
Time taken for 1 iteration, 30.523398
```
2 Nodes
```
------------------Simulation time-----------------------------------------
Total Wall time of the time iteration loop for 10 iterations, 166.546934
Time taken for 1 iteration, 16.654693
```
4 Nodes
```
------------------Simulation time-----------------------------------------
Total Wall time of the time iteration loop for 10 iterations, 106.824265
Time taken for 1 iteration, 10.682427
```
8 Nodes
```
------------------Simulation time-----------------------------------------
Total Wall time of the time iteration loop for 10 iterations, 43.068650
Time taken for 1 iteration, 4.306865
```
16 Nodes
```
------------------Simulation time-----------------------------------------
Total Wall time of the time iteration loop for 10 iterations, 28.934276
Time taken for 1 iteration, 2.893428
```
24 Nodes
```
------------------Simulation time-----------------------------------------
Total Wall time of the time iteration loop for 10 iterations, 17.568893
Time taken for 1 iteration, 1.756889
```
