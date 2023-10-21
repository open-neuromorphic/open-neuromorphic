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

Get in touch with the organization on [Discord](https://discord.gg/JParSCNe5k)!

# List of resources

## SNN training frameworks for ML

Open-source software to train spiking neural networks for ML tasks.


<table>

<tr>
<td>
<a href="https://bindsnet-docs.readthedocs.io/"><img src="images/bindsnet.jpg" alt="bindsnet" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/bindsnet/bindsnet?style=social)
</td>
<td>

[BindsNET](https://bindsnet-docs.readthedocs.io/) is built on top of the PyTorch deep learning platform. It is used for the simulation of spiking neural networks (SNNs) and is geared towards machine learning and reinforcement learning.

</td>
</tr>

<tr>
<td><a href="https://norse.github.io/norse/"><img src="images/norse.png" alt="Norse" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/norse/norse?style=social)

</td>
<td>

[Norse](https://norse.github.io/norse/) aims at exploiting the advantages of bio-inspired neural components, which are sparse and event-driven - a fundamental difference from artificial neural networks. Norse expands PyTorch with primitives for bio-inspired neural components, bringing you two advantages: a modern and proven infrastructure based on PyTorch and deep learning-compatible spiking neural network components.

</td>
</tr>

<tr>
<td><a src="https://synsense.gitlab.io/rockpool/"><img src="images/rockpool.png" alt="Rockpool" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/synsense/rockpool?style=social)</td>
<td>

[Rockpool](https://synsense.gitlab.io/rockpool/) is a Machine Learning library for SNN applications. Design, train and test with GPU, TPU and CPU acceleration (based on PyTorch and Jax), then deploy to Neuromorphic compute hardware. Offers a convenient Torch-like API, and extensive documentation.
</td>
</tr>

<tr>
<td><a href="https://github.com/jeshraghian/snntorch"><img src="images/snntorch.png" alt="snnTorch" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/jeshraghian/snntorch?style=social)</td>
<td>

[snnTorch](https://github.com/jeshraghian/snntorch) is a SNN training framework for machine learning applications. It is focused on gradient-based training of SNNs. 
It is based on PyTorch for GPU acceleration and gradient computation.

</td>
</tr>

<tr>
<td><a href="https://github.com/kmheckel/spyx"><img src="blob/main/spyx.png" alt="Spyx" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/kmheckel/spyx?style=social) </td>

<td>

[Spyx](https://github.com/kmheckel/spyx) is a compact spiking neural network package built on top of DeepMind's Haiku library. Based on JAX, it permits Just-In-Time compilation of partial or entire training loops for maximal utilization on GPUs and TPUs.

</td>
</tr>

<tr>
<td>
 
![GitHub Repo stars](https://img.shields.io/github/stars/fangwei123456/spikingjelly?style=social)</td>
<td>

[SpikingJelly](https://github.com/fangwei123456/spikingjelly) is an open-source deep learning framework for Spiking Neural Network (SNN) based on PyTorch.
The documentation of SpikingJelly is written in both English and Chinese: https://spikingjelly.readthedocs.io.

</td>
</tr>

<tr>
<td><a href="https://sinabs.readthedocs.io"><img src="images/sinabs.png" alt="Sinabs" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/synsense/sinabs?style=social)</td>
<td>

[Sinabs](https://sinabs.readthedocs.io) is a deep learning library based on PyTorch for spiking neural networks, with a focus on simplicity, fast training and extendability. Sinabs works well for Vision models because of its support for weight transfer.

</td>
</tr>

</table>


## SNN training frameworks for neuroscience

Open-source software to train spiking neural networks. In these the tools, the goal is to emulate the human brain as efficiently as possible, instead of optimizing neuron model and simulation for speeding up AI tasks.

<table>
<tr>
<td><a href="https://briansimulator.org/"><img src="images/brian.png" alt="Brian" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/brian-team/brian2?style=social)</td>
<td>

[Brian](https://briansimulator.org/) is a free, open source simulator for spiking neural networks. It is written in the Python programming language and is available on almost all platforms. We believe that a simulator should not only save the time of processors, but also the time of scientists. Brian is therefore designed to be easy to learn and use, highly flexible and easily extensible.

</td>
</tr>


<tr>
<td><a href="https://www.nest-simulator.org/"><img src="images/nest.png" alt="nest" width="1000px"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/nest/nest-simulator?style=social)</td>
<td>
[NEST](https://www.nest-simulator.org/) is a simulator for spiking neural network models that focuses on the dynamics, size and structure of neural systems rather than on the exact morphology of individual neurons. The development of NEST is coordinated by the NEST Initiative.

NEST is ideal for networks of spiking neurons of any size, for example:

- models of information processing e.g. in the visual or auditory cortex of mammals,
- models of network activity dynamics, e.g. laminar cortical networks or balanced random networks,
- models of learning and plasticity.
</td>
</tr>

</table>

## SNN training frameworks for ML and neuroscience
Open-source software to train spiking neural networks for both neuroscience and ML applications.


<table>

<tr>
<td><a href="https://nengo.ai/"><img src="images/nengo.jpg" alt="Nengo"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/nengo/nengo?style=social)</td>
<td>

[Nengo](https://nengo.ai) is a Python package for building, testing, and deploying neural networks.
It supports plenty of backends for the SNN simulation.

</td>
</tr>

<tr>
<td><a href="https://lava-nc.org/"><img src="images/lava.png" alt="Lava"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/lava-nc/lava?style=social)</td>
<td>


[Lava](https://lava-nc.org/) is an open-source software framework for developing neuro-inspired applications and mapping them to neuromorphic hardware. Lava provides developers with the tools and abstractions to develop applications that fully exploit the principles of neural computation. Constrained in this way, like the brain, Lava applications allow neuromorphic platforms to intelligently process, learn from, and respond to real-world data with great gains in energy efficiency and speed compared to conventional computer architectures.

</td>
</tr>



</table>


## Event-based data utilities

Open-source software to handle event-based data, including data generated by dynamic vision sensors and other neuromorphic sensors.


<table>


<tr>
<td><a href="https://github.com/neuromorphs/tonic"><img src="https://github.com/neuromorphs/tonic/raw/develop/docs/_static/tonic-logo-black.png" alt="tonic"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/neuromorphs/tonic?style=social)</td>
<td>

[Tonic](https://github.com/neuromorphs/tonic) is a tool to facilitate the download, manipulation and loading of event-based/spike-based data. It's like PyTorch Vision but for neuromorphic data!

</td>
</tr>


<tr>
<td><a href="https://github.com/open-neuromorphic/expelliarmus"><img src="https://raw.githubusercontent.com/open-neuromorphic/expelliarmus/develop/docs/_static/Logo.png" alt="Expelliarmus"/></a>

![GitHub Repo stars](https://img.shields.io/github/stars/open-neuromorphic/expelliarmus?style=social)</td>
<td>

[expelliarmus](https://github.com/open-neuromorphic/expelliarmus) is a Python/C package to decode binary files produced by Prophesee cameras. 

</td>
</tr>


<tr>
<td>

![GitHub Repo stars](https://img.shields.io/github/stars/norse/aestream?style=social)</td>
<td>

[AEStream](https://github.com/norse/aestream) parses event-based dynamic-vision system (DVS) data from an input source and streams it to a sink (GPU, CPU, network ports...).

</td>
</tr>


<tr>
<td>

![GitHub Repo stars](https://img.shields.io/github/stars/neuromorphicsystems/aedat?style=social)</td>
<td>

[AEDAT](https://github.com/open-neuromorphic/aedat) is a fast AEDAT 4 python reader, with a Rust underlying implementation.
</td>
</tr>


<tr>
<td>

![GitHub Repo stars](https://img.shields.io/github/stars/event-driven-robotics/bimvee?style=social)</td>
<td>

[BIMVEE](https://github.com/event-driven-robotics/bimvee) is an open-source python library for Batch Import, Manipulation, Visualisation and Export of Events etc. It has import routines for several different event formats including, notably, a python-native unpacker of rpg-rosbags (no ROS installation required). It imports event data together with bundled data such as rgb images, point-clouds, IMU etc, handling timestamp synchronisation. It has visualisers with intuitive defaults, allowing quick visualisation of the contents of event-data containers, and it has export routines for several data formats. Manipulations include time-stamp re-alignments, spatial cropping and event filtering. 

</td>
</tr>


<tr>
<td>

![GitHub Repo stars](https://img.shields.io/github/stars/event-driven-robotics/mustard?style=social)</td>
<td>

[MUSTARD](https://github.com/event-driven-robotics/mustard) is an open-source python application for playback of multistream data, including event-camera data. Each data stream present in a container (such as rosbag, but it can import any data-type which BIMVEE supports) opens a visualiser sub-window and data playback of all visualisers is controlled globally, including the speed, direction and time-window of visualisation. It has visualisers for events, rgb images, 6-DOF poses, point-clouds, depth maps etc. 

</td>
</tr>


</table>



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

### RANC - Reconfigurable Architecture for Neuromorphic Computing

<img src="images/ranc.png" alt="ranc" width="500"/>

[RANC](https://ua-rcl.github.io/RANC/) is a highly flexible environment that enables rapid experimentation with neuromorphic architectures in both software via C++ simulation and hardware via FPGA emulation. RANC enables hardware architects and application engineers to investigate and tune parameters of their neuromorphic architecture that would otherwise be unavailable on a purely prefabricated ASIC. This level of flexibility creates an environment that allows for optimizing architectures based on application insights as well as prototyping future neuromorphic architectures that can support new classes of applications entirely.

### SNE: an Energy-Proportional Digital Accelerator for Sparse Event-Based Convolutions 

<img src="images/sne-di-mauro.png" alt="sne-di-mauro" width="500"/>

[SNE](https://github.com/pulp-platform/sne) is a novel digital sparse neural engine (SNE) to efficiently accelerate SNN inference tasks at the extreme edge. The accelerator exploits an explicit input event temporal and spatial location encoding; the SNE architecture is designed to improve input data and weight reuse, reducing the traffic towards the memory. SNE achieves a maximum performance of 51.2 GSOP/s, and an energy efficiency of 4.5TSOP/s/W. Ultimately, SNE shows 3.55X higher energy efficiency than SoA neuromorphic platform [16], approaching classical DNN accelerators energy efficiencies, while performing energy-proportional computations. As a proof of concept, it is shown that SNE consumes 0.221 pJ/SOP and achieves 92.8% accuracy on a classification task performed on the IBM DVS-Gesture data set. 

### A Lightweight Spiking Neural Network Accelerator [Google Shuttle]

<img src="images/snn-asic-google-jason.png" alt="snn-asic-google-jason" width="500"/>

[A spiking neural network accelerator](https://github.com/jeshraghian/snn-accelerator) in the SkyWater 130nm process using heterogenous time constants to model a variety of temporal dynamics. Input events can be streamed at a rate of up to 50 MEvents per second, and the accelerator can process them in a dense network with 128 hidden neurons at up to approximately 214 MHz.

### SNN ASIC accelerator [Google Shuttle]

<img src="images/snn-asic-google-pengzhou.png" alt="snn-asic-google-pengzhou" width="500"/>

An [SNN ASIC](https://github.com/pengzhouzp/wrapped_snn_network) with adaptive threshold neurons and recurrent connective synapses.

### OpenSpike: An OpenRAM SNN AcceleratorOpenSpike

<img src="images/OpenSpike.png" alt="OpenSpike"/>

This paper presents a spiking neural network (SNN) accelerator made using fully open-source EDA tools, process design kit (PDK), and memory macros synthesized using OpenRAM. The chip is taped out in the 130 nm SkyWater process and integrates over 1 million synaptic weights, and offers a reprogrammable architecture. It operates at a clock speed of 40 MHz, a supply of 1.8 V, uses a PicoRV32 core for control, and occupies an area of 33.3 mm^2. The throughput of the accelerator is 48,262 images per second with a wallclock time of 20.72 us, at 56.8 GOPS/W. The spiking neurons use hysteresis to provide an adaptive threshold (i.e., a Schmitt trigger) which can reduce state instability. This results in high performing SNNs across a range of benchmarks that remain competitive with state-of-the-art, full precision SNNs. The design is open source and [available online](https://github.com/sfmth/OpenSpike).
