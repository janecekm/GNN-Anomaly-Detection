# GNN-Anomaly-Detection

This project is for Brock University's COSC 5P30 - Graph Data Mining course. It consists of a graph neural network (GNN) based anomaly detection approach for system call sequence data. Further details regarding the overall structure of the proposed methodology are described in the [report](https://github.com/janecekm/GNN-Anomaly-Detection/blob/main/Report.pdf).

## Running
All code is within [this notebook](https://github.com/janecekm/GNN-Anomaly-Detection/blob/main/Anomaly_Detection.ipynb), and should run earily with minor changes to the **Installs**, **Imports and Google Drive**, and **Parameters** cells. 

## Results
When tested using the [Australian Defence Force Academy - Linux Dataset (ADFA-LD) dataset](https://research.unsw.edu.au/projects/adfa-ids-datasets), this method achieves: 

* 63.472\% accuracy
* 61.254\% precision
* 73.324\% recall
