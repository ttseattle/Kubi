#KubiDemo

##Overview
This application integrates components of voice recognition into a tablet robot face. It must be connected to the internet to work.

##Instructions
1. Clone this project by running: git clone https://github.com/elimenta/KubiDemo.git
2. Read the requirements section to install any additional libraries that may be required
3. After everything is set up, connect to an Android device that supports Bluetooth 4.0, and run the project to install it
4. To start using the app, open it and click the options menu to connect to the nearest kubi device. Make sure the device is also connected to the internet for the chat server features to work properly.
5. To give voice actions, open the options menu and click the 'Listen' button. Say something and a response will be given.
6. Note that some voice commands may cause the Kubi to perform gestures.

##Requirements
The following are some publicly-available libraries that have been integrated into this demo:
This code requires that the android SDK has been installed.

1. OpenCV Library (instructions for installation are [here](http://docs.opencv.org/doc/tutorials/introduction/android_binary_package/O4A_SDK.html#o4a-sdk))
2. TTSLib, VPALib, XMLLib (available for download [here](https://github.com/zoraidacallejas/sandra/tree/master/Libs)), Note that these libraries are required to enable the chatbot service (pandorabot). 
3. After download make sure to check the project properties in eclipse to ensure that the Project Build Target has the Google APIs/ Android APIs checked for all the libraries used.
