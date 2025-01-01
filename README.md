# AI-Powered Expense Tracker with Gradio Interface

## Overview
This project leverages machine learning and data visualization techniques to analyze monthly expenses. Users can upload a CSV file containing their expense data, and the system provides detailed expense summaries, cost-saving suggestions, and visual insights in the form of bar and pie charts. The Gradio interface ensures a seamless user experience by allowing users to interact with the model without any programming knowledge.

---

## Key Features
- **Expense Categorization and Tracking**: Automatically categorizes expenses based on descriptions and amounts.
- **AI-Driven Predictions**: Predicts expense categories if not provided in the data.
- **Data Visualizations**: Generates bar charts for expense distribution and pie charts for percentage breakdowns.
- **Gradio Interface**: User-friendly interface for uploading CSV files and viewing real-time analysis.
- **Actionable Suggestions**: Provides tailored recommendations to optimize spending based on expense patterns.

---

## Setup and Usage

### Requirements
To run this project locally, ensure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- gradio
- Pillow

Install them via pip if not already available:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn gradio Pillow
```

### Steps to Run
1. Clone or download the repository.
2. Use provided csv files or Prepare a CSV file with the following columns:
   - **Description**: Short description of the expense.
   - **Amount**: Numeric value of the expense.
   - **Category**: (Optional) Category for each expense (e.g., Food, Travel, etc.).
3. Open the Python file in your preferred environment (Google Colab, Jupyter Notebook, or VS Code).
4. In the setup_interface() replace the file location with the file provided (expenses_.csv). Execute the script. A Gradio interface will launch in your default browser.
5. Upload your CSV file via the interface and view:
   - Expense summaries.
   - Bar and pie chart visualizations.
   - Personalized spending suggestions.

---

## Results
Upon processing your CSV file, the system provides:
- **Expense Summary**: Categorized total amounts.
- **Visual Insights**:
  - Bar chart showing distribution across categories.
  - Pie chart illustrating percentage breakdowns.
- **Recommendations**: Suggestions to optimize spending based on identified patterns.

---

## Technical Details
- **Machine Learning**: Utilizes an SVM model with a linear kernel for expense categorization.
- **Text Preprocessing**: Employs TF-IDF vectorization to process descriptions.
- **Custom Suggestions**: Analyzes category-wise spending and flags overspending based on thresholds.

---

## Contributing
We welcome contributions to enhance functionality or introduce new features!

### To Contribute:
1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Commit and push your changes.
4. Open a pull request with a detailed description of your modifications.

---

## License
This project is licensed under the MIT License. Feel free to use and modify the code for personal or commercial purposes.

---

## Contact
For questions, suggestions, or collaborations, reach out via:
- **GitHub**: [srivardhan8919](https://github.com/srivardhan8919)
- **LinkedIn**: [Srivardhan Nutenki](https://www.linkedin.com/in/srivardhan-nutenki-207b55249)
- **Email**: srivardhannani8919@gmail.com

