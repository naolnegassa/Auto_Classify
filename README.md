# Auto_Classify
Small weekend project, takes in user requests for the images to be pulled from Google Images, using the handy script provided by [hardikvisa](https://github.com/hardikvasa/google-images-download) and builds a classifier to distiguish.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install google_images_download.

```bash
pip install google_images_download
```

## Usage
Can be run in Google Colab.
Make sure to have the Hardware Accelerator set to 'GPU' to make use of it.


Make sure you have a folder named 'Auto_Query' in your Google Drive, or change the path accordingly.


## Future Development
Replace the command line interface for user requests with Voice requests from [Speech Recognition](https://pypi.org/project/SpeechRecognition/)

Using Tensorflow and Keras to build custom models from the voice requests. You can see them in the Colab file, but I haven't written anything yet.
## License
[MIT](https://choosealicense.com/licenses/mit/)
