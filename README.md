# DLMF4-WFPMWV
This code for article "Short-term forecasting of 3D wind field based on deep learning and water vapor"

All files starting with "风场反演-多层次小时数据-" are model operation results; the "1hour" following the file name indicates a forecast lead time of 1 hour, and so on; the "CNN-Transformer" in the file name represents the use of the CNN-Transformer model for water vapor retrieval of wind; "5year-order" denotes the use of 5 years of data with sequential splitting for the training set, validation set, and test set (all models adopt this configuration); if the file name ends with "fusion," it indicates a hybrid model.  

All files starting with "ANN风场网络风场反演-多层次小时数据-" represent experiments conducted using the ANN network, where "1hour" indicates a forecast lead time of 1 hour, and so on; the "PE" in the file name is consistent with the naming in the extended experiments in the article—detailed meanings can be found in the paper; "5year-order" denotes the use of 5 years of data with sequential splitting for the training set, validation set, and test set (all models adopt this configuration).  

Other codes are plotting scripts for the paper.  

The custom library package "Auto_paint_self" used in the article, along with its documentation, has been uploaded.  

For any questions, please contact the author at: 492947833@qq.com.
