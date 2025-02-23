#Network Security Model
This repository contains a machine learning model designed to detect network intrusions and enhance cybersecurity measures. The project utilizes the CICIDS2017 dataset to train and evaluate the model's performance in identifying various types of network attacks.

Table of Contents
Introduction
Dataset
Features
Model Architecture
Results
Usage
Contributing
License
Introduction
In the current digital landscape, network security is paramount. This project aims to develop a robust intrusion detection system (IDS) using machine learning techniques to identify and prevent malicious activities within a network.

Dataset
The model is trained and evaluated using the CICIDS2017 dataset, which offers a comprehensive set of network traffic data for security analysis. This dataset includes various features related to network traffic, such as packet lengths, flow durations, and protocol types, along with labels indicating different types of network intrusions.

Features
The dataset comprises numerous features extracted from network traffic, including but not limited to:

Src_Port: Source port number
Dst_Port: Destination port number
Protocol: Protocol used (e.g., TCP, UDP)
Flow_Duration: Duration of the flow
Tot_Fwd_Pkts: Total number of forward packets
Tot_Bwd_Pkts: Total number of backward packets
Flow_Byts/s: Flow bytes per second
Flow_Pkts/s: Flow packets per second
For a complete list of features, refer to the dataset documentation.

Model Architecture
The project explores various machine learning algorithms to identify the most effective model for intrusion detection:

Random Forest (RF): Implemented for its robustness, achieving an accuracy of 99.84%.
XGBoostCLASSIFIER : Implemented for its unquestionable preformance with an accuracy of 99.81%.
ANN model : for it's self learning and auto adaptation technique with MAE and MSE score 0.0150, 0.02328 resp.
The models were evaluated to determine the most accurate and interpretable approach for intrusion detection and anomaly recognition.

Results
The rrandom forest model demonstrated superior performance with an accuracy of 99%, making it the most effective model for this dataset.And created a output function to alert about attack
