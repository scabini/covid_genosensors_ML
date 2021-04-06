# covid_genosensors_ML

Supporting Information for the paper:

"Detection of a SARS-CoV-2 Sequence with Genosensors Using Data Analysis Based on Information Visualization and Machine Learning Techniques"


The repositoty contains the Machine Learning data computed from SEM images of the genosensors. Matlab files under /COVID-DNA_descriptors/ are organized as:

_scale_method.mat_

where "_scale_" are either 1 or 10, corresponding to _1,000×_ or _10,000×_. The "_method_" is the computer vision algorithm used to extract visual descriptors from each image. The file contains a list of variable as follows: 

charc           -> cell array of experimental metadata of each sample 

classes_8       -> array of sample classes

classes_9       -> array of sample classes

classes_binary  -> array of sample classes in the binary form (positive and negative)

features        -> _m × n_ matrix where _m_ corresponds to samples and _n_ to features

filenames       -> cell array with the file name of each sample

indexes_charc   -> 

method          -> name of the method used for computing features
