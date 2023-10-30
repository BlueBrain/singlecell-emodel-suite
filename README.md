# Single-Cell E-Model Suite

A suite to handle single-cell electrophysiological data and to build and validate detailed electrical models.

- [eFEL](#efel) — Electrophys Feature Extraction Library
- [BluePyEfe](#bluepyefe) — Blue Brain Python E-feature extraction
- [BluePyOpt](#bluepyopt) — Blue Brain Python Optimisation Library
- [BluePyMM](#bluepymm) — Blue Brain Python Cell Model Management
- [BlueCelluLab](#bluecellulab) - Blue Brain Cellular Laboratory
- [BluePyEModel](#bluepyemodel) - Blue Brain Python Electrical Modeling Pipeline
- [EModelRunner](#emodelrunner) — Runs cells from stand-alone packages
- [BlueNaaS-SingleCell](#bluenaas-singlecell) - Interacts with single cell models through a web application
- [Currentscape](#currentscape) - Plot currents in electrical models
- [SSCxEModelExamples](#SSCxEModelExamples) - Reproduce Reva, Maria, et al. "A universal workflow for creation, validation and generalization of detailed neuronal models" (2023).


## eFEL
<a href="https://github.com/BlueBrain/eFEL">
<img alt="eFEL Banner" src="https://github.com/BlueBrain/eFEL/raw/master/docs/source/logo/eFELBanner.png" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/eFEL),
[Documentation](https://efel.readthedocs.io/en/latest/).

**Electrophys Feature Extraction Library**

The Electrophys Feature Extraction Library (eFEL) allows neuroscientists to automatically extract features from
time series data recorded from neurons (both in vitro and in silico). Examples are the action potential width and amplitude
in voltage traces recorded during whole-cell patch clamp experiments.
The user of the library provides a set of traces and selects the features to be calculated.
The library will then extract the requested features and return the values to the user.


## BluePyEfe
<a href="https://github.com/BlueBrain/BluePyEfe">
<img alt="BluePyEfe Banner" src="https://github.com/BlueBrain/BluePyEfe/raw/master/docs/source/logo/BluePyEfeBanner.jpg" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyEfe),
[Documentation](https://github.com/BlueBrain/BluePyEfe#readme).

**Blue Brain Python E-feature extraction**

BluePyEfe aims at easing the process of reading experimental recordings and extracting batches of electrical features from these recordings.
To do so, it combines trace reading functions and features extraction functions from the eFel library.

## BluePyOpt
<a href="https://github.com/BlueBrain/BluePyOpt">
<img alt="BluePyOpt Banner" src="https://github.com/BlueBrain/BluePyOpt/raw/master/docs/source/logo/BluePyOptBanner.png" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyOpt),
[Documentation](https://github.com/BlueBrain/BluePyOpt#readme).

**Blue Brain Python Optimisation Library**

The Blue Brain Python Optimisation Library (BluePyOpt) is an extensible framework for data-driven model parameter optimisation that wraps
and standardises several existing open-source tools.

## BluePyMM
<a href="https://github.com/BlueBrain/BluePyMM">
<img alt="BluePyMM Banner" src="https://github.com/BlueBrain/BluePyMM/raw/master/docs/source/logo/BluePyMMBanner.png" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyMM),
[Documentation](https://github.com/BlueBrain/BluePyMM#readme).

**Blue Brain Python Cell Model Management**

When building a network simulation, biophysically detailed electrical models (e-models) need to be tested for every morphology
that is possibly used in the circuit.

## BlueCelluLab
<a href="https://github.com/BlueBrain/BlueCelluLab">
<img alt="BluePyCelluLab Banner" src="https://github.com/BlueBrain/BlueCelluLab/raw/main/docs/source/logo/BlueCelluLabBanner.jpg" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BlueCelluLab),
[Documentation](https://github.com/BlueBrain/BlueCelluLab#readme).

**Blue Brain Cellular Laboratory**

BlueCelluLab is designed for simulations and experiments on individual cells or groups of cells. Suitable use cases for BlueCelluLab include:
* Scripting and statistical analysis for single cells or cell pairs.
* Lightweight, detailed reporting on specific state variables after simulation.
* Developing synaptic plasticity rules.
* Validating dynamics of synaptic properties.
* Automating in-silico whole-cell patching experiments.
* Debugging, both scientifically and computationally.

## BluePyEModel
<a href="https://github.com/BlueBrain/BluePyEModel">
<img alt="BluePyEModel Banner" src="https://github.com/BlueBrain/BluePyEModel/raw/main/doc/source/logo/BluePyEModelBanner.jpg" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyEModel),
[Documentation](https://github.com/BlueBrain/BluePyEModel#readme).

**Blue Brain Python Electrical Modeling Pipeline**

The Blue Brain Python Electrical Modeling Pipeline (BluePyEModel) is a Python package facilitating the configuration and execution of electrical neuron model (e-model) building tasks. It covers tasks such as extraction of electrical features from electrophysiology data, e-model parameters optimisation and model validation. As such, it builds on top of eFEL, BluePyEfe and BluePyOpt.

## EModelRunner

<a href="https://github.com/BlueBrain/EModelRunner">
<img alt="EModelRunner Banner" src="https://github.com/BlueBrain/EModelRunner/raw/main/doc/source/logo/BBP-eModelRunner.jpg" width="600"/>
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/EModelRunner),
[Documentation](https://github.com/BlueBrain/EModelRunner#readme).

**Runs cells from stand-alone packages**

EModelRunner is a python library designed to run the cell models provided by the Blue Brain portals in a simple and straightforward way.

## BlueNaaS-SingleCell

<a href="https://github.com/BlueBrain/BlueNaaS-SingleCell">
<img alt="BlueNaaS-SingleCell" src="https://github.com/BlueBrain/BlueNaaS-SingleCell/raw/main/BlueNaaS-SingleCell.jpg" width="600" />
</a>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BlueNaaS-SingleCell),
[Documentation](https://ebrains-cls-interactive.github.io/docs/online_usecases/single_cell_in_silico/single_cell_clamp/single_cell_clamp.html)

**Interacts with single cell models through a web application**

Blue-Neuroscience-as-a-Service-SingleCell is an open source web application. It enables users to quickly visualize single cell model morphologies in 3D or as a dendrogram. Using a simple web user interface, single cell simulations can be easily configured and launched, producing voltage traces from selected compartments.

## Currentscape

Currentscape is a Python tool enabling scientists to easily plot the currents in electrical neuron models. The code is based on the paper Alonso and Marder, 2019.

Useful links:
[GitHub repo](https://github.com/BlueBrain/Currentscape),
[Documentation](https://currentscape.readthedocs.io).

<a href="https://github.com/BlueBrain/Currentscape">
<img alt="Currentscape example" src="https://raw.githubusercontent.com/BlueBrain/Currentscape/main/doc/source/images/plot.png" width="600"/>
</a>

## SSCxEModelExamples

Software repository to reproduce the results of the publication below.

> Reva, M., Rössert, C., Arnaudon, A., Damart, T., Mandge, D., Tuncel, A., Ramaswamy, 
> S., Markram, H., & Van Geit, W. (2023). A universal workflow for creation, validation, and 
> generalization of detailed neuronal models. Patterns, 100855. https://doi.org/10.1016/j.patter.2023.100855

In the paper, we present a generalized automated workflow for the creation of robust electrical models and illustrate its performance by building cell models for the rat somatosensory cortex. Each model is based on a 3D morphological reconstruction and a set of ionic mechanisms. We use an evolutionary algorithm to optimize neuronal parameters to match the electrophysiological features extracted from experimental data. Then we validate the optimized models against additional stimuli and assess their generalizability on a population of similar morphologies. Compared to the state-of-the-art canonical models, our models show 5-fold improved generalizability. This versatile approach can be used to build robust models of any neuronal type.

[GitHub repo](https://github.com/BlueBrain/SSCxEModelExamples)
