Jmod benchmarks
===============

The package ch.epfl.lis.jmod.benchmarks includes the following classes for generating community detection benchmarks:

* CliqueRingBenchmark
* ErdosRenyiBenchmark
* LFRBenchmark

The header of each class provides detailed information about the implementation of the benchmarks and how to run them. Note that their execution benefit from multiple processors in order to generate faster large number of benchmark networks.

Installing LFR binaries
-----------------------

LFRBenchmark requires the installation of Andrea Lancichinetti's binaries for generating LFR benchmarks.

1. Download the four archives from Andrea Lancichinetti's website and place them in the directory 'benchmarks' located in the project base directory
  * [binary_networks.tar.gz](https://sites.google.com/site/andrealancichinetti/files/binary_networks.tar.gz)
  * [directed_networks.tar.gz](https://sites.google.com/site/andrealancichinetti/files/directed_networks.tar.gz)
  * [weighted_directed_nets.tar.gz](https://sites.google.com/site/andrealancichinetti/files/weighted_directed_nets.tar.gz)
  * [weighted_networks.tar.gz](https://sites.google.com/site/andrealancichinetti/files/weighted_networks.tar.gz)
2. Go to the directory 'benchmarks' and run './install.sh' (requires execution permission)
3. Done