
# Brain Hemorrhage Detection System
## Table of Contents
1. [Description](#description)
2. [Folder Structure](#folderstructure)
3. [Dependencies](#dependencies)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Screenshots](#screenshots)

## Description
The Brain Hemorrhage Detection System is a web-based application designed to classify computed tomography (CT) images of brain hemorrhages. It provides a user-friendly interface for interacting with the system.
It utilizes convolutional neural networks (CNNs) for feature extraction and classification, along with additional methods to analyze CT images and classify them based on the presence of hemorrhage.

## FolderStructure
- **Dataset**: Contains CT scan images.
- **Static**: Contains CSS, JavaScript, and other static files.
- **Templates**: Contains HTML files.
- **Model**: Contains the model files used in the notebook. These models were trained on the provided dataset to perform specific tasks related to brain hemorrhage detection.
- **app.py**: The `app.py` file serves as the main entry point for the web application. It contains the code responsible for handling HTTP requests, routing, and rendering web pages

### app.py

Below is a brief overview of its functionality:

- **Web Application Setup**: Initializes the Flask application and configures routes.

- **Routes**: Defines routes for different pages and endpoints of the web application.

- **Request Handling**: Handles incoming HTTP requests and performs necessary actions, such as loading models, processing data, and rendering templates.

- **Model Integration**: Incorporates trained models (stored in the `Model` folder) to perform predictions or other tasks related to brain hemorrhage detection.

- **Template Rendering**: Renders HTML templates stored in the `Templates` folder to display web pages to users.

- **Static File Serving**: Serves static files (e.g., CSS, JavaScript) stored in the `Static` folder to enhance the user interface.





## Dependencies

To run this project, you'll need the following external libraries or dependencies:

- **TensorFlow**: TensorFlow is an open-source machine learning framework developed by Google. It is used for building and training neural network models. Install TensorFlow using pip:

  ```bash
  pip install tensorflow

- **OpenCV**: OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. It provides various functions for image and video processing. Install OpenCV using pip:

    ```bash
    pip install opencv-python

- **Pillow**: Pillow is a Python Imaging Library (PIL) fork. It adds image processing capabilities to Python, including reading and writing various image file formats. Install Pillow using pip:
    ```bash
    pip install pillow

## Installation


1. **Clone the Project**: If you have access to the project files, you can clone the project repository to your local machine using Git or download the project folder directly.

2. **Navigate to the Project Directory**: Open your command line interface (CLI) or terminal and navigate to the directory where you have saved the project folder.

3. **Install Dependencies**: Before running the project, make sure you have installed all the required dependencies. Refer to the "Dependencies" section in this README file for a list of dependencies and installation instructions.

4. **Run the Project**: Once the dependencies are installed, you can run the project by executing the main Python file (`app.py`) using Python. For example:

    ```bash
    python app.py
    ```

5. **Access the Application**: After the project is running, you can access the application by opening a web browser and navigating to the specified URL or port where the application is hosted.

6. **Usage Instructions**: If the project has any specific usage instructions or configuration settings, they will be provided in the "Usage" section of this README file.

By following these steps, you should be able to install and set up the project on your local machine.

## Usage

### Sign In or Sign Up

1. **Home Page**: Initially, when you access the application, you will be presented with the home page, where you can choose to sign in if you already have an account or sign up to create a new account. 

   - If you already have an account, you can proceed to sign in using your credentials.
   
   - If you don't have an account, you can register yourself by providing the necessary details.

### Upload CT Scan Image

2. **Index Page**: After successfully signing in, you will be directed to the index page. Here, you will have the option to upload a CT scan image.

   - Click on the upload button to select the CT scan image from your local machine.

   - Once the image is selected, click on the submit button to proceed.

### View Result

3. **Result Page**: After submitting the CT scan image, the application will process the image to determine the presence or absence of brain hemorrhage.

   - The result will be displayed on the result page, indicating whether brain hemorrhage is present or absent based on the analysis of the uploaded image.

### Logout

4. **Logout**: After completing the above actions or when you want to end your session, you can logout from the application.

   - Click on the logout button to log out from your account and securely end your session.

By following these steps, you can effectively use the application to upload CT scan images, analyze them for brain hemorrhage, view the results, and manage your session by signing in or out as needed.

## Screenshots

Below are screenshots of the project to provide visual context for users:

1. Home Page - ![home](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/00b73237-7f8a-4f98-8315-63a916dedf6b)

2. Sign Up Page - ![signup](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/86803658-d647-4b22-999c-fce48f9cec15)

3. Sign In Page - ![signin](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/8fb9c39d-374d-4467-bcdb-fb1aaf2a7b32)

4. Index Page - ![index](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/d838397b-9604-4047-a6bb-82023529bc07)
 ![upload](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/5ddebe8b-ec3d-4a33-b63f-873e578ce27d)
![uploading](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/748ed1e8-eb45-4667-b8a8-47352307c9cc)


6. Result Page - ![detected](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/e732e164-32be-431d-93ac-3120df5b6cf7)
![result](https://github.com/Pujitha-kothapalli/Brain-Hemorrhage-detection/assets/99169462/f7200a8a-dd01-463e-82aa-9dc32aa8e274)

