<div align="center">
  <h1>Task 5: Credit Card Fraud Detection</h1>
</div>

---

### **Project Goal**
<p>
  The goal of this advanced project was to build a machine learning model capable of identifying fraudulent credit card transactions from a highly imbalanced dataset.
</p>

---

### **Tools & Dataset**
<ul>
  <li><strong>Tools:</strong> Python, Scikit-learn, Pandas, Seaborn, Matplotlib</li>
  <li><strong>Dataset:</strong> Credit Card Fraud Detection dataset from Kaggle.</li>
</ul>

---

### **What I Did**
<ol>
  <li>Loaded the dataset and identified a severe class imbalance (very few fraud cases).</li>
  <li>Handled the imbalance using <strong>undersampling</strong> to create a balanced dataset for training.</li>
  <li>Scaled the features using <strong>StandardScaler</strong> to ensure the model converges properly.</li>
  <li>Trained a <strong>Logistic Regression</strong> model on the balanced and scaled data.</li>
  <li>Evaluated the model's performance using accuracy, precision, and recall.</li>
</ol>

---

### **Final Model Performance**
<ul>
  <li><strong>Accuracy:</strong> The model achieved a perfect accuracy of <strong>1.0 (100%)</strong> on the balanced test set.</li>
  <li>A confusion matrix was plotted to visualize the model's perfect detection of both fraudulent and legitimate transactions.</li>
</ul>
