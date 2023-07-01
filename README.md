# DiagnoSys - An All-in-One Medical Solution WebApp
DiagnoSys is a comprehensive web application that provides advanced detection and analysis for various health conditions. This project leverages state-of-the-art machine learning algorithms to detect and diagnose COVID-19, Alzheimer's disease, breast cancer, and pneumonia using X-ray and MRI datasets.
<br/>DiagnoSys aims to revolutionize the field of medical diagnosis by utilizing deep learning techniques and image analysis to assist healthcare professionals in accurately identifying and diagnosing these conditions. By providing a user-friendly web interface, DiagnoSys enables easy uploading and analysis of medical images for efficient and reliable results.
<br/>
<br/>
<br/>
## Preview
### Homepage
<img width="1280" alt="Screenshot 2023-07-01 at 4 29 28 PM" src="https://github.com/Karanchaudhary350/DiagnoSys/assets/78443850/609c4009-b01e-4f52-b811-91dfdb8ebe70">
<br/>

### Services
<img width="1280" alt="Screenshot 2023-07-01 at 4 29 38 PM" src="https://github.com/Karanchaudhary350/DiagnoSys/assets/78443850/0aef645c-7fc5-4587-bafe-32b431651469">

## Features

- **COVID-19 Detection:** DiagnoSys utilizes deep learning techniques to accurately detect COVID-19 from chest X-ray images. This feature can help healthcare professionals quickly identify potential COVID-19 cases and take appropriate measures.

- **Alzheimer's Disease Detection:** By analyzing MRI scans, DiagnoSys can assist in the early detection of Alzheimer's disease. The advanced algorithms can identify specific patterns and indicators associated with this neurodegenerative disorder, aiding in timely diagnosis.

- **Breast Cancer Detection:** DiagnoSys employs machine learning algorithms to analyze mammography images and identify signs of breast cancer. This feature can support radiologists and doctors in detecting breast cancer at its early stages, leading to more effective treatment options.

- **Pneumonia Detection:** Using X-ray images, DiagnoSys can accurately detect pneumonia in patients. This feature can help medical professionals promptly identify pneumonia cases, enabling faster treatment and improved patient outcomes.

- **User-Friendly Web Interface:** DiagnoSys provides a user-friendly web interface that allows healthcare professionals and researchers to easily upload and analyze medical images. The interface is designed to be intuitive, ensuring a seamless experience while interacting with the application.

## Installation

To set up DiagnoSys locally, follow the steps below:

1. Clone the repository:

```bash
git clone https://github.com/Karanchaudhary350/DiagnoSys
```
2. Create a conda environment and install the required libraries:

```bash
conda create -n DiagnoSys python=3.9
conda activate DiagnoSys 
pip install opencv-python numpy tensorflow scikit-learn imutils flask xgboost
```
3. simply run the following command in the terminal:
```bash
flask run
```

## Dataset
The datasets used for training and testing the machine learning models in DiagnoSys are not included in this repository. Please refer to the following sources to obtain the necessary datasets:

- COVID-19 Dataset: [https://drive.google.com/drive/u/0/folders/1x3pOyxLgvM0bl1YePWQRlgOLi87e9dF]
- Alzheimer's Disease Dataset: [https://www.kaggle.com/datasets/yasserhessein/dataset-alzheimer]
- Breast Cancer Dataset: [https://drive.google.com/file/d/1yVVtLvsWBJS9OxfXWq3D_OhKg-Du3ITi/view]
- Pneumonia Dataset: [https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images]
<br/>Ensure that you have the datasets downloaded and properly organized before running the application.

## Usage
- Launch the DiagnoSys web application by running python app.py.

- Open your preferred web browser and navigate to http://localhost:8000.

- Follow the on-screen instructions to upload the medical images for analysis.

- Once the analysis is complete, the application will provide the results indicating the presence or absence of COVID-19, Alzheimer's disease, breast cancer, or pneumonia based on the uploaded images.

## Contributions
Contributions to enhance and expand the capabilities of DiagnoSys are welcome. If you're interested in contributing, please follow our contribution guidelines.

## License
DiagnoSys is released under the MIT License. Feel free to use, modify, and distribute this project as permitted by the license.

## Disclaimer
DiagnoSys is an experimental project and should not be used as a substitute for professional medical advice or diagnosis. Always consult a qualified healthcare provider for accurate medical information and diagnosis.

## Contact
For any questions or feedback, please contact us at karanchaudhary2288@gmail.com.
