## **Deep Recurrent Neural Networks for Magnetic Resonance Fingerprinting**

Abstract: Magnetic resonance imaging (MRI) is a medical imaging technique used to generate highly detailed anatomical images of the body. Magnetic resonance fingerprinting (MRF) has been introduced as a powerful alternative to traditional MRI by providing enhanced measurement accuracy and image acquisition speed. MRF functions by simultaneously acquiring multiple tissue parameters in a pseudo-randomized manner, generating a signal evolution, or 'fingerprint', unique to different tissues. A pattern recognition algorithm is used to pattern match fingerprints to a preexisting dictionary of predicted signal evolution's. Current research aims to enhance the speed and accuracy of this search algorithm by using machine learning techniques. Within this study we aim to exploit the time-dependent features found with an MRF signal sequence to train a deep recurrent neural network for parameter map reconstruction. In particular we propose two deep RNN architectures, the deep GRU and deep LSTM. Our deep RNN models contribute to the existing literature on MRF deep learning algorithms in that it scales to multi-parametric map reconstructions, with greater accuracy and compactness. 


The neural network architectures found within this package are proposed by:

DRONE model:
Cohen, O., Zhu, B. and Rosen, M.S., 2018. MR Fingerprinting Deep Reconstruction Network (DRONE). Magnetic resonance in medicine, 80(3), pp.885–894

Simple RNN models:
Oksuz, I., Cruz, G., Clough, J., Bustin, A., Fuin, N., Botnar, R.M., Prieto,C., King, A.P. and Schnabel, J.A., 2019. Magnetic resonance fingerprinting using recurrent neural networks. 2019 IEEE 16th international symposium onbiomedical imaging (isbi 2019). pp.1537–1540.

Deep RNN models:
C Litrico, "Deep Recurrent Neural Networks for Magnetic Resonance Fingerprinting", 2020.

Furthermore, data was acquired using an IR-bSSFP via the Cover BLoch response Iterative Projection (CoverBLIP) method: https://github.com/mgolbabaee/CoverBLIP
M Golbabaee, Z Chen, Y Wiaux, M Davies, “CoverBLIP: accelerated and scalable iterative matched-filtering for Magnetic Resonance Fingerprint reconstruction”, arxiv, 2018. (Extended version)

Training and testing data can be downloaded from:

t1t2rfdict: https://drive.google.com/file/d/12omFIZC9ThSabHOgIR5VtLWpwWkPviUI/view?usp=sharing

brain_phantom: https://drive.google.com/file/d/1p5yVTBrzzi_AjOBtFiMZQHBGyJKd70UO/view?usp=sharing

Pre-trained models can be downloaded from:

https://drive.google.com/drive/folders/13qOWR3GNLdxffKpVHat2wpyQ2ZTiJt6J?usp=sharing

© C Litrico (2020)
