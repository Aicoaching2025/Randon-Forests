# Random Forest Income Classification & Feature Engineering

![Python Version](https://img.shields.io/badge/Python-3.8-blue)
![License MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## Overview

This project demonstrates how to classify income levels using a Random Forest classifier built on a fictional dataset. The analysis is broken down into several key steps:

- **Data Investigation:** The script begins by checking the income distribution and cleaning up extra spaces in categorical columns.
- **Baseline Model:** A Random Forest model is built and evaluated to serve as a baseline for income prediction.
- **Tuning:** The model is tuned by varying the `max_depth` parameter to find the best performing depth based on test accuracy.
- **Feature Importance:** Once tuned, the model’s most influential features are identified.
- **Feature Engineering:** A new feature (`education_bin`) is created to group education levels into three categories, and the model is re-tuned with the extended feature set to see if performance improves.

---

## Project Structure

```
project/
├── data/                        # (Optional) Data files can be placed here
├── scripts/
│   ├── script.py                # Main project script
│   ├── script_1.py              # Data Investigation script
│   ├── script_1_solution.py     # Solution for Data Investigation
│   ├── script_2.py              # Model tuning and feature engineering script
│   ├── script_2_solution.py     # Solution for model tuning
├── README.md                    # This file
└── requirements.txt             # Python dependencies
```

---

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

Run the complete project with:

```bash
python scripts/script.py
```

Or run individual parts of the project:

- **Data Investigation:**  
  ```bash
  python scripts/script_1.py
  ```
- **Model Tuning & Feature Engineering:**  
  ```bash
  python scripts/script_2.py
  ```

---

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions, improvements, or bug fixes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Happy coding and exploring the power of machine learning and automation! 🚀
