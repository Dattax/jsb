# JuliaSim Batteries: Build Better Batteries with Experiments and Simulations

`JuliaSimBatteries` is an advanced lithium-ion battery simulation tool integrating sophisticated electrochemical, thermal, and degradation physics. Utilizing the Doyle Fuller Newman (`DFN`) model, it can predict a battery's entire lifetime with fast charging 150,000 times faster than real time. The number of connected batteries is scalable from one cell to packs of thousands using electrochemical models. [Scientific Machine Learning (SciML)](https://sciml.ai/) enables the discovery of hidden governing laws from data, such as degradation and low-temperature behavior. Characterize material properties and propose battery designs using the parameter estimation and optimization tools in [JuliaSim](https://help.juliahub.com/juliasim/stable/).

## Our software can simulate 100 days of cycling in 60 seconds

Physical prototyping can take weeks – our product can cut down your prototyping process by providing physics-backed machine learning libraries that can simulate the same battery performance - and give you the output of an experiment in under 60 seconds. This rapid experimentation can help your teams build the best cells and packs. 

JuliaSim Batteries helps you reduce time and overhead to build better batteries 10x faster and at a much lower cost.

See it in action [Video]

## Introduction

JuliaSim Batteries is an advanced lithium-ion battery simulation tool integrating sophisticated electrochemical, thermal, and degradation physics. Utilizing the Doyle-Fuller-Newman (DFN) model, it can predict a battery's entire lifetime with fast charging 150,000 times faster than real time. The number of connected batteries is scalable from one cell to packs of thousands using electrochemical models. Scientific Machine Learning (SciML) enables the discovery of hidden governing laws from data, such as degradation and low-temperature behavior. Characterize material properties and propose battery designs using the parameter estimation and optimization tools in JuliaSim.

[screenshot]

Building accurate models are essential for understanding, optimizing, and designing batteries. Physically accurate battery models are computationally expensive and difficult to solve robustly. `JuliaSimBatteries` is more than 100 times faster than other battery modeling tools while solving the same physics, thanks to the speed of the [Julia](https://julialang.org/) programming language. Bring your battery workflow to the next level to solve challenging problems:
+ **Pack modeling** -- `JuliaSimBatteries` is performant and enables the predictive power of electrochemical models for large-scale battery packs.
+ **Uncertainty quantification** -- Uncertainty is inherent in battery modeling. `JuliaSimBatteries` helps mitigate and understand the root causes of uncertainty with JuliaSim Model Optimizer.
+ **Fast charging** -- Built for robust and efficient simulations, even at the extreme operating conditions of fast-charge.
+ **Degradation** -- Predict battery lifetime and health with SEI capacity fade models.
+ **Discover hidden physics** -- Combine physics from our battery models and your data to discover hidden governing laws using [SciML](https://sciml.ai/) tools.
+ **Lifetime prediction** -- Estimate a battery's entire lifetime with fast charging in under a minute with the `DFN` model.

## Capabilities
* Seamlessly scale single cells to packs of thousands for real-time simulation, optimization, and design
* Design electrochemical cells and entire battery packs with thousands of cells with ease
* Enhances physics-based precision with Scientific Machine Learning insights for the best of the worlds
* Extreme speed and efficiency in computing helps you rapidly converge on the optimal decision, saving your company thousands of hours of time
* Interpretability means that every step in the process can be observed and accounted for. Adjust any parameter to better understand the output

## Features

### 1: Optimize your Battery Chemistry

JuliaSim Batteries offers several electrochemical models in cells, modules, and packs

[screenshot]

### 2: Build Experiments

[screenshot]

### 2: Run Predictive Analysis

[screenshot]

## Contact Us 

Our team consists of battery experts and JuliaSim modeling experts. We’ll build a custom plan of action to bridge the gap between theory and testing, leading to an accelerated workflow, reduced risk, and increased productivity.

Email us at: sales@juliahub.com

Visit us at: https://juliahub.com/products/batteries

# JuliaSim Batteries: high-performance lithium-ion battery simulations

JuliaSim Batteries is one piece of the JuliaSim ecosystem.

![Graphical user interface](figures/gui.png)

## More Details of `JuliaSimBatteries`

![Lifetime simulation](figures/lifetime.gif)

`JuliaSimBatteries` offers several electrochemical models for use at any scale:
+ **Doyle-Fuller-Newman Model (`DFN`)** -- The `DFN` model is an advanced pseudo-2D battery model. It accurately represents electrochemical processes within a lithium-ion battery, including diffusion, reactions, and concentration gradients in both electrodes. This model offers high-fidelity simulations, enabling analysis and optimization of battery performance under various operating conditions.

+ **Single Particle Model with electrolyte (`SPMe`)** -- The `SPMe` model is a popular model to understand lithium-ion battery behavior. It simplifies the battery into a single particle for each electrode, considering electrolyte dynamics within the cell. This model allows for efficient simulations and provides valuable insights into cell-level behavior and degradation mechanisms.

+ **Single Particle Model (`SPM`)** -- The `SPM` model is a simplified version of the `SPMe` model, commonly used by technical battery engineers for quick and computationally efficient simulations. It represents the battery as single particles in both electrodes without considering the electrolyte dynamics. While less detailed than the `DFN` or `SPMe` models, the `SPM` model is effective for initial assessments, rapid battery analysis, and large-scale pack simulations.
