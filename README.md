**Overview**

This project focuses on automating AlphaFold predictions using ChimeraX, a molecular visualization program, and Google Colab, a cloud-based Jupyter notebook environment. The automation leverages the convenience of Google Sheets for seamless implementation and interaction.

**Features**

Google Sheets Integration: Users can upload amino acid sequences conveniently through column A in a Google Sheet named AlphaFoldSequences.
Automatic Concatenation: The automation process automatically reads the concatenation of the inserted sequence with another string, eliminating the need for manual concatenation.
Google Colab Automation: The concatenated string is imported into Google Colab, where the automation takes place.
Sequence Prediction: The code runs through an array of strings representing sequences, predicting their structures using AlphaFold.
Terminal Output: Predicted structures are displayed as images in the terminal for easy visualization.
Downloadable Predictions: After processing the entire array, a zip file containing the predicted structures is downloaded onto the user's computer.

**Usage**

Open the provided Google Sheet named AlphaFoldSequences.
Upload amino acid sequences into column A.
Click "Run" to execute the automation code.
View predicted structures in the terminal.
Download the zip file containing the predictions.

**Requirements**

Google account for accessing Google Sheets and Google Colab.
ChimeraX installed on the local machine for visualization.
Python environment with necessary dependencies for running the automation code.
