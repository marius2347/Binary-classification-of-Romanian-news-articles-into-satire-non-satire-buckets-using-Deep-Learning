<h1>Binary classification of Romanian news articles into satire / non-satire buckets using Deep Learning in Python on Kaggle</h1>
<br>
<h2>Features</h2>
<ul>
    <li>TF-IDF vectorizer with a max_features parameter, initialized to handle textual data processing (used for transforming text data).</li>
    <li>Filling NaN values in the 'content' column with empty strings to avoid missing data issues before text transformation.</li>
    <li>Transforming the 'content' column using the TF-IDF vectorizer to generate a matrix of TF-IDF features.</li>
    <li>Converting the TF-IDF matrix to a DataFrame to easily integrate with other features in the dataset.</li>
    <li>Concatenating the TF-IDF DataFrame with the original dataset to include the extracted features.</li>
    <li>Dropping the original 'content' column after extracting useful features using TF-IDF, leaving only the numerical features for modeling.</li>
    <li>Splitting the dataset into training and testing sets using `train_test_split`, with an 80/20 split.</li>
    <li>Using the CharCNN model architecture, which includes convolutional layers, dropout, and other neural network configurations for text classification.</li>
    <li>Encoding target labels using `LabelEncoder` and converting them into one-hot encoded format using `to_categorical` for multi-class classification.</li>
    <li>Training the CharCNN model with training inputs and labels using the `.train()` function, specifying epochs and batch size for training control.</li>
    <li>Testing the model's performance on the test dataset using the `.test()` method, followed by saving the trained model to a `.keras` file.</li>
</ul>
</ul>

<h2>Acknowledgments</h2>

<b> Python3: http://bit.ly/python3-certifications </b>
<br>
<b> Machine Learning: https://bit.ly/machine-learning-certification <b>
<br>

<h2> Link </h2>
<b> Kaggle Competition: https://www.kaggle.com/competitions/nitro-language-processing-3</b>
<br>

<h2>Photo</h2>
<img src="photo.png">
<br>
<h2>Contact</h2>

<b> Email: mariusc0023@gmail.com </b>
