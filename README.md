# Classic Algorithms
Classic algorithms included in the Stanford [algorithm course](https://www.coursera.org/specializations/algorithms?) on Coursera, implemented in Python.

## Requirements

* Python 3.7+

## Getting started

Install dependencies

```shell script
pip install -r requirements.txt
```

## Algorithms
### Arithmetic
* Integer multiplication: [Karatsuba's algorithm](karatsuba_algorithm.py)
### Array
* Sort: [Merge Sort](merge_sort.py), [Quick Sort](quick_sort.py)
* Search: [Linear Search](linear_search.py)
* Inversions: [Inversion Count](count_inversions.py)
### Graph
* Minimum cut: [Karger's algorithm](karger_min_cut.py)
* Graph search: [BFS](graph_search.py), [DFS](graph_search.py), [topological sort](graph_search.py)
* Strongly connected components: [Kosaraju's algorithm](graph_search.py)
* Shortest path: [BFS](graph_search.py), [Dijkstra's alogrithm](dijsktra_shortest_path.py), 
[Bellman-Ford algorithm](bellman_ford_algorithm.py), [Floyd-Warshall algorithm](floyd_warshall_algorithm.py)
* Minimum spanning tree: [Prim's algorithm](prim_mst.py), [Kruskal's algorithm](max_spacing_clustering.py)
* Clustering: [Maximum Spacing Clustering](max_spacing_clustering.py)
* Maximum weight independent set: [Dynamic programming](max_weight_independent_set.py)
### Others
* Optimisation: [Greedy scheduling](greedy_scheduling.py)
* Lossless compression: [Huffman Coding](huffman_coding.py)

## Data Structures
* [Binary tree](binary_tree.py)
* [Heap](heap.py)
* [Hash table](hash_table.py)
* [Union find](union_find.py)