.. role:: hidden
    :class: hidden-section

gluonvision.utils
=================
We implemented a broad range of utility functions which cover visualization, file handler, download and training helpers.

.. currentmodule:: gluonvision.utils
.. automodule:: gluonvision.utils

:hidden:`Visualization`
~~~~~~~~~~~~~~~~~~~~~~~~~

Image Visualization
---------------------
.. autofunction:: gluonvision.utils.viz.plot_image

.. autofunction:: gluonvision.utils.viz.get_color_pallete

Bounding Box Visualization
----------------------------
.. autofunction:: gluonvision.utils.viz.plot_bbox

:hidden:`Miscellaneous`
~~~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: gluonvision.utils.download

.. autofunction:: gluonvision.utils.makedirs

.. automodule:: gluonvision.utils.random
    :members:

:hidden:`Training Helpers`
~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autoclass:: gluonvision.utils.PolyLRScheduler
    :members:

.. autofunction:: gluonvision.utils.set_lr_mult

:hidden:`Bounding Box Utils`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: gluonvision.utils.bbox_iou