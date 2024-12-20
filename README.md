# End to End Student Performance ML APP

## Project Overview
This project focuses on predicting student Performance in Maths using various Regression models. With an accuracy of 89%,Ridge regression performed well among other machine learning algorithms. The project is designed in a well manner using modular coding and an interactive userface has been created using Flask framework.

## Table of contents

- [Analysis](#analysis)
- [Dataset](#dataset)
- [Model Building](#model_Building)
- [Installation](#installation)
- [Interface](#interface)
- [Usage](#usage)
- [Technologies Used](#technologies_used)
- [Project Structure](#project_structure)
- [Future Enhancements](#future_enhancements)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Analysis
Performed various analysis with the help of scikit learn and seaborn libraries.

![Screenshot 2024-12-13 102821](https://github.com/user-attachments/assets/5e86073b-337e-4cd2-bba1-290ed9ae7e3a)

![Screenshot 2024-12-13 103138](https://github.com/user-attachments/assets/2433fa89-689e-4681-b116-d57a8f5f5a3e)

![Screenshot 2024-12-13 103305](https://github.com/user-attachments/assets/6504146c-1157-4235-afb9-301e9a2f6948)

![Screenshot 2024-12-13 103602](https://github.com/user-attachments/assets/0356f94b-87ad-479e-b62e-f251410a01eb)
  
## Dataset
The dataset used in this analysis include information on:
- Student Demographics (age,gender, parental education)
- Academic performance (math,reading and writing scores)
- Study habits (test preparation, study time )

## Model Building
**Data Pipelines**
- **Data Ingestion**: Automated collection and preparation of raw data.
- **Data Transformation**: Data cleaning and scaling for good prediction. Used One Hot Encoding and Label encoding for converting categorical values to numerical.
- **Model Training**: Experimented with multiple algorithms to acheive an 89% accuracy using Ridge regression.

**Prediction Pipeline**
- Built a system to handle real-time predictions based on user inputs like study time, attendance and previous scores.

**User Interface**
- With the help of Flask framework, built a user interface for the model.

## Installation
**Clone the repository**

<pre>
  <code>
git clone https://github.com/Althaf777/mlproject.git
cd your -repo-folder
  </code>
  <button onclick="navigator.clipboard.writeText(`# Python Example\ndef greet(name):\n    return f\"Hello, {name}!\"\nprint(greet(\"World\"))`)"></button>
</pre>

**Setup environment**
<pre>
  <code>
pip install -r requirements.txt 
  </code>
</pre>

**Run the app locally**
<pre>
  <code>
python app.py
  </code>
</pre>

## Interface

![Screenshot 2024-12-12 131852](https://github.com/user-attachments/assets/6952c7e2-274c-4fbb-8b2d-2d388ac412ba)

## Usage
1. Load the dataset through the provided interface.
2. View exploratory data analysis visualizations.
3. Enter input parameters for predictions.
4. Obtain predicted math scores and performance insights.

## Technologies Used
- **Ridge Regression:** For high-accuracy predictions.
- **Flask:** To develop the interactive web interface.
- **Matplotlib & Seaborn:** For detailed data visualization.
- **Pandas & NumPy:** For data manipulation and preprocessing.
- **Scikit-learn:** For model development and evaluation.
  
## Project Structure
```plaintext
  📂 Project Root
├── 📁 data                  # Dataset files 
├── 📁 models                # Trained model files
├── 📁 src                   # Source code
│   ├── data_pipeline.py     # Data ingestion and transformation
│   ├── train.py             # Model training scripts
│   └── predict.py           # Prediction pipeline
├── 📄 app.py
├── 📄 requirements.txt      # Python dependencies
└── 📄  README.md            # Project documentation
```

## Future Enhancements
- Extend prediction to other subjects (e.g., Science, Reading).
- Incorporate deep learning models for enhanced performance.
- Add support for real-time data inputs from school systems.


## Contributing
Contributions are welcome!

## Acknowledgments
Special thanks to the contributors of open-source libraries such as Scikit-learn, Flask, Matplotlib, and Seaborn for enabling the development of this project.





  
