# Reassessment-project-Resit
## Abstract
The novel COVID-19 pandemic has spread all over the world. Due to its easy transmission, it is crucial to develop techniques to accurately and easily identify the presence of COVID-19 and distinguish it from other forms of touches of flu and pneumonia. Recent research has shown that the chest X-rays of patients suffering from COVID-19 depict certain radiography abnormalities. This work aims to build a deep CNN that can perform feature extraction and binary classification of the open-source dataset of CT scan of coronavirus patients. This work presents a 3-step technique to fine-tune a pre-trained VGG19, Xception, and Inception V3 architectures to improve model performance and reduce training time. It was achieved through progressively resizing input images to  224x224x3 pixels and fine-tuning the network at each stage. Among three selected pre-trained models, the VGG 19 outperformed with a 0.99, 0.88, 0.85, 0.86, 0.83, 0.85, 0.85 for Train accuracy, validation accuracy, test accuracy, precision, recall, F1 score, area under the curve values, respectively. 
## Materials
The Coronavirus CT dataset can be obtain through the [LINK](https://github.com/UCSD-AI4H/COVID-CT) or via the command:  ``` !git clone https://github.com/UCSD-AI4H/COVID-CT.git``` on the juypter notebook, google colaboratory, or any other platform.
## Codes
The codes were written with python programming language.
## Acknowledgement
The author appreciates and wishes to acknowledge the reuse of codes implemented on the VGG16 binary classification by the course coordinator: [Prof. Raza Haider](https://github.com/sagihaider), and asssited by Matran-Fernandez, Ana.
