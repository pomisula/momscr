# MOMSCR

Official repository for the paper **"Modeling and Solution for Multi-objective Cold-rolling Planning Problem in Multi-stage Production"**.

> **Release status:** The benchmark instances are available now. The source code will be released after the associated paper is published.

## About

This project studies multi-objective production and inventory planning for multi-stage, multi-period cold-rolling systems.  

The proposed solution method is a learning-assisted multi-objective evolutionary algorithm (LMOEA).

## Benchmark instances

The [`instance`](./instance) directory contains 20 instances. File names follow the convention `T_K_L`, where:

- `T` is the number of planning periods;
- `K` is the number of material types; 
- `L` is the material-processing complexity level (from 1 to 4).

| Instance group | Periods (`T`) | Material types (`K`) | Complexity levels (`L`) | Number of instances |
| -------------- | --------------: | ---------------------: | ------------------------: | ------------------: |
| `5_10_L`     |               5 |                     10 |                       1-4 |                   4 |
| `7_15_L`     |               7 |                     15 |                       1-4 |                   4 |
| `10_20_L`    |              10 |                     20 |                       1-4 |                   4 |
| `12_25_L`    |              12 |                     25 |                       1-4 |                   4 |
| `15_30_L`    |              15 |                     30 |                       1-4 |                   4 |

Each instance records the complete numerical data required by the model.

## Environment

- Windows 11
- C++17
- CMake 3.10 or later
- [HiGHS](https://highs.dev/)

Build and usage instructions will be added when the source code is released.

## Citation

Citation information will be added after publication.
