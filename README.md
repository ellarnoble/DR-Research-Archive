# DR-Research-Archive

# Project Overview
This repository accompanies a research report investigating lexical markers of Alzheimer’s disease (AD) in the Pitt Cookie Theft Corpus. The project comprises a two-stage analysis: first, a binary classifier is implemented and evaluated to detect speech samples produced by participants with AD; second, a feature-based analysis examines 11 empirically supported lexical features across AD and control groups. 

# Structure of Repository 
The repository consists of one file containing all code which was used to conduct the data analysis. This may be run in any local Python environment with the required dependencies installed.

# Running the Code 
The code was developed and executed using Python 3.12 (64-bit) via Google Colab. All code dependencies are imported in the first cell of the file and consist of standard Python libraries, including NumPy for numerical computation, scikit-learn for model evaluation, and Matplotlib for visualisation.

All code can be run top to bottom. Data/spaCy download cells are marked with a warning for expected additional runtime; however no individual cell should take more than approximately eight minutes to run. Running the file will output model and data evaluation metrics as well as a graphical depiction of the model's loss function.

# Data Access
All data is obtained from the DementiaBank which is a controlled-access database distributed via the CHILDES/TalkBank project. For this project, access to the data was requested and granted by a research supervisor for the duration of one year. Due to data-use restrictions, the corpus is not redistributed in this repository. All analysis was conducted in accordance with ethical and usage guidelines.

# Reproducibility 
Model evaluation metrics have exhibited some variation across re-training runs using a fixed set of hyperparameters and randomness seed. The source of this variation may be due to seeds being generated differently on different Colab machines; this does not substantially affect the interpretation of the results.
