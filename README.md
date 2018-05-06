# MVCNN
MultiVariate Convolutional Neural Network.
This work proposes a tensor scheme along with a novel deep learning architecture called multivariate convolutional neural network (MVCNN) for multivariate time series classification, in which the proposed architecture considers multivariate and lag-feature characteristics. We
evaluate our proposed method with prognostics and health management (PHM) 2015 challenge data.

The proposed input tensor scheme transforms the multivariate time series data into appropriate tensor representation, so that the MVCNN could deal with multivariate data, in which we use filters to exploit local interactions among variables. The PHM 2015 challenge requires to predict start time and end time for each fault, explaining why we use two different models to predict start time and end time, sequentially. MVCNN comprises four stages, including input tensor transformation, univariate convolution, multivariate convolution, and fully connected stages. The introductions for the four stages are listed below.
