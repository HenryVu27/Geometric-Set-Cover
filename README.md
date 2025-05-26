# A Survey of the Geometric Set Cover Problem with Unit Disks in the Plane

**Author:** Henry Vu
**Date:** April 29, 2025

## Abstract

The Geometric Set Cover Problem (GSCP) is a fundamental problem in computational geometry where the goal is to cover a set of points using the minimum number of geometric objects from a given family. This survey focuses on the specific case of covering points in the plane (R²) with unit disks. It reviews the problem's formal definition, its connection to linear programming and duality (hitting sets), the role of range spaces, VC-dimension, nets and samples, various algorithmic approaches (greedy, LP-based, local search, PTAS), key theoretical approximation bounds, and representative pseudocode.

## Key Highlights

This survey provides a comprehensive overview of the GSCP for unit disks, detailing:

*   **Fundamental Concepts:** Formal problem definition, ILP and dual formulations, and the role of VC-dimension and ɛ-nets.
*   **Evolution of Algorithmic Techniques:**
    *   From the classic **Greedy** approach (O(log n) approximation).
    *   To sophisticated **LP-based and Primal-Dual methods** (Iterative Reweighting, MWU, Quasi-Uniform Sampling) achieving constant-factor approximations, some in near-linear time.
    *   To **Polynomial-Time Approximation Schemes (PTAS)** via local search.
*   **Theoretical Underpinnings:** NP-completeness, key approximation ratios, and time complexities for various algorithms.
*   **Practical Illustrations:** Pseudocode for the Greedy algorithm and a Local Search PTAS.
*   **Future Directions:** A look at open problems and ongoing research areas in geometric set cover.

## Structure of the Survey

1.  **Problem Definition:** Introduces the GSCP with unit disks, LP formulations, and range space concepts.
2.  **Algorithmic Approaches:** Details various algorithms, from greedy to PTAS, including a summary table of LP-based methods.
3.  **Theoretical Results:** Summarizes NP-completeness and key approximation algorithm guarantees.
4.  **Research Landscape and Open Problems:** Discusses future directions and open questions.

## Purpose

This survey aims to be a valuable resource for students, researchers, and practitioners interested in understanding the landscape of algorithms and theoretical results for the unit disk set cover problem in the plane.

## Accessing the Paper

The full survey paper (PDF) can be found in this repository.

## Citation (Example)

If you find this survey useful in your research, please consider citing it.
