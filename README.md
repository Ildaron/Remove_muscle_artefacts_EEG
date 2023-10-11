# Remove muscle artefacts EEG

# Introduction
This repository contains the implementation of a novel method for effectively removing artifacts from EEG signals. The approach combines the Empirical Mode Decomposition (EMD) method with a machine learning architecture to overcome the limitations of existing artifact removal techniques.  

# Method Overview
The proposed method focuses on enhancing the EMD method through interpolation of the upper and lower components. In conventional artifact removal methods, EMD is commonly employed. However, accurately interpolating the missing components while preserving inherent frequency components poses a significant challenge. To address this limitation, our method incorporates a machine learning technique. This addition allows us to carefully handle the interpolation process without directly manipulating the data.

# Key Features
EMD Enhancement: The method improves the EMD process by introducing a sophisticated interpolation technique for the upper and lower components.  
Machine Learning Integration: A machine learning technique is incorporated to handle interpolation, ensuring precise artifact removal without direct manipulation of the EEG data.  
Preservation of Characteristics: The key advantage lies in preserving the natural characteristics of the EEG signal during artifact removal.  
Fidelity Retention: By utilizing machine learning for interpolation, the average component obtained through EMD retains crucial frequency components of the original signal, maintaining the integrity and fidelity of the EEG data.  

# Contributing
We welcome contributions from the community. If you have suggestions or improvements, please open an issue or submit a pull request.

# License
This project is licensed under the MIT License. 

#  Contact
For inquiries, please contact ildarr2016@gmail.com
  
