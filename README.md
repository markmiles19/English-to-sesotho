All libraries that are required will be installed automatically when running the notebook.

The following lines of code will install the necessary libraries:

! pip install transformers datasets

! pip install evaluate

! pip install sacrebleu

The notebook will run without any errors just so long as the text files are present and the necessary libraries have been installed at the beginning. The directory where the files are being read in may cause issues in Visual Studio Code but will run without errors in Google Colab. All that would need to be removed is "/content" if it will not run in Visual Studio Code.

The model that translates the text uses the Pipeline function which is included as part of the transformers library. The user can easily modify the sample text they desire to translate by modifying the "text" variable under the section "Inference."

This is what the sample text looks like:

text = "translate English to Sesotho: Respect those who have worked to build and develop our country"

The output will then be displayed after the Pipeline function has run (the next block after the sample text).
