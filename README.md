# Dataset-and-Task-Group-Framework-for-Heterogenous-High-Density-IoT-Environments 

This is the official repository of the paper "Dataset and Task Group 
Framework for Heterogenous High-Density IoT-Environments".

This repository is structured as follows:
- **tgf**: Contains the core components of the Task-Group-Framework. This includes:
  - Task
  - Task-Group
  - Flags
  - Pipeline 
  

- **executors**: Contains the implementations of various data processing steps for BLE packet data. 
                These processing steps are implemented with the Task-Group-Framework as "executors".

  
- **plotting**: Contains various implementations for plotting with matplotlib. Most of these implementations make extensive use of the Task-Group-Framework.


- **notebooks**: Contains three Jupyter Notebooks. These are:

  - "IntroductionToTaskGroupFramework": This Notebook introduces the Task-group-Framework with the application of linear-affine transformations to data.
  - "AnalysisPipeline": This notebook builds a complex data-pipeline for preprocessing the BLE packet data. The purpose of this data-pipeline
    is visual data analysis (i.e., plotting). 
  - "AnalysisPlots": This Notebook generates plots for visual data analysis of the BLE packet data. These plots are enabled by the before mentioned data-pipeline 
  and the plotting implementations built with the Task-Group-Framework.


- **output**: All outputs from the notebooks. This includes:
  - All plots generated with the implementations from the plotting directory.
  - All artefacts created in the notebooks (e.g., data-pipelines) stored as pickle objects for later use.
  - Some tables containing classification reports. 


- **wireshark_profile**: The wireshark-profile used to export from PCAP to CSV.

Note: The raw BLE packet data (including both PCAP and CSV files) is not contained in this repository, as it is too large for GitHub. 
The data can be found on the link below on Kaggle. Include the "data" folder as is on the top level directory to execute the Jupyter Notebooks locally.


Link to data: https://www.kaggle.com/datasets/stefansaxer/ble-packets-from-tracking-devices

**Note**: Local execution requires Python Version **3.11** or later. 



