# PIXEL-MAGIC-
Generate Custom Images Using OpenAI API DALL E


PIXEL MAGIC is a Flask-based application that allows users to generate images based on textual descriptions using the OpenAI API. The generated images can be easily viewed and copied to the clipboard through a simple web interface.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Workflow](#workflow)


## Overview
The Custom Image Generator app takes a textual description of an image as input and generates a corresponding image using the OpenAI API. The app features a clean and intuitive web interface built with Flask and Bootstrap, making it easy to generate and view custom images.

## Features
- Generate images based on textual descriptions.
- Simple and intuitive web interface built with Flask and Bootstrap.
- Easy copying of image URLs to the clipboard.

 **Set up OpenAI API Key:**
    - Obtain an API key from OpenAI.
    - Set the API key as an environment variable:
    ```sh
    export OPENAI_API_KEY='your_openai_api_key'  # On Windows, use `set OPENAI_API_KEY=your_openai_api_key`
    ```
## Workflow
1. **User Input:**
    - The user enters a textual description of the desired image in the provided text box.
2. **Generate Image:**
    - The user clicks the "Share with the Image" button to generate the image.
3. **View and Copy Image URL:**
    - The generated image is displayed, and the user can copy the image URL to the clipboard.

