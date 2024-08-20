# A spiking neural network  model of the Superior Colliculus  that is robust to changes  in the spatial–temporal input
This repo records the the python codes for constructing a two-layer spiking neural network model with a cortical input 
layer, and a layer of superior colliculus (SC) output neurons. Each layer consists of 200 neurons, uniformly distributed on 0–5 mm of the horizontal meridian of the SC motor map.

Schematic overview of the two-layer feedforward neural network. The spiking neural network model generates different saccade-related bursts (bottom) that are evoked by a spatially translation-invariant input population (top), here positioned at T=5, 15 and 40 deg eccentricity. Thickness of the lines for the downward projections symbolizes the synaptic connection strengths, between the input and SC layers (high for the rostral zone, low for the caudal zone).


![image](https://github.com/user-attachments/assets/4d36e7b5-7345-4140-aad7-158dc7857c85)


The excitatory and inhibitory synaptic connections, and their total effect  for central neuron at neural population generating 15 deg saccade, result in a symmetric local excitatory and global inhibitory connectivity. 

![image](https://github.com/user-attachments/assets/ef1be35f-388e-4451-a5d7-75d51fc401aa)

Parameters were optimized by genetic algorithm (look at SNN_eye.py)
Eye-displacement amplitude, and peak eye velocity, as a function of the input current’s population size for stimulation at sites corresponding to T=15, 20 and 30 deg. 

![image](https://github.com/user-attachments/assets/27c65007-fd68-474b-a0ae-591a7d3e80ca)


