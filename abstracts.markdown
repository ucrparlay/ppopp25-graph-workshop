---
layout: page
title: Detailed Talk Information
permalink: /abstracts/
---

### **Parallel and Space-Efficient Dynamic Graph Algorithms**

Abstract:   

I will argue that a lack of space-efficiency is one of the main bottlenecks preventing broader adoption and application of dynamic graph algorithms in other scientific fields and in industry.  I will then describe some recent and ongoing work on parallel batch-dynamic graph algorithms for undirected connectivity that significantly improve upon the space-efficiency of earlier methods while obtaining good theoretical guarantees and good practical performance.  I will end by describing some open problems and thoughts on how to make scalable and theoretically-efficient large-scale dynamic graph processing a reality.

Biography:

I am an Assistant Professor in the Department of Computer Science at the University of Maryland, College Park, and a research scientist at Google Research with the Graph Mining team. I obtained my Ph.D. from Carnegie Mellon University, where I was advised by Guy Blelloch, and was a postdoc at MIT working with Julian Shun. I am broadly interested in efficient and practical parallel algorithms, e.g., for parallel clustering and parallel graph processing. I am also interested in models of parallel computation motivated by emerging hardware and exploring these models theoretically and practically.

### **Recent Advances and Challenges in Parallel Graph Algorithms**

In this talk, we will provide a very brief overview of our recent work on various topics, including single-source shortest paths (SPAA'21), strong connectivity (JACM'20, SIGMOD'23), biconnectivity (PPoPP'23, Best Paper), breadth-first search (SPAA'24), k-core (SIGMOD'25), and more. We will discuss the challenges faced by existing parallel solutions, particularly regarding space efficiency and synchronization efficiency. Additionally, we will introduce our recent graph library, graph benchmarks, and a student competition targeting on graph challenges.

Biography:

Yan Gu is an Assistant Professor in the Computer Science and Engineering (CSE) Department at UC Riverside. He completed his PhD at Carnegie Mellon University in 2018 and his Bachelor’s degree at Tsinghua University in 2012. Before joining UCR, he spent one year as a postdoc at MIT. His research interest lies in designing simple and efficient algorithms with strong theoretical guarantees and good practical performance. He is a recipient of the NSF CAREER Award and the Google Research Scholar Program in 2024. He has won the Best Paper Awards at PPoPP'23 and ESA'23, the Best Paper Runner-up at VLDB'23, and the Outstanding Paper Awards at SPAA'24 and SPAA'20.


### **Randomized numerical linear algebra for graphs?**


Abstract: 

For graph computations that can be formulated in the language of linear algebra where an approximate answer would suffice, it's natural to apply the techniques of randomized numerical linear algebra to them. Sometimes that's easy to do, and sometimes it's hard. We'll illustrate this claim by two examples: triangle counting and all-pairs shortest paths. This work is joint with Irene Simó-Muñoz and Koby Hayashi.

Biography: 

Richard (“Rich”) Vuduc is a professor in the School of Computational Science and Engineering at Georgia Tech. His research lab, the HPC Garage, is interested in performance "by any means necessary," whether by smarter algorithms, better analysis, more effective programming techniques, or novel hardware.



### **Dynamic Graphs: Containers, Frameworks, and Benchmarks**

Abstract: 

In this talk, I will present our work on developing a dynamic graph container and a unified framework for evaluating graph containers. First, I will introduce Terrace, a streaming graph system built on hierarchical data structures to efficiently manage dynamic graph updates. Second, I will discuss BYO, a benchmarking framework designed to provide a standardized evaluation of graph containers, enabling comparative performance analysis across different systems.

Biography:

Prashant Pandey is an assistant professor in the Khoury College of Computer Sciences at Northeastern University, based in Boston.

With the exponential growth in humanity’s ability to generate, acquire, and store data, Pandey is focused on creating scalable data systems with robust theoretical foundations. His goal is to ensure that the next generation of data analysis systems can meet these evolving demands in an equitable way. His work spans the entire spectrum of this challenge, from exploring the theoretical aspects of data structures to addressing the practical issues of scaling data systems. Efficient data management plays a critical role in advancing research across various scientific fields, and Pandey has contributed to interdisciplinary data systems in areas such as computational biology, cybersecurity, stream processing, and storage systems.

Pandey has received the NSF CAREER Award and the IEEE-CS Early Career Researchers Award for Excellence in High Performance Computing, Catacosinos Fellowship, a Best paper award at FAST 2016, and Runner’s Up to Best Paper at FAST 2015. Prior to joining Khoury College, he spent a year as a research scientist at VMware and held postdoctoral research positions at UC Berkeley and Carnegie Mellon University.




### **T-thinker: A Task-Based Parallel Computing Model for Compute-Intensive Graph Analytics and Beyond**

Abstract:

Pioneered by Google's Pregel, the think-like-a-vertex (TLAV) computing model has dominated the area of parallel and distributed graph processing. However, TLAV models are only scalable for data-intensive iterative graph algorithms such as random walks and graph traversal. Unfortunately, researchers were using TLAV models to solve compute-intensive graph problems, leading to performance not much beyond that of a serial algorithm due to the IO bottleneck incurred by unnecessarily materializing a lot of intermediate data. This talk advocates a new parallel computing model called T-thinker, which adopts the think-like-a-task (TLAT) computing paradigm to divide the computing workloads of compute-intensive problems while allowing backtracking search to avoid data materialization as much as possible. We will explain how the T-thinker model can achieve ideal speedup ratio for many compute-intensive problems such as mining dense subgraphs, frequent subgraph pattern mining, and subgraph matching/enumeration. A number of TLAT-based systems will be covered including G-thinker, G-thinkerQ, T-FSM, PrefixFPM, G2-AIMD and T-DFS, which tackles compute-intensive graph problems in various settings such as on a shared-memory multi-core machine, on a distributed cluster, and on multiple GPUs. We will also explain how the T-thinker model applies beyond the graph domain to problems such as training big models consisting of many decision trees, and massively parallel spatial data processing.

Biography:

Da Yan is an Associate Professor in the Department of Computer Sciences of the Luddy School of Informatics, Computing, and Engineering (SICE) at Indiana University Bloomington. He received his Ph.D. degree in Computer Science from the Hong Kong University of Science and Technology in 2014, and he received my B.S. degree in Computer Science from Fudan University in Shanghai in 2009. He is a DOE Early Career Research Program (ECRP) awardee in 2023, and the sole winner of the Hong Kong 2015 Young Scientist Award in Physical/Mathematical Science. His research interests include parallel and distributed systems for big data analytics, data mining, and machine learning (esp. deep learning). He frequently publishes in top DB and AI conferences such as SIGMOD, VLDB, ICDE, KDD, ICML, ICLR, AAAI, IJCAI, EMNLP, and in top journals such as ACM TODS, VLDB Journal, IEEE TKDE, IEEE TPDS, ACM Computing Surveys. He also serves extensively in the major top DB and AI conferences and journals as reviewers, co-organized events such as the BIOKDD workshop with SIGKDD, Dagstuhl seminars, and a few top conferences, and he served as guest editors of journals such as IEEE/ACM TCBB, BMC Bioinformatics, and IEEE CG&A.







