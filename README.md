# RingAttractorModel_HDneuron
Using ring attractor model to simulate neural activity of head direction cells
# RingAttractorModel_HDneuron

This project implements a firing rate network model for a bump attractor with continuous ring connectivity. The model simulates a ring of neurons, designed to serve as a Head-Direction (HD) cell network, which is capable of maintaining stable activity bumps representing angular head direction.

## Overview

The `RingAttractorModel_HDneuron` simulates the dynamic behavior of neurons in a continuous ring configuration. This model is particularly useful for studying how populations of neurons can encode and maintain a stable directional signal, a key feature of head-direction cells in the brain.

### Key Features

- **Ring Connectivity**: Neurons are arranged in a ring, with their connectivity following a Gaussian-like profile, ensuring that nearby neurons excite each other while distant ones inhibit each other.
- **Dynamic Simulation**: The model integrates neural activities over time using Euler's method, allowing for the observation of how activity bumps evolve and stabilize.
- **Fourier Analysis**: Fourier transforms are used to analyze the frequency components of the neuron firing rates and connectivity weights.
- **Regularization**: Weight regularization ensures that the connectivity matrix remains stable and well-conditioned, which is crucial for maintaining the bump attractor dynamics.

## Installation

To run this model, you need MATLAB installed on your system. The code does not require any additional toolboxes, making it easy to run in any MATLAB environment.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RingAttractorModel_HDneuron.git
   
## Implementation 1: single direction hd cell
The implementation by matlab code for [Zhang, K. (1996). Representation of 
spatial orientation by the intrinsic dynamics of the head-direction
cell ensemble: a theory. The Journal of Neuroscience, 16(6), 2112-2126.](https://www.jneurosci.org/content/16/6/2112)

## Implementation 2: double directions hd cell




## References

- [Brunel, N., & Wang, X. J. (2003). What determines the frequency of fast network oscillations with irregular neural discharges? I. Synaptic dynamics and excitation-inhibition balance. Journal of Neurophysiology, 90(1), 415-430.](https://journals.physiology.org/doi/full/10.1152/jn.01095.2002)
- [Zhang, K. (1996). Representation of spatial orientation by the intrinsic dynamics of the head-direction cell ensemble: a theory. The Journal of Neuroscience, 16(6), 2112-2126.](https://www.jneurosci.org/content/16/6/2112)
