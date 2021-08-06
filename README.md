<h1>MNIST-GAN-and-Music-Genre-Prediction</h1>
<h2>MNIST GAN</h2>
In this project, I have trained a DCGAN on the famous MNIST dataset for all 10 classes which are number form 0-9 for 2 epochs.The DCGAN has n Encoder-Decoder architecture as show below.<br>
<h3>Generator</h3>
<img src="Generator.png" width=500 height=500>
<h3>Discriminator</h3>
<img src="disc.png" width=500 height=500>
<br>
<h3>Results</h3>
<img src='GAN.png'>
<img src='GAN2.png'>
<br>
<h2>Music Genre Prediction</h2>
In this project, i have a dataset of 200 songs(audio files) belonging totwo classes:Rock and Classic. I used Librosa audio analysing library to extract extra features from the songs like Spectral centroid,Spectral Rolloff etc. I further created a new Pandas Dataframe from the above features and trained a LightGBM and ANN models on it and showed the results.Some results can be seen below.<br>
<h3>LGBM Classification Report</h3>
<img src="LGBM.PNG" height=300 width=300>
<h3>ANN Classification Report</h3>
<img src="ANN.PNG" height=300 width=300>
