# Experiment: Convolutional Neural Network (CNN)

Implementation of a **Convolutional Neural Network (CNN)** on the **CIFAR-10** dataset.

---

## Dataset

**CIFAR-10 Dataset**

* **Rows:** 60,000 (50,000 training, 10,000 testing)
* **Image Size:** 32 × 32 pixels
* **Channels:** 3 (RGB)
* **Target Classes:** 10 (Object categories)

### Features

* RGB pixel intensities (ranging from 0 to 255)
* Images belonging to the following classes:

  * Airplane
  * Automobile
  * Bird
  * Cat
  * Deer
  * Dog
  * Frog
  * Horse
  * Ship
  * Truck

---

## **Important Note**

The default/latest version of **scikit-learn** in Google Colab is not compatible with **SciKeras**. To ensure compatibility with hyperparameter tuning using `RandomizedSearchCV`, the notebook installs a compatible lower version of **scikit-learn** before execution.

---

## How to Run

1. Open this repository on GitHub.
2. In the URL, replace:
   `github.com`
   with
   `githubtocolab.com`
3. Press **Enter** to open the notebook directly in **Google Colab**.
4. No need to upload any files, as `keras.datasets.cifar10` automatically downloads and loads the dataset.
5. Run all notebook cells sequentially.

---

## **Additional Task**

The notebook includes hyperparameter tuning of the CNN architecture using **SciKeras** and **RandomizedSearchCV** to identify an optimal combination of convolutional layers, filter sizes, dense layer configuration, activation functions, optimizers, learning rates, dropout rates, batch sizes, and training epochs for improved classification performance.
