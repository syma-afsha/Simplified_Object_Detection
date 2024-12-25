### Simplified_Object_Detection

This Assignment is done in the Deep Network Development Lab. 

Step 1 : Dataset Creation:

Select at least ANY 3 objects. 
Remove the background from the chosen objects, ensuring only the object remains.
Collect background images from different locations/scenarios.
Generate a synthetic dataset by randomly inserting one object into a background image at a random location.
Save the coordinates of the inserted objects to create bounding boxes.
Format the bounding boxes appropriately for training (e.g., [x,y,w,h], or YOLO format).
Implement a PyTorch Dataset class to manage the dataset.
Split the dataset into training, validation, and test sets.

Step 2: Model Development:
Design a Convolutional Neural Network (CNN) based architecture for object detection.
Include a backbone for feature extraction and two output branches:
One for class probabilities (equal to the number of chosen objects).
Another for bounding box regression (of size 4 for coordinates).
Experiment with different layers and hyperparameters, incorporating regularization techniques.
Define an optimizer, loss function, and number of epochs for training.
Optimize both classification and bounding box regression losses.
Choose  3 evaluation metrics for your model (Precision, Recall, mAP).
Visualize performance metrics and model predictions.

Step 3: Existing Model Comparison:
Load an existing object detection model (e.g., YOLO).
Fine-tune the model on the synthetic dataset created earlier.
Monitor and visualize losses and metrics during fine-tuning.
Compare the performance of the custom model and the fine-tuned existing model.
Visualize predictions from both models and justify any observed differences.
Provide insights on potential improvements for the custom model.

### Comparison between Simplified Object Detection MOdel and YOLOV11
![Comparison](https://github.com/syma-afsha/Simplified_Object_Detection/blob/main/00158_comparison.png)
![Comparison](https://github.com/syma-afsha/Simplified_Object_Detection/blob/main/00188_comparison.png)
![Comparison](https://github.com/syma-afsha/Simplified_Object_Detection/blob/main/00184_comparison.png)
