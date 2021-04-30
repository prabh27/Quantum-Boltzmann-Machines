# Quantum-Boltzmann-Machines
Quantum Restricted Boltzmann Machines based on the paper: https://arxiv.org/abs/1712.05304 

Code modified from the author's code (https://github.com/MichaelBroughton/QABoM) to support the latest Forest apis and Python 3.x

# Installation
1. `conda env create --file conda_requirements.yml`
2. conda activate qrbm
2. pip install quantum-grove

# How to run the code?
0. Install Forest SDK version 2.23.0 from: https://qcs.rigetti.com/sdk-downloads
1. Start two screens/tmux sessions. Run `qvm -S` on the first screen and `quilc -S` on the second one. 
2. Run the simple_demo jupyter notebook to get an understanding of the code.
