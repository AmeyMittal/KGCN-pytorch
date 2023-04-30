# KGCN-pytorch

This is the Pytorch implementation of [KGCN]

## Structure
1.  `data_loader.py`
    - data loader class for movie / music dataset
    - you don't need it if you make custom dataset

2. `aggregator.py`
    - aggregator class which implements 3 aggregation functions

3. `model.py`
    - KGCN model network

## Running the code

Look at the `KGCN.ipynb`.

It contains
- how to construct Datset
- how to construct Data loader
- how to train network
