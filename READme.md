# SUPER NATIVE

**PURPOSE :** Testing

# SETUP REACT NATIVE APP

**1.** Download **[Node.js](https://nodejs.org/en/)**

**2.** Download **[Visual Studio Code](https://code.visualstudio.com/download)**
OR **[Notepad++](https://notepad-plus-plus.org/downloads/)**
OR **[PhpStrom](https://www.jetbrains.com/phpstorm/download/#section=windows)**
OR **[Atom](https://atom.io/)** or any other text editor

**3.** Download **[Android Studio](https://developer.android.com/studio)**

**4.** Download **[JAVA](https://adoptopenjdk.net/)** (download java 11)  (download java according to gradle support, I
am just providing the current version of java which supports gradle right now, If you are reading this file then first
search the latest version of java which support gradle )

**5.** Run following commands in window terminal

```bash
    npm i -g create-react-app
```

```bash
    npm i -g create-react-native-app
```

```bash
    npm i -g react-native-cli
```

**6.** Open Android Studio and follow the step which showing in image

1) Click on SDK manager
   ![](./img/1.png)
2) Download third point of the list
   ![](./img/2.png)

**7.** Image is given below setup environment variables
![](./img/3.png)

**NOTE :** Here I am using Java Eclipse, you can use other Oracle java

![](./img/4.png)

**NOTE :** Add this in `PATH` section
![](./img/5.png)

**8.** Create React Native App

**9.** Before Executing app do these things

1. if you are using a physical device then
    1. Connect your phone with your system
    2. Open `Developer Tool`
    3. Turn on `USB Debugging`
    4. Run `adb devices` it will show your connected device info
2. If you are using an emulator
    1. Open Android Studio
    2. Click on `AVD Manager`
       ![](./img/6.png)
    3. Click play symbol which is below of `Action` word
       ![](./img/7.png)
        1. If you cannot see any device their then click on `Create Virtual Device`  and download a device what you
           want.

**10.** Run React Native App

```bash
   npx react-native run-android
```