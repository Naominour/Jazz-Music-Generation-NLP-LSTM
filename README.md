# 🎶 Improvise a Jazz Solo with an LSTM Network 🎶

Welcome to the **Improvise a Jazz Solo with an LSTM Network** project! This repository demonstrates the use of a Long Short-Term Memory **(LSTM)** network to generate jazz music solos. This project builds upon existing work, incorporating enhancements and additional functionalities.

![Deep Learning](https://img.shields.io/badge/Skill-Deep%20Learning-yellow)
![Sequence Modeling](https://img.shields.io/badge/Skill-Sequence%20Modeling-blueviolet)
![Generative Models](https://img.shields.io/badge/Skill-Generative%20Models-green)
![Model Training and Evaluation](https://img.shields.io/badge/Skill-Model%20Training%20and%20Evaluation-orange)
![Python Programming](https://img.shields.io/badge/Skill-Python%20Programming-brightgreen)

## Project Overview
This project is organised into multiple Python scripts and a Jupyter Notebook. The main components of the project include data preparation, model training, and music generation. Below is the detailed file structure and the corresponding functionalities:

**Deep Learning**
```bash
.
├── data_utils.py            # Utilities for data handling and preprocessing
├── generateTestCases.py     # Scripts to generate test cases for the model
├── grammar.py               # Grammar rules for music processing
├── inference_code.py        # Inference logic for generating music
├── midi.py                  # MIDI file handling utilities
├── music_utils.py           # Additional music-related utilities
├── outputs.py               # Managing outputs and results
├── preprocess.py            # Preprocessing steps for musical data
├── qa.py                    # Quality assurance and validation scripts
├── test_utils.py            # Testing utilities for model validation
└── Improvise_a_Jazz_Solo_with_an_LSTM_Network_v4.ipynb  # Main notebook for the project
```


## Frameworks and Libraries
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.16.1-orange.svg?style=flat&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-3.3.3-red.svg?style=flat&logo=keras)
![Music21](https://img.shields.io/badge/Music21-v6.1-blue.svg?style=flat&logo=music21)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue.svg?style=flat&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-2.2.2-yellow.svg?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.6.2-green.svg?style=flat&logo=matplotlib)

## Project Architecture
1. **Data Preparation**:
   - The `preprocess.py` and `data_utils.py` files handle the preprocessing of musical data, including the conversion of MIDI files into a format suitable for training.

2. **Model Training**:
   - The `Improvise_a_Jazz_Solo_with_an_LSTM_Network_v4.ipynb` notebook contains the core LSTM model implementation. It builds upon existing deep learning frameworks to train the model on prepared data.
   - `generateTestCases.py` provides test cases to validate the training process.

3. **Music Generation**:
   - The trained LSTM model is used to generate new jazz solos. The `inference_code.py` file contains the logic for inference and music generation.
   - `midi.py` and `music_utils.py` are utilized to handle MIDI files and other music-related data processing tasks.

4. **Quality Assurance**:
   - `qa.py` and `test_utils.py` include scripts to validate the quality and correctness of the generated music.

5. **Output Management**:
   - The `outputs.py` file manages the results and outputs of the music generation process.

## Key Features
- **Deep Learning**: Utilise an LSTM network for music generation.
- **Sequence Modeling**: Handle time series data and sequences effectively.
- **Generative Models**: Create new jazz solos based on learned patterns.
- **Music Processing**: Use the Music21 library for musical data manipulation.

## Usage
**Clone the Repository:**
```bash
jupyter notebook Improvise_a_Jazz_Solo_with_an_LSTM_Network_v4.ipynb
```
**Install Dependencies:**
```bash
pip install -r requirements.txt
```
**Run the Jupyter Notebook:**
```bash
git clone https://github.com/yourusername/jazz-solo-lstm.git
```
## Implementation
The project involves the following steps:

- **Data Preparation:** Preparing musical data for training using existing utilities.
- **Model Training:** Building and training the LSTM network with my modifications.
- **Music Generation:** Generating new jazz solos using the trained model.

**Training Loss**
Below is the plot of the training loss, showing how the model improved over time:

<img src="images\image.png" style="width:400px;">

## Results
**Audio Samples**
Scan the QR Code and listen to the generated jazz solo:

<img src="output\frame.png" style="width:200px;">
