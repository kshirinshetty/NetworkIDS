# Intrusion Detection System (IDS) using Raw Sockets and Random Forest Classifier

## Overview

This project implements a Network Intrusion Detection System (NIDS) that captures network traffic using raw sockets and employs a Random Forest machine learning classifier to identify malicious activity. The system is trained on the "IoT Device Network Logs" dataset from Kaggle ([https://www.kaggle.com/datasets/speedwall10/iot-device-network-logs](https://www.kaggle.com/datasets/speedwall10/iot-device-network-logs)).

The goal of this project is to:

* Capture raw network packets directly from a network interface.
* Extract relevant features from the captured network traffic.
* Utilize a Random Forest classifier to distinguish between normal and malicious network behavior.
* Provide a basic alerting mechanism for detected intrusions.
