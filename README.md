
# Detection of DDoS Attack

## Introduction

This project is designed to analyze network traffic data with the aim of detecting Distributed Denial of Service (DDoS) attacks. The repository contains a Jupyter Notebook that demonstrates how to process a dataset containing network statistics, extract important features, and identify potential instances of flooding attacks. The notebook uses Python along with libraries such as pandas and numpy to load and analyze data, making it suitable for both research and educational purposes. The analysis includes loading a CSV file containing network statistics and applying methods to recognize anomalies that may indicate a DDoS attack, as seen in the provided notebook examples fileciteturn0file4.

## Features

- **Data-Driven Analysis:** Processes CSV datasets (e.g. FloodingAttack.csv) containing various network metrics like packets, bytes, and duration.
- **DDoS Detection:** Focused on identifying suspicious network traffic patterns that indicate flooding attacks (DDoS).
- **Interactive Notebook:** Uses a Jupyter Notebook environment (or Google Colab) to present a step-by-step analysis, including data loading, inspection, and visualization.

## Requirements

To run this project, ensure you have the following:
- **Python 3:** Version 3.6 or later is recommended.
- **Jupyter Notebook or Google Colab:** The main analysis is performed in a notebook format.
- **Python Libraries:**
  - **pandas:** For data manipulation and CSV file handling.
  - **numpy:** For numerical operations.
- **CSV Dataset:** A file named `FloodingAttack.csv` is used to demonstrate network traffic analysis. The notebook assumes this file is available (for example, mounted via Google Drive as shown in the code fileciteturn0file4).

## Usage

1. **Open the Notebook:**
   - Launch the Jupyter Notebook `DDos Flooding attack.ipynb` from the repository. This notebook walks you through the steps to import necessary libraries, mount your Google Drive (if using Colab), and load the CSV dataset.
   
2. **Mounting your Storage (if applicable):**
   - When using Google Colab, use the provided code to mount your Google Drive so that the dataset can be accessed. For example:
     ```
     from google.colab import drive
     drive.mount('/content/drive')
     ```
     This step ensures that the notebook can load the `FloodingAttack.csv` file from your drive fileciteturn0file4.

3. **Running the Analysis:**
   - Execute the code cells sequentially. The notebook starts with basic data import using pandas and then displays the dimensions of the dataset and a preview of the data.
   - The subsequent analysis includes extracting specific network features (e.g., protocol, source/destination IP, ports) and computing statistical summaries that are useful for detecting DDoS patterns.

4. **Interpreting the Results:**
   - Upon running the cells, you will see outputs indicating the presence of malicious traffic. The notebook includes sample output tables that list details such as packet counts and states, which allow you to quickly identify potential DDoS incidents.

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository:**
   - Open your terminal or command prompt and run:
     ```
     git clone https://github.com/tdsrusti/Detection-of-DDoS-attack.git
     ```
2. **Create a Virtual Environment (Optional but Recommended):**
   - For example, use the following commands:
     ```
     python -m venv venv
     source venv/bin/activate  # On Windows use venv\Scripts\activate
     ```
3. **Install Dependencies:**
   - Install the required Python libraries using pip:
     ```
     pip install pandas numpy
     ```
4. **Launch the Notebook:**
   - Navigate to the repository folder and start Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - Open the `DDos Flooding attack.ipynb` file.
5. **Set Up and Run:**
   - Follow the usage instructions within the notebook to mount your drive (if applicable) and load the necessary CSV file for analysis.
