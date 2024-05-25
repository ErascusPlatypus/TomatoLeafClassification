# TomatoLeafClassification

## Project Description

TomatoLeafClassification is a machine learning project that analyzes images of tomato plant leaves to classify them into one of ten categories. The project utilizes a dataset from Kaggle and employs a convolutional neural network (CNN) to achieve an impressive validation accuracy of 90.25%.

## Dataset

The dataset used in this project is sourced from Kaggle ( https://www.kaggle.com/datasets/arjuntejaswi/plant-village ) and contains labeled images of tomato leaves across ten different classes:

1. Bacterial Spots
2. Early Blight
3. Late Blight
4. Leaf Mold
5. Septoria Leaf Spot
6. Spider Mites
7. Target Spot
8. Yellow Leaf Curl Virus
9. Mosaic Virus
10. Healthy

## Uses and Applications

This project has significant implications in the field of agriculture and plant pathology. Some of the key applications include:

- **Early Detection of Diseases**: By identifying diseases at an early stage, farmers can take appropriate measures to prevent the spread and mitigate the impact on crop yield.
- **Automated Monitoring**: This model can be integrated into automated systems to continuously monitor crops and detect diseases in real-time, reducing the need for manual inspections.
- **Resource Optimization**: Early and accurate detection of diseases can help in optimizing the use of pesticides and other resources, promoting sustainable farming practices.
- **Research and Development**: Researchers can use the classification results to study disease patterns and develop better treatment methods or resistant plant varieties.

## Model Performance

The neural network developed in this project has achieved a validation accuracy of 90.25%. This high level of accuracy demonstrates the model's effectiveness in correctly classifying tomato leaf diseases, making it a reliable tool for practical applications in agriculture.

## Getting Started

### Prerequisites

- Python 3.10.8
- TensorFlow
- Keras
- NumPy
- Matplotlib

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/TomatoLeafClassification.git
cd TomatoLeafClassification
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### Usage

1. **Prepare the Dataset**: Download the dataset from Kaggle and place it in the appropriate directory.
2. **Train the Model**: Run the training script to train the neural network on the dataset.

```bash
python train.py
```

3. **Evaluate the Model**: After training, evaluate the model's performance using the test set.

```bash
python evaluate.py
```

4. **Predict**: Use the trained model to classify new images of tomato leaves.

```bash
python predict.py --image_path path_to_image
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Kaggle for providing the dataset.
- TensorFlow and Keras for the machine learning framework.
- The open-source community for the numerous tools and libraries that made this project possible.

---

Feel free to reach out with any questions or feedback. Happy coding!
