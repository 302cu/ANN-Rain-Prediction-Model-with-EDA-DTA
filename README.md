# ANN-Rain-Prediction-Model-with-EDA-DTA
## Project Overview
This project aims to predict whether it will rain tomorrow by training a machine learning model on historical weather data. The model is built using TensorFlow and Keras, with a focus on achieving high accuracy and understanding the key factors that influence rainfall.

## Features
- **Data Preprocessing**: Includes handling missing values, feature engineering, and normalization.
- **Model Training**: Utilizes a deep neural network with layers configured for optimal performance.
- **Evaluation**: Assesses model accuracy on a held-out test set.
- **Callbacks**: Implements EarlyStopping and ReduceLROnPlateau for efficient training.

\`\`\`

## Getting Started
To get a local copy up and running follow these simple steps:

### Prerequisites
- Python 3.8 or higher
- pip

### Installation
1. Clone the repo
   \`\`\`sh
   git clone https://github.com/your_username_/Project-Name.git
   \`\`\`
2. Install Python packages
   \`\`\`sh
   pip install -r requirements.txt
   \`\`\`

### Usage
To start the model training process, navigate to the project directory and run the Jupyter notebooks:
\`\`\`sh
jupyter notebook
\`\`\`
Navigate to \`notebooks/\` and open the model training notebook.

## Model
The model consists of several densely connected layers with ELU activation and dropout to prevent overfitting. It has been trained to predict the likelihood of rain on the following day based on various weather-related inputs.

## Results
Our model achieved a test accuracy of approximately 86.71%, demonstrating its effectiveness in predicting rainfall with high reliability.

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (\`git checkout -b feature/AmazingFeature\`)
3. Commit your Changes (\`git commit -m 'Add some AmazingFeature'\`)
4. Push to the Branch (\`git push origin feature/AmazingFeature\`)
5. Open a Pull Request

## License
Distributed under the MIT License. See \`LICENSE\` for more information.

## Contact
Abdullah Aldosari- [LinkedIn Profile](https://www.linkedin.com/in/abdullah-aldosari-058211239?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) - reff302@gmail.com

Project Link: [ANN Rain Prediction Model with EDA & DTA](https://github.com/302cu/ANN-Rain-Prediction-Model-with-EDA-DTA)

## Acknowledgements
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [NumPy](http://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
EOL
