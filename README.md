#MobileFirst Platform - PI Device Registration 
The purpose of this app is to show implementation PI SDK (device registration) for IOS(swift). This app demonstrates register/unregister with encrypted and unencrypted Data. At the start of the app, it will check to see if the device is already registered.


##Instructions
You can use IOS device or XCode simulator to run this app.

* Open PIDeviceRegistration.xcodeproj
* Edit the file ViewController.swift
	- change the bluemix credentials/information
		- tenantID, orgID, username and password (all this information can be found in your Presence Insights Dashboard)

* Click the play button to build and run


##Quick Walkthrough
ViewController.swift is a great way to see how objects were initialized and implemented. The app will do an initial check to see if the device is already registered. If the device is registered, it will alert the user and fill the Device name and type.

On the sample app, There are 5 text fields, 1 selection, switch, and update button.

* Device Name - Text Field
	- Type in the name you want to register the device as.
* Device Type - Selection
	- It grabs the device types so the user can select instead of having them type.
* Encrypted Data Key - Text Field
	- Encrypted Device Key value
* Encrypted Data Value - Text Field
	- Encrypted Device Data value
* Unencrypted Data Key - Text Field
    - Unencrypted Device Key value
* Unencrypted Data Value - Text Field
    - Unencrypted Device Data value
	
*note:* If Key or Value is empty, it will throw an error. Will pass if both exist or empty.

* UI Switch
	- When the switch is on, it registers the device.
	- When the switch is off, it unregsiters the device. 
* Update
	- will check if the switch is on (regsitered)
	- If the switch is on, it updates the device.


	
	
	
	
	
	


Copyright 2015 IBM Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.





