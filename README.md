# LB-SimTSC

## This is the code for our [[paper]](https://arxiv.org/abs/2301.04838) accepted by DLG-AAAI'23

### Quick Start 
1. Install required packages:
``` 
pip install -r requirements.txt
```
2. Prepare few shot datasets:
``` 
python create_dataset.py --dataset [DATASET] --shot [SHOT] --seed [SEED]
```
3. Prepare LB pairwise matrix:
``` 
python create_lb.py --dataset [DATASET]
```
4. Train LB-SimTSC:
```
python train_lbsimtsc.py --dataset [DATASET] --shot [SHOT]
```
