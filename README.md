# Amplified Notes

**Amplified Notes** is a sample Flutter application that demonstrates the usage of AWS Amplify for building a note-taking app. This repository serves as a starting point for developers who want to integrate AWS Amplify into their Flutter projects.

## Features

- User authentication and authorization with AWS Cognito
- Create, read, update, and delete (CRUD) operations for notes
- Real-time synchronization across multiple devices
- Offline support with automatic synchronization upon reconnection
- Simple and intuitive user interface

## Prerequisites

To run the Amplified Notes app, you'll need the following prerequisites:

- Flutter SDK: Make sure you have Flutter installed on your machine. You can download it from the official [Flutter website](https://flutter.dev).
- AWS Amplify CLI: Install the Amplify CLI globally by running `npm install -g @aws-amplify/cli` in your terminal.
- AWS Account: Create an AWS account if you don't have one already. Amplify offers a free tier that should be sufficient for testing and development.

## Getting Started

1. **Clone the repository:**
 
Install the required dependencies:

```shell
 
flutter pub get
 ```
Configure AWS Amplify:

```shell
 
amplify configure
 ```
Follow the prompts to configure the Amplify CLI with your AWS credentials and region.

Initialize the Amplify project:

```shell
 
amplify init
 ```
Follow the prompts to configure the backend resources required for the app.

Push the local changes to the cloud:

```shell
 
amplify push
 ```
This will provision the necessary AWS resources and generate the required configuration files.

Start the app:

```shell
flutter run
 ```

Ensure that you have an emulator/device connected or use the --device-id flag to specify a specific device.

You should now see the Amplified Notes app running on your emulator/device.

Additional Resources
For more information on AWS Amplify and its usage with Flutter, refer to the following resources:

[AWS Amplify Flutter documentation](https://docs.amplify.aws/ui/q/framework/flutter/).
 
License
The Amplified Notes app is open source and distributed under the MIT License. Feel free to modify and use it as per your requirements.