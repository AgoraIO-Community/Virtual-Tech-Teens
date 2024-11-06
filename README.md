# [ARCHIVED] Virtual Tech Teens

**⚠️ This project is no longer maintained and has been archived.**  
Please note that this repository is now in a read-only state and will not receive any further updates or support.

We recommend using to the latest version of the **Agora iOS SDK**: [Learn more](https://www.agora.io/en/products/video-call/) 

For documentation and support, please visit the [Agora Documentation](https://docs.agora.io/en/).

---
Tech problems are universal. In an era where technology is ubiquitous, people need help navigating this complex landscape. As a result, people turn to friends and family for assistance, with some not even having this luxury. Because of COVID-19, the option to receive support in a face-to-face environment has become less viable. Our app circumvents this, providing a digital infrastructure for the support the user would normally get in person. Using state of the art UI, asking for support only requires one tap. Overall, the benefits of our application are symbiotic. It benefits teens, giving them volunteer hours and invaluable work experience. It benefits those in need of tech support. But most importantly it benefits the community, strengthening the relationship between those of different age groups.

More information about our project, what the app does, and how it works can be found here: https://devpost.com/software/techteens

## Installation

Dependencies: CocoaPods, Firebase

1. In the project directory, run `pod install`
2. In the Xcode workspace, edit the project signing settings
3. Create an Agora project at https://agora.io and paste your App ID into AppID.swift
4. Create a Firebase project at https://console.firebase.google.com, follow instructions
6. Enable Google Sign In as an authentication option
5. Create a Cloud Firestore database with a collection called `users`
6. Create a document called `guests` with two empty array fields titled `assisted` and `list`
7. Create a document called `teens` with an array of verified emails called `verified`
8. Install to a physical device (iOS Simulator will not run with video)



Copyright 2020 Finlay Nathan, Jessica Golden, Ethan Hopkins, Henry Marks

See LICENSE.txt for more information

Virtual Tech Teens is not affiliated with the Tech Teens program at the Santa Monica Public Library. Approval as a Virtual Tech Teen does not indicate acceptance into the Tech Teens program at the SMPL.
