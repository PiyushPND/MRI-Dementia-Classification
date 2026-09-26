# MRI-Dementia-Classification

Dementia is a progressive neurodegenerative disorder that significantly affects cognitive functions such as memory, reasoning, and decision-making. Early detection is essential for effective management and treatment planning. In recent years, deep learning techniques have demonstrated strong potential in automating the diagnosis of dementia using medical data such as Magnetic Resonance Imaging (MRI) and Electroencephalography (EEG). 

This project presents a comparative analysis of four deep learning-based approaches for dementia detection, implemented using both MRI and EEG data. Three independent models are developed using MRI images, including a hybrid Convolutional Neural Network (CNN) with Transformer encoder, a transfer learning-based model utilizing a pretrained ResNet50 architecture, and a custom deep CNN model. Additionally, an EEG-based approach is implemented. 

Each model is designed and evaluated based strictly on its implementation, including preprocessing techniques, architectural design, training procedures, and evaluation strategies. The MRI-based models focus on spatial feature extraction from brain images, while the EEG-based model captures temporal patterns in neural signals. Performance evaluation is conducted using metrics such as accuracy, confusion matrix, classification report, and ROC-AUC where available. 

The study highlights the effectiveness of deep learning techniques in dementia detection across different data modalities and provides a structured comparison of the implemented approaches without introducing external assumptions or modifications. The results demonstrate the applicability of both image-based and signal-based models in supporting automated diagnostic systems. 
