# QuantumCatClassifier
Quantum Computing classifier using Pennylane

<h1>STEPS TO SETUP PROGRAM</h1>
<br>
1. Go to https://www.microsoft.com/en-us/download/details.aspx?id=54765 and download the Kaggle Cats and Dogs dataset from microsoft. Unzip the contents into this repositories directory. 

2. Run the PreprocessData notebook. This should create a "training_data.npy" file in the main repository directory.

3. Run the Quantum Cats vs Dogs notebook
<br><br>
<hr>
<h1>ABOUT THIS PROJECT</h1>
This project is based on an implementation of the Data-reuploading Classifier listed here https://pennylane.ai/qml/app/tutorial_data_reuploading_classifier.html
<br><br>
It uses the above implementation and then expands on that to create a classifier for images. My implementation only requies one Qubit to run. It may be possible to expand this in the future to multiple Qubits using a hadamard gate to entangle another Qubit with the first one.
<br><br>
Also took inspiration from https://www.youtube.com/user/sentdex tutorial series on PyTorch. Used his implementation of data rangling and preprocessing to get the cat and dog images ready for a run through the algorithm.




