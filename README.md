# ResearchProject
# Tuberculosis Detection Using Chest X-ray Images

## Features

### Dataset

- **Source**: Kaggle dataset of tuberculosis chest X-rays.
- **Structure**: Contains labeled images for TB and non-TB cases.

### Models Used

- **Custom CNN**
- **VGG16**
- **MobileNet**
- **EfficientNetB0**

### Optimizers Compared

- **Adam**
- **RMSprop** (Best performance with MobileNet)
- **SGD**
- **Adagrad**

### Key Metrics

- F1-score
- ROC-AUC score
- Confusion matrices
- Class-wise accuracy
- Training and validation loss/accuracy graphs

## Project Workflow

1. **Data Preparation**

   - Downloaded dataset from Kaggle.
   - Preprocessed images using OpenCV and PIL libraries.
   - Split dataset into training, validation, and test sets.

2. **Model Training**

   - Used TensorFlow and Keras frameworks.
   - Applied data augmentation for better generalization.
   - Trained models with different optimizers.

3. **Evaluation**

   - Evaluated performance using metrics like F1-score and ROC-AUC.
   - Visualized results with training history, confusion matrices, and ROC curves.

4. **Results**

   - MobileNet with RMSprop achieved the best results.
   - High F1-score of 0.98 and ROC-AUC of 1.00.

## Requirements

- Python 3.7+
- TensorFlow
- Keras
- OpenCV
- Scikit-learn
- Matplotlib
- Seaborn
- PIL

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Mehwishwajid/ResearchProject
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook CodeFile.ipynb
   ```

4. Upload your Kaggle API key (`kaggle.json`) to download the dataset.

## Results and Visualizations

- Training history plots: Loss and accuracy over epochs.
- Confusion matrices: Detailed class-wise performance.
- ROC curves: Demonstrates the model’s classification power.

## Conclusion

This project demonstrates the potential of deep learning for automated TB detection using chest X-ray images. MobileNet with RMSprop optimizer is particularly effective, making it a viable solution for low-resource clinical settings.

## Future Work

- Explore additional deep learning architectures.
- Address class imbalance in datasets.
- Test on larger and more diverse datasets.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For questions or feedback, please reach out to Mehwishwajid94@gmail.com


