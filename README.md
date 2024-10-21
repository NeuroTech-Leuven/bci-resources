# BCI Resources

Resources for learning about Brain-Computer Interface design, development and research.

If you encounter an interesting or qualitative resource, or something of which you think it might be valuable to the team or future teams, do not hesitate to add it!


## General resources & BCI concepts

* [book,*] [Brain-Computer Interfaces - Principles and Practice, Wolpaw & Wolpaw, 2012](https://www.ece.uprm.edu/~manian/BCI%20principles%20and%20practice.pdf)
* [book] [NeuroTechX Neurotechnology Primer](https://neurotechx.com/download-the-neurotech-primer/)
* [paper] [Nicolas-Alonso, Luis Fernando, and Jaime Gomez-Gil. "Brain computer interfaces, a review." sensors 12.2 (2012): 1211-1279.](https://doi.org/10.3390/s120201211)
* [paper] [Wolpaw, Jonathan R., et al. "Brain–computer interfaces for communication and control." Clinical neurophysiology 113.6 (2002): 767-791.](https://doi.org/10.1016/S1388-2457(02)00057-3)
* [paper] [Wolpaw, Jonathan R., Jose Del R. Millan, and Nick F. Ramsey. "Brain-computer interfaces: Definitions and principles." Handbook of clinical neurology 168 (2020): 15-23.](https://doi.org/10.1016/B978-0-444-63934-9.00002-0)
* [links] [NeuroTechX edu](https://learn.neurotechedu.com/)
* [links] [NeuroTechX BCI resource github](https://github.com/NeuroTechX/awesome-bci)
* [links] [NeuroTechX webinars](https://neurotechx.com/webinars/)

## Paradigm and stimulation

* [paper] [Abiri, Reza, et al. "A comprehensive review of EEG-based brain–computer interface paradigms." Journal of neural engineering 16.1 (2019): 011001.](10.1088/1741-2552/aaf12e)
* [toolkit] [psychopy](https://www.psychopy.org/), a python library for precise experimental visual and auditory stimulation
* [tooklkit] [psychtoolbox](http://psychtoolbox.org/), a MATLAB library for precise experimental visual and auditory stimulation

## Signal processing

* [book] [Cohen, M. X. Analyzing neural time series data: theory and practice. MIT press, 2014.](https://doi.org/10.7551/mitpress/9609.001.0001) (through KU Leuven LIMO for access)
* [video,*]  Analyzing Neural Time Series by Mike X Cohen
  
  https://www.youtube.com/playlist?list=PLn0OLiymPak0t1moK3sn4Sl1seXlEOPHT
  
  https://www.youtube.com/playlist?list=PLn0OLiymPak2jxGCbWrcgmXUtt9Lbjj_A
  
  https://www.youtube.com/playlist?list=PLn0OLiymPak2BYu--bR0ADNBJsC4kuRWs

  https://www.youtube.com/playlist?list=PLn0OLiymPak1wp4wMQ7tbYrtyFUatMVJs

  https://www.youtube.com/playlist?list=PLn0OLiymPak1Ch2ce47MqwpIw0x3m6iZ7  

* [toolkit,*] [MNE](https://mne.tools/stable/index.html): a python library for EEG/MEG signal processing
* [tutorial,*] [MNE's signal processing and analysis tutorials](https://mne.tools/stable/auto_tutorials/index.html)
* [toolkit] [EEGLAB](https://sccn.ucsd.edu/eeglab/index.php): a MATLAB toolbox for EEG signal processing
* [toolkit] [Fieldtrip](https://www.fieldtriptoolbox.org/): a MATLAB toolbox for EEG/MEG/iEEG signal processing
* [toolkit] [MNE-BIDS-pipeline](https://mne.tools/mne-bids-pipeline/stable/) a framework to implement preprocessing pipelines with MNE for BIDS format data

## Decoding

* [paper,*] [Lotte, Fabien, et al. "A review of classification algorithms for EEG-based brain–computer interfaces: a 10 year update." Journal of neural engineering 15.3 (2018): 031005.](https://doi.org/10.1088/1741-2552/aab2f2)
* [paper] [Barachant, Alexandre, et al. "Multiclass brain–computer interface classification by Riemannian geometry." IEEE Transactions on Biomedical Engineering 59.4 (2011): 920-928.](https://doi.org/10.1109/TBME.2011.2172210)
* [toolkit] [MNE decoding module](https://mne.tools/stable/api/decoding.html#module-mne.decoding). Nex to signal processing capabilities, MNE also contains implementations of some frequently used decoding algorithms.
* [toolkit] [pyRiemann](https://pyriemann.readthedocs.io/en/latest/) contains python implementations of Riemannian Geometry-based BCI decoders ant utilities.
* [toolkit,*] [MOABB](https://moabb.neurotechx.com/docs/). Next to an interface for publicly available BCI benchmark datasets, it also contains implementations of preprocessing pipelines and decoders.

## On-line BCI

* [toolkit,*] [Lab Streaming Layer (lsl)](https://labstreaminglayer.org/#/), a middleware ecosystem to stream, receive, synchronize, and record neural, physiological, and behavioral data streams acquired from diverse sensor hardware
* [toolkit] [pyLSL](https://github.com/labstreaminglayer/pylsl), a python library to interface with lsl
* [toolkit,*] [OpenVibe](https://openvibe.inria.fr/), a software platform with graphical user interface dedicated to designing, testing and using brain-computer interfaces
* [tutorial] [OpenVibe tutorials](https://openvibe.inria.fr/documentation-index/) some plug-and-play examples of working, on-line BCIs to get started
* [toolkit] [timeflux](https://timeflux.io/), a framework for the acquisition and real-time processing of biosignals (text-based interface)

## Datasets

* [toolkit,*] [MOABB](https://moabb.neurotechx.com/docs/), the largest BCI benchmark database with python interface
* [tutorial] [Tutorial on MOABB usage](https://github.com/sylvchev/moabb_minischool)
* [toolkit] [Brain Imaging Data Structure (BIDS)](https://bids.neuroimaging.io/), a data format specification for a brain data storage.
* [toolkit] [MNE-BIDS](https://mne.tools/mne-bids/stable/index.html), a python library to manipulate data in BIDS format with an interface to MNE
* [platform] [openneuro](https://openneuro.org/), a free and open platform for validating and sharing BIDS-compliant MRI, PET, MEG, EEG, and iEEG data
* [toolkit] [openneuro-py](https://pypi.org/project/openneuro-py/), a python library to download and manipulate openneuro datasets
* [links] The [BCI competition](https://www.bbci.de/competition/) datasets
* [links] The [BNCI horizon 2020](https://bnci-horizon-2020.eu/database/data-sets) datasets
* [links]  https://github.com/meagmohit/EEG-Datasets
* [links] https://openbci.com/community/publicly-available-eeg-datasets/
* [links] https://github.com/hisunjiang/Public-datasets-of-BCI

## Development

* TODO: Some good python tutorials
* TODO: Some good jupyter tutorials
* TODO: Some good git tutorials

## Hardware

* [toolkit] [brainflow](https://brainflow.org/), a library with support for multiple programming languages to obtain, parse and analyze EEG, EMG, ECG and other kinds of data from biosensors
* TODO: links to documentation for headset use, placement, maintenance and SDKs/interfacing

## Machine learning
* [video,*] [StatQuest machine learning](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) concepts and techniques videos
* [video] [3blue1brown neural network videos](https://www.3blue1brown.com/topics/neural-networks)
* [video] [3blue1brown linear algebra videos](https://www.3blue1brown.com/topics/linear-algebra)
* [toolkit] [Scikit-learn], a python library implementing machine learning models and evaluation pipelines

