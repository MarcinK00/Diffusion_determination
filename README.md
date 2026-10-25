# Diffusion_determination

This repository contains the code and data used in "Method for Measuring Solid-State Diffusivity".

## Abstract

The reliable determination of solid-state lithium diffusivity is essential for parameterizing physics-basedlithium-ion battery models. However, conventional methods misattribute electrolyte concentrationpolarization to solid-state diffusion, introducing systematic errors in the inferred diffusivity. This studyintroduces a resistance-decomposition method that explicitly accounts for electronic conduction,electrolyte transport, charge transfer, and solid-state diffusion within the Doyle–Fuller–Newman (DFN)framework. The diffusion coefficient is calculated from the residual polarization resistance afterindependently determining the other contributions and accounting for the equilibrium potentialdependence on the state of lithiation. The method is evaluated using synthetic voltage data generated withthe DFN model implemented in PyBaMM. The results demonstrate accurate recovery of the prescribeddiffusivity across most of the investigated parameter space under idealized conditions.. These findingsestablish the theoretical basis and numerical feasibility of the proposed method while identifying keylimitations that require experimental validation.

## Requirements

* Python 3.12+
* PyBaMM
* NumPy
* Matplotlib

## Citation

If you use this code, please cite the associated publication:

```
Marcin Kwidziński. Method for Measuring Solid-State Diffusivity:Part 1. Theoretical Introduction. ChemRxiv
DOI: not published yet
```

## License

This repository is licensed under the MIT License.

## Acknowledgments

* [PyBaMM](https://pybamm.org/)
