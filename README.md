# Email Spam Classification

This repository contains a project aimed at classifying emails as spam or non-spam using machine learning techniques. The project includes data preprocessing, feature extraction, model training, and evaluation.

## Table of Contents

- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this project is `email.csv`, which contains email data labeled as spam or non-spam. Each entry includes features extracted from the email content and metadata.

## Dependencies

To run the code in this repository, ensure you have the following Python packages installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- nltk
- jupyter

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk jupyter
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/UdayMalviya/email_spam_classification.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd email_spam_classification
   ```

3. **Open the Jupyter Notebook:**

   ```bash
   jupyter notebook email.ipynb
   ```

4. **Run the cells in `email.ipynb` to preprocess the data, train the model, and evaluate its performance.**

## Project Structure

- `email.csv`: The dataset containing email data with labels.
- `email.ipynb`: Jupyter Notebook with code for data preprocessing, model training, and evaluation.

## Results

The performance of the spam classification model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Detailed results and visualizations are available in the `email.ipynb` notebook.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details. 
