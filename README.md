# Object Detection

This notebook demonstrates how to perform object detection with **`EfficientDet`** pre-trained model and deploy using **`Gradio`**.

## Running the Notebook

This notebook can be run in several ways:

### 1. Run on Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `object_detection.ipynb` file 
3. Ensure all required dependencies are installed (see the [Requirements](#requirements) section below).

### 2. Run with Jupyter Notebook
1. Install Jupyter Notebook if not already installed:
    ```bash
    pip install notebook
    ```
2. Start the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```
3. Open the object_detection.ipynb file and execute the cells.

### 3. Run Locally
1. Ensure Python is installed on your system (version >= 3.12 recommended).
2. Install the required dependencies (see the [Requirements](#requirements) section below).
3. Run the notebook directly using jupyter Notebook or compatible tools (VS Code, PyCharm , etc.).

## Requirements

During developing these packages are used:

- numpy==2.0.2
- opencv-python==4.10.0.84
- matplotlib==3.9.3
- tensorflow==2.18.0
- tensorflow-hub==0.16.1
- gradio==5.8.0

## Installations

You can install these requirements packages using pip:

```bash
pip install numpy==2.0.2 opencv-python==4.10.0.84 matplotlib==3.9.3 tensorflow==2.18.0 tensorflow-hub==0.16.1 gradio==5.8.0
```
Alternatively, you can use the requirements.txt file to install the dependencies:
```bash
pip install -r requirements.txt
```
