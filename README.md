# ParallelizingDTW
This is the master repository for "A Study of Parallelizable Alternatives to Dynamic
Time Warping for Aligning Long Sequences".  You can find the paper [here](https://drive.google.com/file/d/1AuBtyGdU2XUfyiqZYusUpVVpFVNfamLl/view?usp=sharing).

For single-threaded, CPU implementations and results, visit [this repository](https://github.com/HMC-MIR/SegmentalDTW).

For a parallelized, GPU implementation of ParDTW with a python wrapper, visit [this repository](https://github.com/HMC-MIR/pyParDTW).
To use this implementation, first clone the repository, then install it using

`pip insall .`

Then, import the module and run the code

```
from pypardtw import pardtw
pardtw.pardtw(seq1, seq2, subsequence = False)
```

For example usage, look at the Example.ipynb notebook in the same repository


## Citation

Daniel Yang, Thaxter Shaw, and TJ Tsai.  A Study of Parallelizable Alternatives to Dynamic Time Warping for Aligning Long Sequences.  IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 30, pp. 2117-2127, 2022.


### Acknowledgments

This material is based upon work supported by the National Science Foundation under Grant No. 1948531.  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
