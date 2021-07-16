# EyeblinkMaster

Title: Eyeblink Master Library (Offline Set)
Ver. 20160401

Author:  prof. Won-Du Chang, Pukyong National University, Korea Rep.
Contact: 12cross@gmail.com

This is a library to detect Eyeblink Artifact from EEG, using Multi SDW Algorithm

You may try to run as follows to check the results.
">> sample_test"

It is recommended to optimize the threshold to adapt your own data.

--------------------------------------------------------------------------------------------------------
Please cite the following papers if you utilize this library for your purpose.

[1] Won-Du Chang,  Jeong-Hwan Lim, Chang-Hwan Im, An Unsupervised Eye Blink Artifact Detection Method for Real-time Electroencephalogram Processing," Physiological Measurement, 37 (3), 401-417, 19 Feb. 2016.
[2] Won-Du Chang, Ho-seung Cha, Kiwoong Kim, Chang-Hwan Im, "Detection of Eye Blink Artifacts from Single Prefrontal Channel Electroencephalogram," Computer Methods and Programs in Biomedicine (0169-2607) , 1 Feb. 2016


---------------------------------------------------------------------------------------------------------


The file descriptions are as follows:

1. sample_test
	- Detecting eyeblinks from sample.txt
2. detectblink
	- detect eyeblink from given data (should be sampled in 64Hz) Threshold will be automatically set.
3. detectblink_withThreshold
	- similar to detectblink, but you can set your own threshold
4. eogdetection_accdiff.m
	- Detect EOG using a huristic algorithm (accumulated 1st-derivate과 min/max point)

5. mark_allRange
	- a function to highlight the detected range
6. calMultiSDW.m
	- function for MSDW filter
7. calSDW.m
	- Function to calculate SDW
8. automaticThresholding
	- Function for automaticThresholding
9. datastructure
	- Functions related to datastructure
10. SimpleMath
	- custom math library
11. sample.txt
	-sample file (Sampling Rate: 2048Hz)

12. README.txt
	- Description

