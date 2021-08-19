# Batch-normalised LSTM
### Description
Pytorch implementation of the Batch-normalised LSTM (BNLSTM) cell proposed in [1].

The repository contains the code to launch the LSTM with and without batch-norm. In the case of launching without batch norm, there is the option of importing the weights and biases from the classic Pytorch's nn.LSTM module for testing and debugging. 

### References
1. Cooijmans, Tim, et al. «Recurrent Batch Normalization». arXiv:1603.09025 [cs], febrero de 2017. arXiv.org, http://arxiv.org/abs/1603.09025.