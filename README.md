
# Firebase Integration with Flutter

## Step-1 - Install flutterfire 

## FlutterFire

Install FlutterFire in your project.

```bash 
dart pub global activate flutterfire_cli
```
- Make sure that git is installed in your system.

    
## Step-2 Linking Firebase Account with the Flutter.

Link your account with this command.
```bash 
flutterfire configure
```
## Step-3 Make sure that firebase packages are installed correctly and configured correctly.

## Step-4 Add the functions which are provided.

## Step-5 Make sure that google-services.json is added in the android root folder.

## Step-6 Generate SHA KEYS for android

- To Generate SHA KEYS for Android 
- Open Terminal and follow the steps

```bash
 cd android
./gradlew signingReport
```
- Copy the SHA-1 and SHA-256.
- Now, Paste this SHA-1 and SHA-256 into the firebase project settings in the cerfication tab.
