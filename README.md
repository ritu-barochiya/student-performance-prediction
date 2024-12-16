# Student Performance Prediction System

This project is a comprehensive analysis and machine learning system to classify and predict student performance levels (High, Medium, Low) based on various academic and behavioral parameters. It integrates data preprocessing, visualization, and machine learning to provide insights and predictive capabilities.

---

## Features

- **Interactive Visualizations**: Generates insightful graphs for analyzing marks class distributions based on parameters like semester, gender, nationality, and attendance.
- **Machine Learning Models**: Implements five models for classification:
  - Decision Tree Classifier
  - Random Forest Classifier
  - Logistic Regression
  - Perceptron
  - Neural Network (MLP Classifier)
- **Real-Time Predictions**: Allows user input for real-time prediction of student performance.
- **Data Preprocessing**: Handles categorical encoding, feature reduction, and data shuffling for machine learning readiness.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `seaborn` and `matplotlib` for data visualization
  - `scikit-learn` for machine learning algorithms
  - `numpy` for numerical computations
  - `time` for simulation of processing delays

---

## Dataset

The dataset (`AI-Data.csv`) contains information on students' academic and behavioral data, including:
- Gender
- Grade
- Attendance
- Participation metrics (raised hands, discussions, etc.)
- Marks classification (High, Medium, Low)

### Dataset Preprocessing
- **Dropped Columns**: Irrelevant or redundant features such as `Gender`, `StageID`, `GradeID`, `Nationality`, etc.
- **Categorical Encoding**: Converted non-numeric data to numeric format using label encoding.
- **Train-Test Split**: 70% training and 30% testing split.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ritu-barochiya/student-performance-prediction.git
   ```
2. Install required Python libraries:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn numpy
   ```
3. Place the `AI-Data.csv` file in the project directory.
4. Run the script:
   ```bash
   python Project.py
   ```
5. Follow the interactive menu to:
   - View graphs based on various parameters
   - Train and evaluate machine learning models
   - Test predictions with custom input

---

## Machine Learning Models and Results

| Model                  | Accuracy (%) |
|------------------------|--------------|
| Decision Tree          | ~78          |
| Random Forest          | ~85          |
| Logistic Regression    | ~82          |
| Perceptron             | ~80          |
| Neural Network (MLP)   | ~85          |

---

## Sample Visualizations

### Marks Class Count Graph
![Class Count Graph](images/class_count_graph.png)

### Marks Class Semester-wise Graph
![Semester-wise Graph](images/semester_graph.png)

---

## Key Functions

1. **Visualizations**:
   - `Marks Class Count Graph`
   - `Marks Class Semester-wise Graph`
   - `Marks Class Gender-wise Graph`
   - `Marks Class Attendance-wise Graph`

2. **Model Evaluation**:
   - Train and test using various machine learning models.
   - Print classification reports and accuracy scores.

3. **Real-Time Predictions**:
   - Input custom student data to predict performance levels.

---

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any queries, feel free to reach out:
- **Email**: ritu.barochiya2610@gamil.com
- **GitHub**: [ritu-barochiya](https://github.com/ritu-barochiya)
