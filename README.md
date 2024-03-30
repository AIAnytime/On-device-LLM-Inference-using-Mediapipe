# On-device-LLM-Inference-using-Mediapipe
On-device LLM Inference using Mediapipe LLM Inference API.

# LLM Task Sample Setup Guide

This guide provides step-by-step instructions on how to set up and run a sample LLM task on your local machine. Ensure you have Python (3.x or 2.x for older versions) installed and a modern web browser, preferably Chrome, before you begin.

## Setup Instructions

- Create a new folder on your device named `llm_task`.
- Copy `index.html` and `index.js` files into the `llm_task` folder. These are essential for the task's web interface.
- Download the Gemma 2B model (TensorFlow Lite `2b-it-gpu-int4` or `2b-it-gpu-int8`) into the `llm_task` folder. Alternatively, you can convert an external LLM (like Phi-2, Falcon, or StableLM) for a GPU backend, as only that is currently supported.
- Open the `index.js` file in a text editor and update the `modelFileName` variable with the name of your model file.
- Run a local HTTP server within the `llm_task` folder by executing `python3 -m http.server 8000` (or `python -m SimpleHTTPServer 8000` for older Python versions) in your terminal.
- Open a web browser and go to `http://localhost:8000`. The web interface for your LLM task will appear, and the button on the webpage will be enabled after about 10 seconds, indicating the task is ready.

Enjoy exploring the capabilities of your large language model with this simple setup!


