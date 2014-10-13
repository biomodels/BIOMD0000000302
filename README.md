

This is a model of one presynaptic and one postsynaptic cell, as described in
the article:  
**Gamma oscillation by synaptic inhibition in a hippocampal interneuronal network model.**   
Wang XJ, Buzsáki G. J Neurosci. 1996 Oct 15;16(20):6402-13. PMID:
[8815919](http://www.ncbi.nlm.nih.gov/pubmed/8815919) ;

Abstract:  
Fast neuronal oscillations (gamma, 20-80 Hz) have been observed in the
neocortex and hippocampus during behavioral arousal. Using computer
simulations, we investigated the hypothesis that such rhythmic activity can
emerge in a random network of interconnected GABAergic fast-spiking
interneurons. Specific conditions for the population synchronization, on
properties of single cells and the circuit, were identified. These include the
following: (1) that the amplitude of spike afterhyperpolarization be above the
GABAA synaptic reversal potential; (2) that the ratio between the synaptic
decay time constant and the oscillation period be sufficiently large; (3) that
the effects of heterogeneities be modest because of a steep frequency-current
relationship of fast-spiking neurons. Furthermore, using a population
coherence measure, based on coincident firings of neural pairs, it is
demonstrated that large-scale network synchronization requires a critical
(minimal) average number of synaptic contacts per cell, which is not sensitive
to the network size. By changing the GABAA synaptic maximal conductance,
synaptic decay time constant, or the mean external excitatory drive to the
network, the neuronal firing frequencies were gradually and monotonically
varied. By contrast, the network synchronization was found to be high only
within a frequency band coinciding with the gamma (20-80 Hz) range. We
conclude that the GABAA synaptic transmission provides a suitable mechanism
for synchronized gamma oscillations in a sparsely connected network of fast-
spiking interneurons. In turn, the interneuronal network can presumably
maintain subthreshold oscillations in principal cell populations and serve to
synchronize discharges of spatially distributed neurons.

The presynaptic and postsynaptic cell have identical parameters and the
variables in each cell are identified by using **_pre** or **_post** as a
postfix to their names. The presynaptic cell influences the postsynaptic one
via the synapse (variables and parameters: I_syn, E_syn, g_syn, F, theta_syn,
alpha, beta). The applied current to the presynaptic cell, I_app_pre, is set
to 2 microA/cm 2 for 10 ms as in figure 1C of the article. The dependence of
the postsynaptic cell on directly applied current can be investigated in
isolation by setting I_app_pre to 0 and altering I_app_post.

Originally created by libAntimony v1.4 (using libSBML 3.4.1)

