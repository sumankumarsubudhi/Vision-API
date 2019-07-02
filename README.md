# How To: Using The Vision API with Python


## Initial Set-Up

[This page](https://cloud.google.com/vision/docs/reference/libraries#client-libraries-install-python) will guide you through the set-up process. Using the pip Python package installer, you can install the Vision client library with:

_pip install --upgrade google-cloud-vision_ 

Next, follow the steps [here](https://cloud.google.com/sdk/docs/) to install the Google Cloud SDK to your computer.

Finally, run this command to authenticate your computer and the SDK.

_gcloud auth application-default login_

You should now be able to run the python files. Ensure you run them through a Python 2 interpreter and not Python 3, otherwise they will not work.


## Using the Files

For Python to successfully send an image to the Vision API, it must be able to find it. Ensure that your images are saved in the same directory as the Python code.
