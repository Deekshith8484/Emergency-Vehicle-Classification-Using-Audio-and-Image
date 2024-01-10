# Emergency Vehicle Classification Using Audio and Image

For Emergency Vehicle Classification using both audio and image data, the objective is to differentiate emergency vehicles (such as ambulances, fire trucks, and police cars) from other vehicles. This classification task utilizes both audio signals (siren sounds) and image data (visual cues) to identify emergency vehicles. The goal is to address traffic delay fatalities by promptly recognizing emergency vehicles amidst traffic.

### Approach:

1. **Data Collection:**
   - Gather audio samples of emergency vehicle sirens and corresponding image data of these vehicles.
     
![3](https://github.com/Deekshith8484/Vechile-Classification/assets/102028936/4a75bf8f-4e14-45b3-bf47-a5ab2c70d174)
![381](https://github.com/Deekshith8484/Vechile-Classification/assets/102028936/92baf15b-310c-4097-b81f-fe3cf5b26d95)


2. **Feature Extraction:**
   - Extract audio features from sirens (e.g., frequency, intensity) using signal processing techniques.
   - Extract visual features from vehicle images using computer vision methods (e.g., CNNs for feature extraction).

3. **Model Fusion:**
   - Develop separate models for audio and image data (e.g., Convolutional Neural Networks (CNN) for images, audio classification models for audio signals).
   - Combine these models or their respective predictions using ensemble techniques or fusion models.

4. **Multimodal Fusion:**
   - Combine features from audio and image models into a single model for joint classification.
   - Utilize fusion techniques (e.g., late fusion, early fusion) to merge audio and image features effectively.

5. **Training and Evaluation:**
   - Train the multimodal classification model on combined audio and image data.
   - Validate the model's performance using validation datasets and cross-validation techniques.
   - Evaluate the model's accuracy, precision, recall, and F1-score for both emergency and non-emergency vehicle classification.

6. **Fine-tuning and Optimization:**
   - Optimize the model parameters and fusion strategies to improve classification accuracy.
   - Handle imbalanced data, address overfitting, and fine-tune hyperparameters for better performance.

7. **Deployment and Testing:**
   - Deploy the trained model for real-time inference and testing.
   - Test the model's performance on new and unseen audio-visual data of emergency and non-emergency vehicles.

### Importance:
- Crucial for traffic management and emergency services, reducing fatalities by enabling timely emergency vehicle passage through traffic.
- Assists in the development of smarter transportation systems and contributes to the safety and efficiency of autonomous vehicles.

This multimodal approach combining audio and image data aims to enhance the accuracy and robustness of emergency vehicle classification systems, aiding in prompt traffic management and emergency response.



# Data Description
 - train.zip: contains 2 csvs and 1 folder containing image data
 - train.csv – [‘image_names’, ‘emergency_or_not’] contains the image name and correct class for 1646 (70%) train images
 - images – contains 2352 images for both train and test sets
 - test.csv: [‘image_names’] contains just the image names for the 706 (30%) test images
# DataSet:
 - for image Link:https://www.kaggle.com/datasets/abhisheksinghblr/emergency-vehicles-identification/data
