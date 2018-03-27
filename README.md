
## Highlights

| Authors (et al.)  | Title                                                                          | Venue (Link)           |
| :---------------- | :----------------------------------------------------------------------------- | :--------------------- |
| Neumann           | Efficient compiling query plans for modern hardware                            | [PVLDB'12][Neumann12]  |
| Dursun            | SiliconDB: rethinking DBMSs for modern heterogeneous co-processor ...          | [DAMON'17][SiliconDB]  |
| Breb              | GPU-Accelerated Database Systems: Survey and Open Challenges                   | [TLSDKCS'14][GPUDB]    |
| Pirk              | Voodoo - A Vector Algebra for Portable Database Performance on ...             | [VLDB'16][Voodoo]      |
| Klonatos          | Building Efficient Query Engines in a High-Level Language                      | [VLDB'14][Klonatos14]  |
| Stonebraker       | C-Store: A Column-oriented DBMS                                                | [VLDB'05][CStore]      |
| Kemper            | HyPer: A hybrid OLTP&OLAP main memory database system based on ...             | [ICDE'11][Hyper11]     | 
| ...               | ...                                                                            | ...                    |

[Neumann12]: https://dl.acm.org/citation.cfm?id=2002940
[SiliconDB]: https://dl.acm.org/citation.cfm?id=3076124
[GPUDB]: https://link.springer.com/chapter/10.1007/978-3-662-45761-0_1
[Voodoo]: http://www.vldb.org/pvldb/vol9/p1707-pirk.pdf
[Klonatos14]: http://www.vldb.org/pvldb/vol7/p853-klonatos.pdf
[CStore]: http://www.vldb.org/archives/website/2005/program/paper/thu/p553-stonebraker.pdf
[Hyper11]: http://ieeexplore.ieee.org/document/5767867/

## Related Papers

**See [tag convensions](convensions.md)**

### Sable Lab

1. Garg et al., Velociraptor: An Embedded Compiler Toolkit for Numerical Programs Targeting CPUs and GPUs
    - Tags: CPU, GPU
    - Keywords: VRIR, MATLAB, Python, JIT

### Others (A long list)

1. Mitschke et al., [i3QL: Language-Integrated Live Data Views][i3QL], OOPSLA'14
    - Tags: PL, DB
[i3QL]: https://dl.acm.org/citation.cfm?id=2660242

1. MapD - Massive Parallel Database
    - Tags: DB, GPU
    - Root et al., [MapD: a GPU-powered big data analytics and visualization platform][mapd16], 2016
[mapd16]: https://dl.acm.org/citation.cfm?id=2927468

1. Ocelot: A Hardware-Oblivious Database Engine
    - Tags: DB, GPU, MonetDB, OpenCL
    - [Homepage](https://bitbucket.org/msaecker/monetdb-opencl) (Last commit: 2016-05-11)

1. GPU Ocelot: open-source dynamic JIT compilation framework for GPU compute applications
    - Tags: GPU, PTX
    - About GPU Ocelot: [link](http://gpuocelot.gatech.edu/about/)

1. Kohn et al., Adaptive Execution of Compiled Queries, available [online][Kohn]
    - Tags: Hybrid
    - Keywords: Neumann, TPC-H, PostGRE, MonetDB
[Kohn]: https://db.in.tum.de/~leis/papers/adaptiveexecution.pdf

1. Palkar et al., Weld: A Common Runtime for High Performance Data Analytics, CIDR'17
    - Tags: Common IR
    - Keywords: cross functions, SQL, machine learning, graph analytics

1. Wu et al., Red Fox: An Execution Environment for Relational Query Processing on GPUs, CGO'14 ([pdf][redfox])
    - Tags: GPU
    - Keywords: Relational Query, GPU
[redfox](https://dl.acm.org/citation.cfm?id=2544166)

## The State-of-the-art Systems

* MapD
    - [Website][mapd-website] | [GitHub][mapd-github] | [Overview][mapd-overview] (Recommend)

[mapd-website]: https://www.mapd.com/
[mapd-overview]: http://www.smallake.kr/wp-content/uploads/2014/09/mapd_overview.pdf
[mapd-github]: https://github.com/mapd/mapd-core

* MoneDB
    - [Website][monetdb-website] | [GitHub][monetdb-github] | [Embedded NumPy][monetdb-numpy]

[monetdb-website]: https://www.monetdb.org/Home
[monetdb-github]: https://github.com/MonetDB/MonetDB
[monetdb-numpy]: https://www.monetdb.org/blog/embedded-pythonnumpy-monetdb

## Researchers

DB-prone

- [Thomas Neumann](http://dblp.uni-trier.de/pers/hd/n/Neumann_0001:Thomas): SQL query processing
- [Christoph Koch](http://dblp.uni-trier.de/pers/hd/k/Koch_0001:Christoph): Scala + DB

PL-prone

- [David Padua](http://dblp.uni-trier.de/pers/hd/p/Padua:David_A=): Vectorization

Both

- Chenglong Wang under [Rastislav Bodík](http://dblp.uni-trier.de/pers/hd/b/Bod=iacute=k:Rastislav): Program synthesis

## Others

- dplyr, FlumeJava, Pig Latin
- [XLA](https://www.tensorflow.org/performance/xla/): a domain-specific compiler for linear algebra that optimizes TensorFlow computation
- OpenACC: [resources](https://www.openacc.org/resources)
- CPU + FPGA: Intel HARP,
        [Intel altera](https://www.altera.com/solutions/acceleration-hub/academia.html),
        [Performance evaluation](https://www.cse.wustl.edu/~jain/cse567-17/ftp/harp/index.html),
        [Xeon + FPGA.pdf](https://www.ece.cmu.edu/~calcm/carl/lib/exe/fetch.php?media=carl15-gupta.pdf)

