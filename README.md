# NRRSNN
The source code for the frontiers paper NRR-SNN

Different types of dynamics and plasticity principles founded out from natural neural networks have been well applied on Spiking neural networks (SNNs) for their biologically-plausible efficient and robust computations compared to their counterpart deep neural networks (DNNs).  Here we further propose a special Neuronal-plasticity and Reward-propagation improved Recurrent SNN (NRR-SNN). The historically-related adaptive threshold with two channels is highlighted as important neuronal plasticity for increasing the neuronal dynamics, and then global labels instead of errors are used as a reward for the paralleling gradient propagation. Besides, a recurrent loop with proper sparseness is designed for robust computation. Higher accuracy and stronger robust computation are achieved on two sequential datasets (i.e., TIDigits and TIMIT datasets), which to some extent, shows the power of the proposed NRR-SNN with biologically-plausible improvements.

You can use the following code to run the program

```python
python main.py
``` 

The `setup.py` is used to load the dataset. You need to change the `rootfile` variable to change the path of the dataset
