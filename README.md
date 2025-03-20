<h1 align='center'> ASL Image Classification Project</h1>
<br />
<p align="center">
  <img src="images/ASL Logo.png" width="350" height="300">
</p>
<br />

## About The Project
The project focuses on classifying American Sign Language (ASL) characters using neural networks (CNN) and some complex preprocessing of the large input file. The goal is to identify and analyze hand symbols that represent different ASL signs. The model uses a 4-layer CNN to process and classify ASL signed images. After training the model with data, the trained model data will be saved in the other HDF5 file and testing data evaluates this HDF5 file and gives the output and predictions.
<br />

## Dataset
The dataset used in this project consists of images representing various ASL signs named "data_train.npy"(This dataset contains 8443 samples of data.)and "labels_train.npy"(This dataset consists of the lables provided in a certain manner). Each image is labeled with the corresponding ASL sign it represents. These datsets are of large files so can't upload in the github repository. The dataset is split into training and testing sets to evaluate the performance of the CNN model effectively. 
<br />

## Results
The model achieved a promising accuracy rate, indicating its capability to correctly classify ASL signs. Detailed performance metrics can be found in the testing results section of this repository.

<br />

<a href="images/Screenshot (74).png">
  <img src="images/Screenshot (74).png">
</a>

<br />

The result of predicted and actual values will be in form of:

<br />

<a href="images/Screenshot (75).png">
  <img src="Images/Screenshot (75).png">
</a>
and so on...
<br />

<br />

## Dependencies
Here, list all libraries, packages and other dependencies that need to be installed to run your project.
<ul>
  <li>Python 3</li>
  <li>TensorFlow</li>
  <li>Keras</li>
  <li>Scikit</li>
  <li>Numpy</li>
</ul>

<br />

## Usage
Instructions for setting up and running the model are as follows:
<ul>
  <li>Clone the repository.</li>
  <li>Install the required dependencies.</li>
  <li>Run the training script to train the model which is named as "TrainingTheData_final_file.ipynb".</li>
  <li>Evaluate the model using the testing script which is named as "TestingTheData.ipynb".</li>
</ul>
<br />

## Installation
 Clone the repo
   ```sh
   gh repo clone AbhinavReddy18-bytes/ASL-Image-Classification
   ```
<br />

## Contributing
Contributions to this ASL Classification project are welcome. If you have a suggestion that would improve this, please follow the steps below:

1. Fork the Project: Create your own copy of the project on GitHub.
2. Create your Feature Branch: `git checkout -b feature/YourAmazingFeature`
3. Commit your Changes: `git commit -m 'Add some YourAmazingFeature'`
4. Push to the Branch: Upload your changes to your fork.
5. Open a Pull Request: Submit your changes for review to be potentially merged into the project.

<br />

## Liscense
Distributed under the MIT License. See `License.txt` for more information

<br />

## Author
<address>
Abhinav Reddy Pannala <a href="mailto:pannalaabhinav02@gmail.com">Ping me here!!</a>.<br> 
</address>

<br />

## Acknowledgements

Catia Silva <a href="https://github.com/catiaspsilva">Github</a>

<br />

<h3> Thank You 😉</h3>
