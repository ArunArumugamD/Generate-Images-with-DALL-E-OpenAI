# DALL-E-OpenAI


# Setup
Create and activate a virtual environment, then install the openai package:


`$ python --version
Python 3.11.0
$ python -m venv venv
$ source venv/bin/activate
(venv) $ python -m pip install openai`

You need to be on Python 3.7.1 or higher.


# Create Images and Image Variations

You can find the code for each of these steps in dedicated scripts:

create.py: Create an image from a text prompt and save the image data to a file.
convert.py: Convert a Base64-encoded PNG image delivered in a JSON response to a PNG image file.
vary.py: Read Base64-encoded image data and make an API request to receive variations of that image.

# Edit Images (Inpainting and Outpainting)

The OpenAI Image API also allows you to edit parts of an image using text prompts. For this, you need to create a mask with transparent image data in the area where you want to edit the image.
