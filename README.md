# x86-64 CPU Architecture Simulation
## Getting Started

### Prerequisites
Make sure you have installed all of the following prerequisites on your machine:
* `cmake>=3.8`
* a `C++17` compiler `gcc, g++, ...`

### Build
```bash
# make sure to build in a seperate folder
mkdir build
cd build
cmake ..
make
```
### Unit Tests
This project uses [Catch2](https://github.com/catchorg/Catch2).
The tests are available in the `tests` folder.
After building the project, a `unit_tests` executable will be created.
```
$ ./unit_tests
===============================================================================
All tests passed (18 assertions in 3 test cases)
```