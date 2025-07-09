# Cortical microcircuit documentation (Potjans & Diesmann 2014)


Here we provide the documentation for the microcircuit model, developed using
the [NEST Simulator](https://nest-simulator.org/documentation), after the Potjans and Diesmann 2014 [^1] publication.

```{toctree}
:maxdepth: 1

detailed_description.md
implementation.md
auto_examples/index
publications/publications.md
```

The GitHub repository for this model can be found here: [microcircuit-pd14-model](https://github.com/INM-6/microcircuit-PD14-model).

```{include}  ../README.md
:start-line: 2
:end-line: 17
```

::::{grid} 1 2 3 3

:::{grid-item}

![mc](../figures/potjans_2014_microcircuit.png)
:::

:::{grid-item}

![raster_plot](../figures/potjans_2014_raster_plot.png)
:::
:::{grid-item}

![box_plot](../figures/potjans_2014_box_plot.png)

:::
:::::

```{include}  ../README.md
:start-line: 21
:end-line: 23
```

[^1]: Potjans TC. and Diesmann M. 2014. The cell-type specific cortical
      microcircuit: relating structure and activity in a full-scale spiking
      network model. Cerebral Cortex. 24(3):785–806. DOI: 10.1093/cercor/bhs358 <https://doi.org/10.1093/cercor/bhs358>.

[^2]:  van Albada SJ., Rowley AG., Senk J., Hopkins M., Schmidt M., Stokes AB., Lester DR., Diesmann M. and Furber SB. 2018.
       Performance Comparison of the Digital Neuromorphic Hardware SpiNNaker
       and the Neural Network Simulation Software NEST for a Full-Scale Cortical Microcircuit Model.
       Front. Neurosci. 12:291. DOI: 10.3389/fnins.2018.00291 <https://doi.org/10.3389/fnins.2018.00291>.

