# AquaNet — Smart Water Resource Management Platform

A dependency-free Java console project designed to import into Eclipse. Sample assets, demands, a water-quality report, and sensor observations demonstrate each DSA area through an interactive menu.

## Run in Eclipse
1. Choose **File → Import → Existing Projects into Workspace**.
2. Select this `AquaNet` directory and finish.
3. Open `src/aquanet/AquaNetApp.java`, then **Run As → Java Application**.

Requires Java 17 or later (records, `Stream.toList`, and `ThreadLocalRandom`). No Maven/Gradle dependencies are needed.

## DSA coverage
- **M1 / CO1:** KMP, Z-function, Rabin–Karp, Aho–Corasick for report terms, IDs, and contamination keywords.
- **M2 / CO2:** SA-IS suffix-array report indexing, Kasai LCP, binary substring lookup, and suffix automaton.
- **M3 / CO3:** Levenshtein/Damerau–Levenshtein, bitmask DP for selecting treatment resource combinations, matrix-chain ordering, optimal BST cost.
- **M4 / CO4:** Ford–Fulkerson using Edmonds–Karp BFS, Dinic, residual min-cut, bipartite operator matching.
- **M5 / CO5:** brute-force SAT/3-SAT, 3-SAT-to-CLIQUE compatibility graph, complement reduction to independent set and vertex cover, 2-approximate vertex cover.
- **M6 / CO6:** randomized QuickSort, reservoir sampling, Miller–Rabin, Blelloch exclusive scan, parallel reduction, Brent work/span estimate.

The SAT solver is an educational exhaustive solver and is intended for small examples.


