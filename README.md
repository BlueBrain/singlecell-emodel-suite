# Single-Cell E-Model Suite

A suite to handle single-cell electrophysiological data and to build and validate detailed electrical models.

- [eFEL](#efel) — Electrophys Feature Extraction Library
- [BluePyEfe](#bluepyefe) — Blue Brain Python E-feature extraction
- [BluePyOpt](#bluepyopt) — Blue Brain Python Optimisation Library
- [BluePyMM](#bluepymm) — Blue Brain Python Cell Model Management
- [EModelRunner](#emodelrunner) — Runs cells from stand-alone packages
- [BlueNaaS-SingleCell](#bluenaas-singlecell) - Interacts with single cell models through a web application
- [Currentscape](#currentscape) - Plot currents in electrical models

## eFEL
<img alt="eFEL Banner" src="https://github.com/BlueBrain/eFEL/raw/master/docs/source/logo/eFELBanner.png" width="600"/>

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
<img alt="BluePyEfe Banner" src="https://github.com/BlueBrain/BluePyEfe/raw/master/docs/source/logo/BluePyEfeBanner.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyEfe),
[Documentation](https://github.com/BlueBrain/BluePyEfe#readme).

**Blue Brain Python E-feature extraction**

BluePyEfe aims at easing the process of reading experimental recordings and extracting batches of electrical features from these recordings. 
To do so, it combines trace reading functions and features extraction functions from the eFel library.

## BluePyOpt
<img alt="BluePyOpt Banner" src="https://github.com/BlueBrain/BluePyOpt/raw/master/docs/source/logo/BluePyOptBanner.png" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyOpt),
[Documentation](https://github.com/BlueBrain/BluePyOpt#readme).

**Blue Brain Python Optimisation Library**

The Blue Brain Python Optimisation Library (BluePyOpt) is an extensible framework for data-driven model parameter optimisation that wraps 
and standardises several existing open-source tools.

## BluePyMM
<img alt="BluePyMM Banner" src="https://github.com/BlueBrain/BluePyMM/raw/master/docs/source/logo/BluePyMMBanner.png" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/BluePyMM),
[Documentation](https://github.com/BlueBrain/BluePyMM#readme).

**Blue Brain Python Cell Model Management**

When building a network simulation, biophysically detailed electrical models (e-models) need to be tested for every morphology 
that is possibly used in the circuit.

## EModelRunner

<img alt="EModelRunner Banner" src="https://github.com/BlueBrain/EModelRunner/raw/main/doc/source/logo/BBP-eModelRunner.jpg" width="600"/>

Useful links:
[GitHub repo](https://github.com/BlueBrain/EModelRunner),
[Documentation](https://github.com/BlueBrain/EModelRunner#readme).

**Runs cells from stand-alone packages**

EModelRunner is a python library designed to run the cell models provided by the Blue Brain portals in a simple and straightforward way.

## BlueNaaS-SingleCell

<img alt="BlueNaaS-SingleCell" src="https://github.com/BlueBrain/BlueNaaS-SingleCell/raw/main/BlueNaaS-SingleCell.jpg" width="600" />

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

<img alt="Currentscape example" src="https://raw.githubusercontent.com/BlueBrain/Currentscape/main/doc/source/images/plot.png" width="600"/>
