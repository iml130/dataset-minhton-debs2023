# Tree-structured Overlays with Minimal Height: Construction, Maintenance and Operation

This repository contains the dataset used for the evaluation figures 5 and 6 in the paper [_"Tree-structured Overlays with Minimal Height: Construction, Maintenance and Operation"_](https://doi.org/10.1145/3583678.3596894) published at the [17th ACM International Conference on Distributed and Event-based Systems (DEBS 2023)](https://2023.debs.org/).
We refer to the paper for a full explanation of the methodology used for generating the dataset.

## Abstract

Distributed systems, potentially growing large and consisting of heterogeneous nodes, are advised to be constructed following the Peer-to-Peer (P2P) networking paradigm.
It becomes imperative that a Peer-to-Peer (P2P) network is paired with efficient protocols for each phase of its life cycle: construction as well as maintenance and operation.
Three operations are fundamental for a Peer-to-Peer (P2P) network: nodes must be able to a) join, b) be located, c) leave.
The main challenge for efficient protocols is that a single node will only possess limited information about the network, also known as the local view.
In this paper, we present the minimal height tree overlay network (MINHTON), a Peer-to-Peer (P2P) overlay architecture featuring several beneficial structural properties added over existing tree-structured networks.
The minimal height guarantees a global tree balance, yet, it must be retained at all times, even though the Peer-to-Peer (P2P) network may change dynamically.
MINHTON provides efficient protocols for node Join and Departure, both retaining a minimal height tree.
We show that the operations achieve performance in logarithmic order, comparable to tree overlays with less strict structural guarantees.

## Reading the dataset

The dataset is stored as a comma-separated values (CSV) file, using a comma (,) as a delimiter.

## Citation

If you to cite the paper or this dataset for your research, please include the following reference in any resulting publication:

**ACM Reference Format:**

Patrick Laskowski, Peter Detzner, and Steffen Bondorf. 2023. Tree-structured Overlays with Minimal Height: Construction, Maintenance and Operation.
In _The 17th ACM International Conference on Distributed and Event-based Systems (DEBS ’23), June 27–30, 2023, Neuchatel, Switzerland_.
ACM, New York, NY, USA, 9 pages. [https://doi.org/10.1145/3583678.3596894](https://doi.org/10.1145/3583678.3596894)

**BibTeX Citation:**

```bibtex
@inproceedings{laskowskiTreestructuredOverlaysMinimal2023,
  author = {Laskowski, Patrick and Detzner, Peter and Bondorf, Steffen},
  title = {Tree-Structured Overlays with Minimal Height: Construction, Maintenance and Operation},
  booktitle = {The 17th ACM International Conference on Distributed and Event-based Systems},
  series = {DEBS '23},
  year = {2023},
  location = {Neuchatel, Switzerland},
  numpages = {9},
  url = {https://doi.org/10.1145/3583678.3596894},
  doi = {10.1145/3583678.3596894},
  acmid = {3596894},
  publisher = {ACM},
  address = {New York, NY, USA},
}
```
