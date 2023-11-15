<h1 align="center">Advanced Decision Tree Optimization in Spark ML for Breast Cancer Analysis</h1>

## Overview
This README documents the project "Advanced Decision Tree Optimization in Spark ML for Breast Cancer Analysis" by Sai Sanwariya Narayan. The project focuses on optimizing decision trees using Spark ML to analyze breast cancer data. Key components include data loading and setup, feature transformation, decision tree learning, evaluation, visualization, and hyperparameter tuning.

## Program Functionality
1. **Data Setup**: Utilizes Python files and Spark ML libraries to load and prepare the data.
   - Python files: `decision_tree_parser.py`, `decision_tree_plot.py`, and `tree_template.jinja2`.
   - Data schema defined for breast cancer data with Spark DataFrame operations.
   - Data filtering and transformation using Spark SQL functions.

2. **Feature Transformation**:
   - Implementation of DataFrame transformations to prepare features for the decision tree model.

3. **Decision Tree Learning and Evaluation**:
   - Configures and trains Decision Tree models with varying hyperparameters.
   - Evaluation metrics (F1 score) are calculated to assess model performance.
   - Includes a detailed process for both local mode and cluster mode operations.

4. **Decision Tree Visualization**:
   - Scripts to parse and visualize decision trees.

5. **Automated Hyperparameter Tuning**:
   - Extensive tuning of hyperparameters (`maxDepth` and `minInstancesPerNode`) to optimize model performance.
   - Results are documented and best models are identified.

6. **Revised Hyperparameter Tuning**:
   - An extended range of hyperparameters is explored to further refine the model.

## Notes
- The README is intended for users familiar with Spark ML and Python programming.
- Ensure Spark is properly installed and configured before executing the code.
- Adjust file paths in the script according to your local or server environment.

---

# Academic Integrity Statement

Please note that all work included in this project is the original work of the author, and any external sources or references have been properly cited and credited. It is strictly prohibited to copy, reproduce, or use any part of this work without permission from the author.

If you choose to use any part of this work as a reference or resource, you are responsible for ensuring that you do not plagiarize or violate any academic integrity policies or guidelines. The author of this work cannot be held liable for any legal or academic consequences resulting from the misuse or misappropriation of this work.

Any unauthorized copying or use of this work may result in serious consequences, including but not limited to academic penalties, legal action, and damage to personal and professional reputation. Therefore, please use this work only as a reference and always ensure that you properly cite and attribute any sources or references used.
