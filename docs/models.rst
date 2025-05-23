🕸️ Segmentation Models
==============================


.. contents::
   :local:

.. _unet:

Unet
~~~~
.. autoclass:: segmentation_models_pytorch.Unet


.. _unetplusplus:

Unet++
~~~~~~
.. autoclass:: segmentation_models_pytorch.UnetPlusPlus


.. _fpn:

FPN
~~~
.. autoclass:: segmentation_models_pytorch.FPN


.. _pspnet:

PSPNet
~~~~~~
.. autoclass:: segmentation_models_pytorch.PSPNet


.. _deeplabv3:

DeepLabV3
~~~~~~~~~
.. autoclass:: segmentation_models_pytorch.DeepLabV3


.. _deeplabv3plus:

DeepLabV3+
~~~~~~~~~~
.. autoclass:: segmentation_models_pytorch.DeepLabV3Plus


.. _linknet:

Linknet
~~~~~~~
.. autoclass:: segmentation_models_pytorch.Linknet


.. _manet:

MAnet
~~~~~~
.. autoclass:: segmentation_models_pytorch.MAnet


.. _pan:

PAN
~~~
.. autoclass:: segmentation_models_pytorch.PAN


.. _upernet:

UPerNet
~~~~~~~
.. autoclass:: segmentation_models_pytorch.UPerNet


.. _segformer:

Segformer
~~~~~~~~~
.. autoclass:: segmentation_models_pytorch.Segformer


.. _dpt:

DPT
~~~

.. note::

    See full list of DPT-compatible timm encoders in :ref:`dpt-encoders`.

.. note::

    For some encoders, the model requires ``dynamic_img_size=True`` to be passed in order to work with resolutions different from what the encoder was trained for.

.. autoclass:: segmentation_models_pytorch.DPT
