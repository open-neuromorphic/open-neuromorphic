![logo](images/ONM.png)
# Open Neuromorphic

This organisation is created by a loose collective of open source collaborators across academia, industry and individual contributors. What connects us is the love for building tools that can be used in the neuromorphic community and we want to share ownership of this vision. Open Neuromorphic (ONM) provides two things:

1. A curated list of software frameworks to make it easier to find the tool you need.
2. A platform for your code. If you wish to create a new repository or migrate your existing code to ONM, please get in touch with us. You will be made a member of this organisation immediately. 

Projects that we list here can fall into this non-exclusive list of categories:
- Spiking Neural Networks (SNNs) training and/or inference, for both ML and neuroscience application.
- Event-based sensor data handling.
- Digital hardware designs for neuromorphic applications.
- Mixed-signal hardware designs for neuromorphic applications.

# List of resources

## SNN training frameworks for ML

Open-source software to train spiking neural networks for ML tasks.

### snnTorch

<img src="images/snntorch.png" alt="snntorch" width="500"/>

[snnTorch](https://github.com/jeshraghian/snntorch) is a SNN training framework for machine learning applications. It is focused on gradient-based training of SNNs. 
It is based on PyTorch for GPU acceleration and gradient computation. 

### Norse

<img src="images/norse.png" alt="norse" width="500"/>

[Norse](https://norse.github.io/norse/) aims at exploiting the advantages of bio-inspired neural components, which are sparse and event-driven - a fundamental difference from artificial neural networks. Norse expands PyTorch with primitives for bio-inspired neural components, bringing you two advantages: a modern and proven infrastructure based on PyTorch and deep learning-compatible spiking neural network components.

### Sinabs

<img src="images/sinabs.png" alt="sinabs" width="500"/>

[Sinabs](https://sinabs.readthedocs.io) is a deep learning library based on PyTorch for spiking neural networks, with a focus on simplicity, fast training and extendability. Sinabs works well for Vision models because of its support for weight transfer.

### Rockpool

<img src="images/rockpool.png" alt="rockpool" width="500"/>

[Rockpool](https://synsense.gitlab.io/rockpool/) is a Python package for working with dynamical neural network architectures, particularly for designing event-driven networks for Neuromorphic computing hardware. Rockpool provides a convenient interface for designing, training and evaluating recurrent networks, which can operate both with continuous-time dynamics and event-driven dynamics.

### BindsNET

<img src="images/bindsnet.jpg" alt="bindsnet" width="500"/>

[BindsNET](https://bindsnet-docs.readthedocs.io/) is built on top of the PyTorch deep learning platform. It is used for the simulation of spiking neural networks (SNNs) and is geared towards machine learning and reinforcement learning.

## SNN training frameworks for neuroscience

Open-source software to train spiking neural networks. In these the tools, the goal is to emulate the human brain as efficiently as possible, instead of optimizing neuron model and simulation for speeding up AI tasks.

### Brian

<img src="images/brian.png" alt="brian" width="500"/>

[Brian](https://briansimulator.org/) is a free, open source simulator for spiking neural networks. It is written in the Python programming language and is available on almost all platforms. We believe that a simulator should not only save the time of processors, but also the time of scientists. Brian is therefore designed to be easy to learn and use, highly flexible and easily extensible.

### NEST

<img src="images/nest.png" alt="nest" width="500"/>

[NEST](https://www.nest-simulator.org/) is a simulator for spiking neural network models that focuses on the dynamics, size and structure of neural systems rather than on the exact morphology of individual neurons. The development of NEST is coordinated by the NEST Initiative.

NEST is ideal for networks of spiking neurons of any size, for example:

- models of information processing e.g. in the visual or auditory cortex of mammals,
- models of network activity dynamics, e.g. laminar cortical networks or balanced random networks,
- models of learning and plasticity.

## SNN training frameworks for ML and neuroscience

Open-source software to train spiking neural networks for both neuroscience and ML applications.

### Nengo

<img src="images/nengo.jpg" alt="nengo" width="500"/>

[Nengo](https://nengo.ai) is a Python package for building, testing, and deploying neural networks.

<img src="images/nengo_structure.svg" alt="nengo_structure" width="500"/>

It supports plenty of backends for the SNN simulation.

### Lava

<img src="images/lava.png" alt="lava" width="500"/>

[Lava](https://lava-nc.org/) is an open-source software framework for developing neuro-inspired applications and mapping them to neuromorphic hardware. Lava provides developers with the tools and abstractions to develop applications that fully exploit the principles of neural computation. Constrained in this way, like the brain, Lava applications allow neuromorphic platforms to intelligently process, learn from, and respond to real-world data with great gains in energy efficiency and speed compared to conventional computer architectures.

## Dynamic vision sensors utilities

Open-source software to handle data generated by event-based cameras.

### Tonic

<img src="images/tonic.png" alt="tonic" width="500"/>

[Tonic](https://github.com/neuromorphs/tonic) is a tool to facilitate the download, manipulation and loading of event-based/spike-based data. It's like PyTorch Vision but for neuromorphic data!

### expelliarmus 

<img src="images/expelliarmus.png" alt="expelliarmus" width="500"/>

[expelliarmus](https://github.com/open-neuromorphic/expelliarmus) is a Python/C package to decode binary files produced by Prophesee cameras. 

### AEStream - Address Event Streaming library

[AEStream](https://github.com/norse/aestream) parses event-based dynamic-vision system (DVS) data from an input source and streams it to a sink (GPU, CPU, network ports...).

### AEDAT

[AEDAT](https://github.com/open-neuromorphic/aedat) is a fast AEDAT 4 python reader, with a Rust underlying implementation.

### OpenEB

<img src="images/metavision.png" alt="metavision" width="500"/>

[OpenEB](https://github.com/prophesee-ai/openeb) is the open source project associated with [Metavision Intelligence](https://www.prophesee.ai/metavision-intelligence/).

It enables anyone to get a better understanding of event-based vision, directly interact with events and build their own applications or plugins. As a camera manufacturer, ensure your customers benefit from the most advanced event-based software suite available by building your own plugin.

## Digital hardware projects

Open-source digital hardware projects. 

### ODIN Spiking Neural Network (SNN) Processor

<img src="images/odin-frenkel.png" alt="odin-frenkel" width="500"/>

[ODIN](https://github.com/ChFrenkel/ODIN) is an online-learning digital spiking neuromorphic processor designed and prototyped in 28-nm FDSOI CMOS at Université catholique de Louvain (UCLouvain), published in 2019 in the IEEE Transactions on Biomedical Circuits and Systems journal. ODIN is based on a single 256-neuron 64k-synapse crossbar neurosynaptic core with the following key features:

- synapses embed spike-dependent synaptic plasticity (SDSP)-based online learning,
- neurons can phenomenologically reproduce the 20 Izhikevich behaviors.

ODIN is thus a versatile experimentation platform for learning at the edge, while demonstrating (i) record neuron and synapse densities compared to all previously-proposed spiking neural networks (SNNs) and (ii) the lowest energy per synaptic operation across previously-proposed digital SNNs.

### ReckOn: A Spiking RNN Processor Enabling On-Chip Learning over Second-Long Timescales

<img src="images/reckon-frenkel.png" alt="reckon-frenkel" width="500"/>

[ReckOn](https://github.com/ChFrenkel/ReckOn) is a spiking recurrent neural network (RNN) processor enabling on-chip learning over second-long timescales based on a modified version of the e-prop algorithm (we released a PyTorch implementation of the vanilla e-prop algorithm for leaky integrate-and-fire neurons here). It was prototyped and measured in 28-nm FDSOI CMOS at the Institute of Neuroinformatics, University of Zurich and ETH Zurich, and published at the 2022 IEEE International Solid-State Circuits Conference (ISSCC) with the following three main claims:

- ReckOn demonstrates end-to-end on-chip learning over second-long timescales while keeping a milli-second temporal resolution,
- it provides a low-cost solution with a 0.45-mm² core area, 5.3pJ/SOP at 0.5V, and a memory overhead of only 0.8% compared to the equivalent inference-only network,
- it exploits a spike-based representation for task-agnostic learning toward user customization and chip repurposing at the edge.

### SNE: an Energy-Proportional Digital Accelerator for Sparse Event-Based Convolutions 

<img src="images/sne-di-mauro.png" alt="sne-di-mauro" width="500"/>

[SNE](https://github.com/pulp-platform/sne) is a novel digital sparse neural engine (SNE) to efficiently accelerate SNN inference tasks at the extreme edge. The accelerator exploits an explicit input event temporal and spatial location encoding; the SNE architecture is designed to improve input data and weight reuse, reducing the traffic towards the memory. SNE achieves a maximum performance of 51.2 GSOP/s, and an energy efficiency of 4.5TSOP/s/W. Ultimately, SNE shows 3.55X higher energy efficiency than SoA neuromorphic platform [16], approaching classical DNN accelerators energy efficiencies, while performing energy-proportional computations. As a proof of concept, it is shown that SNE consumes 0.221 pJ/SOP and achieves 92.8% accuracy on a classification task performed on the IBM DVS-Gesture data set. 

### A Lightweight Spiking Neural Network Accelerator [Google Shuttle]

<img src="images/snn-asic-google-jason.png" alt="snn-asic-google-jason" width="500"/>

[A spiking neural network accelerator](https://github.com/jeshraghian/snn-accelerator) in the SkyWater 130nm process using heterogenous time constants to model a variety of temporal dynamics. Input events can be streamed at a rate of up to 50 MEvents per second, and the accelerator can process them in a dense network with 128 hidden neurons at up to approximately 214 MHz.

### SNN ASIC accelerator [Google Shuttle]

<img src="images/snn-asic-google-pengzhou.png" alt="snn-asic-google-pengzhou" width="500"/>

An [SNN ASIC](https://github.com/pengzhouzp/wrapped_snn_network) with adaptive threshold neurons and recurrent connective synapses.
