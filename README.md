# Emotion_Recognition
Technical Documentation

Setting Up the Experiment Environment:

To reproduce the experiment efficiently, utilizing an environment with robust computational capabilities is crucial. Google Colab is highly recommended for this purpose due to its generous computational offerings, including free access to GPUs, which can significantly speed up processing times. Nonetheless, if the user has access to another high-performance computational environment, that may be suitable as well.

Development Environments and IDEs:

While Google Colab provides a browser-based Python interpreter, users who prefer local development can execute the experiment in any Integrated Development Environment (IDE) of their choice. Popular IDEs like PyCharm, Jupyter Notebook, or Visual Studio Code are suitable candidates.

Dependencies and Libraries:

Before executing the experiment, ensure all required libraries and dependencies are installed. The code contains detailed comments on the necessary libraries. 

Accessing the Code and Dataset:

The entire codebase, along with the associated datasets in CSV format, is available on GitHub. To access the code, simply clone the repository:
git clone https://github.com/sidali-lari/Emotion_Recognition.git

Once the repository is cloned, navigate to the respective directories to find the algorithms and datasets. The repository contains the following algorithm files:
svm.py: Support Vector Machine implementation.
knn.py: K-Nearest Neighbors algorithm
rnn.py: Recurrent Neural Network model.
lstm.py: Long Short-Term Memory model.
hybrid-resnet-lstm.py: A hybrid model combining ResNet and LSTM.
transformer.py: Transformer-based model.

Running the Experiment:

To run the experiment:
Set your working directory to where the code and datasets reside.
item Choose the desired algorithm file.
item Execute the script either through your IDE or directly from the command line.

For instance, to run the SVM algorithm:

python svm.py


Conclusion:

Reproducibility is a cornerstone of scientific experiments. This documentation ensures that any user, regardless of their technical expertise, can reproduce the experiment with ease. Should any issues arise during setup or execution, refer to the accompanying README on the GitHub repository for troubleshooting tips and additional information.
