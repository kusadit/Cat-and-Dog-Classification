# Cat vs Dog Image Classifier using CNN

This project uses a Convolutional Neural Network (CNN) to classify images of cats and dogs. It’s built with TensorFlow and OpenCV, and trained on real pet images from a Kaggle dataset. A simple, beginner-friendly implementation of deep learning for image classification.

---

## Dataset

The dataset used is from Kaggle:  
**[Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)**

After downloading and extracting, make sure the folder structure looks like this:

```
PetImages/
├── Cat/
└── Dog/
```

Images are loaded from these folders and split into training and testing sets using `train_test_split`.

---

## Features

- Image classification using a custom CNN
- Accuracy of over 82% on test data
- Predicts on new images using a simple function
- Clean image preprocessing with OpenCV
- Fully written in Python using Jupyter Notebook

---

## Dependencies

Install required packages using:

```bash
pip install tensorflow opencv-python numpy tqdm scikit-learn matplotlib
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/cat-dog-classifier.git
cd cat-dog-classifier
```

2. Make sure the dataset is placed at:

```text
D:/cat_dog/PetImages/
```

Or update the `DATA_PATH` variable in the notebook to match your path.

3. Open the `cat_dog_classifier.ipynb` file in Jupyter Notebook and run all cells.

---

## Predict on Custom Images

You can use this function to test your own images:

```python
predict_image(r"D:\cat_dog\testing\cat3.jpg")
```

Make sure the image path is correct and the image format is supported (JPG or PNG).

---

## License

This project is licensed under the MIT License.  
See the `LICENSE` file for full details.

---
