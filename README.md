# Nativescript-Todo-App

### Step 1: Install Node.js
The NativeScript CLI is built on Node.js, and as such you need to have Node.js installed to use NativeScript.
### Step 2: Install the NativeScript CLI
Open your terminal or command prompt and execute the following command to install the NativeScript CLI from npm, which is the Node.js package manager.

npm install -g nativescript
### Step 3: Verify that the installation was successful by running tns in the terminal.

$ tns

### Step 4: Creating apps
Use the tns create command

$ tns create HelloWorld

The create command will take a minute to complete, as the NativeScript CLI needs to download a few dependencies while setting up your new app.

### Step 5
When the command finishes, use the cd command (change directory) to navigate into your new app’s folder.

$ cd HelloWorld


### Step 6: Running apps
In NativeScript you use the CLI’s tns run command to run your apps on iOS or Android. Let’s start with Android.

$tns run android
