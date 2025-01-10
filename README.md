
Prerequisites
To run this project, ensure you have the following:

Python 3.7 or higher installed on your system.
Required Python libraries:
OpenCV for image and video processing.
NumPy for numerical operations.
A pre-trained face recognition model from Google Teachable Machine.
Installation Steps

Step 1: Train the Model Using Google Teachable Machine
Open your browser and visit the Google Teachable Machine website.
Click on Get Started to begin creating a new project.
Under the New Project section, select the Image Model option.
Choose the Standard Image Model setting.
Define the required classes (e.g., individual faces to recognize).
Upload images for each class using a webcam or from files stored in Google Drive.
Train the model and review the comparison percentages displayed for each class.

Step 2: Export and Download the Model
Once the training is complete, click on Export Model.
Navigate to the TensorFlow tab and select Download My Model.
A .zip file containing the following will be downloaded:
keras_model.h5 (the trained model file).
labels.txt (the file containing class labels).

Step 3: Set Up the Project Locally
Extract the contents of the downloaded .zip file.
Copy the keras_model.h5 and labels.txt files into the project directory.

Step 4: Add the Code
Open the project in an IDE such as PyCharm or another Python editor.
Paste the provided Python script into the editor.

Step 5: Install Required Libraries
Open the terminal in your IDE or system.
Run the following command to install the dependencies:
bash
Copy code
pip install opencv-python numpy mysql-connector-python tensorflow
Ensure that the Python and TensorFlow versions are compatible to avoid syntax errors.

Step 6: Run the Project
Execute the Python script in your IDE or terminal.
The system will:
Detect faces in real-time using the webcam.
Log attendance into a MySQL database with the recognized name and status.
Pro Tips
Double-check Python and TensorFlow versions to prevent compatibility issues.
Make sure the webcam is functional and configured correctly.
For better results, retrain the model by adding more image samples to each class.
This revised version improves clarity, readability, and professional formatting. Let me know if you'd like further edits!













