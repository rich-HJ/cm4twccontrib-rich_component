A template to create cm4twc-compliant components
================================================

This repository features the package structure and contains the files
one needs to create component(s) that can be used with the Community
Model for the Terrestrial Water Cycle (`cm4twc`) Python package.

How to use the template?
------------------------

1. Copy this repository locally using git clone:

.. code-block:: bash

   git clone https://github.com/cm4twc-org/cm4twccontrib-template.git

2. Rename the directory using your model name:

.. code-block:: bash

   mv cm4twccontrib-template cm4twccontrib-<model_name>

3. Change the remote repository using git remote and your GitHub account:

.. code-block:: bash

   cd cm4twccontrib-<model_name>
   git remote set-url origin https://github.com/<github_id>/cm4twccontrib-<model_name>.git

4. Rename the Python package using your model name:

.. code-block:: bash

   mv cm4twccontrib/template cm4twccontrib/<model_name>

5. Develop your own component contribution(s) following the
   `Guide for Contributors <https://cm4twc-org.github.io/cm4twc/for_contributors/preparation.html>`_

5. List your package dependencies in `<requirements.txt>`_

6. Update `<README.rst>`_ to briefly describe your component(s)

7. Update the first part of `<setup.py>`_ with your details
