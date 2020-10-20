[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/graph-random-neural-network/node-classification-on-citeseer-with-public)](https://paperswithcode.com/sota/node-classification-on-citeseer-with-public?p=graph-random-neural-network)[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/graph-random-neural-network/node-classification-on-pubmed-with-public)](https://paperswithcode.com/sota/node-classification-on-pubmed-with-public?p=graph-random-neural-network)[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/graph-random-neural-network/node-classification-on-cora-with-public-split)](https://paperswithcode.com/sota/node-classification-on-cora-with-public-split?p=graph-random-neural-network)

# grand
This is the code of paper: Graph Random Neural Network

## Requirements
* Python 3.7.3
* Please install other pakeages by 
``` pip install -r requirements.txt```

## Usage Example
* Running one trial on Cora:
```sh run_cora.sh ```
* Running 100 trials with random initializations on Cora:
```sh run100_cora.sh ```
* Calculating the average accuracy of 100 trails on Cora:
```python result_100run.py cora ```

## Running Environment 

The experimental results reported in paper are conducted on a single NVIDIA GeForce RTX 2080 Ti with CUDA 10.0, which might be slightly inconsistent with the results induced by other platforms.
