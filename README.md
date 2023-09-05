```md
> ⚠ Disclaimer: This application is meant for educational purposes only and should not be used in a real-world context.
```

## Contents:

1. [Background](#background)
2. [Problem definition](#problem)
   1. [CT scan radiation](#ctscan)
   2. [Cost and time effective](#cost)
   3. [Accessibility](#accessibility)
3. [Functionalities](#functionalities)
   1. [Web application](#webapp)
   2. [CNN](#cnn)
   3. [Prediction of COVID-19 results](#results)
   4. [Probability](#probability)
   5. [Patient database](#db)
4. [Architecture](#architecture)
5. [Links](#links)
6. [Team](#team)

<div class="m-3" id="background">
    <br />
    <h2>📚 Background:</h2>
</div>

The global outbreak of the coronavirus has instilled fear in people worldwide. As daily infection rates continue to rise, it becomes imperative to develop a swift method for virus detection, allowing for more time to administer treatment. One effective means of diagnosing both pneumonia and COVID-19 is through the analysis of Chest X-rays (CXR), particularly as CT scans can be cost-prohibitive. Nevertheless, sifting through numerous CXR images can be a time-consuming and challenging task.

In response to this challenge, this research study harnesses Convolutional Neural Networks (CNNs) to automate the identification of Pneumonia and COVID-19 in CXR images provided by users, whether they are patients or healthcare professionals. Breathe.ai accepts a CXR image as input and swiftly categorizes it into one of three classes: COVID-19, pneumonia, or normal. To implement Breathe.ai, a Deep CNN is employed.

The training data for the model comprises CXRs from patients with COVID-19 and pneumonia, as well as those from individuals with normal health. Data augmentation techniques are applied to enhance training efficiency and mitigate overfitting. Notably, the model is rigorously trained and tested, with a particular emphasis on minimizing false negatives, which are deemed unacceptable in this context.

Furthermore, a comprehensive patient database will be maintained, housing each patient's historical health records, which can be readily accessed by healthcare providers.

<div class="m-3" id="problem">
    <br />
    <h2>🎯 Problem definition:</h2>
</div>

<div class="m-3" id="ctscan">
    <br />
    <h4>1. CT scan radiation:</h4>
</div>

CT scans are an effective method used to detect COVID, but it increases the risk of exposing patients to high levels of radiation. This method has been under scrutiny since it exposes patients to a very high level of radiation known to increase the probability of cancer. As quoted by the AIIMS Director, one CT Scan is equivalent to around 300-400 Chest X-rays.

Hence, in this report, we will be using a deep learning approach to predict COVID 19 results from Chest X-ray images avoiding the effects of radiation. RespAI takes a CXR image as input and classifies it into three classes: Covid 19, pneumonia and normal, within a short period of time.

<div class="m-3" id="cost">
    <br />
    <h4>2. Cost and Time effective:</h4>
</div>

Along with the risk of radiation, CT scans are also expensive and might not be affordable for certain patients. In a few cases, the results take a few hours or days to be produced. Due to this limitation, it is not available for everyone to use it. Getting a quick result might be difficult and costly.
In this model, instead of CT scans we will be using Chest X-Ray images which are more cost effective, thus making it more usable. Once a Chest X-ray is obtained, it is a simple procedure to obtain the result using Breathe.ai within a few minutes.

<div class="m-3" id="accessibility">
    <br />
    <h4>3. Accessibility:</h4>
</div>

COVID 19 tests are usually built in a way so as to be used in clinical settings at home and need elaborate arrangements and equipment. Some countries lack these requirements and this delays the production of results, affecting many patients’ health.
Breathe.ai is a web app which is platform independent and accessible as it can be used anywhere, anytime. The application is linked with the patient’s history so as to aid the doctors in analysing his/her condition. Because of its flexibility, anyone can use it by simply uploading CXR images and getting the required results.

<div class="m-3" id="functionalities">
    <br />
    <h2>✅ Functionalities:</h2>
</div>

<div class="m-3" id="webapp">
    <br />
    <h4>1. Web application:</h4>
</div>

Breathe.ai will be a web application with very convenient and accessible features. One main functionality is being able to upload CXR images for results. Using html, css javascript for frontend and python for backend, this functionality has been made such that uploading X ray images and displaying the results is done in a short period of time.

<div class="m-3" id="cnn">
    <br />
    <h4>2. CNN (Convolutional Neural Network):</h4>
</div>

This project involves creation of a Deep learning based Convolutional Neural Network (CNN) using Keras (python library) and integrating the model with a front-end user interface for ease of use. This leads up to the creation of a software which we have named as Breathe.ai. It uses the sequential Keras model which is built layer by layer, which then gives the final output. The proposed approach gives a classification accuracy of 99%.

<div class="m-3" id="results">
    <br />
    <h4>3. Prediction of COVID-19 results:</h4>
</div>

After implementing the CNN approach on the CXR images provided, all the layers are trained independently to make independent predictions which are then combined to give the final output. The model is built such that the positive or negative covid results are displayed on the screen in a few minutes.

<div class="m-3" id="probability">
    <br />
    <h4>4. Probability:</h4>
</div>

It includes the probability of the result. Depending on the images, this model also gives a probability result to determine the surety of it. This information helps the radiologist/doctor to make a clinical decision.

<div class="m-3" id="db">
    <br />
    <h4>5. Patient database:</h4>
</div>

This application also includes a complete database of the patient which contains the patient's details history. This aids the doctors in inspecting the patient’s condition depending on their history, thus taking necessary precautions.

<div class="m-3" id="architecture">
    <br />
    <h2>🏙 Architecture:</h2>
</div>

<div align='center'>
<img width="913" alt="Screenshot 2022-11-07 at 10 36 05 PM" src="https://user-images.githubusercontent.com/73516876/200371209-b103d183-532c-485b-a4fa-efa6ad8b51c4.png">
</div>

<div class="m-3" id="links">
    <br />
    <h2>🚀 Links:</h2>
</div>



<div class="m-3" id="team">
    <br />
    <h2>🌏 Team:</h2>
</div>

- A Nilavan
- TM Vishnu Mukundan
