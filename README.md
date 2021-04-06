# covid_genosensors_ML

Supporting Information for the paper:

"Detection of a SARS-CoV-2 Sequence with Genosensors Using Data Analysis Based on Information Visualization and Machine Learning Techniques"


The repositoty contains the Machine Learning data computed from SEM images of the genosensors. Matlab files under /COVID-DNA_descriptors/ are organized as:

_scale_method.mat_

where "_scale_" are either 1 or 10, corresponding to _1,000×_ or _10,000×_. The "_method_" is the computer vision algorithm used to extract visual descriptors from each image. The file contains a list of variable as follows: 

_charc_           -> cell array of experimental metadata of each sample 

_classes_8_       -> array of sample classes

_classes_9_       -> array of sample classes

_classes_binary_  -> array of sample classes in the binary form (positive and negative)

_features_        -> _m × n_ matrix where _m_ corresponds to samples and _n_ to features

_filenames_       -> cell array with the file name of each sample

_indexes_charc_   -> 

_method_          -> name of the method used for computing features
