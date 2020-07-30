## LAD
Official python implementation of the paper: Laplacian Change Point Detection for Dynamic Graphs (KDD 2020)

arXiv link: https://arxiv.org/abs/2007.01229

![anomalous snapshots](figs/20122013.png)

For more info on me and my work, please checkout my [website](https://www.cs.mcgill.ca/~shuang43/). If you have any questions, feel free to contact me at my email: shenyang.huang@mail.mcgill.ca

Many thanks to my amazing co-authors: Yasmeen Hitti, [Guillaume Rabusseau](https://www-labs.iro.umontreal.ca/~grabus/), [Reihaneh Rabbany](http://www.reirab.com/) 

## Content:
all synthetic experiments and real world experiments from the paper can be reproduced here. 

## Datasets:
In datasets/, You can find edgeslists for both the synthetic and real world experiments we have. 

In datasets/canVote_processed, you can find our original Canadian Bill Voting network. 
if you use it, please cite this paper. 
 
## Usage:

1. first extract the edgelists in datasets/SBM_processed/hybrid, pure, resampled.zip

2. To reproduce synthetic experiments  (-n is the number of eigenvalues used) 

* python SBM_Command.py -f pure -n 499

substitute pure with hybrid or resampled for the corresponding settings

3. To reproduce real world experiments

* python Real_Command -d USLegis -n 6


## Library: 

1. python 3.8.1

2. scipy  1.4.1

3. scikit-learn 0.22.1

4. tensorly 0.4.5

5. networkx 2.4

6. matplotlib 1.3.1



## Citation:


