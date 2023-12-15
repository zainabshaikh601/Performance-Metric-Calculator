# Performance-Metric-Calculator

## Overview

This Streamlit app calculates model performance metrics given the actual and predicted values. It supports uploading a CSV file, encoding categorical data, and provides metrics such as accuracy, balanced accuracy, precision, recall, MCC, F1 score, and Cohen's Kappa.

## Usage

### Input Panel

- Upload your input CSV file using the sidebar.
- Select the desired performance metrics from the available options.

### Example CSV File

An [example CSV file](https://raw.githubusercontent.com/dataprofessor/model_performance_app/main/Y_example.csv) is provided for testing.

### Performance Metrics

- **Accuracy**: Overall accuracy of the model.
- **Balanced Accuracy**: Accuracy that considers imbalanced datasets.
- **Precision**: Precision score weighted by the number of instances for each label.
- **Recall**: Recall score weighted by the number of instances for each label.
- **MCC (Matthews Correlation Coefficient)**: Measures the quality of binary classifications.
- **F1 Score**: Harmonic mean of precision and recall.
- **Cohen's Kappa**: Measures the agreement between two raters.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   streamlit run your_app.py
   ```

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
