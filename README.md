# mpi
MPI Matrix multiplication

**Overview**
This repository contains a mini‑project that demonstrates how to accelerate matrix multiplication by distributing the workload across multiple processes with MPI (Message Passing Interface). If MPI is not available, the script automatically falls back to a serial implementation so you can still run and test the code locally.

**Features**

Parallel matrix multiplication with mpi4py
Automatic serial fallback when mpi4py is absent
Execution‑time benchmarking
Easy scalability (configure the number of processes)
Clean, well‑documented code

**Project Structure**
├── mpi_matrix_multiplication.py   # Main script (parallel + serial)
├── requirements.txt               # Python dependencies
├── README.md                      # This file
├── execution_time_plot.png        # Benchmark chart (execution time)
└── speedup_plot.png               # Benchmark chart (speedup)


**Usage**
Serial Execution
python mpi_matrix_multiplication.py


**Parallel Execution (Example: 4 processes)**
mpiexec -n 4 python mpi_matrix_multiplication.py



