# Project Details

This application can detect and categorize 6 diseases — Malaria using cell images, Brain Tumor detection using MRI scans, Pneumonia using chest X-ray images, Retinal diseases using Optical Coherence Tomography images, Nonproliferative Diabetes Retinopathy disease and Invasive Ductal Carcinoma using breast cancer histopathology images. All the models are trained on the publicly available datasets from Kaggle.

Huge thanks to [Saugata Paul](https://github.com/saugatapaul1010/Medical-AI-Android) for his wonderful repo.



# Future Improvements


1) Update the application IP addresses by settip up Google cloud or Amazon Ec2 instance to make it available online to all.Currently this project could be set up locally on the localhost as i ran out of free tiers in amazon and google cloud accounts. 

2) Later making a android application apk file to see the application in the phone as well

### Setting up the Project

1. Clone the repo
   ```sh
   git clone https://github.com/krishnakaushik25/DL-models-medical.git
   ```
2. We need to navigate to the working directory and Install pip(python) packages.You can see the file requirements.txt file present inside this directory.
   ```
   cd Medical-AI-Android/WebApp
   pip install -r requirements.txt
   ```
3. Now wait for all the packages to get installed. Once this step is done, we need to run our application
    ```py
   python core_app.py
   ```
