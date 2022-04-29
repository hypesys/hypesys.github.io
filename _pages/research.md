---
title: "𝕙𝘆𝕡𝗲𝕤𝘆𝕤 Lab - Research"
layout: textlay
excerpt: "𝕙𝘆𝕡𝗲𝕤𝘆𝕤 Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

TODO: This part requires more help to explain our works in the lab. Open to all suggestions. I could fill the initial parts since I'm working on those. We can fill the rest. 

We, as a group, target high-performance computing for autonomous system. Our research focus is primarily based on heterogeneous architectures, runtime systems, performance modelling, autonomous computing, machine learning acceleration. We target both the computationally-powerful platforms and heterogeneous embedded systems.

Our primarily goal is to fill out the gaps in heterogeneous computing by creating a system that can both efficiently use the resources on a given computing platform and maximize the effectiveness of accelerators. This is possible thanks to Mehmet's expertise on the area. He finished his post-doctoral study and work as a computer scientist at Oak Ridge National Laboratory (ORNL) on Computer Science and Mathematics Division Department. ORNL holds Summit supercomputer, which is the fastest supercomputer in USA for the last 4 years. His Ph.D. dissertation topic was also "Efficient Execution of Scientific Applications on Heterogeneous Architectures”. We also have multiple Ph.D., master and bachelor students from multiple areas with a deep background that works on our lab. 

Our current research topics are listed below:

**Scheduling in heterogeneous architectures:**
* Balancing performance/energy trade-off in energy-limited systems: We work on running neural network (NN) inference on multiple accelerators of an SoC. Our goal is to enable an energy-performance trade-off with an by distributing layers in a NN between a performance- and a power-efficient accelerator. We first provide an empirical modeling methodology to characterize execution and inter-layer transition times. We then find an optimal layers-to-accelerator mapping by representing the trade-off as a linear programming optimization constraint. We evaluate our approach on the NVIDIA Xavier AGX SoC with commonly used NN models. We use the Z3 SMT solver to find schedules for different energy consumption targets, with up to 98% prediction accuracy.

* Multiple workload scheduling in heterogeneous architectures

* Exploiting multi-accelerators in diversely heterogeneous architectures: We investigate Multi-accelerator Execution (MAE) on diversely heterogeneous embedded systems, where sub-components of a given workload, such as neural network inference, can be assigned to different type of accelerators to achieve a desired latency or energy goal. We first analyze the energy and performance characteristics of execution of neural network layers on different type of accelerators. We then explore energy/performance trade-offs via layer-wise scheduling for neural network inference by considering different layer-to-accelerator mappings. Our empirical results on Jetson Xavier SoCs show that our methodology can provide up to 28% energy/performance trade-off benefit when compared to the case where all layers are assigned to a single accelerator.


**Autonomous Systems:**
* Scheduling and resource management

* Hardware-CPS representation for performance modelling

**GPU Utilization**
* Designing GPU to NVM data-transfer framework

* 







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
