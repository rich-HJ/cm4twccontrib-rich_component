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

2. Rename the directory using your model name (note: replace <model_name> with your model name,
   please follow `PEP8 naming convention <https://www.python.org/dev/peps/pep-0008/#package-and-module-names>`_
   for your model name, i.e. all-lowercase names with underscores if this improves readability only):

.. code-block:: bash

   mv cm4twccontrib-template cm4twccontrib-<model_name>

3. Change the remote repository using git remote (note: replace <github_id> with your GitHub account):

.. code-block:: bash

   cd cm4twccontrib-<model_name>
   git remote set-url origin https://github.com/<github_id>/cm4twccontrib-<model_name>.git

4. Rename the Python package using your model name:

.. code-block:: bash

   mv cm4twccontrib/template cm4twccontrib/<model_name>

5. Develop your own component contribution(s) following the
   `Guide for Contributors <https://cm4twc-org.github.io/cm4twc/for_contributors/preparation.html>`_

6. List your package dependencies in `<requirements.txt>`_

7. Update `<README.rst>`_ to briefly describe your component(s)

8. Update the first part of `setup.py <setup.py#L4-L20>`_ with your details
