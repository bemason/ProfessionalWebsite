+++
title = "Projects"
slug = "projects"
tags = ["projects", "research", "contributions"]
+++

# CURRENT PROJECTS

## Real-time flood inundation modeling using sensor data
Real-time flood inundation modeling is critical for informing citizens and emergency services of hazardous flash flood conditions. To that end, I am combining my lab's open-source sensor data, USGS stream gauge data, and publicly accessible GIS datasets to develop a real-time flood inundation model for southeast Michigan.


# COMPLETED PROJECTS

## New generation water quality computational toolchain
Autonomous water systems are promising to transform watershed management, but no computational toolchains existed to evaluate their potential, due to overlapping needs to model water flow, water quality, and controls. To address this need, I built an open-source, computational Python package, [*StormReactor*](https://github.com/kLabUM/StormReactor), which coupled the popular EPA’s Stormwater Management Model [(SWMM)](https://www.epa.gov/water-research/storm-water-management-model-swmm) with a new generation water quality module. This integrated model will revolutionize how researchers and practitioners test water quality-based real-time control strategies. More details on *StormReactor* can be found in a recently published [article](https://www.sciencedirect.com/science/article/abs/pii/S1364815221002176) in Environmental Modelling & Software.

## Novel stormwater infrastructure sensing network
I developed a novel, “Internet of Things” stormwater infrastructure sensing network in partnership with the [Detroit Sierra Club](https://www.sierraclub.org/michigan). A network of over twenty custom sensor nodes, built using open-source solutions, are monitoring flooding and stormwater infrastructure performance in Detroit, Michigan. I speculate this network has created the largest dataset of stormwater infrastructure performance to date, shedding a light on the complexities of stormwater dynamics at an unprecedented spatial and temporal scale. Insights from this network will not only improve the design and placement of future infrastructure in Detroit, but in communities around the world. In addition, the network will serve as an instructional testbed for a workforce development program, teaching Detroiters the trade skills necessary for the rising autonomous water systems sector. This work is currently under review in Landscape and Urban Planning. The data, however, can be downloaded for free [Zenodo](https://zenodo.org/record/6390875#.Yw0FHy-B1hE).

## Real-time controlled green infrastructure
Studies have shown inconsistent nutrient removal in green infrastructure, particularly in bioretention systems. One potential solution is real-time control, which has been shown to improve pollutant removal in grey infrastructure. Since few studies have investigated this potential solution for green infrastructure, I simulated pollutant treatment in a real-time controlled bioretention cell using *StormReactor*. The results suggest real-time control may provide a “digital” alternative to existing, passive upgrades, like soil amendments, for boosting pollutant treatment. More details on this work can be found in a recently published [article](https://www.tandfonline.com/doi/abs/10.1080/1573062X.2022.2108464) in the Urban Water Journal.

## Water Quality Sampling Nodes
I collaborated with the [Huron River Watershed Council](https://www.hrwc.org/) on a surface water quality monitoring project. Brooke developed a small, low-cost, data node to collect real-time data, make automated decisions, and allow for remote triggering of the samplers. The node sends data to a dashboard allowing a team to monitor the depth of water in the stream/creek, along with sampler information. In manual mode, the team can simply tap a “trigger” button on the dashboard to order a sample.
