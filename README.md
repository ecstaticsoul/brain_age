# Prediction of Individual Brain Ages from 3D MRI Datasets



## Abstract

Index terms: deep learning; brain age estimation; MRI.

Deep learning can accurately predict healthy individuals’ chronological age from T1-weighted MRI brain images. By feeding novel data into the model, the resulting bio-marker, termed brain age, has the potential to help investigate brain maturation and degeneration, as well as detect brain diseases in early phases. In this project, in order to evaluate the robustness of the brain age estimation system, four Convolutional Neural Network models were developed using different datasets. The training efficiency of the model is excellent compared to previous attempts.

Images were selected from an archive containing 2072 samples to form four datasets. By training separately on the datasets, the model’s performance with or without rotated images, with or without non-brain tissue interference, with or without dropout during testing, and with different data quality was compared. Input data were raw MRI images from individuals without known brain diseases with the mean image of the training data subtracted.

With the best performance model, the correlation between brain age and chronological age is evaluated as r=0.92, RMSE=9.66 years. With a smaller dataset, the model achieved 0.96 correlation. The model is capable of dealing with images with different orientations but performs poorly when non-brain tissues are involved. Removing dropout during testing phase shrinks the estimated chronological age, with strong correlation intact, suggesting the estimated value is a sum of several indexes. The image quality of 65×65×55 is enough for the sound performance of the model.

By integrating with deep learning techniques such as feature visualization and inversion, brain age has the potential to deepen our understanding of brain development processes. Furthermore, data from individuals with known brain diseases can turn the biomarker into a valid tool for clinical evaluation.
