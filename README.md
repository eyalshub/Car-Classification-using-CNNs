# Car Classification with Deep Learning CNNs 🚗

This repository contains a comprehensive deep learning project for classifying car images into 196 categories. The project emphasizes data exploration, model development, and experimental evaluation, showcasing a robust approach to image classification
This repository contains a comprehensive deep learning project for classifying car images into 196 categories. The project emphasizes data exploration, model development, and experimental evaluation, showcasing a robust approach to image classification.

## Project Structure

The project is organized into the following primary files:

### 1. Exploratory Data Analysis (`anlaize_car.ipynb`)
- Conducts a detailed analysis of the Stanford Cars dataset.
- Visualizes data distributions, class imbalances, and image characteristics.
- Prepares data for training, including preprocessing and augmentation.

### 2. Model Development (`modal_cnn.ipynb` and `Advanced models.ipynb`)
- Implements and fine-tunes multiple neural network architectures for car classification.
- Adapts pre-trained models by replacing the final layer to match the classification task.
- Utilizes techniques like L2 regularization and gradient clipping to stabilize training.
- Provides detailed metrics, including validation and test performance.

### 3. Experiments and Report (`Report.pdf`)
- Documents hyperparameter tuning and comparative analysis of different architectures.
- Evaluates model behavior across iterations, identifying performance bottlenecks.
- Offers insights into challenges faced during training and potential improvements.

### 4. Documentation (`README.md`)
- Overview of the project, dataset, and implementation details.

## Dataset

The project uses the **Stanford Cars Dataset**, which contains **16,185 images** of cars categorized into **196 classes**. Images are annotated with class labels, making it suitable for supervised learning tasks.

## Key Features

- Hands-on implementation and fine-tuning of deep learning architectures.
- Extensive use of regularization and training stabilization techniques.
- Comparative analysis of models to evaluate performance across multiple metrics.
- Exploration of computational limitations and creative solutions to improve results.

## How to Run

Clone the repository:

```bash
git clone https://github.com/NadavToledo1/Cars-Classification.git
cd car-classification
