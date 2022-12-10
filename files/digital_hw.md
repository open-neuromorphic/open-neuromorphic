# Digital hardware projects

Open-source digital hardware projects. 

## ODIN Spiking Neural Network (SNN) Processor

<img src="../images/odin-frenkel.png" alt="odin-frenkel" width="500"/>

[ODIN](https://github.com/ChFrenkel/ODIN) is an online-learning digital spiking neuromorphic processor designed and prototyped in 28-nm FDSOI CMOS at Université catholique de Louvain (UCLouvain), published in 2019 in the IEEE Transactions on Biomedical Circuits and Systems journal. ODIN is based on a single 256-neuron 64k-synapse crossbar neurosynaptic core with the following key features:

- synapses embed spike-dependent synaptic plasticity (SDSP)-based online learning,
- neurons can phenomenologically reproduce the 20 Izhikevich behaviors.

ODIN is thus a versatile experimentation platform for learning at the edge, while demonstrating (i) record neuron and synapse densities compared to all previously-proposed spiking neural networks (SNNs) and (ii) the lowest energy per synaptic operation across previously-proposed digital SNNs.

## ReckOn: A Spiking RNN Processor Enabling On-Chip Learning over Second-Long Timescales

<img src="../images/reckon-frenkel.png" alt="reckon-frenkel" width="500"/>

[ReckOn](https://github.com/ChFrenkel/ReckOn) is a spiking recurrent neural network (RNN) processor enabling on-chip learning over second-long timescales based on a modified version of the e-prop algorithm (we released a PyTorch implementation of the vanilla e-prop algorithm for leaky integrate-and-fire neurons here). It was prototyped and measured in 28-nm FDSOI CMOS at the Institute of Neuroinformatics, University of Zurich and ETH Zurich, and published at the 2022 IEEE International Solid-State Circuits Conference (ISSCC) with the following three main claims:

- ReckOn demonstrates end-to-end on-chip learning over second-long timescales while keeping a milli-second temporal resolution,
- it provides a low-cost solution with a 0.45-mm² core area, 5.3pJ/SOP at 0.5V, and a memory overhead of only 0.8% compared to the equivalent inference-only network,
- it exploits a spike-based representation for task-agnostic learning toward user customization and chip repurposing at the edge.

## SNE: an Energy-Proportional Digital Accelerator for Sparse Event-Based Convolutions 

<img src="../images/sne-di-mauro.png" alt="sne-di-mauro" width="500"/>

[SNE](https://github.com/pulp-platform/sne) is a novel digital sparse neural engine (SNE) to efficiently accelerate SNN inference tasks at the extreme edge. The accelerator exploits an explicit input event temporal and spatial location encoding; the SNE architecture is designed to improve input data and weight reuse, reducing the traffic towards the memory. SNE achieves a maximum performance of 51.2 GSOP/s, and an energy efficiency of 4.5TSOP/s/W. Ultimately, SNE shows 3.55X higher energy efficiency than SoA neuromorphic platform [16], approaching classical DNN accelerators energy efficiencies, while performing energy-proportional computations. As a proof of concept, it is shown that SNE consumes 0.221 pJ/SOP and achieves 92.8% accuracy on a classification task performed on the IBM DVS-Gesture data set. 

## A Lightweight Spiking Neural Network Accelerator [Google Shuttle]

<img src="../images/snn-asic-google-jason.png" alt="snn-asic-google-jason" width="500"/>

[A spiking neural network accelerator](https://github.com/jeshraghian/snn-accelerator) in the SkyWater 130nm process using heterogenous time constants to model a variety of temporal dynamics. Input events can be streamed at a rate of up to 50 MEvents per second, and the accelerator can process them in a dense network with 128 hidden neurons at up to approximately 214 MHz.

## SNN ASIC accelerator [Google Shuttle]

<img src="../images/snn-asic-google-pengzhou.png" alt="snn-asic-google-pengzhou" width="500"/>

An [SNN ASIC](https://github.com/pengzhouzp/wrapped_snn_network) with adaptive threshold neurons and recurrent connective synapses.
