# Text-Recognition-System
# Handwritten Text Recognition Project

## Project Overview
This project, titled "Handwritten Text Recognition using Machine Learning Techniques," was undertaken to develop a system capable of recognizing handwritten text and converting it into a digital format. The project was submitted in partial fulfillment of the requirements for the Bachelor of Engineering degree in Computer Engineering at Thadomal Shahani Engineering College, University of Mumbai.

## Project Description
Handwritten Text Recognition (HTR) systems are crucial for digitizing written documents in a readable and editable format. This technology plays a significant role in various fields such as healthcare, banking, and legal sectors, where handwritten documents are still prevalent.

## Objectives
- To develop a machine learning model that can accurately recognize handwritten text from images.
- To streamline the process of digitizing written content, reducing the need for manual data entry.
- To provide a reliable solution for industries that handle a large volume of handwritten documents.

## Technologies Used
- **Python**: A high-level programming language known for its readability and support for multiple programming paradigms.
- **TensorFlow**: An open-source framework for numerical computation and machine learning.
- **OpenCV**: Open Source Computer Vision Library, used for processing images and videos.
- **NumPy**: A library for the Python programming language, adding support for large, multi-dimensional arrays and matrices.
  
## System Architecture
The system utilizes a combination of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) with Long Short-Term Memory (LSTM) cells to process and recognize handwritten text. The overall architecture involves several stages:
1. **Image Acquisition**: Capturing the image from real-world documents.
2. **Preprocessing**: Enhancing image quality for better analysis.
3. **Feature Extraction**: Using CNNs to identify relevant features from the image.
4. **Sequence Labeling**: Employing LSTM to handle sequences in the data.
5. **Transcription**: Converting the recognized characters into textual output.

![System Architecture](https://github.com/Nishieee/Text-Recognition-System/blob/main/images/architecture_HTR.png)


## Block Diagram
![Block Diagram - Flow](https://github.com/Nishieee/Text-Recognition-System/blob/main/images/Block_Diagram.png)

## Interface Images 
![GUI](https://github.com/Nishieee/Text-Recognition-System/blob/main/images/Interafce_1.png)

## Output 
![Ooutput image](https://github.com/Nishieee/Text-Recognition-System/blob/main/images/Interface_output_2.png)



## Repository Structure
```plaintext
/handwritten-text-recognition
|-- /data                  # Folder for datasets and inputs
|-- /models                # Trained models and model files
|-- /notebooks             # Jupyter notebooks for experiments and analysis
|-- /src                   # Source code for HTR system
|-- /tests                 # Test scripts for validation
|-- README.md              # Project documentation
