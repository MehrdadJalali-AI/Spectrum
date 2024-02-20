<!DOCTYPE html>
<html>
<head>
<title>README: Spectroscopy Prediction Models</title>
</head>
<body>

<h1>README: Spectroscopy Prediction Models</h1>

<h2>Overview</h2>
<p>This repository contains scripts for generating synthetic spectroscopy data and predicting material facets using CNN and DNN. It's aimed at aiding the analysis and prediction of material properties from their infrared spectroscopy data.</p>

<h2>Files Description</h2>
<ul>
  <li><strong>generatesynthetic_cnn.py:</strong> Generates synthetic spectra data and builds a CNN model for predicting amplitudes of specific frequencies.</li>
  <li><strong>generatesysnthetic_dnn.py:</strong> Similar to the CNN script but uses a DNN model for prediction.</li>
  <li><strong>facetprediction_experiment.py:</strong> Utilizes a pre-trained CNN to predict material facets from spectroscopy data.</li>
</ul>

<h2>Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>TensorFlow 2.x</li>
  <li>NumPy, Pandas, Matplotlib, Scikit-learn</li>
</ul>

<h2>Usage</h2>
<p>Install dependencies:</p>
<pre>pip install tensorflow numpy pandas matplotlib scikit-learn</pre>
<p>Run the scripts:</p>
<pre>python generatesynthetic_cnn.py
python generatesysnthetic_dnn.py
python facetprediction_experiment.py</pre>

<h2>Note</h2>
<p>Scripts are designed for Google Colab. Adjustments may be required for different environments.</p>

<h2>Contribution</h2>
<p>Contributions are welcome! Please create a pull request or open an issue for suggestions.</p>

</body>
</html>
