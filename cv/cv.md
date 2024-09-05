# Zihan Sun 孙梓涵

Contact：(+86)19801338002

Email：sunzh22@mails.tsinghua.edu.cn

Github: https://github.com/Al0ha0e

Homepage: https://al0ha0e.github.io/szh.md




## Edcucation

2022.9 - present &emsp; **Tsinghua University** 

M.E., Computer Science, <u>3.85/4.0</u> GPA, supervised by Prof. Yong Zhang

2018.9 - 2022.7 &emsp; **Beijing University of Posts and Telecommunications** 

B.E., Computer Science, <u>90.55/100</u> GPA

## Awards

2019 Chinese National Scholarship

## Publications

Weimin Chen, **Zihan Sun**, Haoyu Wang, Xiapu Luo, Haipeng Cai, Lei Wu:
WASAI: uncovering vulnerabilities in Wasm smart contracts. ISSTA 2022: 703-715.

## Preprints

**Zihan Sun**, Yong Zhang, Chao Li, Chunxiao Xing:
Harnessing GPU Power for Enhanced OLTP: A Study in Concurrency Control Schemes. CoRR abs/2406.10158 (2024).

## Internship

2024.5 - 2024.9 &emsp; Meituan Co. LTD, Beijing, China, Software Engineer Intern
- Helped to migrate Meituan's customized NCCL communication library to the new NCCL and PyTorch version
- Customized torch.distributed library to accurately locate slow nodes in the distrubuted training process

## Patents

Yong Zhang, **Zihan Sun**, Chunxiao Xing, Chao Li, Ming Sheng.
Time Series Data Processing Methods, Apparatus and Equipment.
CN118260708A,
2024. 

Yi Sun, Linpeng Jia, **Zihan Sun**, Lei Yu.
A Blockchain-based Grid Computing System and Method
CN111475286A,
2020.

## Selected Projects

### Concurrency Control Test-Bed on GPU
- A research project to evaluate the performance of several concurrency control schemes with different workloads on GPU
- Implemented concurrency control shcemes including 2PL, T/O, MVCC, OCC using C++ and CUDA on GPU
- Designed a set of interfaces of transaction operations and representations of data types. Implemented a code generator using NVRTC to generation GPU code for different benchmark settings (CC schemes, indexes, transaction operations) at runtime
- Related Technologies: **C++**, **CUDA**
- https://github.com/Al0ha0e/gpu_cc_tb

### Voxel Renderer 
- Utilized C++ smart pointers and RAII mechanism to manage Vulkan resources
- Combined Dual-Countour algorithm and compute shader to implement high-performance voxel-based terrain modification
- Related Technologies: **C++**, **Vulkan**
- https://github.com/Al0ha0e/voxel_engine 

### PingCAP Talent Plan TinyKV
- TinyKV is a distributed KV database course opend sourced by PingCAP. Learners are required to implement key components of the Golang code framework in four subtasks to finally implement a Raft-based distributed KV storage system
- Refered to the Raft paper to implement leader election, log replication and snapshot application of the Raft protocol
- Implemented leader transfer, node addition/deletion and region splitting according to the document to implement a Multi-Raft cluster
- Refered to the Percolator paper to implement distributed transaction
- Related Technologies：**Golang**, **Raft**

## Technical Skills

- Mastered: C/C++，Golang，CUDA，Python，JavaScript, Linux, Git
- Others: MySQL, Redis, Socket, Raft 