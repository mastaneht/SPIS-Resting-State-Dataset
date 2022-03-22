# SPIS-Resting-State-Dataset
A Multimodal Dataset with EEG and forehead EOG for Resting-State analysis.

This dataset is a subset of SPIS Resting-State EEG Dataset.

Copyright:

Mastaneh Torkamani-Azar and Mujdat Cetin

Signal Processing and Information Systems (SPIS) Laboratory

Faculty of Engineering and Natural Sciences 

Sabanci University 

Istanbul 34956, Turkey

If you use SPIS Resting-State Dataset in your research, please cite the following paper:

M. Torkamani-Azar, S. D. Kanik, S. Aydin and M. Cetin, "Prediction of Reaction Time and Vigilance Variability From Spatio-Spectral Features of Resting-State EEG in a Long Sustained Attention Task," in IEEE Journal of Biomedical and Health Informatics, vol. 24, no. 9, pp. 2550-2558, Sept. 2020, doi: 10.1109/JBHI.2020.2980056. https://ieeexplore.ieee.org/document/9034192

If you have any questions about this dataset, please kindly contact Mastaneh Torkamani Azar (mastaneh.torkamani@uef.fi) or Prof. Mujdat Cetin (mujdat.cetin@rochester.edu).
http://labs.sabanciuniv.edu/spis/

Data Description:

These 10 datasets were recorded prior to a 105-minute session of Sustained Attention to Response Task with fixed-sequence and 
varying ISIs.

Each dataset contains 2.5 minutes of eyes-open (EO) and 2.5 minutes of eyes-closed (EC) resting-state EEG.

Monopolar EEG activity was collected at 2,048 Hz via 64 Ag/AgCl active electrodes mounted according to the 10-10 International 
Electrode Placement System.

Experiments were conducted in the early afternoon to induce drowsiness in the already idled brain networks.

More explanation is provided in M. Torkamani-Azar, S. Demir Kanik, S. Aydin and M. Cetin, "Prediction of Reaction Time and 
Vigilance Variability from Spatio-Spectral Features of Resting-State EEG in a Long Sustained Attention Task," in IEEE Journal 
of Biomedical and Health Informatics.

File format:

All files are saved as the .mat format using Matlab Version 7.3. The channe location is also provided.

The raw data in this file has been downsampled to 256 Hz from the original sampling rate of 2,048 Hz.

Channels 1 to 64 correspond to the monopolar EEG channels using the following channel names:

channelList = 
{'Fp1';'AF7';'AF3';'F1';'F3';'F5';'F7';'FT7';'FC5';'FC3';'FC1';'C1';'C3';'C5';'T7';'TP7';'CP5';'CP3';'CP1';'P1';'P3';'P5';'P7';.
..
    'P9';'PO7';'PO3';'O1';'Iz';'Oz';'POz';'Pz';'CPz';'Fpz';
    'Fp2';'AF8';'AF4';'Afz';'Fz';'F2';'F4';'F6';'F8';'FT8';'FC6';'FC4';'FC2';'FCz';'Cz';...
    'C2';'C4';'C6';'T8';'TP8';'CP6';'CP4';'CP2';'P2';'P4';'P6';'P8';'P10';'PO8';'PO4';'O2'};

Channels 65 to 67: Three surface EOG electrodes connected to the outer corners of the eyes and middle of the eyebrows.

Channel 68: The trigge channel. 

trigger values = 200 correspond to the eyes-open (EO) and trigger values = 220 correspond to the eyes-closed (EC) states.
