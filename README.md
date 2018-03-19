# Edge Macros
[![Apache 2.0 License](https://img.shields.io/badge/license-Apache%20v2.0-blue.svg)](LICENSE)

The edge macros are used for extending partially constructed acyclic paths with one of the programmed edges.
The repository contains multiple macro definitions for different combinations of the node label sizes and the number of edges that can be programmed using the same macro.
For every macro, this repository contains an ANML definition file and a corresponding precompiled version.

* **edge_*B*_*d*.anml**  
This file contains the definition of macro for programming *d* edges of a graph, with *B*-byte node labels, and the same endpoint.

* **edge_*B*_*d*_compiled.anml**  
This file contains precompiled version of the macro defined in edge_*B*_*d*.anml.

Currently, the repository contains the macros for all possible combinations of *B* = 2, 3, 4 and *d* = 1, 2, 3, 4, 5.

## Publication
Roy, Indranil, Nagakishore Jammula, and Srinivas Aluru. "Algorithmic Techniques for Solving Graph Problems on the Automata Processor." In _Parallel and Distributed Processing Symposium, 2016 IEEE International_, pp. 283-292. IEEE, 2016.
