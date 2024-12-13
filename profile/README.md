## iDesignRes

IDesignRes is an European Union-funded research initiative aimed at advancing the integration of renewable energy across Europe.
The project brings together 22 partners from 11 countries to develop open-source tools that assist public authorities and network operators in planning and optimizing the adoption of low and zero-emission energy sources at regional, national, and European levels.

This repository provides access to all open-source software made available through the project.

## Component models

Multi-parameter component models capable of representing complex operational conditions are developed within the Project.
The represented components span from primary energy sources, energy conversion and distribution to end-users.

### Detailed system models

The detailed system models are derived for individual energy carriers, *e.g.*, electricity and natural gas.
These models are available for detailed analyses of these systems.

EDF models - https://github.com/iDesignRES/Plan4Res-SMS \
POMATWO - https://github.com/iDesignRES/POMATWO \
MGET/GGM - https://github.com/iDesignRES/GGM

### Energy consumer models

Detailed models for the energy consumers of a given area/industry type are developed.
The modules can be used stand-alone or provide data to be used together with the [component models assembly tool](#component-models-assembly-tool).

Deusto - https://github.com/iDesignRES/IDR-IIsim \
Technalia buildings - https://github.com/iDesignRES/Tecnalia \
Transport - https://github.com/iDesignRES/transcomp

### Multi-parameter component models for direct integration

Some multi-parameter models will be directly integrated into the [component models assembly tool](#component-models-assembly-tool).
These different models improve the description of different technologies whose operational behavior differs significantly from the standard description.
A detailed description with links to the individual models can be found in the repository on [EMX component models](https://github.com/iDesignRES/EnergyModelsX_component_models).

### Stand-alone component models

The stand-alone component models have detailed operational analysis capabilities.
The [component models assembly tool](#component-models-assembly-tool) will sample data from the component model outputs and use in the assessment of the integrated, multi-carrier energy system operations.

Nuclear EDF - tba \
Solar - https://git.code.tecnalia.com/swt-tecu/idesignres.git \
Wind - https://github.com/EnergyModelsX/EnergyModelsRenewableProducers.jl/tree/dev_windpower \ 
CHP - tba

## Component models assembly tool

The component models assembly tool is an extension to the [EnergyModelsX (EMX)](https://github.com/EnergyModelsX) framework.
It will be available from April 2025.
It is combining the individual component models through either direct integration, linking, or sampling of data from the different tools.
