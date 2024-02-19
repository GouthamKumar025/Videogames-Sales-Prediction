<h1><center>Videogames Sales Prediction using Regression</center></h1>
This repository contains code for predicting video game sales using linear regression. The goal of this project is to develop a model that can accurately predict the sales of video games based on various features such as platform, genre, critic scores, user scores, etc.

<h2>Dataset</h2>
The dataset used for this project is sourced from Kaggle. It contains information about video games including their sales figures and various attributes like platform, genre, critic scores, user scores, etc. The dataset is split into training and testing sets to evaluate the performance of the model.

<h2>Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Scikit-learn</li>
  <li>Matplotlib</li>
</ul>

<h2>Usage</h2>
<h3>Clone the repository:</h3>

```bash
git clone https://github.com/your-username/video-game-sales-prediction.git
```

<h3>Navigate to the project directory:</h3>

```bash
cd video-game-sales-prediction
```

<h3>Install the required dependencies:</h3>

```bash
pip install -r requirements.txt
```

Run the Jupyter notebook videogame sales prediction.ipynb to train the linear regression model and make predictions.

<h2>Methodology</h2>
<h3>Data Preprocessing:</h3>
<ul>
  <li>Handle missing values.</li>
  <li>Encode categorical variables.</li>
  <li>Scale numerical features.</li>
</ul>

<h3>Model Training:</h3>

<ul>
  <li>Split the data into training and testing sets.</li>
  <li>Train a linear regression model on the training data.</li>
</ul>


<h3>Model Evaluation:</h3>

<ul>
  <li>Evaluate the model's performance on the testing data.</li>
  <li>Analyze metrics such as mean squared error, R-squared, etc.</li>
</ul>


<h3>Prediction:</h3>

Make predictions on new data.

<h3>Results</h3>
The trained model achieves an accuracy of > 97% on the testing data, indicating its capability to predict video game sales based on the provided features.

<h3>License</h3>
This project is licensed under the MIT License. See the <a href = "https://mit-license.org/">LICENSE</a> file for details.


