# Detection of Sensor Failures with CNN

Condition monitoring of hydraulic systems data: https://archive.ics.uci.edu/ml/datasets/Condition+monitoring+of+hydraulic+systems

The dataset addresses the condition assessment of a hydraulic test rig based on multi sensor data. Four fault types are superimposed with several severity grades impeding selective quantification. The data set was experimentally obtained with a hydraulic test rig. This test rig consists of a primary working and a secondary cooling-filtration circuit which are connected via the oil tank. The system cyclically repeats constant load cycles (duration 60 seconds) and measures process values such as pressures, volume flows and temperatures while the condition of four hydraulic components (cooler, valve, pump and accumulator) is quantitatively varied. The data set contains raw process sensor data (i.e. without feature extraction) which are structured as matrices (tab-delimited) with the rows representing the cycles and the columns the data points within a cycle. The aim is to predict the state of the hydraulic components according to the temperature sensors measured with a frequency of 1 Hz (60 observations for each cycle). A model made with CNN in Keras will be used to analyze the classification problem.

Notebook: https://github.com/belenburcu/deep-learning-CNN/blob/main/Project.ipynb
