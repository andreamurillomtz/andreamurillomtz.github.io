---
layout: project
type: project
image: img/tinyML/tinyMLLogo.jpg
title: "TinyML Keyword Spotting Model deployed onto Arduino Nano"
date: "Jan. 2024 – May 2024"
published: true
labels:
  - Machine Learning
  - Python
  - Tensor Flow
  - Tensor Flow Lite
  - Google Colab
  - Edge Impulse
  - Arduino Nano Microcontroller
summary: "nck"
---
**Summary**   
Implemented machine learning models on resource-constrained platforms such as Arduino Nano 33 microcontrollers, utilizing TensorFlow and TensorFlow Lite for model development. Leveraged Google
Colab for training and optimization processes.      
<img width="200px" src="../img/tinyML/arduinoNano.png" class="img-thumbnail" >   

**Description**   
Develop an end-to-end (E2E) KWS application with Edge Impulse to voice control a light-emitting diode (LED) that emits a colored light (red, green, or blue) a certain amount of times (one, two, or three blinks) on the Arduino Nano.   

Began with dataset preparation, acquiring audio data with a mobile phone and the built-in microphone on the Arduino Nano. Then, we designed a model for speech recognition based on the popular Mel-filterbank energy (MFE) features. Ectracted these features from audio samples, train a machine learning (ML) model, and fine-tune model’s performance with the Edge Impulse EON Tuner. Finally, deployed the KWS application on the Arduino Nano.   

Firmware runs on the microcontroller while the daemon runs on your computer as shown:   
<img width="600px" src="../img/tinyML/tinyMLProcess.png" class="img-thumbnail" >   

**Steps**   
1. Acquiring audio data with a smartphone   
2. Acquiring audio data with the Arduino Nano   
3. Extracting MFE features from audio samples   
4. Designing and training a convolutional neural network (CNN)   
5. Tuning model performance with the EON Tuner   
6. Live classifications with a smartphone   
7. Keyword spotting on the Arduino Nano   

**Demo**   
<div class="text-center p-4">
  <iframe 
    src="https://youtube.com/shorts/W4ZFZW9YG8c?feature=share" 
    width="560" 
    height="315" 
    frameborder="0" 
    allow="autoplay; encrypted-media; picture-in-picture" 
    allowfullscreen>
  </iframe>
</div>
