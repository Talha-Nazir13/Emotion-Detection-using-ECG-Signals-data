<h1>Emotion Detection using ECG Signals Data: Arousal, Liking, Dominance, and Valence Classification</h1>

<p>This project focuses on detecting and classifying human emotions using ECG data. The aim is to predict emotional states across four dimensions: <strong>Arousal</strong>, <strong>Liking</strong>, <strong>Dominance</strong>, and <strong>Valence</strong>. This is achieved using machine learning algorithms applied to ECG signals.</p>

<h2>Features</h2>

<ul>
  <li>Loading and preprocessing ECG data for emotion classification.</li>
  <li>Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).</li>
  <li>Implementation of machine learning classifiers, including Random Forest and Logistic Regression.</li>
  <li>Evaluation of model performance using accuracy, confusion matrix, and classification report.</li>
  <li>Visualizations of performance metrics using Matplotlib and Seaborn.</li>
</ul>

<h2>Dataset</h2>

<p>The project uses an ECG dataset that contains signals captured from participants during various emotional states. The data is split into training and testing sets, with labels corresponding to the four emotion dimensions:</p>

<ul>
  <li><strong>Arousal</strong>: Measures the intensity of the emotional response.</li>
  <li><strong>Liking</strong>: Indicates how pleasant or unpleasant the emotion is.</li>
  <li><strong>Dominance</strong>: Reflects the control or influence one feels over the emotion.</li>
  <li><strong>Valence</strong>: Represents the positivity or negativity of the emotional state.</li>
</ul>

<h2>Requirements</h2>

<p>To run this project, you will need the following Python libraries:</p>

<ul>
  <li><code>numpy</code></li>
  <li><code>scipy</code> (for data loading and processing)</li>
  <li><code>scikit-learn</code> (for machine learning algorithms)</li>
  <li><code>imblearn</code> (for handling class imbalance using SMOTE)</li>
  <li><code>matplotlib</code></li>
  <li><code>seaborn</code></li>
</ul>

<p>Install the dependencies using:</p>

<pre><code>pip install -r requirements.txt
</code></pre>

<h2>Model Architecture</h2>

<p>The project implements two machine learning models:</p>

<ul>
  <li><strong>Random Forest Classifier</strong>: A robust and popular ensemble learning method.</li>
  <li><strong>Logistic Regression</strong>: A linear model used for binary classification, extended to multiclass classification here.</li>
</ul>

<p>Both models are evaluated using accuracy, confusion matrices, and detailed classification reports to assess their effectiveness in detecting emotional states from ECG data.</p>

<h2>Results</h2>

<p>The project evaluates the models on the test set and provides visualizations of the confusion matrix and other performance metrics. The goal is to accurately classify emotions across the four dimensions: Arousal, Liking, Dominance, and Valence.</p>

<h2>Customization</h2>

<p>You can adjust the following aspects of the project:</p>

<ul>
  <li><strong>ECG data preprocessing</strong>: Modify the data preprocessing steps, such as filtering or feature extraction, for better performance.</li>
  <li><strong>Model selection</strong>: Implement additional machine learning or deep learning models (e.g., SVM, Neural Networks) to improve classification accuracy.</li>
  <li><strong>Handling class imbalance</strong>: Experiment with different resampling techniques or loss functions to address class imbalance.</li>
</ul>

<h2>Acknowledgments</h2>

<ul>
  <li>Thanks to the open-source libraries such as <strong>Scikit-learn</strong> and <strong>Imbalanced-learn</strong> for providing robust tools for machine learning and data preprocessing.</li>
  <li>Gratitude to the creators of the ECG dataset used for this research.</li>
</ul>

