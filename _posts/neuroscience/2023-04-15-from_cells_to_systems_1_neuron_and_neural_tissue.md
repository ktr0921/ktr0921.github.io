---
title: "Neuron and Neural Tissue"
date: 2023-04-10
last_modified_at: 2023-04-15
excerpt: "In the field of neuroscience, there are specific biological components that play unique roles. A neuron acts as an electrical device that sends a signal by inlet and outlet of charged ions through ion channels on the membrane. Together with neuroglia, they make up neural tissues that transfer information or process information. This post aims to provide a tutorial on the two lower levels of body organization in neuroscience, namely the cell level and the tissue level."
categories:
  - Neuroscience&#x003a; From Cells to Systems
permalink: /posts/neuroscience/neuron_and_neural_tissue/
toc: true
toc_label: "Table of Contents"
toc_sticky: true
comments: true
---

{% include neuroscience/quote.md %}

{% include neuroscience/intro.md %}

{% include neuroscience/from_cells_to_systems/from_cells_to_systems.md %}

A neuron acts as an electrical device that sends a signal by inlet and outlet of charged ions through ion channels on the membrane. Together with neuroglia, they make up neural tissues that transfer information or process information. This post aims to provide a tutorial on the two lower levels of body organization in neuroscience, namely the cell level and the tissue level.

# Neuron

A **neuron**, or nerve cell or neuronal cell or neurocyte, is the fundamental unit of the nervous system, responsible for sending and receiving electrochemical signals to interact with the world. It is the smallest component that is responsible for everything that involves perception, cognition and consciousness.

<figure class="align-center" style="width: 400px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/1_1_neuron.png">
    <figcaption class="figure-caption text-center">
        A neuron from
        <a href="https://commons.wikimedia.org/wiki/File:Neuron.svg">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

A neuron is structurally unique.
- **Dendrite** is a tree branch-like shape filament that receives input signals from other neurons. Usually, it outreaches from the *cell body*. which contains *nucleus* in its centre.
- **Axon**, or **nerve fibre** is a long tube-like shape filament that passes the received signals from dendrites to the other end. It is one of the commonly damanged parts, since it is approximately 50 times thinner than hair.
- **Myelin sheath**, or **myelination**, is a lipid-rich material of *neuroglia*, such as *Schewan cell*, that wraps the axon to protect it from physical trauma. **Node of Ranvier** is the gap between myelin sheaths. Myelin sheath is not part of neuron and is not found in every neuron.
- **Axon terminal** is a splitted axon at the other end that sends the passed signals to other neurons.

A neuron is also functionally unique.
- **Neurotransmission**: The chemical signal between axon terminal of one neuron and dendrite of another neuron.
- **Action potential propagation**: The electrical signal through axon from dendrite to axon termianl within the neuron.

In this section, I will briefly introduce the types of neurons, then, focus on the two core functions of neurons, neurotransmission and action potential propagation.

## Neuron Type
There are many different ways to differentiate neurons. Morphologically, four types of neuron exist.
- **Unipolar**: One axon extending from the cell body to dendrites.
- **Bipolar**: Two axons extending from the cell body to dendrites and axon terminals separately.
- **Multipolar**: Dendrites on the cell body and one axon extending from the cell body to axon terminals.
- **Pseudounipolar**: One axon extending from the cell body splited into two branches in different lengths, one for dendrites and the other for axon terminals.

<figure class="align-center" style="width: 300px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/1_2_neuron_type.png">
    <figcaption class="figure-caption text-center">
        A neuron type from
        <a href="https://commons.wikimedia.org/wiki/File:Neurons_uni_bi_multi_pseudouni.svg">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

Unipolar neuron is only present in invertebrates, such as insects, so humans only have neurons of bipolar, multipolar and pseudopolar. Multipolar neuron has two variants in human.
- **Pyramidal**: Multipolar with dendrites in pyramidal shape for excitatory neurotransmitter.
- **Purkinje**: Multipolar with dendrites in planar fan-shaped for inhibitory neurotransmitter.

The morphology of neurons usually follows its functionality. There are three functional classes of neuron.
- **Sensory neuron**: Passes the sensation signal from the external world to the brain. Most are bipolar or pseudounipolar.
- **Interneuron**: Connects sensory neurons, interneurons and/or motor neurons, forming circuits of various complexity. Most are multipolar, pyramidal, or Purkinje.
- **Motor neuron**: Passes the innervation signal from the brain to muscles and glands. Most are also multipolar.

The functional types of neurons vary drastically by the location.
- Neurons found in the peripheral nervous system (PNS) are generally sensory neurons or motor neurons.
    - Sensory neuron branches out towards the sensory organs (long) and the CNS (short) separately.
- Neurons found in the central nervous system (CNS) are generally interneurons.
    - There are extensive number of neuron types in the brain, distinguished by neurotransmitter type, structure, synapse location, electrical properties, gene expressions, projection patterns and many more. Due to this, yet community has not come to an agreement on how to distinguish them.

Thus, the process can be thought of as:
1. Receive the sensation signal through sensory neurons in the PNS.
2. Process the information through interneurons in the CNS.
3. Convey the innervation signal through motor neurons in the PNS.

Of course, there are neurons in the brain, involved in sensation, i.e. visual cortex or auditory cortex, or in movement, i.e. motor cortex, but they are composed of interneurons. Sensory neurons and motor neurons are usually present in the PNS to deliver signals between the body and the CNS. Most of the processing is done with interneurons in the CNS.

## Neurotransmission

A **neurotransmission** is the chemical process that a neuron communicates with another neuron. The process involves two neurons, releasing and receiving signalling molecules, called **neurotransmitters**, at the junction between two neurons, called **synapse**. The two neurons are named based on whether to release or receive neurotransmitters, or *the direction of the signal*.
- **Presynaptic neuron**: The neuron that sends the neurotransmitters from the axon terminal.
- **Postsynaptic neuron**: The neuron that receives the neurotransmitters at the dendrite.

A neurotransmitter has two opposite roles, either *excite (initiate)* or *inhibit (hinder)* the activation of an action potential propagation in the postsynaptic neuron.
- Excitatory neurotransmitter: **Glutamate**, noradrenaline and histamine.
- Inhibitory neurotransmitter: **Gamma-aminobutyric acid (GABA)**, serotonin and glycine.
- Excitatory and inhibitory neurotransmitter: Acetylcholine and dopamine.
    - Acetylcholine is excitatory to contract skeletal muscles while inhibitory to slow the heart rate.

Glutamate and GABA predominate the neurotransmitters in the brain, 80\% \~ 90\% and 30\% \~ 40\% synapses, respectively. Note that a neuron may have more than one neurotransmitter types, so most of neurons with glutamate also carry other neurotransmitters in the brain.
- Glutamate helps learning and memory whereas GABA produces a calming effect.
- Glutamate is the metabolic precursor of GABA, where glutamate is decarboxylated to GABA and CO2. Which means GABA is produced from glutamate.
- Since GABA is for calming effects, some people take GABA for anxiety relief or ADHD.
- Excessive glutamate is known to cause overexcitement of neurons and may result in the death of neurons, or neuroapoptosis. This phenomenon is called **excitotoxicity**.

It is very important to balance excitatory and inhibitory neurotransmitters. In a cell level, it determines whether an action potential will result or not, and in an organ level, excess or lack of one may result in neurological or mental diseases.

The full process of a neurotransmission is:

<figure class="align-center" style="width: 400px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/1_3_neurotransmission.png">
    <figcaption class="figure-caption text-center">
        A neurotransmission from
        <a href="https://commons.wikimedia.org/wiki/File:SynapseSchematic_en.svg">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

1. Action potential travels through presynaptic neuron and reaches the axon terminal of the postsynaptic neuron.
2. Action potential at the axon terminal opens voltage-gated Ca<sup>2+</sup> channels, allowing Ca<sup>2+</sup> influx to the axon terminal.
3. Neurotransmitters are released from the axon terminals of the presynaptic neuron into the synaptic cleft.
4. Neurotransmitter binds to neurotransmitter receptors on the dendrites of the postsynaptic neuron.
5. This binding opens ion channels, positive (e.g. Na<sup>+</sup>, K<sup>+</sup>, Ca<sup>2+</sup>) or negative (e.g. Cl<sup>-</sup>) depending on the neurotransmitter type, allowing ion influx to the membrane of postsynaptic neuron.
6. Neurotransmitters attached to the dentrites of the postsynaptic neuron are detached and collected through neurotransmitter transporters.

Few details are,
- (3) Synaptic cleft is a 20nm \~ 40nm gap between the presynaptic axon terminal and the postsynaptic dendrite. Synapse includes all the presynaptic axon terminal, the synaptic cleft and the postsynaptic dendrite.
- (4, 5) Neurotransmitters are not the ones that travel into postsynaptic neurons, but ions are.
- (8) Neurotransmitter transporters are responsible for maintaining appropriate levels of neurotransmitters inside and outside neurons.

A neurotransmission occurs between other cells in muscles and glands. In the case of muscle, it is called *neuromuscular transmission*, covered in the later section.

## Action Potential Propagation

An **action potential propagation** is the electrical process that a signal is propagated within a single neuron from dendrites to axon terminals. The process involves the changes of electric potentials inside the membrane, called **action potential**, or nerve impulse or spike.

The full process of an action potential propagation is:

<figure class="align-center" style="width: 750px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/1_4_action_potential_propagation.png">
    <figcaption class="figure-caption text-center">
        An action potential propagation from
        <a href="https://commons.wikimedia.org/wiki/File:Membrane_Permeability_of_a_Neuron_During_an_Action_Potential.svg">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

1. Membrane potential stays at the **resting membrane potential**. There is lower concentration of Na<sup>+</sup> (a) and higher concentration of K<sup>+</sup> inside the axon.
2. During neurotransmission, if more excitatory neurotransmitters than inhibitory neurotransmitters bind to the dendrites, the positive ions enter the membrane of the neuron, increasing the membrane potential.
3. If the membrane potential rises to the **action potential threshold**, the action potential propagation initiates. In other words, neuron fires.
4. An increased membrane potential activates voltage-gated Na<sup>+</sup> channels (c) to inlet Na<sup>+</sup> into the axon, increasing membrane potentials further, called **depolarization**.
5. Na<sup>+</sup> influx activates voltage-gated K<sup>+</sup> channels (d) to outlet K<sup>+</sup> out of the axon, decreasing membrane potentials, called **repolarization**.
6. The outlet of K<sup>+</sup> is more excessive than the inlet of Na<sup>+</sup>, causing undershoot of the membran potential to drop below the resting membrane potential, called **hyperpolarization**.
7. The resting potential is ultimately re-established by closing of all voltage-gated ion channels and the activitation of the Na<sup>+</sup>/K<sup>+</sup> pump (e). This is called **refractory period**.
8. (4,5,6,7) occur consecutively through the axon until the axon terminal.

Few details are,
- (1, 3) Membrane potential is the difference in electrical potential between inside and outside of a cell. The resting membrane potential and action potential threshold are usually -70 mV and -55 mV, but they vary drastically by neuron types.
- (2) During neurotransmission, if more inhibitory neurotransmitters than excitatory neurotransmitters bind to the dendrites, the membrane potential decreases, and thus no action potential.
- (3) If the membrane potential does not rise to the action potential threshold, no action potential propagation is initiated.
- (6) Hyperpolarization is known to prevent action potential to travel backwards.
- (4,5,6) are the process of action potential propagation.

Through action potential propagation, a neuron consecutively opens and closes electrically activated ion channels to pass electrical impulse from dendrites to axon terminals. Then, at the end of axon terminals, a neurotransmission occurs with a postsynaptic neuron. In the postsynaptic neuron, the sum total of dendritic inputs, excitatory as positive charges and inhibitory as negative charges, determines whether the neuron will fire an action potential.

Myelin sheath is a lipid-rich fatty substance of neuroglia that encases axons. It is very important in action potential propagation as it increases the rate of action potential propagation. This phenomenon is referred to as **saltatory conduction**.

The exchanges of ions can only occur at unmyelinated part of axon, so the increase in the conduction velocity of action potential propagation is because the action potential is *skipped* at myelinated areas. Due to this myelin sheaths are often seen as an insulator for action potential propagation.

<figure class="align-center" style="width: 350px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/1_5_saltatory_conduction.gif">
    <figcaption class="figure-caption text-center">
        Saltatory conduction from
        <a href="https://commons.wikimedia.org/wiki/File:Saltatory_Conduction.gif">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

# Nerve Fibre
A **nerve fibre** is another name for an *axon* that is commonly used to classify a neuron serving a particular function. This can be considered as a subdivision of sensory neurons and motor neurons. Here, the naming convention is based on the direction of the information flow, that is sensory neurons as *afferent neurons* and motor neurons as *efferent neurons*.

There are three subdivisions that exist in nerve fibre.
- Location: A nerve fibre can be **general** or **special**. The former refers to a nerve fibre branching out from the spinal cord in the CNS and the latter from the brain in the CNS.
- Function: A nerve fibre can be **somatic** or **autonomic**. Somatic refers to as *voluntary* and autonomic as *involuntary*. Visceral is another name for autonomic. Therefore, somatic nerve fibre is for voluntary system while visceral nerve fibre is for involuntary system.
- Direction: A nerve fibre can be **afferent** or **efferent**. Afferent is to bring sensations to CNS and efferent is to send commands from CNS. Afferent is derived from the Latin *afferre* that means *to bring towards* and efferent is from the Latin *efferre*, *to bring away from*.

A nerve fibre is named with a combination of these three subdivisions, such as *general somatic afferent nerve fibre* or *special visceral efferent nerve fibre*. This naming convention is used to describe neural tissues while morphological and functional classifications are used more on neurons.

Herein, I will mainly focus on the general function and idea on afferent nerve fibre and efferent nerve fibre. Note that although there exist neurons that send and receive signals in the CNS, this content is mainly on the PNS.

## Afferent Nerve Fibre

An **afferent nerve fibre** is an axon of **afferent neuron**, or sensory neuron, that brings the sensation signals from the body to the CNS. There are four types of afferent nerve fibres.
- **General somatic afferent (GSA) nerve fibre**: Carry pain, touch or temperature from the skins, muscles, tendons or joints to the CNS through the spinal nerve.
- **General visceral afferent (GVA) nerve fibre**: Carry pain or physiological sensation from the internal organs, glands or blood vessels to the CNS through the spinal nerve.
- **Special somatic afferent (SSA) nerve fibre**: Carry vision, hearing or balance from the eyes, ears or body to the CNS through cranial nerve.
- **Special visceral afferent (SVA) nerve fibre**: Carry smell or taste from the nose or tongue to the CNS through cranial nerve.

An sensory neuron is a neuron that is activated by sensory input from the environment or within the body. There are largely two sensations in the human body.
- **Exteroception**: Sensation from outside the body.  
- **Interoception**: Sensation from inside the body.

The action potential propagation of an sensory neuron is initiated by four types of sensations of different stimuli.
- **Chemosensation**: Induced by **chemoreceptor** that detects chemical molecule.
- **Mechanosensation**: Induced by **mechanoreceptor** that detects mechanical force.
- **Thermalsensation**: Induced by **thermoreceptor** that detects thermal excitation.
- **Photosensation**: Induced by **photoreceptor** that detects photoexcitation.

The stimuli open ion channels and depolarize membrane potentials to initiate action potential propagation. Exteroception and interoception contain the sensations of different stimuli.
- Exteroception
    - Chemosensation for smell and taste.
    - Mechanosensation for touch and hearing.
    - Thermalsensation for heat and chill.
    - Photosensation for sight.
    - Chemosensation, mechanosensation and thermalsensation for pain.
- Interoception
    - Chemosensation for blood sugar level.
    - Mechanosensation for blood pressure and body position.

Exteroception covers the majority of conscious sensations we use to perceive the world. Interoception, on the other hand, covers both conscious and non-conscious sensations that are important to physiology. Due to this, major research on sensations is driven by exteroception, and only recently, researchers started focusing on interoception, such as the intersection with immune system or gastrointestinal system. Thus, interoception is still quite gray area.
- Some literature puts the sense of body position as different sensation from exteroception and interoception, but here, I included in interoception.

## Efferent Nerve Fibre

An **efferent nerve fibre** is an axon of **efferent neuron**, or motor neuron, that sends the innervation signals from the CNS to the body. There are three types of efferent nerve fibres.
- **General somatic efferent (GSE) nerve fibre**: Carry motor innervation from the spinal cord to skeletal muscles through the spinal nerve.
- **General visceral efferent (GVE) nerve fibre**: Carry motor innervation from the spinal cord to smooth muscles, cardiac muscles or glands through the spinal nerve.
- **Special visceral efferent (SVE) nerve fibre**: Carry motor innervation from the brain to the muscles of the pharyngeal arches, which include head, neck and tongue through the cranial nerve.

There is no special somatic efferent nerve fibre, instead, SVE nerve fibre takes care of both somatic and visceral functions. Due to this, the neuron of SVE nerve fibre is often referred to as **branchial motor neuron**.

An motor neuron is a neuron that is activated by innervation output from the CNS. It can be divided based on the location or function.
- Location: An **upper motor neuron** is between the brain and the spinal cord while a **lower motor neuron** is between the spinal cord to muscles or glands.
- Function: A **somatic motor neuron** is to control skeletal muscle while a **visceral motor neuron** is for smooth muscle, cardiac muscle and glands.

Upper motor neurons are of the CNS, so GSE, GVE and SVE nerve fibres are part of lower motor neurons.

Muscle contraction is the main function of GSE fibres. They activate skeletal muscles through a process called **neuromuscular transmission**.

<figure class="align-center" style="width: 700px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/2_1_neuromuscular_junction.png">
    <figcaption class="figure-caption text-center">
        A neuromuscular junction from
        <a href="https://commons.wikimedia.org/wiki/File:The_Muscle_Contraction_Process.png">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

1. Action potential travels through motor neuron (A) and reaches the axon terminal of the motor neuron (B).
2. Depolarization at the axon terminal opens voltage-gated Ca<sup>2+</sup> channels, allowing Ca<sup>2+</sup> influx to the axon terminal.
3. Neurotransmitters, mostly acetylcholine (ACh), are released from the axon terminals of the motor neuron into the **neuromuscular junction**, or myoneural junction (C). This process is referred to as **exocytosis**.
4. ACh binds to post-synaptic receptors on the membrane of the muscle cell, or sarcolemma (D).
5. This binding opens Na<sup>+</sup> channels, allowing Na<sup>+</sup> influx to the membrane of muscle cell.
6. An increase in Na<sup>+</sup> generates the action potential propagation in the muscle cell, resulting in muscle contraction via myofibril (E).
7. Neurotransmitters attached to the membrane of the muscle cell are detached and collected through neurotransmitter transporters.

Few details are,
- (3) ACh is excitatory to contracts the skeletal muscles but inhibitory and excitatory for involuntary systems. It contracts smooth muscles (excitation) while slowing the heart rate (inhibition).
- (6) Depolarization triggers the release of Ca<sup>2+</sup>. Then, it binds to troponin to initiate contraction, which is sustained by ATP. As long as Ca<sup>2+</sup> remains bound to troponin and ATP is available, the contraction is maintained.

Relaxation is opposite to contraction, where either no more AChs produced from motor neurons or ATPs run out. Although this process is specific to somatic motor neuron stimulating skeletal muscle, the logic can be generally applies to others, such as visceral motor neuron stimulating glands.

# Neural Tissue
A **neural tissue**, or nervous tissue, is a group of cells working together to perform a function in the nervous system. A neuron alone is nothing more than a cell, but a collection of neurons with neuroglia serves a purpose. Again, similar to neurons, neural tissues found in the PNS and the CNS are different.

There are two types of neural tissues in the PNS of the human.
- **Nerve**: An enclosed bundle of axons, or nerve fibers. Action potentials are transmitted as a bundle to muscles, glands or CNS.
- **Ganglion**: A cluster of dendrites, neuronal cell bodies, axon terminals and neuroglia. Neurotransmission occurs between a lot of neurons, exciting or inhibiting the activation of action potential propagation.

A nerve usually contains a mixture of different nerve fibres while a ganglion contains neurons of a particular function.

In the CNS, neural tissues share similar characteristics to nerve and ganglion.
- **White Matter**: Nerve in CNS, but action potentials are transmitted between the various grey matter, and between the gray matter and the rest of the body along with myelination of oligodendrocytes. Myelin sheath is what makes white matter white.
- **Grey Matter**: Ganglion in CNS. Grey matter is actually more pink-coloured than grey because of the abundant blood supply.

White matter is where the information is transferred while grey matter is where the information is processed. Their structures and functions can be somewhat generalized as nerve and ganglion, but in details, they vary drastically by location.

This section mostly focuses on the neural tissues in the PNS. Thus, I will cover basics of neuroglia, then introduce nerve and ganglion.

## Neuroglia

**Neuroglia**, or glia or glial cell, is a cell that provides support for neurons. Their functions vary by a cell type, from metabolic to physiological function. Largely, there are six types of neuroglia.

<figure class="align-center" style="width: 500px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/3_1_neuroglia_type.png">
    <figcaption class="figure-caption text-center">
        A neuroglia type from
        <a href="https://commons.wikimedia.org/wiki/File:Blausen_0870_TypesofNeuroglia.png">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

- **Ependymal cell**: Surface for neural tissues in the CNS.
- **Astrocyte**: Metabolism in the CNS.
- **Oligodendrocyte**: Myelination in the CNS.
- **Microglia**: Immune system in the CNS.
- **Satellite cell**: Metabolism in the PNS.
- **Schwann cell**: Myelination in the PNS.

Although neuroglia appear to be less important than neurons, they are believed to contribute in learning and memory.

Neurons and neuroglia make up **extracellular matrix** with a composition of proteins.

<figure class="align-center" style="width: 400px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/3_2_neuroglia_type_brain.png">
    <figcaption class="figure-caption text-center">
        An extracellular matrix in the brain from
        <a href="https://commons.wikimedia.org/wiki/File:Glial_Cell_Types.png">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

- Ependymal cell is pink.
- Astrocyte is green.
- Oligodendrocyte is blue.
- Microglia is red.

Extracellular matrix is important to maintain the shape and regulate the processes, which are done by many different proteins. We refer to a group of neurons, glia and extracellular matrix as *neural tissue*.

There are many proteins that provide structural and biochemical supports to cells, but some unique and important proteins in the extracellular matrix of the neural tissue are:
- **Neurotrophin**, or neurotrophic factor: Regulating survival, development and function of neurons, which belongs to the growth factor family. It is one of the most widely studied proteins, where *nerve growth factor (NGF)*, *brain-derived neurotrophic factor (BDNF)*, neurotrophin-3 (NT-3) and neurotrophin-4 (NT-4) belong to this.
- Neuronal apoptosis inhibitory protein (NAIP): Regulating an apoptosis of a neuron, which belongs to the inhibiter of apoptosis (IAP) family.
- Hippocalcin: Allowing Ca<sup>2+</sup> to bind to interact with other proteins and regulate various processes, which belongs to the neuronal calcium sensor (NCS) family.

## Nerve

A **nerve** is composed of nerve fibres that bring the sensation signals from the body to the CNS (afferent) and that send the innervation signals from the CNS to the body (efferent), and neuroglia that wraps nerve fibres. There are two large classifications.
- **Spinal nerve**: Branching out from the spinal cord, so it contains *general nerve fibres*, such as GSA, GVA, GSE, and GVE nerve fibres. There are 31 pairs of spinal nerves in the human.
- **Cranial nerve**: Branching out from the brain, so it contains *special nerve fibres*, such as SSA, SVA, and SVE nerve fibres. There are 12 pairs of cranial nerves in the human.

Note that this classification is little vague, where some describe them as tissue while others describe them as peripheral organ, but the general idea is that any form of a bundle of axons in the PNS is considered as nerve.

A spinal nerve can be anatomically divided as:

<figure class="align-center" style="width: 600px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/3_3_nerve_anatomy.jpg">
    <figcaption class="figure-caption text-center">
        A nerve anatomy from
        <a href="https://commons.wikimedia.org/wiki/File:1319_Nerve_StructureN.jpg">
            Wikimedia Commons
        </a>
    </figcaption>
</figure>

- **Nerve fascicle**: A bundle of axons filled with **endoneurium** and enclosed by **perineurium**. The term fascicle is also used for muscles, for instance, muscle fascicle.
- **Fasciculus**: A bundle of fascicles with blood vessel and **epineurium**. The spinal nerve is a fasciculus outreaching from the spinal cord.

The anatomy of nerve differ extremely per location, i.e. in cranium or in the CNS, but nerve fascicle and fasciculus are generally present in all of them.
- In the PNS, a nerve consists of a combination of nerve fibres of different directions, afferent or efferent, and different functions, somatic or visceral, with or without myelinations of Schwann cells.
- While nerves in the PNS are fairly well-known, white matters in the CNS are still grey area. However, at least, we know that most of them are wrapped with myelinations of oligodendrocytes.

## Ganglion
A **ganglion** is composed of dendrites, neuronal cell bodies, axon terminals and neuroglia. There are four large classifications.
- **Dorsal root ganglion**, or spinal ganglion: The cell bodies of GSA and GVA, located next to spinal cord. There is not neurotransmissions inside the dorsal root ganglia. For each spinal nerve, dorsal root ganglion is held next to the spinal cord.
- **Cranial nerve ganglion**: The cell bodies of SSA, SVA and SVE, located near the brain. Some cranial nerve ganglia contain synapses for neurotransmissions and some not. Not every cranial nerve contains cranial nerve ganglion. Some cranial nerves have their cell bodies inside the brain.
- **Autonomic ganglion**: The cell bodies of GVA and GVE, located in near the spinal cord or peripheral organs. Many autonomic ganglia contain synapses for neurotransmissions. Often autonomic ganglions lie near the organs that they are responsible of.
- **Ventral ganglion**: The cell bodies of GSE nerve, located in the ventral horn inside spinal cord. The cell bodies of the GSE are not part of the PNS. They reside inside the spinal cord, so often ventral ganglion refers to **ventral nucleus** instead.

Some ganglia act as a synaptic relay station between neurons since they contain presynaptic axon terminals and postsynaptic dendrites. The information enters to the ganglia from presynaptic neurons, excites the postsynaptic neurons in the ganglia and then exits through the nerve fibres of postsynaptic neurons. However, this is not the case for every ganglion. For instance, the cell bodies of GVA are located in either dorsal root ganglion or autonomic ganglion. This is why some autonomic functions are viable without the CNS.

Not all of these four ganglia are part of the PNS.
- Dorsal root ganglion, cranial nerve ganglion and autonomic ganglion belong to the PNS.
- Ventral ganglion belongs to the CNS. A ganglion is often referred to as nucleus in the CNS, i.e. motor nucleus as ventral ganglion.

The main differences between ganglion and grey matter is:
- The neuroglia in ganglion are mostly satellite cells.
- The neuroglia in grey matter are astrocytes and oligodendrocytes.

# Summary
Neuron
* Neuron is anatomically divided as dendrite, cell body, axon and axon terminal
* Neuron types vary morphologically, unipolar & bipolar & pseudounipolar & multipolar & pyramidal & Purkinje
* Neuron types vary functionally, sensory neuron & interneuron & motor neuron
* A neurotransmission is a chemical process that transfers neurotransmitters from the presynaptic neuron and the postsynaptic neuron for action potential propagations
    * The presynaptic neuron releases neurotransmitters and the postsynaptic neuron takes the neurotransmitters
    * Neurotransmitters are commonly glutamate for excitation and GABA for inhibition
    * A neurotransmission either initiate or inhibit action potential propagation in the postsynaptic neuron by neurotransmitters opening the ion channels, allowing ion influx
* An action potential propagation is a electrical process that propagates action potential from the dendrites to the axon terminals for neurotransmissions
    * Action potential is a phenomenon that membrane potential rises and falls, from depolarization, repolarization to hyperpolarization
    * The changes of membrane potential is due to voltage-gated ion channels, which allows the ions to pass when the membrane potential reaches a particular voltage
    * Saltatory conduction is a phenomenon that an action potential propagation is speed up with myelincation since voltage-gated ion channels only appear on nodes of Ranvier

Nerve Fibre
* Nerve fibre types vary by location (general and special), function (somatic and autonomic) and direction (afferent and efferent)
- An afferent nerve fibre is part of a sensory neuron
    * An afferent neuron is a synonym for sensory neuron
    * Afferent nerve fibre types are general somatic Afferent (GSA), General Visceral Afferent (GVA), Special Somatic Afferent (SSA) and Special Visceral Afferent (SVA)
    * Sensations are classified based on where the stimuli arise, exteroception and interoception
    * Sensations are classified based on the types of stimuli, chemosensation, mechanosensation, thermalsensation and photosensation
- An efferent Nerve Fibre is part of a motor neuron
    * An efferent neuron is a synonym for motor neuron
    * Efferent nerve fibre types are General Somatic Efferent (GSE), General Visceral Efferent (GVE) and Special Visceral Efferent (SVE)
    * Motor neuron types vary by Location (Upper and Lower) and Function (Somatic and Visceral)
    * Muscle Contraction is a result of neuromuscular transmission between motor neuron and muscle cell

Neural Tissue
* Neural tissue is formed by neurons, neuroglia and extracellular matrix
* A bundle of axons form nerve in the PNS or white matter in the CNS
* A cluster of dendrites, cell bodies, axon terminals and neuroglia form ganglion in the PNS or gray matter in the CNS
- Neuroglia
    * Neuroglia types are ependymal cell, astrocyte, oligodendrocyte, microglia, satellite cell and Schwann cell
    * Extracellular matrix is formed by neuron, neuroglia and proteins
    * Some unique and important proteins found in the neural tissue are neurotrophin, neuronal apoptosis inhibitory protein (NAIP) and hippocalcin
- Nerve
    * Equivalent to white matter in the CNS
    * Any form of a bundle of axons in the PNS is considered as nerve
    * Generally, nerve contains nerve fascicle and fasciculus
    * Spinal nerve and cranial nerve are used to describe nerve types, but often they are grouped as peripheral nerve and classified as an organ
- Ganglion
    * Equivalent to gray matter in the CNS
    * Ganglion types are dorsal root ganglion, containing GSA and GVA, cranial nerve ganglion, containing SSA, SVA and SVE, autonomic ganglion, containing GVA and GVE, and ventral ganglion, containing GSE
    * Dorsal root ganglion, cranial nerve ganglion and autonomic ganglion belong to the PNS while ventral ganglion belongs to the CNS

## Overview of Somatic Process
The generic description of somatic process is as follows.

<figure class="align-center" style="width: 850px">
    <img src="/assets/neuroscience/from_cells_to_systems_1/4_information_flow.png">
    <figcaption class="figure-caption text-center">
        Information flow in the nervous system from
        <a href="https://open.oregonstate.education/aandp/chapter/12-3-the-function-of-nervous-tissue/">
            Oregon State University
        </a>
    </figcaption>
</figure>

Well, the figure is self-explanatory, but just to point out:
- Sensory neurons detect stimuli from sensory receptors.
- Sensation signals from stimuli travel to the dorsal root ganglion through the afferent nerve fibres of the sensory neurons.
- Sensation signals is transferred to the neurons of sensory pathways to travel to the brain through the spinal cord.
- The brain processes the signals with interneurons and generates innervation signals.
- The brain sends innervation signals to the spinal cord through upper motor neurons.
- Innervation signals are sent from the spinal cord to the neuromuscular junctions through efferent nerve fibres of the lower motor neurons.
- Neuromuscular transmission occurs at the neuromuscular junctions, resulting in muscle contraction.

Other processes follow the same procedures, but just involve different nerve and ganglion, and perhaps additional components.

## Reference

- https://en.m.wikipedia.org/wiki/Glia
