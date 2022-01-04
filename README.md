# ParallelizingDTW
This is the master repository for "A Study of Parallelizable Alternatives to Dynamic
Time Warping for Aligning Long Sequences"

For single-threaded, CPU implementations and results, visit [this repository](https://github.com/HMC-MIR/SegmentalDTW).

For a parallelized, GPU implementation of ParDTW with a python wrapper, visit [this repository](https://github.com/HMC-MIR/pyParDTW).
To use this implementation, first clone the repository, then install it using
`pip insall .`
Then, import the module and run the code
`from pypardtw import pardtw
pardtw.pardtw(seq1, seq2, subsequence = False)`
For example usage, look at the Example.ipynb notebook in the same repository
