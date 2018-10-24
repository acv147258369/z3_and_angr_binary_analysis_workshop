# Intro to Binary Analysis with Z3 and Angr

Originally delivered by Sam Brown at Steelcon and hack.lu 2018, this was a three hour workshop introducing attendees to using Z3 and Angr for SMT solving. The workshop provided an introduction to SMT solvers, the Z3 SMT solver and its python library and the Angr binary analysis framework.

Through out the workshop exercises were provided which aimed to demonstrate potential applications of the technology to assist security researchers carrying out reverse engineering and vulnerability research.

The slides provide a rough guide for the content and what order to try the exercises in. 

## Examples and Exercises

### Z3

| Name | Type | Description |
|------|------|-------------|
| [N Queens](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/n_queens) | Example | 'How can N queens be placed on an NxN chessboard so that no two of them attack each other?' Uses Z3 to generate solutions for an N * N chessboard|
| [Suduko](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/suduko) |  |
| [Hackvent 15](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/hackvent_15) |  |
| [RNG](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/rng)) |  |
| [x86](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/x86) ||
|[Opaque Predicates](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/opaque_predicates)||
|[Equivalence Checking](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/z3/equivalence_checking)||
### Angr
| Name | Type | Description |
|------|------|-------------|
| [opaque_predicates](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/angr/opaque_predicates)| |
| [IOCTLs](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/angr/ioctls)| |
| [Hello World](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/angr/hello_world)| |
| [Bomb Lab](https://github.com/sam-b/z3_and_angr_binary_analysis_workshop/tree/master/angr/bomb_lab)| |
## Setup
