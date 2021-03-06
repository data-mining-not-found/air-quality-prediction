# air-quality-prediction

This project is a group coursework on the data mining module designed to predict air quality (PM2.5, PM10, and NO2 concentrations of the next 48 hours) in London.

The entire folder of 'London' can refer to the sharing google drive folder, which contains all of the processed data files. (https://drive.google.com/drive/folders/1ueRCwIpzqs520pXdmIw77c9leaLDkO4y?usp=sharing)

These ten notebooks show the version 1.0 released code and the remaining Todo-list on May 1st.

Release note: (Compared with version 0.0)

Add the 64 weather forecasting features in the 2_feature_engineering.ipynb file. (Yuefu)

Add the generate_train_data function in the 3_generate_train_data.ipynb file. (Yuefu)

Update the station selection in the 3_generate_train_data.ipynb file. (Yuefu)

Update the lightgbm model training and optimization in the 4_lightgbm_model.ipynb file. (Yuefu)

Update the lightgbm model testing scores in the 4_lightgbm_model.ipynb file. As the result of adding 64 weather forecasting features, in version 1.0, the SMAPE (symmetric mean absolute percentage error) of the PM 2.5 validation dataset reduced from 0.409 (version 0.0) to 0.248, and the SMAPE of the PM 10 validation dataset reduced from 0.355 (version 0.0) to 0.224, and the SMAPE of the N02 validation dataset reduced from 0.402 (version 0.0) to 0.259 (Yuefu) 

Add the 5_xgboost_model.ipynb file. (YuLin)

Add the 6_nn_model.ipynb file. (Danfeng)

Add the 7_lr_model.ipynb file. (Pengxiang)

Add the 8_feature_analysis.ipynb file. (YuLin, Weiqin)

Add the 9_model_ensemble.ipynb file. (some people)
