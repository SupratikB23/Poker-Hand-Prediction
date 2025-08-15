<!-- README.md (HTML format) for Poker Hand Prediction Model -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  
</head>
<body>

  <h1>🎴 Poker Hand Prediction Model 🎴</h1>
  <p>
    A Machine Learning & Deep Learning project that predicts <strong>poker hand rankings</strong> from 5-card combinations.
    The model classifies hands such as <em>High Card, Pair, Two Pair, Three of a Kind, Straight, Flush, Full House,
    Four of a Kind, Straight Flush,</em> and <em>Royal Flush</em>.<br> <b>[Project for Social Winter of Code (SWOC 2025)]</b>
  </p>



  <div class="badges">
    <img alt="Made with Jupyter" src="https://img.shields.io/badge/Made%20with-Jupyter-orange.svg" />
    <img alt="Python 3.x" src="https://img.shields.io/badge/Python-3.x-blue.svg" />
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg" />
  </div>

  <hr />
  <img width="600" height="400" alt="Screenshot 2025-01-14 092314" src="https://github.com/user-attachments/assets/a8632fb9-d850-426b-8ab8-1c2fad6669eb" />
  
  <h2>📊 Dataset Information</h2>
  <ul>
    <li>Each row represents a single 5-card poker hand.</li>
    <li>Columns encode the <strong>rank</strong> and <strong>suit</strong> for each card.</li>
    <li>A target column stores the integer label for the hand category.</li>
    <li>
      Source: <a href="https://www.kaggle.com/datasets/dysphoria/poker-hand-classification" target="_blank" rel="noopener noreferrer">
      Noah Boggs – Poker Hand Dataset</a>.
    </li>
  </ul>

  <h2>⚙️ Workflow</h2>
  <ol>
    <li><strong>Data Loading</strong> – Import training and testing files from <span class="mono">/Dataset</span>.</li>
    <li><strong>Preprocessing</strong> – Validate schema, handle encoding and normalizate the data.</li>
    <li><strong>Feature Engineering</strong> – Represent ranks/suits and derive hand features where useful.</li>
    <li><strong>Model Training</strong> – Train models (MLP, Random Forest, Gradient Boosting).</li>
    <li><strong>Evaluation</strong> – Accuracy, precision, recall, F1-score, and confusion matrix on the test set.</li>
  </ol>

<h2>🧠 Models Used</h2>
<ul>
  <li><strong>Multi-Layer Perceptron Classifier (MLP)</strong></li>
  <li><strong>Random Forest Classifier</strong></li>
  <li><strong>Gradient Boosting Classifier</strong></li>
  <li><strong>Stacking Classifier (all above 3 models)</strong></li>
</ul>

<h2>📈 Results</h2>
<h4>Model vs Accuracy</h4>
<img width="600" height="400" alt="__results___19_0" src="https://github.com/user-attachments/assets/5891a4bf-bcdb-4bf7-9ba0-90906469ef17" />
<h4>ROC Curve</h4>
<img width="500" height="600" alt="ROC 20_0" src="https://github.com/user-attachments/assets/da717b1e-4ad0-46cf-b6d4-a9f98f6da2b8" />
<h4>Heatmap for Stacking Classifier</h4>
<img width="800" height="550" alt="Heat 0" src="https://github.com/user-attachments/assets/98e33ba4-35fa-4b2c-86ba-e02737c2e44c" />



<h2>🛠️ Requirements</h2>
  <p>Install the core dependencies:</p>
  <pre><code>pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn </code></pre>
  <div class="grid">
    <div class="card">

  <h2>🚀 How to Run</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/SupratikB23/Poker-Hand-Prediction.git</code></pre>
    </li>
    <li>Open the notebook:
      <pre><code>jupyter notebook Poker_Hand_Prediction_Model.ipynb</code></pre>
    </li>
    <li>Run all cells to train and evaluate the model.</li>
  </ol>

 <h2>📂 Repository Structure</h2>
  <pre><code>Poker Hand Prediction
├── Dataset
│   ├── poker-hand-training.data   
│   └── poker-hand-testing.data  
├── Poker_Hand_Prediction_Model
└── README.md                    
</code></pre>


  <h2>💡 Use Cases</h2>
  <ul>
    <li><strong>Educational Tool</strong> – Practice and compare classification algorithms.</li>
    <li><strong>Game Simulation</strong> – Integrate into poker bots or simulators.</li>
    <li><strong>Statistical Analysis</strong> – Explore hand probability patterns.</li>
  </ul>

  <h2>📜 License</h2>
  <p>This project is licensed under the <strong>MIT License</strong>. You are free to use, modify, and distribute with attribution.</p>

  <h2>🙌 Acknowledgements</h2>
  <ul>
    <li>
      <a href="https://www.kaggle.com/datasets/dysphoria/poker-hand-classification" target="_blank" rel="noopener noreferrer">
      Noah Boggs - Poker Hand Classification </a> for the dataset.
    </li>
    <li>Social Winter of Code (SWOC 2025)</li>
  </ul>

</body>
</html>
