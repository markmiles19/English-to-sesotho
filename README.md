All libraries that are required will be installed automatically when running the notebook.

The following lines of code will install the necessary libraries:

! pip install transformers datasets

! pip install evaluate

! pip install sacrebleu

The notebook will run without any errors just so long as the text files are present and the necessary libraries have been installed at the beginning. The directory where the files are being read in may cause issues in Visual Studio Code but will run without errors in Google Colab. All that would need to be removed is "/content" if it will not run in Visual Studio Code.
