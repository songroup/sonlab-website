---
title: Resources
nav:
  order: 6
  tooltip: Hardware, GPUs/CPUs
---

# {% include icon.html icon="fa-solid fa-wrench" %}Resources

Our lab mainly utilizes massively parallel MD simulation package OpenMM using graphical processing units (GPUs). Our lab creates a high-performance supercomputing ecosystem equipped with >100 GPUs (mostly GeForce 30 series + 10 RTX 4090 !), which enables a single simulation across multiple GPUs, or alternatively run a different simulation on each one at the same time.

|  Node  |                 GPUs              |                           CPUs                      |     RAM    |
| -----: | --------------------------------: | --------------------------------------------------: | ---------: |
|   15   |   NVIDIA GeForce RTX 4090   x 10  |    Intel(R) Xeon(R) Gold 6242R CPU     x 40cores    |    250GB   |
|   18   |   NVIDIA GeForce RTX 4090   x 6   |    Intel(R) Xeon(R) Gold 6348  CPU     x 112cores   |    500GB   |
|   19   |   NVIDIA GeForce RTX 4090   x 6   |    Intel(R) Xeon(R) Gold 6348  CPU     x 112cores   |    500GB   |
|   20   |   NVIDIA GeForce RTX 4090   x 10  |    Intel(R) Xeon(R) Platinum 8360Y CPU x 72cores    |    500GB   |
| -----: | --------------------------------: | --------------------------------------------------: | ---------: |
|   1    |   NVIDIA GeForce RTX 3090   x 8   |    Intel(R) Xeon(R) Gold 6230  CPU     x 32cores    |    125GB   |
|   3    |   NVIDIA GeForce RTX 3090   x 10  |    Intel(R) Xeon(R) CPU E5-2680 v4     x 28cores    |    250GB   |
|   11   |   NVIDIA GeForce RTX 3090   x 12  |    Intel(R) Xeon(R) Gold 6242R CPU     x 40cores    |    250GB   |
|   12   |   NVIDIA GeForce RTX 3090   x 12  |    Intel(R) Xeon(R) Gold 6242R CPU     x 40cores    |    250GB   |
|   13   |   NVIDIA GeForce RTX 3090   x 8   |    Intel(R) Xeon(R) Gold 6230R CPU     x 52cores    |    125GB   |
|   16   |   NVIDIA GeForce RTX 3090   x 10  |    Intel(R) Xeon(R) Gold 6242R CPU     x 40cores    |    250GB   |
| -----: | --------------------------------: | --------------------------------------------------: | ---------: |
|   5    |   NVIDIA GeForce RTX 3080Ti x 8   |    Intel(R) Xeon(R) Gold 6242R CPU     x 40cores    |    250GB   |
|   6    |   NVIDIA GeForce RTX 3080Ti x 8   |    Intel(R) Xeon(R) CPU E5-2699 v4     x 40cores    |    250GB   |



## GPU clusters (12 Nodes, 150 GPUs, 5,000 Tflops)


Server 14

Integrated GPU : 12 GPUs (NVIDIA GeForce RTX 3080 Ti)
Node : Intel(R) Xeon(R) Gold 6242R CPU (3.10GHz, 40 Cores) * 2 / 250 GB RAM

Server 17

Integrated GPU : 12 GPUs (NVIDIA GeForce RTX 3080 Ti)
Node : Intel(R) Xeon(R) Gold 6248R CPU (3.00GHz, 48 Cores) * 2 / 250 GB RAM
2nd generation GPU cluster (1 Nods, 35 GPUs, 471 Tflops)

## Master

Integrated GPU : 3 GPUs (NVIDIA GeForce RTX 2080 Ti)
Node : Intel(R) Core(TM) i9-10900X CPU (3.70GHz, 20 Cores) / 100 GB RAM
Left

32 GPUs (NVIDIA GeForce RTX 2080 Ti)
Non-GPU clusters

## Data Storage

nas1 : 490 TB

nas2: 490 TB

nasall : 80 TB
