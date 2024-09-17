# EasiScriptX 
### ☆_(coming soon)_☆

## Introduction

**_E_**asi**_S_**cript**_X_**  a high level programming language designed and devloped in [C++](https://en.m.wikipedia.org/wiki/C%2B%2B) specifically for [Artifical Intelligence](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://en.wikipedia.org/wiki/Artificial_intelligence&ved=2ahUKEwiTurPdtsWIAxV93TQHHcvUHtQQFnoECC4QAQ&usg=AOvVaw0svSWXI233PfYA4MrKZd4I) (**AI**), [Machine Learning](https://en.m.wikipedia.org/wiki/Machine_learning) (**ML**), [Deep Learning](https://en.m.wikipedia.org/wiki/Deep_learning) and [Large Language Models](https://en.m.wikipedia.org/wiki/Large_language_model) (**LLM**s). It supports _both_ **Object-Oriented** and **Functional Programming** paradigms, making it adaptable and easy to use. While being powerful and flexible, _**ESX**_ remains user-friendly for developers at all levels. Also, it is one of the _**First dedicated programming language for artifical Intelligence**_

## Key Features:
- **AI and ML**: Over 100 built-in commands/functions specifically tailored for building AI and ML projects, LLM training, and Deep Learning models.
- **IoT Integration (_available shortly after ESX inital release_)**: Special functions to work with IoT devices like Raspberry Pi and Arduino, making it a great choice for AI-IoT projects (e.g., creating smart assistants, autonomous robotics).
- **Complete Backward Compatibility**: ESX inherits all 150 commands from [EasiScript](https://github.com/PulewaveSoftware/EasiScript).
- **Planned Extensions**: Audio output features are in the roadmap for future updates.
- **Advanced Networking**: Commands to handle distributed computing and data across networks.

## Example Use Case: AI-IoT Integration
You could build a smart home system using Raspberry Pi, where you train an AI model to recognize objects using a camera module and control IoT devices like lights or locks based on real-time AI inferences.

## Supported Commands
ESX has all 150 commands from EasiScript, along with additional commands specific to AI, ML, LLMs, and IoT. Below is the current list of commands with brief descriptions.

### Core AI and ML Commands

- **TRAIN_MODEL**: Trains a machine learning model using a specified dataset.
  ```
  TRAIN_MODEL dataset.csv model.h5
 '''
### EVAL_MODEL: Evaluates the performance of a trained model using validation data.

```
EVAL_MODEL model.h5 val_data.csv
```
### LOAD_MODEL: Loads a pre-trained model for inference or further training.

```
LOAD_MODEL model.h5
```

### PREDICT: Makes a prediction based on input data using a pre-trained model.
```
PREDICT model.h5 input_data.csv
```
### TUNE_MODEL: Fine-tunes a pre-trained model with new data.
```
TUNE_MODEL model.h5 new_data.csv
```
### CREATE_LAYER: Creates a neural network layer for custom model architecture.
```
CREATE_LAYER type=Dense units=128 activation=relu
```
### ADD_LAYER: Adds a layer to an existing model architecture.
```
ADD_LAYER model.h5 layer=Conv2D filters=32 kernel_size=3x3
```
### SAVE_MODEL: Saves the current model state to a file.
```
SAVE_MODEL model.h5
```

# Data Processing Commands

- **LOAD_DATA**: Loads a dataset from a file for processing.
```
  LOAD_DATA dataset.csv
```
- **NORMALIZE_DATA** : Normalizes the input data.
```
NORMALIZE_DATA dataset.csv
```
- **SPLIT_DATA**: Splits the dataset into training and testing sets.
```
SPLIT_DATA dataset.csv test_size=0.2
```
- ** TRANSFORM_DATA**: Transforms data using specified functions.
```
TRANSFORM_DATA dataset.csv function=log
```

# IoT and Networking commands
- **CONNECT_IOT_DEVICE**: Connects to an IoT device (e.g., Raspberry Pi, Arduino).
```
  CONNECT_IOT_DEVICE device_id="RaspberryPi4"
```
- **SEND_IOT_COMMAND**: Sends a command to an IoT device.
```
  SEND_IOT_COMMAND device_id="ArduinoUno" command="LED_ON"
```
- **RECEIVE_IOT_DATA**: Receives data from a connected IoT device.
```
RECEIVE_IOT_DATA device_id="RaspberryPi4"
```
- **CONNECT_TO_NETWORK**: Connects to a network for distributed computing.
```
CONNECT_TO_NETWORK network_id="AI_Cluster"
```
- **SEND_DATA**: Sends data to another machine or device on the network.
```
SEND_DATA network_id="AI_Cluster" data="sensor_readings.csv"
```
- **RECEIVE_DATA**: Receives data from another machine or device.
```
RECEIVE_DATA network_id="AI_Cluster"
```
 # Advanced AI and ML Commands

- **CREATE_LLM**: Creates a new Large Language Model architecture.
```
  CREATE_LLM type=Transformer layers=12 hidden
```
- **TRAIN_LLM** : Trains a new Large Language Model with a dataset.
```
TRAIN_LLM llm_model.h5 dataset.txt epochs=10
```
- **GENERATE_TEXT**: Generates text from a pre-trained LLM.
```
GENERATE_TEXT llm_model.h5 prompt="Hello, world!"
```
- **FINE_TUNE_LLM**: Fine-tunes a pre-trained LLM with new text data.
```
FINE_TUNE_LLM llm_model.h5 new_data.txt
```

- **Data Visualization** Commands

- **PLOT_DATA**: Plots the dataset as a graph for visualization.
```
  PLOT_DATA dataset.csv x=feature1 y=feature2
```
- **SHOW_GRAPH**: Displays the current model's accuracy/loss graph.
```
SHOW_GRAPH model.h5
```

 # Utility Commands

- **SAVE_LOG**: Saves the session log to a file.
```
  SAVE_LOG file_name="session_log.txt"
```

- **LOAD_CONFIG**: Loads a configuration file for the session.
```
LOAD_CONFIG config_file="config.json"
```
- **DEBUG**: Enables or disables debug mode for detailed logs.
```
DEBUG mode=on
```
## Planned Features:

- Audio Output Support: Planned for future releases.

- Enhanced IoT Commands: Additional commands for robotics and automation projects.

 # How to Use (after release)

- 1. Clone the repository (in command prompt):
```
git clone https://github.com/PulsewaveSoftware/EasiScriptX.git
```

- 2. Explore the examples/ folder for project examples.


- 3. Start coding in ESX to build powerful AI and ML models, and integrate them with IoT devices.
