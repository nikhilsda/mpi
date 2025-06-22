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


Execution Time vs Number of Processes
 
🔸 Speedup vs Number of Processes
<img width="396" alt="image" src="https://github.com/user-attachments/assets/f44d045c-ea57-4fe0-8d92-597ada420c31" />



**Conclusion**
This mini project successfully demonstrates the benefits of distributed computing in matrix multiplication using MPI. It provides hands-on experience in partitioning data, coordinating processes, and measuring speedup—all crucial concepts in parallel and high-performance computing.![image](https://github.com/user-attachments/assets/6f0612be-0ecc-449b-98c9-423ff2759ad7)





