# Instructions for Codex

## Project overview

This repository contains scientific software written in C. The project implements a family of ecological consumer--resource models, with local population interactions and movement among connected patches. It combines deterministic population equations, individual stochastic simulations, probability-distribution dynamics, and statistical inference. The project has evolved through incremental development, so its current architecture may contain historical design decisions that should be critically evaluated.

## Scientific integrity

- Never change the mathematical model without explicit approval.
- Preserve the interpretation of all state variables and parameters.
- Preserve numerical reproducibility whenever possible.
- Do not silently modify model implementation.
- Distinguish scientific assumptions from implementation choices.

## Software architecture

- Prefer modular designs with clearly defined responsibilities.
- Identify unnecessary dependencies between modules.
- Evaluate whether data structures can be simplified.
- Examine memory allocation and ownership.
- Evaluate the organization of input/output functions.
- Avoid introducing unnecessary external libraries.

## Working procedure

1. Understand the existing implementation before suggesting changes.
2. Explain proposed modifications and their scientific implications.
3. Do not modify existing source code without explicit authorization.
4. Make changes incrementally.
5. Compile and test after modifications.
6. Report any differences in numerical results.

## Documentation

- Maintain scientific documentation in DOCUMENTATION/.
- Use LaTeX for mathematical descriptions.
- Ensure that documented equations correspond to the C implementation.
- Identify uncertainties rather than inventing mathematical explanations.
