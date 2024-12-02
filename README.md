# CLASSIFICATION OF BRAIN TUMOUR DETECTION USING CONVENTIONAL NEURAL NETWORKS(With 96% Accuracy)

### STEP 1: LOADING AND PREPROCESSING THE DATASET: 

1. The code reads the images from each category in the training directory, counts the number of images in each category, and creates a Pandas DataFrame (***train_df***) to store the image filenames, corresponding categories, and counts.

2. A bar plot is generated to visualize the distribution of tumor types in the training dataset.

![image](https://github.com/user-attachments/assets/73a6c904-fe20-4862-a860-ecd63335757e)

### STEP 2: VISUALIZING IMAGES FOR EACH TUMOR TYPES: 

Here, the code displays sample images for each tumor type using a grid of subplots.

![image](https://github.com/user-attachments/assets/588cce32-18af-452f-8897-d702eb24eaa7)

### STEP 3: VISUALIZATION THROUGH GRAPH:

![image](https://github.com/user-attachments/assets/9616ce73-a695-4496-ae25-5b3eee6ecbfc)

![image](https://github.com/user-attachments/assets/9ee0824e-df90-459c-b243-0faa984282e8)

### STEP 4: EVALUATION:

Found 5712 images belonging to 4 classes.
Found 1311 images belonging to 4 classes.
Epoch 1/50
178/178 [==============================] - 86s 418ms/step - loss: 0.9777 - accuracy: 0.5785 - val_loss: 1.0344 - val_accuracy: 0.6234
Epoch 2/50
178/178 [==============================] - 44s 244ms/step - loss: 0.7096 - accuracy: 0.7176 - val_loss: 0.8210 - val_accuracy: 0.6836
Epoch 3/50
178/178 [==============================] - 44s 247ms/step - loss: 0.6279 - accuracy: 0.7523 - val_loss: 0.7135 - val_accuracy: 0.7172
Epoch 4/50
178/178 [==============================] - 44s 247ms/step - loss: 0.5469 - accuracy: 0.7859 - val_loss: 0.7600 - val_accuracy: 0.7023
Epoch 5/50
178/178 [==============================] - 47s 261ms/step - loss: 0.4961 - accuracy: 0.8093 - val_loss: 0.6723 - val_accuracy: 0.7656
Epoch 6/50
178/178 [==============================] - 47s 264ms/step - loss: 0.4224 - accuracy: 0.8368 - val_loss: 0.5063 - val_accuracy: 0.7930
Epoch 7/50
178/178 [==============================] - 46s 258ms/step - loss: 0.3627 - accuracy: 0.8629 - val_loss: 0.3800 - val_accuracy: 0.8445
Epoch 8/50
178/178 [==============================] - 45s 254ms/step - loss: 0.3228 - accuracy: 0.8799 - val_loss: 0.2933 - val_accuracy: 0.8852
Epoch 9/50
178/178 [==============================] - 46s 259ms/step - loss: 0.2944 - accuracy: 0.8903 - val_loss: 0.3837 - val_accuracy: 0.8453
Epoch 10/50
178/178 [==============================] - 46s 260ms/step - loss: 0.2766 - accuracy: 0.8982 - val_loss: 0.2584 - val_accuracy: 0.8953
Epoch 11/50
178/178 [==============================] - 44s 248ms/step - loss: 0.2615 - accuracy: 0.9058 - val_loss: 0.3563 - val_accuracy: 0.8680
Epoch 12/50
178/178 [==============================] - 47s 263ms/step - loss: 0.2478 - accuracy: 0.9104 - val_loss: 0.2476 - val_accuracy: 0.9156
Epoch 13/50
...
Epoch 49/50
178/178 [==============================] - 47s 264ms/step - loss: 0.0870 - accuracy: 0.9710 - val_loss: 0.0858 - val_accuracy: 0.9695
Epoch 50/50
178/178 [==============================] - 47s 265ms/step - loss: 0.0921 - accuracy: 0.9678 - val_loss: 0.1343 - val_accuracy: 0.9578
Output is truncated. View as a scrollable element or open in a text editor. Adjust cell output settings...


40/40 [==============================] - 3s 85ms/step - loss: 0.1343 - accuracy: 0.9578
Test Loss: 0.13427262008190155
Test Accuracy: 0.957812488079071
41/41 [==============================] - 4s 84ms/step

### STEP 5: CONFUSION MATRIX AND EXPLANATION:

![image](https://github.com/user-attachments/assets/22fb6f3c-1070-4642-8231-6024ae5f18bb)

### Calculate precision, recall, and F1-score from the confusion matrix:

Class: glioma
Precision: 0.992831541218638
Recall: 0.9233333333333333
F1-Score: 0.9568221070811743

Class: meningioma
Precision: 0.9395973154362416
Recall: 0.9150326797385621
F1-Score: 0.9271523178807947

Class: notumor
Precision: 0.9484777517564403
Recall: 1.0
F1-Score: 0.9735576923076924

Class: pituitary
Precision: 0.9576547231270358
Recall: 0.98
F1-Score: 0.9686985172981878

![image](https://github.com/user-attachments/assets/32f022ea-aefb-4ed9-adeb-7fd2938b6fd5)
