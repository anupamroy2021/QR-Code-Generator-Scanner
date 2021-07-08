# QR-Code-Generator-Scanner
## Step 1: Create a New Project
To create a new project in Android Studio please refer to How to Create/Start a New Project in Android Studio. Note that select Java as the programming language.
## Step 2: Add dependency to build.gradle(Module:app)
Navigate to the Gradle Scripts > build.gradle(Module:app) and add the below dependency in the dependencies section.
```bash
implementation 'androidmads.library.qrgenearator:QRGenearator:1.0.3
```
```
implementation ('eu.livotov.labs.android:CAMView:2.0.1@aar') {transitive=true}
```
Now sync the project from the top right corner option of Sync now.
## Step 3: Add permission for the camera in the manifest file 
We are adding a camera and vibrate permission in our manifest file. Navigate to the app > manifest to find AndroidManifest.xml. Below is the code snippet for AndroidManifest.xml
``` xml
    <!--Permission for camera-->
    <uses-permission android:name="android.permission.CAMERA" />
    <!--Permission to vibrate-->
    <uses-permission android:name="android.permission.VIBRATE"/>
```
## Step 4: Working with the activity_main.xml file
Navigate to the app > res > layout > activity_main.xml and add the code to that file.
## Step 5: Working with the MainActivity.java file
Navigate to the app > java > your apps package name > MainActivity.java file. 
