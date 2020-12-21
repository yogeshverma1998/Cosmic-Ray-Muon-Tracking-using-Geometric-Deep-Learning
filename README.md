# Particle Track Reconstruction using Geometric Deep Learning

Tracking cosmic ray muons in a 3-D Scintillator detector simulated using GEANT-4 and air showers created using CORSIKA. The approach is based on using geometric deep learning a.k.a Graph Neural Networks by creating a undirected graph of hitpoints in the detector. The work is accpeted in XXIV DAE-BRNS High Energy Physics Symposium for [:bar_chart:](https://www.niser.ac.in/daehep2020/posters.php) and is availiable on [:page_facing_up:](https://arxiv.org/abs/2012.08515). 


# Input Data Generation




# Network Architecture


# Required Libraries
```js
python 3.6.8
ROOT + PyROOT 6.2
CORSIKA 
GEANT4
Pytorch 1.6.0 + CUDA 10.1
Torch-Geometric
Torch-Scatter
```
All other standard libraries like pandas, numpy etc are required. Detailed list and installation in server using anaconda environment is provided here: https://github.com/kschweiger/TF4ttHFH/blob/master/setup_t3PSI.sh

# Training
To train the model, Load the anaconda environment and change the input data files in Data_load.py to actual location of your dataset and set the path to save accuracy and loss plots in Train.py
```js
python Train.py
```

