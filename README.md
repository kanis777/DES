# DES
# Project Title: Parallelized DES Algorithm Implementation

## Description:
This project implements the Data Encryption Standard (DES) algorithm using parallel computing techniques, specifically OpenMP and MPI. DES is a symmetric-key block cipher that encrypts data in 64-bit blocks, widely used for secure data transmission and storage. The implementation aims to enhance the performance of DES encryption and decryption processes by leveraging parallel processing capabilities.

## Objective:
The primary objective of this project is to parallelize the DES algorithm to improve its efficiency and speedup its execution time. By utilizing parallel computing frameworks such as OpenMP and MPI, the project aims to achieve concurrent execution of DES encryption and key reversal operations, thereby reducing the overall processing time for encrypting and decrypting data.

## Features:
Implementation of the DES algorithm in C++.
Utilization of OpenMP for parallelizing encryption and decryption operations within a shared memory system.
Integration of MPI for parallelizing encryption and decryption operations across distributed memory systems.
Efficient key generation and key reversal techniques.
Verification of encryption and decryption correctness through comparison of original and decrypted plaintext.

## Contents:
DES_openmp.cpp: Implementation of DES algorithm parallelized using OpenMP.
DESMPI.cpp: Implementation of DES algorithm parallelized using MPI.
README.md: Detailed documentation providing an overview, objectives, features, and usage instructions for the project.
License.txt: License information for the project.

## Usage Instructions:
Compile the source code using appropriate compilers for C++.
Execute the compiled executable, providing necessary input parameters such as plaintext and encryption key.
Monitor the output for the ciphertext generated and the corresponding execution time.
Optionally, verify the correctness of encryption and decryption by comparing the original plaintext with the decrypted text.


