# cpp-convex-hull

2D convex hull implementations in C++17, with a visual debugger and
performance benchmarks comparing both algorithms.

## Algorithms

- **Graham Scan** — O(n log n), sort-based, processes points by polar angle
- **Incremental Convex Hull** — O(n log n), insert points one at a time and
  maintain hull invariants

## Planned Features

- Eigen-based point storage
- SFML visualizer showing hull construction step by step
- Benchmark suite comparing runtime, memory, and correctness across both
  algorithms on random and adversarial inputs
- CLI: `./convex_hull --algo graham --input points.txt --visualize`

## Stack

C++17, Eigen, SFML, CMake

## Status

Starting August 2026, as part of a broader computational geometry and
robotics systems portfolio. See also:
[rrt-motion-planner](https://github.com/mpraneel/rrt-motion-planner)

## Background

Built as part of a progression toward motion planning and SLAM systems
in C++. The convex hull is a foundational primitive in collision detection,
configuration space computation, and spatial data structures.
