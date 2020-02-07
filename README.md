# T-scheduling
T-scheduling is a quantum circuit synthesizer for lattice surgery based on [T-par](https://github.com/meamy/t-par).  
T-par algorithm is described in the paper [Polynomial-time T-depth Optimization of Clifford+T circuits via Matroid Partitioning](https://arxiv.org/abs/1303.2042). 

## Requirements
- g++ 6.3 or later
- CMake 3.5 or later
- boost-1.72 or later
- [z3](https://github.com/Z3Prover/z3)

## Getting Started
### Build
```
$ cd build
$ cmake ..
$ make
```

### Usage
```
$ ./t-scheduling [option]
```

## Project layout
```
.
├── CMakeLists.txt
├── README.md
├── benchmarks
├── build
└── src
    ├── character
    ├── circuit
    ├── decomposer
    ├── io
    ├── layout
    ├── main.cpp
    ├── matrix
    ├── parallel
    ├── simulator
    ├── synthesis
    ├── tpar
    └── util
```