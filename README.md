# White Blood Cell Classification

This project focuses on classifying white blood cells (WBCs) from images using a Convolutional Neural Network (CNN). The model is designed to accurately identify different types of WBCs, which is a crucial task in medical diagnostics.

## 🚀 Features

- **Image Preprocessing**: The model preprocesses images by resizing and normalizing them to ensure consistency and improve performance.
- **Data Augmentation**: To enhance the dataset and prevent overfitting, the project uses data augmentation techniques such as rotation and flipping.
- **CNN Model**: A robust CNN architecture is implemented to learn and classify the different types of WBCs.
- **Evaluation**: The model's performance is evaluated using various metrics, including accuracy and a confusion matrix.

## 🛠️ Technologies Used

- **Python**: The primary programming language for this project.
- **TensorFlow/Keras**: Used for building and training the deep learning model.
- **NumPy**: For numerical operations and data manipulation.
- **OpenCV**: For image processing tasks.
- **Matplotlib**: For data visualization and plotting.
- **Scikit-learn**: For model evaluation and metrics.

## 📊 Dataset

The project uses a dataset of white blood cell images, which is split into training and testing sets. The dataset contains images of the following types of WBCs:

- Eosinophil
- Lymphocyte
- Monocyte
- Neutrophil

## ⚙️ Installation and Usage

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/White-Blood-Cell-Classification.git
   ```

2. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Open the `code.ipynb` notebook in a Jupyter environment to see the code and run the model.

## 📈 Results

The model achieves a high accuracy in classifying the different types of white blood cells. The results are visualized using a confusion matrix to show the performance for each class.
