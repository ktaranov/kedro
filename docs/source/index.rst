.. Kedro documentation master file, created by
   sphinx-quickstart on Mon Dec 18 11:31:24 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


.. image:: https://raw.githubusercontent.com/quantumblacklabs/kedro/develop/static/img/kedro_banner.png
    :alt: Kedro logo
    :class: kedro-logo

Welcome to Kedro's documentation!
=============================================

.. image:: https://img.shields.io/circleci/build/github/quantumblacklabs/kedro/master?label=master
    :target: https://circleci.com/gh/quantumblacklabs/kedro/tree/master
    :alt: CircleCI - Master Branch

.. image:: https://img.shields.io/circleci/build/github/quantumblacklabs/kedro/develop?label=develop
    :target: https://circleci.com/gh/quantumblacklabs/kedro/tree/develop
    :alt: CircleCI - Develop Branch

.. image:: https://img.shields.io/badge/license-Apache%202.0-blue.svg
    :target: https://opensource.org/licenses/Apache-2.0
    :alt: License is Apache 2.0

.. image:: https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue.svg
    :target: https://pypi.org/project/kedro/
    :alt: Python version 3.6, 3.7, 3.8

.. image:: https://badge.fury.io/py/kedro.svg
    :target: https://pypi.org/project/kedro/
    :alt: PyPI package version

.. image:: https://img.shields.io/conda/vn/conda-forge/kedro.svg
    :target: https://anaconda.org/conda-forge/kedro
    :alt: Conda package version

.. image:: https://readthedocs.org/projects/kedro/badge/?version=stable
    :target: https://kedro.readthedocs.io/
    :alt: Docs build status

.. image:: https://img.shields.io/discourse/users?server=https%3A%2F%2Fdiscourse.kedro.community%2F
    :target: https://discourse.kedro.community/
    :alt: Discourse users

.. image:: https://img.shields.io/badge/code%20style-black-black.svg
    :target: https://github.com/psf/black
    :alt: Code style is Black

.. image:: https://zenodo.org/badge/182067506.svg
   :target: https://zenodo.org/badge/latestdoi/182067506
    :alt: Citation Reference

.. toctree::
   :maxdepth: 2
   :caption: Introduction

   01_introduction/01_introduction


.. toctree::
   :maxdepth: 2
   :caption: Get started

   02_get_started/01_prerequisites
   02_get_started/02_install
   02_get_started/03_hello_kedro
   02_get_started/04_new_project
   02_get_started/05_example_project
   02_get_started/06_starters

.. toctree::
   :maxdepth: 2
   :caption: Tutorial

   03_tutorial/01_spaceflights_tutorial
   03_tutorial/02_tutorial_template
   03_tutorial/03_set_up_data
   03_tutorial/04_create_pipelines
   03_tutorial/05_package_a_project
   03_tutorial/06_visualise_pipeline

.. toctree::
   :maxdepth: 2
   :caption: Kedro project setup

   04_kedro_project_setup/01_dependencies
   04_kedro_project_setup/02_configuration
   04_kedro_project_setup/03_session
   04_kedro_project_setup/04_mini_kedro

.. toctree::
   :maxdepth: 2
   :caption: Data Catalog

   05_data/01_data_catalog
   05_data/02_kedro_io

.. toctree::
   :maxdepth: 2
   :caption: Nodes and pipelines

   06_nodes_and_pipelines/01_nodes
   06_nodes_and_pipelines/02_pipeline_introduction
   06_nodes_and_pipelines/03_modular_pipelines
   06_nodes_and_pipelines/04_run_a_pipeline
   06_nodes_and_pipelines/05_slice_a_pipeline

.. toctree::
   :maxdepth: 2
   :caption: Extend Kedro

   07_extend_kedro/01_common_use_cases
   07_extend_kedro/02_hooks
   07_extend_kedro/03_custom_datasets
   07_extend_kedro/04_plugins
   07_extend_kedro/05_create_kedro_starters
   07_extend_kedro/06_transformers
   07_extend_kedro/07_decorators


.. toctree::
   :maxdepth: 2
   :caption: Logging

   08_logging/01_logging

.. toctree::
   :maxdepth: 2
   :caption: Development

   09_development/01_set_up_vscode
   09_development/02_set_up_pycharm
   09_development/03_commands_reference
   09_development/04_lint
   09_development/05_debugging

.. toctree::
   :maxdepth: 2
   :caption: Deployment

   10_deployment/01_deployment_guide
   10_deployment/02_single_machine
   10_deployment/03_distributed
   10_deployment/04_argo
   10_deployment/05_prefect
   10_deployment/06_kubeflow
   10_deployment/07_aws_batch
   10_deployment/08_databricks
   10_deployment/09_aws_sagemaker
   10_deployment/10_aws_step_functions
   10_deployment/11_airflow_astronomer

.. toctree::
   :maxdepth: 2
   :caption: Tools integration

   11_tools_integration/01_pyspark
   11_tools_integration/02_ipython

.. toctree::
   :maxdepth: 2
   :caption: FAQs

   12_faq/01_faq
   12_faq/02_architecture_overview

.. toctree::
   :maxdepth: 2
   :caption: Resources

   13_resources/01_logos
   13_resources/02_glossary


API documentation
=================

.. autosummary::
   :toctree:
   :caption: API documentation
   :template: autosummary/module.rst
   :recursive:

   kedro

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
