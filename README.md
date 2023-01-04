# Data Structures and Algorithms in Rust

---

This repo contains the implementation of various classic algorithms for
educational purposes in [Rust](https://www.rust-lang.org/). It includes
a comprehensive list of algorithms. Contributions are welcome!

---
### Prerequisites
I studied the Rust Book completely before embarking on this journey. I made implementations
of all concepts learned [here](https://github.com/theghostmac/Learning-RustLang). After
this, I am building [the rust-blockchain project](https://github.com/theghostmac/rust-blockchain)
from scratch with knowledge gained here.

---

### Foundations
* [ ] What is Big O Notation
  * [ ] What is Big O
  * [ ] O(n) - Linear Notation
  * [ ] O(1) - Constant Notation
  * [ ] O(n^2) - Polynomial Notation

---

### Strings

- [ ] Naive
- [ ] Finite Automaton
- [ ] Z-Algorithm
- [ ] [Aho-Corasick Algorithm](./src/string/aho_corasick.rs)
- [ ] [Burrows-Wheeler transform](./src/string/burrows_wheeler_transform.rs)
- [ ] [Knuth Morris Pratt](./src/string/knuth_morris_pratt.rs)
- [ ] [Manacher](./src/string/manacher.rs)
- [ ] [Rabin Karp](./src/string/rabin_karp.rs)
- [ ] [Reverse a string](./src/string/reverse.rs)
- [ ] [Hamming Distance](./src/string/hamming_distance.rs)

---

### Data Structures
- [ ] [Linked List](./src/data_structures/linked_list.rs)
- [ ] [Stack](./src/data_structures/stack.rs)
- [ ] [Queue](./src/data_structures/queue.rs)
- [ ] [Heap](./src/data_structures/heap.rs)
- [ ] [Graph](./src/data_structures/graph.rs)
  - [ ] [Directed](./src/data_structures/graph.rs)
  - [ ] [Undirected](./src/data_structures/graph.rs)
- [ ] [Trie](./src/data_structures/trie.rs)
- [ ] [Binary Search Tree](./src/data_structures/binary_search_tree.rs)
- [ ] [B-Tree](./src/data_structures/b_tree.rs)
- [ ] [AVL Tree](./src/data_structures/avl_tree.rs)
- [ ] [RB Tree](./src/data_structures/rb_tree.rs)
- [ ] [Stack using Linked List](./src/data_structures/stack_using_singly_linked_list.rs)
- [ ] [Segment Tree](./src/data_structures/segment_tree.rs)
- [ ] [Fenwick Tree](./src/data_structures/fenwick_tree.rs)
- [ ] [Union-find](./src/data_structures/union_find.rs)

---

## Algorithms

---

### Sorting Algorithms

- [ ] [Bubble](./src/sorting/bubble_sort.rs)
- [ ] [Bucket](./src/sorting/bucket_sort.rs)
- [ ] [Cocktail-Shaker](./src/sorting/cocktail_shaker_sort.rs)
- [ ] [Counting](./src/sorting/counting_sort.rs)
- [ ] [Cycle](./src/sorting/cycle_sort.rs)
- [ ] [Exchange](./src/sorting/exchange_sort.rs)
- [ ] [Heap](./src/sorting/heap_sort.rs)
- [ ] [Insertion](./src/sorting/insertion_sort.rs)
- [ ] [Gnome](./src/sorting/gnome_sort.rs)
- [ ] [Merge](./src/sorting/merge_sort.rs)
- [ ] [Odd-even](./src/sorting/odd_even_sort.rs)
- [ ] [Pancake](./src/sorting/pancake_sort.rs)
- [ ] [Quick](./src/sorting/quick_sort.rs)
- [ ] [Radix](./src/sorting/radix_sort.rs)
- [ ] [Selection](./src/sorting/selection_sort.rs)
- [ ] [Shell](./src/sorting/shell_sort.rs)
- [ ] [Stooge](./src/sorting/stooge_sort.rs)
- [ ] [Comb](./src/sorting/comb_sort.rs)
- [ ] [Bucket](./src/sorting/bucket_sort.rs)
- [ ] [Timsort](./src/sorting/tim_sort.rs)

### Searching Algorithms

- [ ] [Linear](./src/searching/linear_search.rs)
- [ ] [Binary](./src/searching/binary_search.rs)
- [ ] [Recursive Binary](./src/searching/binary_search_recursive.rs)
- [ ] [Kth Smallest](./src/searching/kth_smallest.rs)
- [ ] [Exponential](./src/searching/exponential_search.rs)
- [ ] [Jump](./src/searching/jump_search.rs)
- [ ] [Fibonacci](./src/searching/fibonacci_search.rs)
- [ ] [Quick Select](./src/searching/quick_select.rs)

### Graphs

- [ ] [Dijkstra](./src/graph/dijkstra.rs)
- [ ] [Kruskal's Minimum Spanning Tree](./src/graph/minimum_spanning_tree.rs)
- [ ] [Prim's Minimum Spanning Tree](./src/graph/prim.rs)
- [ ] [Breadth-First Search (BFS)](./src/graph/breadth_first_search.rs)
- [ ] [Depth First Search (DFS)](./src/graph/depth_first_search.rs)
- [ ] [Bellman-Ford](./src/graph/bellman_ford.rs)
- [ ] [Prufer Code](./src/graph/prufer_code.rs)
- [ ] [Lowest Common Ancestor](./src/graph/lowest_common_ancestor.rs)
- [ ] [Heavy Light Decomposition](./src/graph/heavy_light_decomposition.rs)
- [ ] [Tarjan's Strongly Connected Components](./src/graph/strongly_connected_components.rs)
- [ ] [Topological sorting](./src/graph/topological_sort.rs)
- [ ] [Centroid Decomposition](./src/graph/centroid_decomposition.rs)
- [ ] [Dinic's Max Flow](./src/graph/dinic_maxflow.rs)


### Dynamic Programming

- [ ] [0-1 Knapsack](./src/dynamic_programming/knapsack.rs)
- [ ] [Edit Distance](./src/dynamic_programming/edit_distance.rs)
- [ ] [Longest common subsequence](./src/dynamic_programming/longest_common_subsequence.rs)
- [ ] [Longest continuous increasing subsequence](./src/dynamic_programming/longest_continuous_increasing_subsequence.rs)
- [ ] [Longest increasing subsequence](./src/dynamic_programming/longest_increasing_subsequence.rs)
- [ ] [K-Means Clustering](./src/general/kmeans.rs)
- [ ] [Coin Change](./src/dynamic_programming/coin_change.rs)
- [ ] [Rod Cutting](./src/dynamic_programming/rod_cutting.rs)
- [ ] [Egg Dropping Puzzle](./src/dynamic_programming/egg_dropping.rs)
- [ ] [Maximum Subarray](./src/dynamic_programming/maximum_subarray.rs)
- [ ] [Is Subsequence](./src/dynamic_programming/is_subsequence.rs)
- [ ] [Maximal Square](./src/dynamic_programming/maximal_square.rs)

### General

- [ ] [Convex Hull: Graham Scan](./src/general/convex_hull.rs)
- [ ] [N-Queens Problem](./src/general/nqueens.rs)
- [ ] Graph Coloring
- [ ] [Tower of Hanoi](./src/general/hanoi.rs)
- [ ] [Kmeans](./src/general/kmeans.rs)
- [ ] [Two Sum](./src/general/two_sum.rs)
- [ ] [Huffman Encoding](./src/general/huffman_encoding.rs)

### Ciphers

- [ ] [Caesar](./src/ciphers/caesar.rs)
- [ ] [Morse Code](./src/ciphers/morse_code.rs)
- [ ] [Polybius](./src/ciphers/polybius.rs)
- [ ] [SHA-2](./src/ciphers/sha256.rs)
- [ ] [TEA](./src/ciphers/tea.rs)
- [ ] [Transposition](./src/ciphers/transposition.rs)
- [ ] [Vigenère](./src/ciphers/vigenere.rs)
- [ ] [XOR](./src/ciphers/xor.rs)
- Rot13
  - [ ] [Another Rot13](./src/ciphers/another_rot13.rs)
  - [ ] [Rot13](./src/ciphers/rot13.rs)

### Bit Manipulation

- [ ] [Bit Distance](./src/bit_manipulation/basic.rs)
- [ ] [Bits Length](./src/bit_manipulation/basic.rs)
- [ ] [Clear Bit](./src/bit_manipulation/basic.rs)
- [ ] [Count Ones](./src/bit_manipulation/basic.rs)
- [ ] [Divide By Two](./src/bit_manipulation/basic.rs)
- [ ] [Get Bit](./src/bit_manipulation/basic.rs)
- [ ] [Is Even](./src/bit_manipulation/basic.rs)
- [ ] [Is Positive](./src/bit_manipulation/basic.rs)
- [ ] [Is Power Of Two](./src/bit_manipulation/basic.rs)
- [ ] [Multiply By Two](./src/bit_manipulation/basic.rs)
- [ ] [Multiply Signed](./src/bit_manipulation/basic.rs)
- [ ] [Multiply Unsigned](./src/bit_manipulation/basic.rs)
- [ ] [Set Bit](./src/bit_manipulation/basic.rs)
- [ ] [Twos Complement](./src/bit_manipulation/basic.rs)
- [ ] [Update Bit](./src/bit_manipulation/basic.rs)

### Geometry

- [ ] [Closest pair of 2D points](./src/geometry/closest_points.rs)

### Mathematics
- [ ] [Baby-Step Giant-Step Algorithm](./src/math/baby_step_giant_step.rs)
- [ ] [Extended euclidean algorithm](./src/math/extended_euclidean_algorithm.rs)
- [ ] [Gaussian Elimination](./src/math/gaussian_elimination.rs)
- [ ] [Greatest common divisor](./src/math/greatest_common_divisor.rs)
- [ ] [Greatest common divisor of n numbers](./src/math/gcd_of_n_numbers.rs)
- [ ] [Least common multiple of n numbers](./src/math/lcm_of_n_numbers.rs)
- [ ] [Miller Rabin primality test](./src/math/miller_rabin.rs)
- [ ] [Pascal's triangle](./src/math/pascal_triangle.rs)
- [ ] [Square root with Newton's method](./src/math/square_root.rs)
- [ ] [Fast power algorithm](./src/math/fast_power.rs)
- [ ] [Perfect number](./src/math/perfect_numbers.rs)
- [ ] [Prime factors](./src/math/prime_factors.rs)
- [ ] [Prime number](./src/math/prime_numbers.rs)
- [ ] [Linear Sieve](./src/math/linear_sieve.rs)
- [ ] [Pollard's Rho algorithm](./src/math/pollard_rho.rs)
- [ ] [Quadratic Residue](./src/math/quadratic_residue.rs)
- [ ] [Simpson's Rule for Integration](./src/math/simpson_integration.rs)
- [ ] [Fast Fourier Transform](./src/math/fast_fourier_transform.rs)
- [ ] [Armstrong Number](./src/math/armstrong_number.rs)
- [ ] [Permuted Congruential Random Number Generator](./src/math/random.rs)
- [ ] [Zeller's Congruence Algorithm](./src/math/zellers_congruence_algorithm.rs)
- [ ] [Karatsuba Multiplication Algorithm](./src/math/karatsuba_multiplication.rs)

### Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md)