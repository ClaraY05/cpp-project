# C++ Matching Engine

A C++20 limit order book and matching engine.

## Build

Requires CMake 3.20+ and a C++20 compiler.

```bash
cmake -S . -B build -DCMAKE_BUILD_TYPE=Debug
cmake --build build
```

## Run

```bash
./build/src/matching_engine
```

## Tests

Run all tests with CTest:

```bash
ctest --test-dir build --output-on-failure
```

## Project Structure

- `include/` — Header files
- `src/` — Implementation
- `tests/` — Unit tests
- `benchmarks/` — Performance benchmarks