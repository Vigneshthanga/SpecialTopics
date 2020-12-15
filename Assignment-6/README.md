# TFX Interactive context

This Colab-based tutorial will interactively walk through each built-in component of TensorFlow Extended (TFX).

It covers every step in an end-to-end machine learning pipeline, from data ingestion to pushing a model to serving.

Overview of Program
=================
Orchestration

In a production deployment of TFX, you will use an orchestrator such as Apache Airflow, Kubeflow Pipelines, or Apache Beam to orchestrate a pre-defined pipeline graph of TFX components. In an interactive notebook, the notebook itself is the orchestrator, running each TFX component as you execute the notebook cells.
Metadata

In a production deployment of TFX, you will access metadata through the ML Metadata (MLMD) API. MLMD stores metadata properties in a database such as MySQL or SQLite, and stores the metadata payloads in a persistent store such as on your filesystem. In an interactive notebook, both properties and payloads are stored in an ephemeral SQLite database in the /tmp directory on the Jupyter notebook or Colab server.

Requirements
============
Our model requires Tensorflow and Tensorflow Extended

How to Run / Alter Code
=======================
1) Run TFX_keras.ipynb
