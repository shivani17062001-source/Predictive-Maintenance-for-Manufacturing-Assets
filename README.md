# Predictive-Maintenance-for-Manufacturing-Assets

AssetGuard:

Empowering manufacturers to predict and prevent asset failures before they happen.

🚀 Overview

AssetGuard is an innovative predictive maintenance solution for manufacturing assets. Using the AI4I 2020 Predictive Maintenance Dataset, it leverages Python, pandas, and XGBoost in Google Colab to perform exploratory data analysis (EDA), visualize insights via heatmaps and correlation matrices, and predict equipment failures with high accuracy. Designed for data scientists and manufacturing professionals, AssetGuard minimizes downtime by turning sensor data into actionable intelligence.

Key Stats:

Dataset: 10,000 samples

Model Accuracy: ~98% with XGBoost

Focus: Anomaly detection, correlations, and ROC-AUC evaluation


✨ Features


EDA: Distributions, outlier detection, and scatter plots for deep insights.

Visualizations: Correlation heatmaps, feature importance, confusion matrices, and ROC curves.

ML Pipeline: Preprocess data, train XGBoost for failure prediction, and evaluate performance.

Anomaly Detection: Z-score-based identification of issues in metrics like torque.

Extensible: Modular code for adding SMOTE, SHAP, or custom features.

Colab-Friendly: No local setup needed for initial use.


📊 Demo

Correlation heatmap example:

import seaborn as sns
import matplotlib.pyplot as plt

# Assuming corr_matrix is computed
plt.figure(figsize=(10, 8))
sns.heatmap(corr_matrix, annot=True, cmap='coolwarm')
plt.title('Correlation Matrix Heatmap')
plt.show()

(Add screenshots/GIFs of outputs in your repo for better engagement!)


🛠️ Installation

Clone the Repository:

git clone https://github.com/yourusername/assetguard.git
cd assetguard

Set Up Environment:

Google Colab: Upload ai4i2020.csv and run the notebook.

Local Setup: Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost



Dataset: Download ai4i2020.csv from Kaggle and place it in the project root.

📖 Usage


Colab Workflow:

Upload ai4i2020.csv to Colab.

Run notebook cells for EDA, visualizations, and XGBoost training.


Steps:

Explore data: Summaries, distributions, correlations.

Train model: Scale features, fit XGBoost, evaluate with ROC-AUC.

Customize: Adjust hyperparameters or add features.

See assetguard_notebook.ipynb for full code.

🤝 Contributing

We welcome contributions! To contribute:

Fork the repo.

Create a branch: git checkout -b feature/YourFeature.

Commit: git commit -m 'Add YourFeature'.

Push: git push origin feature/YourFeature.


Open a Pull Request.

Follow our Code of Conduct and check issues.

📄 License

Licensed under the MIT License. See LICENSE for details.


📬 Contact

Author: Shivani Uppala

Email: Shivaniuppala034@gmail.com

Phone: (475) 287-3249

LinkedIn: linkedin.com/in/shivani-uppala


🙌 Acknowledgments

Built with the AI4I 2020 dataset from Kaggle.

Created by Shivani Uppala on September 28, 2025.


Thanks to the open-source community for tools like pandas, XGBoost, and Colab.

Star the repo to support AssetGuard! 🚀 Let's connect on GitHub or LinkedIn.
