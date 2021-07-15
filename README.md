# DFUC21
This repository contains code for the submission of NITS_AS21 team in the Diabetic Foot Ulcer Grand Challenge 2021 , which is organized as part of MICCAI 2021.


The DFUC21 challenge is accessible at https://dfu-2021.grand-challenge.org/

The MICCAI 2021 website can be accessed at https://www.miccai2021.org/en/

In this work, a **Prediction Level Ensembling Approach** is proposed which combines the predicitve capabilities of 3 Deep CNN models (Pretrained EfficientNetB0, Pretrained DenseNet121 and DenseNetSmall with Regularization).

The proposed approach has been evaluated on the held out validation set, the results for which are mentioned below:

    "bothAUC": 0.9120065789473684,
    "noneAUC": 0.8039833997777924,
    "Accuracy": 0.624,
    "macroAUC": 0.8509005108759262,
    "microAUC": 0.8734173333333334,
    "BothRecall": 0.5227272727272727,
    "NoneRecall": 0.8691588785046729,
    "MacroRecall": 0.6170611119636398,
    "BothF1-Score": 0.5476190476190476,
    "NoneF1-Score": 0.7181467181467183,
    "infectionAUC": 0.7545464814187282,
    "ischaemiaAUC": 0.9291408934707904,
    "BothPrecision": 0.575,
    "MacroF1-Score": 0.5553030526434782,
    "NonePrecision": 0.6118421052631579,
    "MacroPrecision": 0.5623355263157894,
    "InfectionRecall": 0.40969162995594716,
    "IschaemiaRecall": 0.6666666666666666,
    "InfectionF1-Score": 0.5299145299145299,
    "IschaemiaF1-Score": 0.425531914893617,
    "InfectionPrecision": 0.75,
    "IschaemiaPrecision": 0.3125,
    "WeightedAverageRecall": 0.624,
    "WeightedAverageF1-Score": 0.6089044255852767,
    "WeightedAveragePrecision": 0.6623434210526316
