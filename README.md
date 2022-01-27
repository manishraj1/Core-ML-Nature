# Core-ML-Nature

The Nature app allows the user to upload an image and giving the task to the mobile application to predict that particular image which the user have uploaded its a fun playing application but this application involes a core-ml model in it called (GoogleNetPlaces)

<a><img src="https://user-images.githubusercontent.com/88855727/151354778-3f774e9c-18a4-4e35-93ea-d887bdaee7e8.PNG" width="230"></a>
<a><img src="https://user-images.githubusercontent.com/88855727/151354788-5a11fa88-720e-4bca-af8d-0a92ba5080b2.PNG" width="230"></a>
<a><img src="https://user-images.githubusercontent.com/88855727/151354790-596ccb18-68f0-41b7-84da-5b674c8a175e.PNG" width="230"></a>

# Core-ML Model GoogleNetPlaces General

- GoogleNetPlaces

Model Type Neural Network Classifier
Size 24.8 MB
Document Type Core ML Model
Availability iOS 11.0+ | macOS 10.13+ | tvOS 11.0+ | watchOS 4.0+

- Metadata

Description:
Detects the scene of an image from 205 categories such
as airport, bedroom, forest, coast etc.

Author:
B. Zhou, A. Lapedriza, J. Xiao, A. Torralba, and A. Oliva
License

Creative Common License: 
More information available at
http://places.csail.mit.edu

- Precision

Compute
Float16

Storage
Float32

# Core-ML Model GoogleNetPlaces Predictions

- Input

scenelmage: 
Image (Color 224 × 224)
Description: 
Input image of scene to be classified

- Output


sceneLabelProbs:
Dictionary (String - Double)
Description:
Probability of each scene

sceneLabel: 
String
Description: 
Most likely scene label

# Requirements

Built in
Xcode Version 13.2.1 (13C100)
Swift 5

# License

©CopyRight
Created by Manish raj(MR)

iOS Core-Ml Project
