AD-MRI-classification
This programs is for the paper [1], whose abstract is as follows.
Background As a kind of dementia, Alzheimer’s disease (AD) cannot be cured once diagnosed. Hence, it is very important to diagnose early and delay the deterioration of the disease through drugs.
Objective To reduce the computational complexity of conventional 3D convolutional networks, this paper uses machine learning as an auxiliary diagnosis of AD, and proposes three-dimensional (3D) transfer network which is based on two-dimensional (2D) transfer network to classify AD and normal groups with magnetic resonance imaging (MRI).
Method First, the method uses a 2D transfer Mobilenet to extract features from 2D slices of MRI, and further perform dimension reduction for the extracted features. Then, all of the 2D slice features of one subject are merged to classify.
Results The experiment in this paper uses an open access Alzheimer's disease database to evaluate the method. The experiment result show that the classifcation accuracy of the proposed 3D network is better than that of the existing 2D transfer network, increased by about 10 percentage points and the classifcation time is only about 1/4 of the existing one.
Conclusion The proposed method is to realize the classifcation of 3D MRI data through an existing 2D transfer network, and it not only reduces the complexity of conventional 3D networks, but also improves the classifcation accuracy. Because of the shared weight of the transfer network, besides, the classifcation time is reduced.
We use MATLAB and SPM12 software to complete the pre-processing of MRI data, and the details can be found in [1] and data proccess folder. The processed data can be obtained through the following links and extraction codes.
Link: https://pan.baidu.com/s/11MFNiYsUt08OrCwgYLNLeQ 
Extraction codes: ljli
OASIS: http://www.oasis-brains.org/
ADNI: http://adni.loni.usc.edu/
SPM12: https://www.fil.ion.ucl.ac.uk/spm/software/spm12/
In addition, all transfer learning methods are performed on Anaconda Python2.7 under Ubuntu, and the transfer learning platform is Keras with TensorFlow as the back end.
