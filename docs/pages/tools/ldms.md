---
layout: page
title: Lightweight Distributed Metric Service (LDMS)
subtitle: High-Fidelity, Whole System, Synchonized Data Collection and Transport
---

LDMS provides an unprecedented ability to collect system data at resolutions necessary for detecting features and events of interest and to respond on meaningful timescales. Key features of LDMS are described here.

### No significant application impact ###
LDMS has been shown to have no significant impact on applications at collection rates (1Hz) necessary for resolving resource utilization features. This is enabled by:
**Optimized data structures** - data and metadata in memory are laid out to enable efficient data access. Metadata is only transported upon change, with most aggregation consisting of only the data values, which are smaller in size.

**Small, bounded footprint** - data is stored on-node in a user-specified memory region. This can be set to store only the most data sample in order to minimize the memory footprint.

**Efficient transport** - LDMS supports multiple transports including RDMA, IB, and socket. RDMA enables fetch with minimal CPU interruption. 

### Synchronized system snapshots ###
LDMS enables coherent whole-system analysis by collecting data as synchronized *snapshots* across the system. Data on all components is collected at the same time relative to each component's clock.

### Flexible transport topology with high fan-in ###
LDMS can collect and transport data on large node-count systems, with only a few aggregation points required. Multiple transports can be combined -- for instance data can be aggregated from compute nodes via RDMA over the high speed network and then transported off system via socket. In addition, arbitrary aggregation topologies are supported (not just tree-based) which can enable redirection and use of data anywhere, including exposure on compute nodes.

### Adding collectors and directing data to your data stores is easy ###
LDMS is easily extensible. Its plugin architecture makes the creation of additional samplers and stores simple and encapsulated. In addition, store plugins enable easy direction of LDMS output to different formats and consumers.

### Platform Independent ###
LDMS can run on all *nix OS

### For more information ###
* *[Lightweight Distributed Metric Service (LDMS)](https://github.com/ovis-hpc/ovis)* 
* *[Lightweight Distributed Metric Service: A Scalable Infrastructure for Continuous Monitoring of Large Scale Computing Systems and Applications](https://ovis.ca.sandia.gov/index.php/Publications_and_presentations)*. A. Agelastos, B. Allan, J. Brandt, P. Cassella, J. Enos, J. Fullop, A. Gentile, S. Monk, N. Naksinehaboon, J. Ogden, M. Rajan, M. Showerman, J. Stevenson, N. Taerat, and T. Tucker, IEEE/ACM Int'l. Conf. for High Performance Storage, Networking, and Analysis (SC14) Nov 2014.
