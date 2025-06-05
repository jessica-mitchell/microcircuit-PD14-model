Cortical microcircuit documentation (Potjans & Diesmann 2014)
==============================================================


Here we provide the documentation for the microcircuit model, developed using
the :doc:`NEST Simulator <nest:index>`, after the Potjans and Diesmann 2014 [1]_ publication.

The documentation is separated into two sections:

1. implementation-agnostic `detailed description of the microcircut model <_static/microcircuit-pd14-model.pdf>`_
2. :doc:`PyNEST implementation <implementation>` of the model and :doc:`example use cases <auto_examples/index>`.

The GitHub repository for this model can be found here: `microcircuit-pd14-model <https://github.com/INM-6/microcircuit-PD14-model>`_

.. mdinclude:: ../README.md
   :start-line: 2
   :end-line: 17


.. grid:: 1 2 3 3

   .. grid-item::

     .. image:: ../figures/potjans_2014_microcircuit.png

   .. grid-item::

     .. image:: ../figures/potjans_2014_raster_plot.png

   .. grid-item::

     .. image:: ../figures/potjans_2014_box_plot.png

.. mdinclude:: ../README.md
   :start-line: 21
   :end-line: 23


.. [1]  Potjans TC. and Diesmann M. 2014. The cell-type specific cortical
        microcircuit: relating structure and activity in a full-scale spiking
        network model. Cerebral Cortex. 24(3):785–806. DOI: `10.1093/cercor/bhs358 <https://doi.org/10.1093/cercor/bhs358>`__.

.. [2]  van Albada SJ., Rowley AG., Senk J., Hopkins M., Schmidt M., Stokes AB., Lester DR., Diesmann M. and Furber SB. 2018.
        Performance Comparison of the Digital Neuromorphic Hardware SpiNNaker
        and the Neural Network Simulation Software NEST for a Full-Scale Cortical Microcircuit Model.
        Front. Neurosci. 12:291. DOI: `10.3389/fnins.2018.00291 <https://doi.org/10.3389/fnins.2018.00291>`__.

For a list of publications that use or cite the microcircuit model see the `bibliography file <https://github.com/INM-6/microcircuit-PD14-model/blob/main/publications.bib>`_

.. toctree::
   :maxdepth: 1
   :glob:
   :hidden:

   detailed_description
   PyNEST implementation <implementation>
   auto_examples/index


