# HandSpeak-Bisindo
![Platform](https://img.shields.io/badge/platform-Android-green.svg)

HandSpeak is an application for interactively learning BISINDO sign language. 
We offer an interactive platform for studying BISINDO sign language with hand recognition via smartphone camera.
 
 
# Mobile Development
This repository contains code for a front-end mobile development project that utilizes several technologies. The technologies used in this project are as follows:

Figma: Figma is a cloud-based design and prototyping tool that allows collaborative interface design. It enables designers to create, share, and iterate on designs in real-time.
Kotlin: Kotlin is a modern programming language used for Android app development. It is fully interoperable with Java and provides a concise and expressive syntax.
Android Studio: Android Studio is the official integrated development environment (IDE) for Android app development. It provides tools and features for building, testing, and debugging Android applications.
Firebase: Firebase is a comprehensive development platform provided by Google. It offers a wide range of services, including authentication, real-time database, storage, cloud functions, and more, to help build mobile and web apps.
Retrofit: Retrofit is a type-safe HTTP client library for Android and Java. It simplifies the process of making network requests by handling the conversion of API responses to Java or Kotlin objects.
Intent Camera: Intent Camera is an Android API that allows developers to integrate the device's camera functionality into their applications. It enables capturing photos or videos and provides access to various camera features.
Installation
To set up and run the front-end mobile development project, follow these steps:

Clone this repository to your local machine.
Open Android Studio and import the project from the cloned repository.
Install any required dependencies and libraries specified in the project's build files or documentation.
Set up Firebase by creating a project on the Firebase console (https://console.firebase.google.com) and following the provided instructions. Make sure to enable the necessary services (e.g., Authentication, Firestore, Storage) based on the project requirements.
Connect the project to the Firebase project by adding the necessary configuration files (e.g., google-services.json) provided by Firebase to the project's app directory.
Open the project's source code files in Android Studio and ensure that the necessary dependencies (e.g., Retrofit) are properly configured in the project's Gradle files.
Build and run the project on an Android device or emulator using Android Studio.
Note: Make sure you have the required access and permissions to use the technologies mentioned above. You may need to sign up for developer accounts or obtain API keys for certain services.

Usage
Once the project is set up and running, you can use the mobile application to perform specific tasks or interact with the provided features. The exact functionality and usage instructions will depend on the specific requirements and implementation of the project. Refer to the code documentation, comments, or consult the project team for detailed information on how to effectively use the application.

License
This code is provided under the MIT License. Please refer to the LICENSE file in the repository for more information.

Acknowledgments
Figma
Kotlin
Android Studio
Firebase
Retrofit
Android Developer Documentation for Intent Camera





# Machine Learning
Using over 3000 images for our dataset from kaggle and combined with self-made dataset.
Using CNN to train the data set and generate .Json model using python.
Deploy our model using Tensorflow.js 

These are some resources that you can use to replicate our work

A. Dataset : https://drive.google.com/drive/folders/1znB9RNheIBSHRWsa-i2DjAsXKJMMGmLu?usp=drive_link
![messageImage_1686661168755](https://github.com/HandSpeak-Bisindo/ML/assets/119036482/20ce2c82-e81c-44a2-96b1-84c8495a9136)

B. Our CNN training code: [Train_Code_2.ipynb](https://github.com/HandSpeak-Bisindo/ML/blob/main/Train_Code_2.ipynb)
We used many techniques (Callbacks, Regularization, Dropout) to prevent overfitting and reached 87% accuracy, [our latest model](https://github.com/HandSpeak-Bisindo/ML/tree/main/model).

C. Python Deploy Code: [Deploy.py](https://github.com/HandSpeak-Bisindo/ML/blob/main/Deploy.py)


There are some false detection, and need further improvement for our projects.

# Cloud Computing
## HandSpeak Backend
This repository contains code that utilizes various technologies for a specific application. The technologies used in this code are as follows:

## Technologies Used
### -Node.js : 
Node.js is a JavaScript runtime that allows executing JavaScript code outside of a web browser. It provides a server-side environment for running JavaScript applications.
### -TensorFlow.js : 
TensorFlow.js is a JavaScript library for machine learning in the browser and on Node.js. It allows you to build and train machine learning models using JavaScript and perform predictions using TensorFlow.
### -JWT (JSON Web Tokens): 
JWT is a standard for securely transmitting information between parties as a JSON object. It is commonly used for authentication and authorization purposes in web applications. JWT consists of three parts: a header, a payload, and a signature.
### -Sequelize: 
Sequelize is a promise-based ORM (Object-Relational Mapping) library for Node.js. It provides an easy way to interact with relational databases by abstracting the underlying SQL queries.
### -Bcrypt : 
Bcrypt is a library used for password hashing. It provides a secure way to store user passwords by encrypting them using a hashing algorithm.
### -Google Cloud Storage : 
Google Cloud Storage is a scalable object storage service provided by Google Cloud Platform. It allows you to store and retrieve data in a highly available and durable manner.
### -Sharp : 
Sharp is a high-performance image processing library for Node.js. It provides features like resizing, cropping, and applying filters to images.
### -Jimp : 
Jimp is an image processing library for Node.js. It provides a simple and easy-to-use API for manipulating images, including resizing, cropping, and applying various effects.

## Installation
To run this code, make sure you have Node.js and npm (Node Package Manager) installed on your machine. Then, follow these steps:
1.Clone this repository to your local machine.<br>
2.Navigate to the project directory.<br>
3.Install the dependencies by running the following command:<br>
```shell
npm install
```
4.Configure the necessary credentials for Google Cloud Storage, if applicable.<br>
5.Run the application using the following command:<br>
```shell
npm run dev
```
Note: Make sure you have the required access and permissions to use the technologies mentioned above.

## Endpoint : https://capstone-project-c23-pc635.ts.r.appspot.com


## Usage
Once the application is running, you can use the provided features to perform specific tasks related to the application's functionality. Please refer to the code documentation or consult the project team for more information on how to use the application effectively.

## License
<p>This code is provided under the <a href="LICENSE">MIT License</a>.</p>

## Acknowledgments
<ul>
    <li><a href="https://nodejs.org/">Node.js</a></li>
    <li><a href="https://www.tensorflow.org/js">TensorFlow.js</a></li>
    <li><a href="https://www.npmjs.com/package/bcrypt">Bcrypt</a></li>
   <li><a href="https://cloud.google.com/storage">Google Cloud Storage</a></li>
    <li><a href="https://nodejs.org/api/child_process.html">Child Process</a></li>
    <li><a href="https://jwt.io/">JWT (JSON Web Tokens)</a></li>
    <li><a href="https://sequelize.org/">Sequelize</a></li>
    <li><a href="https://cloud.google.com/storage">Google Cloud Storage</a></li>
    <li><a href="https://www.npmjs.com/package/jimp">Jimp</a></li>
    <li><a href="https://www.npmjs.com/package/sharp">Sharp</a></li>



