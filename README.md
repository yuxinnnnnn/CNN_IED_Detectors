## Deep Learning for Detection of Interictal Epileptic Discharges (IEDs) from Scalp Electroencephalogram (EEG) and Magnetoencephalogram (MEG) Recordings

### NSCI 420 - Final Year Project

#### Author: Yuxin Zhou

#### Supervisor: Dr. Sylvain Baillet

#### Department of Neuroscience, McGill University

#

This repository contains three Jupyter Notebook files, each serving a specific purpose in the development of 2D CNN IED detectors:

1. `IED_Detector_EEG_and_MEG_single-patient.ipynb`: This notebook focuses on generating individual 2D CNN IED detectors for each of the six patients (Patients 0013, 0025, 0049, 0053, 0060, 0090), utilizing both EEG and MEG recordings. It demonstrates the process of training and evaluating the performance of single-patient models.
2. `IED_Detector_EEG_std-PCA-method.ipynb`: This notebook explores the development of 2D CNN IED detectors using EEG recordings that have been processed with the _**standard PCA method***_. This method involves extracting the first 20 principal components (PCs) to reduce dimensionality and noise in the data.
3. `IED_Detector_EEG_PCs-ordering-method.ipynb`: This notebook presents an alternative approach to processing EEG recordings, using the _**PCs ordering method****_. This method builds upon the standard PCA method, incorporating additional ranking algorithms based on kurtosis and variance to emphasize relevant features and minimize noise impact. The notebook demonstrates the generation of 2D CNN IED detectors using this method.

##

_Acknowledgment_: The single-patient model using data from Patient 0090 was originally developed by Jenny Zheng, a previous NSCI 420 student from the host lab. We have adapted and utilized the code with permission from the original repository, which can be found at https://github.com/jenny12138/CNN_SinglePatient. Throughout the code development process, we received valuable assistance and guidance from Raymundo Cassani. We extend our gratitude to both Jenny Zheng and Raymundo Cassani for their contributions to this project.
