# Fault-identification-in-wind-turbine

Here is a draft README.md file for your research work on fault identification in wind turbines using neural networks:

# Fault Identification in Wind Turbines using Neural Networks

## Overview
This research explores the application of neural networks, specifically Convolutional Neural Networks (CNNs), for identifying faults in wind turbines. The goal is to enhance the reliability and efficiency of wind turbine systems through accurate and timely fault detection.

## Dataset
The [Wind Turbine SCADA Dataset](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset) from Kaggle is used. It contains operational data from real wind turbines, including parameters like power output, wind speed, theoretical power curve etc. The data also has fault labels indicating presence/absence of faults.

## Methodology
- The dataset is preprocessed to handle missing values, outliers etc. 
- A CNN model is designed and trained on the dataset for binary fault classification
- The model consists of convolutional, pooling and dense layers
- It is trained for 10 epochs with batch size of 32, optimizing the binary cross-entropy loss
- Performance metrics like accuracy, precision, recall and F1-score are computed
  
## Results
The CNN model achieves:
- Training accuracy: 96.22%
- Validation accuracy: 95.71%
- Testing accuracy: 95.71%

This demonstrates the effectiveness of the CNN model in accurately identifying faults in wind turbines.

## Conclusion
The results validate that CNNs can learn useful patterns from wind turbine data for precise fault detection. This contributes towards improving reliability and efficiency of wind energy systems.

## Reference
The full paper is available [here](22MCA1065_FullPaper.docx).

Let me know if you would like me to modify or add any other details!
