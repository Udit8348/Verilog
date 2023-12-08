# Verilog Learning
Currently studying "Quick Start Guide to Verilog" by Brock J. LaMeres

## Format
Each folder represents a simple module that I write for practice

Inside there is the hdl, test-bench, and `_run.sh` to compile and simulate

Repo mainly for code and light comments, however most *notes* are kept in notion

## Toolchain
Toolchain setup is roughly based on repl.it env script, but modified to run locally on macos

Icarus Verilog for compilation and GTKWave for waveform simulation

## Todo
It would be cool to graphically see the circuit or key simulated output, then automatically generate a readme for each module

Why not use Verilator to compile?
- verilator needs a cpp test-bench to compile
- verilator does not support verilog test-benches
- verilator compilation requires extra steps
- learning modules are too simple to realize any of the performance benefits of verilator over icarus
