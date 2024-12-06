Installation
============

It is recommended to use **pip** for installation. Please make sure
**the latest version** is installed, as DeepOD is updated frequently:

.. code-block:: bash

   pip install deepod            # normal install
   pip install --upgrade deepod  # or update if needed


Alternatively, you could clone and run setup.py file:

.. code-block:: bash

   git clone https://github.com/python-devops-sre/deepod.git
   cd pyod
   pip install .


**Required Dependencies**\ :


* Python 3.10+
* numpy>=2.1.0
* scipy>=1.14.0
* scikit-learn>=1.5.0
* pandas>=2.0.0
* torch>=2.0.0
* ray>=2.6.1
* pyarrow>=11.0.0
* einops

