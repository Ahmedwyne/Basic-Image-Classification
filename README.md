# 👕 Basic Image Exploration with Fashion MNIST

This project demonstrates how to **load, inspect, and visualize** the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset using TensorFlow and Matplotlib. It's ideal for beginners learning about image data, preprocessing, and the first steps toward image classification using deep learning.

---

## 📌 Project Overview

- 🔹 Loads the Fashion MNIST dataset using `tf.keras.datasets`
- 🔹 Prints dataset shapes and label structure
- 🔹 Maps numeric labels to readable class names
- 🔹 Visualizes sample image data using `matplotlib`
- 🔹 Lays the foundation for building an image classifier

---

## 🧠 About the Dataset

**Fashion MNIST** is a dataset of **28x28 grayscale images** of 70,000 fashion items in 10 categories. It is often used as a drop-in replacement for the classic MNIST dataset.

- **Training images**: 60,000  
- **Test images**: 10,000  
- **Image size**: 28 x 28 pixels  
- **Color mode**: Grayscale

### Class Labels

| Label | Class        |
|-------|--------------|
| 0     | T-shirt/top  |
| 1     | Trouser      |
| 2     | Pullover     |
| 3     | Dress        |
| 4     | Coat         |
| 5     | Sandal       |
| 6     | Shirt        |
| 7     | Sneaker      |
| 8     | Bag          |
| 9     | Ankle boot   |

---

## 🛠️ Tools & Libraries

This project uses the following libraries:

- [TensorFlow](https://www.tensorflow.org/) for loading the dataset
- [Matplotlib](https://matplotlib.org/) for plotting images
- [NumPy](https://numpy.org/) for numerical operations

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ahmedwyne/Basic-Image-Classification.git
cd Basic-Image-Classification
````

### 2️⃣ Install Dependencies

Make sure Python 3.7+ is installed, then run:

```bash
pip install tensorflow matplotlib numpy
```

### 3️⃣ Run the Script

You can run the script directly in any Python environment:

```bash
python visualize_fashion_mnist.py
```

Or use a Jupyter Notebook to interactively view outputs.

---

## 🔍 Sample Output

The code displays a training image and prints its corresponding label.

<img width="840" height="840" alt="image" src="https://github.com/user-attachments/assets/cb27ce11-5a3a-40ea-b146-44bf731faa33" />

```python
Label: Ankle boot
```

![fashion\_mnist](https://github.com/zalandoresearch/fashion-mnist/raw/master/doc/img/fashion-mnist-sprite.png)

---

## 📚 Learning Goals

This project helps you learn:

* How image data is stored in arrays
* How to load and preprocess datasets using `tf.keras.datasets`
* How to visualize 2D image data with `matplotlib`
* How to interpret label data and map it to human-readable class names

---

## 🧩 What’s Next?

Once you're comfortable with the basics, you can extend this project to:

* Build a neural network classifier with TensorFlow/Keras
* Use convolutional neural networks (CNNs) for better accuracy
* Apply data normalization and augmentation
* Evaluate model performance on the test set

---

## 🤝 Contributions

Contributions are welcome! You can:

* Fix bugs or typos
* Add a classification model
* Improve visualization (e.g., grid of images)
* Create a Jupyter notebook version

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and share it!

---

## 🙋‍♂️ Acknowledgments

* [Fashion MNIST Dataset - Zalando Research](https://github.com/zalandoresearch/fashion-mnist)
* [TensorFlow Datasets Documentation](https://www.tensorflow.org/datasets/overview)

---

Happy Learning! 🚀

