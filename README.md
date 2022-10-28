# My-Project
COMP4560 Homework

keywords: Functional connectivity, fMRI, Convolutional Neural Networks, Autism Spectrum Disorder, ABIDE

Please modify the root folder in order to make the code read the input file.

__Setup__ \
We need to read the input dataset follow the instruction in https://github.com/preprocessed-connectomes-project/abide \

The Command is \
python download_abide_preproc.py -d func_preproc -p cpac -s filt_global -o RootFolder\DataSet\ 
python download_abide_preproc.py -d rois_aal -p cpac -s filt_global -o RootFolder\DataSet\ 
python download_abide_preproc.py -d rois_cc200 -p cpac -s filt_global -o RootFolder\DataSet\ 
python download_abide_preproc.py -d rois_cc400 -p cpac -s filt_global -o RootFolder\DataSet\ 

__Requirements__ \
Tensorflow (>= 2.6.0) \
Keras ( = 2.6.0) \
Numpy \
Nibabel \
Scikit-learn \

__Usage__ \
