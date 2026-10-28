# MoE EP Compiler

A distributed execution compiler and runtime planner for MoE expert parallelism.

## Goal

Compile model structure, cluster topology, workload traces, and runtime constraints
into a versioned execution plan for expert placement, routing, communication, and
online migration.

## Planned Scope

- logical expert -> replica -> rank/local slot mapping
- EPLB and LPLB placement policies
- rank-major dispatch to expert-major grouped GEMM layout lowering
- versioned plan migration and atomic runtime switching
- simulator, correctness tests, and end-to-end benchmarks

## Status

Early-stage project.
