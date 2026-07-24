# Experiment: Multi Layer Perceptron

Implementation of a **Multi Layer Perceptron** on the Fashion-MNIST dataset.

---

## Dataset

**Fashion MNIST Dataset**

* **Rows:** 70,000 (60,000 training, 10,000 testing)
* **Features:** 784 (Flattened 28x28 images)
* **Target Classes:** 10 (Clothing categories)

### Features

* Grayscale pixel intensities (ranging from 0 to 255)

---

## **Important Note**
The default/latest version of sci-kit learn in google colab is not compatible with scikeras. To deal with this, a lower version of sci-kit learn is used in the notebook.


## How to Run

1. Open this repository on GitHub.
2. In the URL, replace:
`github.com`
with
`githubtocolab.com`
3. Press **Enter** to open the notebook directly in **Google Colab**.
4. No need to upload any files as `keras.datasets.fashion_mnist` loads the file by itself.
5. Run all cells in order.

## **Additional Task**

The final cell of the notebook depicts how a multilayer perceptron is capable of solving the XOR problem.
