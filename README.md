# PhosphorCV

## Welcome
This is PhosphorCV, a machine learning library for First Tech Challenge teams.
PhosphorCV uses the [TensorFlow](https://www.tensorflow.org/) ml platform and integrates
it into capabilities for FTC robot.

### Machine Learning Abilities
- Supervised learning object detection neural network that requires no determination
algorithims, leading to simple reuse for every game.
- Cache & boundary box machine learning odometer algorithim using static in game objects.

#### Versatile Object Detection
- Object detection that is changed by updating a single photo. Based off of a Cornell reinforcement learning algorithim, only a single upload is needed per classification. Using a YOLO tool, the browser program shows the real time prediction on if your object matches one of the image classes (currently at 3 different class options due to the fact that there are 3 different randomizaton for every FTC game). So far, the machine learning model is in the browser and does not need training.
![Prediction A Test](https://github.com/AlessioToniolo/PhosphorCV/blob/main/predictiona.PNG)
![Prediction B Test](https://github.com/AlessioToniolo/PhosphorCV/blob/main/predictiona.PNG) 
![Prediction C Test](https://github.com/AlessioToniolo/PhosphorCV/blob/main/predictiona.PNG)  

## Getting Started
**Rest Coming Soon!**
* FOR BROWSER
** Open up index.html on a server (personal computer server recommended (to access, double click on the index.html file and it should appear in your default browser))
** Allow access to your camera
** Face your camera towards whatever object/picture you want as an image classifier and click the class button for each image
** You should see a prediction! Apply this algorithim to your teamcode using the external webcam class or phone cam class and your done!

## Contributing
To contribute to PhosphorCV, create a pull request by forking this repository and
creating a new branch, instantiate an issue, or join our Discord server!
* https://discord.gg/FtVDSW