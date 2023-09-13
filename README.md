# [Air Assault Application](https://github.com/KevinTudor/AAA_MobileApp/tree/main)
![Project Poster](assets/Poster_original.png)
## Introduction
The Air Assault Application is a mobile solution developed in response to a Request for Proposal (RFP) from the [101st Airborne Division](https://www.army.mil/101stairborne). It aims to enhance training tools and materials for soldiers pursuing Air Assault, Ranger, and Pathfinder qualifications. This README provides an overview of the project, its goals, and key information.

## Team
- [Kevin Tudor](https://github.com/KevinTudor)
- Alex Chaban
- Renan Queiroz

## Project Timeline
- Start Date: August 2022
- End Date: May 2023

## Task

This project responds to the 101st Airborne Division's RFP by creating a proof-of-concept mobile application. The application serves as a hub for training resources, recent news, and general information related to Air Assault, Ranger, and Pathfinder qualifications.

## Criteria

To meet the project's goals, we aim to:
- Offer easily accessible educational resources for [Air Assault](AirAssaultHome.js), [Pathfinder](PathfinderHome.js), and [Ranger](RangerHome.js) training.
    - News section for any updates to the Air Assault, Pathfinder, and Ranger education modules and current events.
    - Provide material to study for the Air Assault, Pathfinder, and Ranger qualification tests.
- [Distribute the application locally on both iOS and Android devices.](eas.json)

## Technology Stack
The application was built using the following technologies:
- [JavaScript:](https://www.javascript.com/) a programming language that is one of the core technologies of the World Wide Web, alongside HTML and CSS.
- [React Native:](https://reactnative.dev/) an open-source UI software framework created by Meta Platforms, Inc. It is used to develop applications for Android, Android TV, iOS, macOS, tvOS, Web, Windows and UWP by enabling developers to use the React framework along with native platform capabilities.
- [React.js:](https://react.dev/) a free and open-source front-end JavaScript library for building user interfaces based on components. It is maintained by Meta and a community of individual developers and companies. React can be used to develop single-page, mobile, or server-rendered applications with frameworks like Next.js.
- [Cheerio JS:](https://cheerio.js.org/) Fast, flexible & elegant library for parsing and manipulating HTML and XML.
- [Expo:](https://expo.dev/) an open-source app publicly available on the App Store and Play Store that makes testing apps easy via a scannable QR code.

## Installation and Usage
To simulate the app for live development testing:
- Create account with Expo - [signup here](https://expo.dev/signup)
- Clone the repository.
- Open with VS Code and create a new terminal.
    - run "git checkout main" ->  "npm install" (this will update necessary dependency modules).
    - In VS Code terminal run "npx expo login -h" ("whoami" should say your Expo username).
    - Once successfully logged in run "npx expo start".
- Download Expo Go on an iOS or Android device and sign in.
- Scan the QR code with the device.
- Metro Bundler should now be hosting the application through the Expo Go application.

## Current State and Future Plans
The application is currently able to run effectively on Android devices (local or emulated). The application is only available on iOS via live testing on Expo Go as the ".ipa" can not be verified without a Developers License with Apple. In the future the application should be able to run locally on iOS, have profiles to save user progress and have additional course testing pages. Personally, I would like to see this application hosted on the respective mobile stores and push/maintain versions with Expo.
