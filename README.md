# Overview

An experimental repo for developing sparse CNN operators aiming to run on risc-v architecture (especially on Boom w\ Gemmini).

Files under ```/test/pkCXX/torchsparse``` are functions form Torchsparse by MIT-Han Lab.


## Quick Start

Run the following commands:
```bash
./build.sh
```

- To get quick result by risc-v emulator Spike:
```bash
./run-spike.sh
```

- To get cycle-accurate result by Verilator:
```bash
./run-verilator.sh
```

---
*Only for CMake/RISC-V exercise.
