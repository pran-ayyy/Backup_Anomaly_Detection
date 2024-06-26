# Backup Anomaly Detection

This project leverages machine learning (ML) anomaly detection techniques to identify anomalous data backups based on various attributes such as network throughput, size of the backup, number of files, and more.

## Project Structure

The project consists of the following files:

- `data.py`: Contains code to preprocess and load the data used for training and detecting anomalies.
- `model.pkl`: A pre-trained machine learning model used for anomaly detection.
- `train.py`: Includes code to train the machine learning model.
- `output.py`: Generates and displays the anomaly detection results.

## Project Details

### Attributes Used for Anomaly Detection

- **Network Throughput**: The amount of data transferred over the network during the backup.
- **Size of the Backup**: The total size of the backup.
- **Number of Files**: The total number of files included in the backup.

### Machine Learning Techniques

The project utilizes the following ML anomaly detection techniques:

- **Isolation Forest**
- **DBSCAN**
- **Local Outlier Factor (LOF)**

These techniques help identify unusual patterns in the backup data that may indicate potential issues or irregularities.

## Contribution

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request or open an issue.
