# EfficientNet Diabetic Retinopathy classification
Fine-tuning two EfficientNet-B3 for Diabetic Retinopathy classification using Kaggle APTOS 2019 Blindness Detection dataset.

### Background

Diabetic retinopathy (DR) is a common complication of diabetes and a leading cause of blindness in working-age adults [1]. Early detection and treatment of DR could prevent vision loss. In this project, we train two EfficientNet [2] Convolutional Neural Networks (CNNs) to classify DR into five categories: normal, mild, moderate, severe, and proliferative. We fine-tuned an EfficientNet-B3 model on the Kaggle APTOS-19 dataset as a baseline, achieving a balanced accuracy (BACC) of 0.565 on the test set. This performance was further improved through an enhanced training procedure, resulting in a BACC of 0.594.


### Fine-tuning the last linear layer
![baseline_results](https://github.com/user-attachments/assets/887a5f28-915f-4990-9fe5-a13f6f148416)

### Fine-tuning all layers
![improved_results](https://github.com/user-attachments/assets/92378720-3d87-49ff-a4d1-1db065875ab5)

### Training and validation loss
![losses](https://github.com/user-attachments/assets/86cbc033-4729-4df1-84d3-6ac47c37a635)

### Validation scores
![metrics](https://github.com/user-attachments/assets/8d4bee28-3d4f-4364-b937-d95768d59df1)

### Bootstrapped CI
![bootstrap](https://github.com/user-attachments/assets/a7c45073-7abf-45f0-aa9d-158694fbd350)

\\

[1] Martina Kropp et al. “Diabetic retinopathy as the leading cause of blindness and early predictor of cascading complications—risks and mitigation.” In: EPMA Journal 14.1 (Feb. 2023), 21–42. ISSN: 1878-5085. DOI: 10.1007/s13167-023-00314-8. URL: http://dx.doi.org/10.1007/s13167-023-00314-8.

[2] Mingxing Tan and Quoc V. Le. “EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.” In: ArXiv abs/1905.11946 (2019).
