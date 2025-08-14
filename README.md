**Sign Language Classification using Deep Learning**

This code contains a comprehensive implementation of a deep learning solution to help Margot annotate sign language images for creating a sign-to-text tool for deaf people.

**Overview**

The implementation demonstrates advanced computer vision techniques for automatic sign language annotation with:
 * Transfer learning using pre-trained ResNet architecture
 * Advanced data augmentation and image enhancement techniques
 * Test-time augmentation for improved prediction accuracy
 * Multi-dataset training combining old annotated data with example data
 * Alphabet letter mapping for sign language recognition
 * GPU acceleration support for faster training

**Prerequisites**

Install the required Python libraries:

```bash
pip install torch torchvision opencv-python pillow numpy matplotlib pandas seaborn scikit-learn
```

**File Structure**

* `sign_language_classification.ipynb` - Complete implementation with detailed explanations
* `old_annotated.pth` - Pre-annotated training dataset with hand signs
* `todo.pth` - Images to be annotated for Margot
* `todo_example.pth` - Optional example annotations to enhance training
* `predictions.csv` - Final predictions in competition format
* `todo_annotated.pth` - Fully annotated TODO dataset
* `sign_language_model.pth` - Trained model weights

**Key Components**

1. **Data Loading and Preprocessing**
2. **Image Enhancement Pipeline**
3. **Data Augmentation Strategy**
4. **SignLanguageClassifier Model**
5. **Training Pipeline**
6. **Test-Time Augmentation (TTA)**
7. **Alphabet Mapping System**
**Acknowledgment**

 Thanks to Prof. Dr. Magda Gregorova for providing insightful lectures on Deep Learning and giving us these interesting and fun assignments.