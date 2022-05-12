---
title: "𝕙𝘆𝕡𝗲𝕤𝘆𝕤 Lab - Research"
layout: textlay
excerpt: "𝕙𝘆𝕡𝗲𝕤𝘆𝕤 Lab -- Research"
sitemap: false
permalink: /research/
---

# Research


We, as a group, target high-performance computing for autonomous system. Our research focus is primarily based on heterogeneous architectures, runtime systems, performance modelling, autonomous computing, machine learning acceleration. We target both the computationally-powerful platforms and heterogeneous embedded systems.

Our primarily goal is to fill out the gaps in heterogeneous computing by creating a system that can both efficiently use the resources on a given computing platform and maximize the effectiveness of accelerators. This is possible thanks to Mehmet's expertise on the area. He finished his post-doctoral study and work as a computer scientist at Oak Ridge National Laboratory (ORNL) on Computer Science and Mathematics Division Department. ORNL holds Summit supercomputer, which is the fastest supercomputer in USA for the last 4 years and the second among the world. His Ph.D. dissertation topic was also "Efficient Execution of Scientific Applications on Heterogeneous Architectures”. We also have multiple Ph.D., master and bachelor students from multiple areas with a deep background that works on our lab. 

Our current research topics are listed below:

**Low latency motion tracking for Autonomous Discovery Drones:**
* Autonomous Discovery & Intercept missions can provide valuable intel against an adversary. While prior work has been completed into individual parts of such a system, there is no open established framework for this task. As such there is a need for a former framework to be developed, that can serve as the basis for further research. This project builds a framework for an autonomous interception drone. Included in this framework are a physical and simulated test platform as well as the detection and control software for this scenario.

**CloudRenderVR: Motion-prediction based Speculative Cloud rendering for VR platforms**
* The project spans three components: The server, to render frames and update the game world. The model, to predict future human motion to allow for preemptive rendering. And, the client, to record pose data and communicate with both the server and the model.  

**Graph-based analytical computation models for autonomous software and heterogeneous hardware**
* In this project, we will build FLAME, a graph-based machine representation to flexibly model a given hardware design at any desired resolution while providing the ability to refine specific components along the hierarchy. FLAME allows each processing unit in the system to declare its specific capabilities and enables higher level elements to reuse and leverage these declarations to form more complex system topologies.

**Scheduling in heterogeneous architectures:**
* Balancing performance/energy trade-off in energy-limited systems: 
![]({{ site.url }}{{ site.baseurl }}/images/pubpic/MAE_Control_Flow_updated.png){: style="width: 250px; float: left; margin: 0px  8px"}
We work on running neural network (NN) inference on multiple accelerators of an SoC. Our goal is to enable an energy-performance trade-off with an by distributing layers in a NN between a performance- and a power-efficient accelerator. We first provide an empirical modeling methodology to characterize execution and inter-layer transition times. We then find an optimal layers-to-accelerator mapping by representing the trade-off as a linear programming optimization constraint. We evaluate our approach on the NVIDIA Xavier AGX SoC with commonly used NN models. We use the Z3 SMT solver to find schedules for different energy consumption targets, with up to 98% prediction accuracy.

* Multiple workload scheduling in heterogeneous architectures: We investigate Multi-accelerator Execution (MAE) on diversely heterogeneous embedded systems, where sub-components of a given workload, such as neural network inference, can be assigned to different type of accelerators to achieve a desired latency or energy goal. We first analyze the energy and performance characteristics of execution of neural network layers on different type of accelerators. We then explore energy/performance trade-offs via layer-wise scheduling for neural network inference by considering different layer-to-accelerator mappings.


**Autonomous Systems:**
* ![]({{ site.url }}{{ site.baseurl }}/images/pubpic/cauws.png){: style="width: 250px; float: left; margin: 0px  8px"} Hardware-CPS representation for performance modelling: Many cyber-physical systems (CPS) such as robots and self-driving cars pose strict timing requirements to avoid failure.These time-critical requirements limit the operating conditions of the system—e.g., driving slowly to ensure sufficient braking time to avoid a crash. We propose the creation of a structured system, the Constrained Autonomous Workload Scheduler (CAuWS). By using a representative language (AuWL), Timed Petri nets, and mixed-integer linear programming, CAuWS offers novel capabilities to represent and schedule many types of heterogeneous CPSs, real world constraints, and optimization criteria, creating a schedule of the optimal assignment of processors to tasks. This structured and general approach differs from current ad-hoc approaches which are either created for specific optimization criteria, architectures, or CPSs; or which don't consider physical constraints.

**GPU Utilization**
* ![]({{ site.url }}{{ site.baseurl }}/images/pubpic/dragon_img.png){: style="width: 250px; float: left; margin: 0px  8px"} Managing memory in GPU accelerated workloads is a difficult task especially as dataset sizes grow beyond available host memory on an  ndividual system. With GPU accelerated systems ranging from nodes on supercomputers, to data science workstations, working around traditional GPU memory limitations is important. On traditional GPU memory architectures if data is larger than GPU memory, the user must process their data in batches, adding complexity to the task. Architectures like NVIDIA’s Unified Virtual Memory (UVM) allow for users to allocate GPU memory across CPU and GPU memory, removing the limitations that data must be smaller than GPU memory. However, UVM still limits data sizes to be smaller than the combined CPU and GPU memory on the system.







<!-- **Scanning tunneling noise spectroscopy (STNS).** We have developed a novel cryogenic MHz amplifier that allows us to measure not only the average tunneling current, but also its fluctuation! This has many applications: one can detect the fluctuations of the electronic states, peculiar tunneling processes, and shot noise. We have used this instrument to discover charge trapping in the insulating layer of the cuprates, connected to the c-axis mystery, and to measure the doubling of the charge due to Andreev processes to the superfluid in a lead sample.


**Mott physics and high-temperature superconductivity.** Questions of interest include: (i), How does the Mott state collapse upon doping and how is this related to the complex phase diagram of high-temperature superconductors? (ii), What is the strange metal phase seen in correlated electron systems? Is this an exotic long-range entangled state? What is the mechanism of dissipation in that state? (iii), Why is the transition temperature in high-temperature superconductors so high? We have worked on iridates, rhodates, and cuprates.

**Nanofabricated "Smart Tips"**.
![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}
One of the  projects back from my job-proposal is to develop nanofabricated STM tips. The idea behind these “smart tips” is to use the technologies that were developed over decades in nanofabrication and make them available for scanning probe by using a nano-device instead of the traditional STM tungsten tip. One gains the flexibility of using different functionalities that are known from the fields of nanofabrication and mesoscopic physics. We are collaborating with the group Simon Groeblacher at TU Delft to realize this concept, benefitting from their unparalleled micro/nano fabrication know how.  A prototype of a smart tip is shown to the left. See publications in Microsyst Nanoeng, Nanotechnology, and PRB.

**Josephson STM.** Josephson STM has the ability to gain insight into spatial variations of the order parameter, or superfluid density. We have managed to, for the first time, use JSTM with atomic resolution on a quantum material.
We have used atomic-resolution Josephson scanning tunneling microscopy to reveal a strongly inhomogeneous superfluid in the iron-based superconductor FeTe0.55Se0.45. The results and their implications are published in Nature.

We also detected and investigated a quite particular YSR state in the same material.

**Ultra-stable SI-STM instrument.**  ![]({{ site.url }}{{ site.baseurl }}/images/respic/STMHead.png){: style="width: 250px; float: right; margin: 0px 10px"}
For SI-STM, having the most stable STM head is key. We have used finite element simulations, good choices in material science, and craftsmanship to build the most stable STM head in the world, to our knowledge. See publication in RSI.


**Strange Metals.** The strange metal phase might be the most mysterious phase of high-temperature superconductors. Here, the electrical resistivity grows linearly with temperature T in large areas of the phase diagram, with a mean free path that diminishes to a fraction of the interatomic distance. T-linear resistivity is often associated with quantum critical points and marginal-Fermi-liquid physics. In strange metals, the mystery seems to go even further: we deal with something that looks like a quantum critical phase over an extended range of the phase diagram instead of cumulating in a point. There exists no consistent theory for strange metals, leading to more adventurous new approaches including the holographic theories that use insights from gravity to explain strange metals (a recent textbook on this was written by our colleagues at Leiden University, Schalm and Zaanen).
We are part of the 'Strange Metal consortium NL' that includes the groups of Hussey, Golden, van Heumen, Zaanen, Schalm, Stoof and Vandoren. 

**Magnetic fluctuations and electron spin resonance.**
![]({{ site.url }}{{ site.baseurl }}/images/respic/SpinFluc.png){: style="width: 70%; float: center; margin: 10px"}

**Twisted bilayer graphene and other material with super-periodicities.**
We have proposed that artificial super-periodicities can lead to improved superconductivity, both because of increased density of states and because of phase space arguments (see image from our SciPost publication below). Perhaps for different reasons, twisted bilayer graphene has been shown to superconduct! We are investigate this material with the groups of Efetov, Baumberger, and van der Molen.

![]({{ site.url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"}

### ... and more. -->
