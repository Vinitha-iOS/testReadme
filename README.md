# iOS Application Stageflo

![Logo](./Logo/logo.png)   

![Platform](https://img.shields.io/badge/platforms-iOS-lightgrey)
![Xcode](https://img.shields.io/badge/Xcode-13.0%2B-yellowgreen)
![Swift](https://img.shields.io/badge/Language-SWIFT%205-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

This Project is mainly used to create a band or join the band. you can search the sound engineer and request them and saved them for furture purpose.

This directory contains the full implementation of Stageflo application for iOS platform. This app is created and layout it programmatically, and get everything done with Storyboard. Additionally, It also provides a way to cooperate with UIScrollView.

# Requirements

iOS 12.4+

Xcode 13.0+

Swift  5

# Installation


The preferred way of installing stageflo is Clone this repository and import into the Xcode.

1. open terminal and select the preferred Locations for the app 
2. use the clone command below:

```swift

git clone https://github.com/SelfInnovations/stageflo_ios_app.git

```
The files contained here:
You can use this as a starting point to create new apps from scratch.


# Configuration


## API Setup:
Update ```Stageflo/Stageflo/Supporting files/Constants.swift``` with the following info:

```swift
SERVER_BASE_URL = "Contact support team to get APP-BASE-URL"
PRIVACY_URL = "Contact support team to get PRIVACY_URL"
TERMS_AND_CONDITIONS_URL = "Contact support team to get ABOUTUS_URL"

```


## Update ```Stageflo/Stageflo/GoogleService-Info.plist```

Generate the GoogleService-Info.plist from Firebase Console to enable O-Auth, Crashlytics, Google Sigin and Push Notifications.

After Generating the GoogleService-Info.plist, Replace the GoogleService-Info.plist with new one.

## Update ```Stageflo/Stageflo/info.plist``` 

Update the URL types with the Following info:

URL Types - "Reverse Client Id in GoogleService-info.plist" with the  GoogleService-Info.plist Reverse Client-id.


# Usage

You could directly clone and open in the xcode. 
Select the scheme as "Stageflo" and Choose the device and run on the xcode.


# Generating the ipa

 Step 1: In .entitlements file, Enter the APS Environment as "development" for development ipa or Enter the APS Environment as "production" for Production ipa.
 
 Step 2: Choose "Any iOS devices" in scheme.

 Step 3: Choose Product->Archive to generate the ipa in organizer.

 Step 4: Choose Distribute App.

 Step 5: Upload the app to AppStore.

# UI Customization

We tried to keep things as native as possible, so this is done mostly through native Apis. 

App theme - we use the Default app theme only. so you no need to import any font classes seperately.

We Implemented all the Features you need through the Storyboard.

We Split the Storyboards and done all the Viewcontrollers UI. you can search the Storyboard by using the feature name itself.

Most of the Reusable Cells  are done on Storyboard itself. 


### Naming:

We can use the naming Standards that provided by apple itself. 

All the Reusable Cells are ending in the Form TVC or CVC.

All the ViewControllers are ending in the Form of ViewController. 

(It is useful for you to search the files Easily.)

All Configurations are declared in ```Constants.Swift``` file.

### Design Pattern:

We use the MVVM architecture pattern in this project.
 
All ViewModels are ending in form of  ViewModel.
```
for example 
LoginViewModel, ProfileViewModel,RegisterViewModel. 
```
All Model are ending in the form of Model.

```
for example.
ProfileUserDataModel - for profile information of the user who logged in.
LoginModel - for login information of the user. It can reuse for registration.

```
Some Models are reused for various information collections. because we receive the same key for
show the information.


# Data collection

The Stageflo collect below data. We provide this notice to help you fill out [App Privacy Details](https://developer.apple.com/app-store/app-privacy-details/).

* Name
* Brief Detail information about you.
* Email
* Photos or Videos

# Contribution
Hey! Do you like Stageflo? Awesome! We could actually really use your help!

Open source isn't just writing code. so feel free to contribute. How?

* Open an issue.
* Send feedback via email.
* Propose your own fixes, suggestions and open a pull request with the changes.

Please Read the [Contribution Guidelines](./CONTRIBUTING.md) before Contribution. We take it very seriously, and expect that you will as well.

# License
Stageflo is Released under the MIT License. See [MIT License](./License.md) for more information.
