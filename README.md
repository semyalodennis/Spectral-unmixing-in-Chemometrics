# Spectral-unmixing-in-Chemometrics
This repo provides an introduction, and hands-on practice in python for spectral unmixing in chemometrics.

# Main files in the repo   
Spectral unmixing workshop 20241205.pdf  
-> This file provides a detailed introdution to spectral unmixing in chemometrics  

Spectral_unmixing_workshop-1.ipynb  
-> This script demonstrates spectral  unmixing with a simulated hyperspectral imaging (HSI) dataset  

Spectral_unmixing_workshop-2.ipynb  
-> This script demonstrates spectral unmixing with a custom dataset

emulsion_imageM.csv
-> The oil emulsion dataset used in the demo

# How to execute the scipts in the repo  
Setup and installations
1. Python version
python >= 3.4
• Tested with 3.12

2. Install pyMCR python library
Using pip
# Only Python 3.* installed
pip install pyMCR

# If you have both Python 2.* and 3.* you may need
pip3 install pyMCR

3. Install additional libraries (Dependencies)
numpy
• pip install numpy

scipy
• pip install scipy

matplotlib
• pip install matplotlib

6. Verify Installation
import pymcr

print(pymcr.__version__)

