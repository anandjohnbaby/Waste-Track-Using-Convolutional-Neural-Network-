# **Waste Track Using Convolutional Neural Network (Xception)**
This project focuses on waste classification using deep learning techniques, specifically leveraging the **Xception** architecture for its efficiency in 
handling image classification tasks. The model achieved an impressive **94% accuracy** after being trained for **10 epochs** on the 
[**TrashNet**](https://www.kaggle.com/datasets/feyzazkefe/trashnet) dataset, which includes images of various waste categories such as cardboard, 
glass, metal, paper, plastic, and general trash. This high accuracy demonstrates the 
effectiveness of the Xception model in automating waste classification for improved waste management solutions.

# **Dataset**
The TrashNet dataset contains labeled images across several waste categories, including cardboard, glass, metal, paper, plastic, and general trash. <br>
[Dataset Link](https://www.kaggle.com/datasets/feyzazkefe/trashnet)
### *Dataset Samples*
![d72b22c2-d7b1-41c9-b0cc-28f1c5f01517](https://github.com/user-attachments/assets/a6655c6f-9438-424d-b80f-79de39490d4e)

# Evaluation
The project achieves an impressive **accuracy of 94%** using a CNN with the Xception architecture. Key metrics include **precision
(0.93–0.96), recall (0.91–0.99), and F1-scores (0.92–0.96)**, reflecting balanced performance. Further testing and optimization 
are underway to ensure robustness across diverse datasets and real-world scenarios.

### *Accuracy and Loss Graph*
The training and validation accuracy steadily improve, reaching above 94% with slight fluctuations in validation accuracy. The training and validation 
loss consistently decrease, indicating good model performance.

![7fc5bb7b-1d11-40ef-9439-303b33f8ed05](https://github.com/user-attachments/assets/c276b03d-3767-49ad-ac7d-8b6ede3c5a0d)

### *Confusion Matrix*
The confusion matrix shows strong performance for cardboard, glass, and paper, with high accuracy in these categories. Some misclassifications occur, notably for metal and trash, indicating areas for improvement.

![8ca23293-61ed-4ef1-8533-b157262338d5](https://github.com/user-attachments/assets/67856b6a-493b-42a6-9e32-2dc50d4bdd1b)

# **Predictions on Test Data**
![fae5fcbd-76f9-48fb-95d1-74714a78a78d](https://github.com/user-attachments/assets/2f5ccbd1-9ca2-4941-a99a-2705154bf758)
