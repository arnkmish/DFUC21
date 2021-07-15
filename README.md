# DFUC21
This repository contains code for the submission of NITS_AS21 team in the Diabetic Foot Ulcer Grand Challenge 2021 , which is organized as part of MICCAI 2021.


The DFUC21 challenge is accessible at https://dfu-2021.grand-challenge.org/

The MICCAI 2021 website can be accessed at https://www.miccai2021.org/en/

In this work, a **Prediction Level Ensembling Approach** is proposed which combines the predicitve capabilities of 2 Deep CNN models (Pretrained EfficientNetB0 and Pretrained DenseNet121).

The proposed approach has been evaluated on the held out validation set, the results for which are mentioned below:

    "bothAUC": 0.9089912280701755,
    "noneAUC": 0.8111724723874257,
    "Accuracy": 0.594,
    "macroAUC": 0.8439229430214277,
    "microAUC": 0.8757613333333332,
    "BothRecall": 0.3409090909090909,
    "NoneRecall": 0.8084112149532711,
    "MacroRecall": 0.5318968899751353,
    "BothF1-Score": 0.38461538461538464,
    "NoneF1-Score": 0.7004048582995951,
    "infectionAUC": 0.7404431104871634,
    "ischaemiaAUC": 0.9103780068728522,
    "BothPrecision": 0.4411764705882353,
    "MacroF1-Score": 0.48613309637572144,
    "NonePrecision": 0.6178571428571429,
    "MacroPrecision": 0.48970035382574084,
    "InfectionRecall": 0.44493392070484583,
    "IschaemiaRecall": 0.5333333333333333,
    "InfectionF1-Score": 0.532981530343008,
    "IschaemiaF1-Score": 0.326530612244898,
    "InfectionPrecision": 0.6644736842105263,
    "IschaemiaPrecision": 0.23529411764705882,
    "WeightedAverageRecall": 0.594,
    "WeightedAverageF1-Score": 0.5853889663414532,
    "WeightedAveragePrecision": 0.6119962627156126
