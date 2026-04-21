---
title: "Speakers"
description: "Confirmed speakers for the DSAIL / MARS Materials Workshop 2026"
---

<div class="speaker-list">

<div class="speaker" id="david-bourne--ibraheem-rasheed">
<h3>David Bourne &amp; Ibraheem Rasheed</h3>
<p class="meta">Heriot-Watt University · Wednesday 6 May, 3pm</p>
<p class="talk-title">Fast algorithms for generating synthetic polycrystalline microstructures</p>
<p class="abstract">We present fast algorithms for generating synthetic microstructures for modelling polycrystalline materials, such as steel. The geometry of the microstructure is modelled using Voronoi diagrams, Laguerre diagrams and anisotropic power diagrams (APDs). These low-parameter tessellations are able to represent a rich family of polycrystalline microstructures. We use tools from optimal transport theory and computational geometry to give precise control over the volumes of the grains and to generate synthetic microstructures with 10,000+ grains in the order of seconds. By using APDs and GPU-acceleration, we can also control the shape of the grains and allow for curved grain boundaries. Applications include crystal plasticity simulations, modelling grain growth and recrystallisation, and fitting diagrams to EBSD and XRD images of metals. In this talk we will give demonstrations of our software libraries SynthetMic and PyAPD.</p>
</div>

<div class="speaker" id="sam-engel">
<h3>Sam Engel</h3>
<p class="meta">UK Atomic Energy Authority (UKAEA) · Thursday 7 May, 9:45am</p>
<p class="talk-title">Uncertainty Quantification of Surface Microplasticity Using Stochastic Microstructural Perturbations</p>
<p class="abstract">Experimental methods such as high-resolution digital image correlation (HR-DIC) allow the spatially resolved deformation response of a material to be measured, which is a promising method for the validation of crystal plasticity (CP) models. However, experimental measurements of the microstructure are often limited to the surface, and as such, the subsurface microstructure is unknown. Therefore, it is important to understand how the deformation on the free surface may be influenced by this unknown subsurface. The effects of subsurface grain morphology on microplasticity on the free surface of pure copper under tensile deformation have been investigated. We propose a method to generate volume elements (VE) for CP, which uses a stochastic Monte Carlo Markov chain (MCMC) approach to vary the subsurface microstructure. The method utilises Voronoi tessellations, in which the subsurface grains are incrementally perturbed whilst ensuring the surface remains invariant. The method allows for sampling of subsurface microstructures with large variances for a given surface observation. We demonstrate that the surface microplasticity is significantly influenced by the subsurface microstructure, as previously reported. However, we further reveal that small perturbations in grain morphology give rise to noticeable variation in the evolution of deformation on the surface.</p>
</div>

<div class="speaker" id="didier-farrugia">
<h3>Didier Farrugia</h3>
<p class="meta">Tata Steel UK · Wednesday 6 May, 3:45pm</p>
<p class="talk-title">Microstructure modelling from the perspective of a steel manufacturer: a journey from the past, present and into the future</p>
<p class="abstract"><em>Abstract to follow.</em></p>
</div>

<div class="speaker" id="peter-hatton">
<h3>Peter Hatton</h3>
<p class="meta">Amentum · Friday 8 May, 9am</p>
<p class="talk-title">From Atomistics to Kinetic Monte Carlo and Beyond: Applications of Multiscale Materials Modelling in the Nuclear Industry</p>
<p class="abstract">In nuclear fuel materials, fission and subsequent damage events occur at the atomic scale in fractions of a second, but affect the material at the microstructural level, the component level, and the wider system behaviour over many years. For decades, however, models approximating these degradation and failure modes have been dominated by poorly defined empirical correlations leading to large uncertainties and pessimisms in extrapolative predictions.<br><br>As the industry moves away from pure feasibility and towards optimisations, reactor lifetime extensions and novel reactor designs, there is need for mechanistic accuracy in materials models to reclaim operating margins. This mechanistic accuracy comes, out of the box, from adopting a multiscale materials modelling paradigm where information at each time/length scale is passed from quantum level interactions up to, ideally, engineering scale predictions.<br><br>In this talk, I will describe how such a multiscale modelling framework is being developed and applied at Amentum to support in-operation fuel performance modelling for civil fuel. In particular, I will present a novel approach that couples accelerated molecular dynamics, static environment redecoration techniques, and graph-based state-space mapping. This framework systematically captures the influence of local chemical heterogeneity on defect migration pathways and energetics. The resulting data are used to train surrogate models, which directly feed into kinetic Monte Carlo simulations, enabling mesoscale exploration of defect dynamics with retained atomistic fidelity. I will demonstrate this method by studying uranium mononitride (UN) under burnup conditions, where local compositional fluctuations affect defect mobility in unintuitive and surprising ways.</p>
</div>

<div class="speaker" id="tom-hudson">
<h3>Tom Hudson</h3>
<p class="meta">University of Warwick · Thursday 7 May, 3:30pm</p>
<p class="talk-title">Connecting atomistic and continuum theories of crystal defects</p>
<p class="abstract">Scale-bridging between atomistic and continuum materials models remains a fundamental challenge due to the disparate physical descriptions at each scale. Rigorous mathematical results proved over the last decade have begun to close this gap, providing formal foundations to better connect the two. These theoretical insights are now directly informing computational workflows through enhanced error control and more efficient coarse-graining strategies. In this talk, I will present the mathematical developments mentioned alongside some more recent applications, showing that rigour is improving both practical computational performance and understanding.</p>
</div>

<div class="speaker" id="shresht-jain">
<h3>Shresht Jain</h3>
<p class="meta">University of Manchester · Thursday 7 May, 11:45am</p>
<p class="talk-title"><em>TBC</em></p>
<p class="abstract"><em>Abstract to follow.</em></p>
</div>

<div class="speaker" id="samuel-magorrian">
<h3>Samuel Magorrian</h3>
<p class="meta">STFC Hartree Centre · Thursday 7 May, 2:15pm</p>
<p class="talk-title">AI-accelerated computational discovery of high-entropy ceramics for extreme environments</p>
<p class="abstract">Ultra-high temperature ceramics (UHTCs) are designed for use at extreme temperatures in extreme conditions where they would be subjected to rapid heating in reactive environments, in applications including thermal barrier coatings in aerospace or hypersonics. Their drawback is that they are inherently brittle, bottlenecking their adoption in industry.<br><br>Here we present a pathway to engineer more durable UHTCs through high-entropy mixing of multiple UHTCs which can reduce the Young's modulus, which is expected to improve the ability of UHTCs to absorb and redistribute stress, enhancing toughness. We use a newly developed dedicated machine learning interatomic potential (MLIP) model in our in-house materials discovery engine for computational prediction of the synthesisability and the elastic moduli of the high-entropy ceramic composition space of group IV-V rocksalt carbides. We demonstrate that the model can map out the entire composition space at excellent accuracy and at the fraction of the cost of traditional modelling techniques. We identify a mixture of three UHTCs, HfC, VC, and ZrC, as the most promising candidate, and show that through the high-entropy mixing of these materials the Young's modulus may be reduced by up to 40 GPa compared to ZrC which has the lowest Young's modulus among the component ceramics.<br><br>Our model demonstrates an ability of bespoke machine learning models like MLIPs to efficiently discover optimal compositions of mixture compounds including high-entropy materials, accelerating crucial innovations in transformative technologies, predicting essential performance characteristics including elastic properties, stability, and the coefficient of thermal expansion.</p>
</div>

<div class="speaker" id="angela-mihai">
<h3>Angela Mihai</h3>
<p class="meta">Cardiff University · Thursday 7 May, 11am</p>
<p class="talk-title">Deformation localisation and topological defects in liquid crystal polymers</p>
<p class="abstract">Liquid crystalline polymers (LCPs) are advanced responsive materials composed of polymer chains cross-linked with rod-like liquid crystal (LC) mesogens that, in the nematic phase, align along a non-polar director. In this talk, I will present a unified framework for modelling LCPs and apply it to characteristic inhomogeneous deformations. When the mesogens are loosely cross-linked and can reorient relative to the polymer matrix, large-strain deformations arise under external stimuli or mechanical loads. In uniaxial tension, two instabilities occur. Necking appears as localised thinning where the material elongates more in a narrow region. Shear striping develops when the in-plane director rotates and eventually aligns with the applied force, forming alternating strips of clockwise and anticlockwise director rotation. Theory and simulations show that necking occurs if nematic order evolves during deformation, whereas shear striping arises if it is preserved. When LC molecules are tightly cross-linked, they are convected by deformation and singularities may form in the director field. These are known as topological defects, or disclinations, and are classified by their charge. Unlike in other polymer networks, defects in LCPs enable richer shape-morphing behaviours and are more diverse than in fluid LCs. Disclinations in LCPs are also analogous to defects in metals, as both disrupt local order and strongly affect physical properties.</p>
</div>

<div class="speaker" id="sam-murphy">
<h3>Sam Murphy</h3>
<p class="meta">Lancaster University · Friday 8 May, 11am</p>
<p class="talk-title">Modelling the electronic contribution to radiation damage</p>
<p class="abstract"><em>Abstract to follow.</em></p>
</div>

<div class="speaker" id="adam-plowman">
<h3>Adam Plowman</h3>
<p class="meta">UK Atomic Energy Authority (UKAEA) · Thursday 7 May, 9am</p>
<p class="talk-title">Data-centric materials modelling with MatFlow: high-throughput workflows and uncertainty quantification</p>
<p class="abstract">MatFlow is an open-source workflow management framework for automating complex computational workflows in materials science. It enables structured definition and reproducible execution of interconnected simulation and data-processing tasks, while remaining code-agnostic and adaptable to a wide range of modelling approaches. By separating workflow definition from execution, MatFlow provides flexibility across computing environments, from local systems to high-performance computing (HPC) platforms. Its emphasis on provenance tracking and data standardisation supports reproducible, data-driven modelling and facilitates integration with machine learning methods. MatFlow is particularly well suited to high-throughput studies, enabling systematic exploration of parameter spaces and robust uncertainty quantification in computational models. In this talk, we will discuss some recent applications, including a subset simulation workflow for efficient rare-event estimation, and a crystal plasticity calibration workflow using Bayesian inference to obtain optimised parameter distributions.</p>
</div>

<div class="speaker" id="matthias-sachs">
<h3>Matthias Sachs</h3>
<p class="meta">Lancaster University · Friday 8 May, 9:45am</p>
<p class="talk-title">Machine Learning Interatomic Potentials and Friction Tensors for Simulation of Molecule Surface Interactions</p>
<p class="abstract"><em>Abstract to follow.</em></p>
</div>

<div class="speaker" id="carl-slater">
<h3>Carl Slater</h3>
<p class="meta">Warwick Manufacturing Group, University of Warwick · Wednesday 6 May, 1:45pm</p>
<p class="talk-title">Rapid Alloy Development at WMG – Bringing together physical, digital and smart alloy processing</p>
<p class="abstract">The rise in energy and raw material prices means that industrial scale alloy / process development is more challenging than ever. Dr Slater will present the 3 streams of Rapid Alloy Processing (RAP) at Warwick; Physical, Digital and Smart. He will present the ecosystem that houses these systems and give examples of how they work both independently and also synergistically to help derisk alloy/process development in the modern age.</p>
</div>

<div class="speaker" id="mike-white">
<h3>Mike White</h3>
<p class="meta">UK Atomic Energy Authority (UKAEA) · Thursday 7 May, 9:45am</p>
<p class="talk-title">3D variational autoencoder for parameterising microstructure inputs for crystal plasticity surrogate models</p>
<p class="abstract">A 3D variational autoencoder (VAE) is trained on a dataset of randomly generated microstructure volume elements. The latent space constructed by the VAE is explored and edge cases analysed to showcase the generalisability of the VAE to unseen microstructures. The encoder from the trained VAE is then used to generate a dataset of latent representations, alongside running a crystal plasticity simulation in DAMASK for each microstructure with a random load path to yield a stress response. A recurrent neural network (RNN) is then trained to predict the stress response, given some latent representation and load path as an input.</p>
</div>

<div class="speaker" id="viktor-zólyomi">
<h3>Viktor Zólyomi</h3>
<p class="meta">STFC Hartree Centre · Thursday 7 May, 1:30pm</p>
<p class="talk-title">The Hartree Materials Discovery Engine</p>
<p class="abstract">The rise of machine learning interatomic potentials created an age where discovery of complex materials like high-entropy compounds is feasible through atomistic modelling that can predict essential performance criteria of materials. However, the composition space remains vast, necessitating efficient high-throughput screening. Furthermore, out-of-the-box general purpose machine learning interatomic potentials are often limited in precision when it comes to complex crystals, until the models are fine-tuned for the desired composition space.<br><br>Here we present the Hartree Materials Discovery Engine, a program primarily but not exclusively designed for high-throughput screening of high-entropy material composition spaces using fine-tuned machine learning interatomic potentials based on the MACE architecture. We demonstrate on a series of industrially relevant examples how strategic generation of density functional theory training data can be efficiently used to create fine-tuned MACE models for materials design challenges including: melting simulations of silicon carbide at extreme temperatures covering multiple polytypes of the crystal as well as their interfaces, relevant to fusion technologies; high-entropy ceramic discovery, relevant to hypersonics as well as the energy sector including fusion technologies; and high-entropy refractory alloy discovery with built-in surface prediction capability, relevant to the design of improved biocompatible implants.</p>
</div>

</div>
