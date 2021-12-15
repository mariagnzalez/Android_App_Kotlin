# Android_App_Kotlin

Related to the second part of the project, the connection by Bluetooth Low Energy (BLE) between the devices (scale and smart band) and the mobile app is needed, so this repository includes the code to implement the BLE connection, specifically the code for:

- Scanning BLE devices
- Establishing the connection with BLE devices
- Reading and writing data of characteristics and descriptors
- Requesting the Maximum Transmission Unit (MTU)

## Steps to run the code

After downloading Android Studio and Android File Transfer (the last one only if you use a MacOS computer) on the computer, you have to connect the phone to your computer using a USB cable and then follow the steps specified in the google drive report ("Material to create an Android app") so that Android Studio can make the installation of the app in the physical phone. Then you run the code and the app will be installed directly on the phone (it will take a few minutes).


The location while using the BLE actions is required, so an alert will appear on the first screen to allow the patient to be located as well as another alert to turn on the Bluetooth of the phone if it was turned off. The next screen is a button that scans BLE devices nearby. After pressing the button, "MI SCALE 2" has to appear, which is our test scale, and if pressed it will make the connection and be ready to read and write data of features and descriptors. 

The app is configured to request the MTU which has a minimum (23) and a maximum (512). The app will reply with a message if it is possible to read and write or not. 

## Next Steps

Remove the MTU request that is not needed for the project and find a way to get the weight and the other vital measures of the patient.

## Contributors

Example code taken from Punch Through (https://github.com/PunchThrough/ble-starter-android).

Adaption made by María González García and Marina Castrillo Fernández.






