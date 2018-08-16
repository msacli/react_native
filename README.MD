-- enable usb debugging on phone connect via usb and detect that phone is connected on windows cmd via adb devices command

-- install react native cli globally

1 react-native init myapp create app

2 downgrade node modules


    "react": "16.3.1"
"react-native": "0.55.4"
In devDependencies :-
"babel-preset-react-native": "2.1.0"

npm install

3 Create a file called local.properties with this line:

sdk.dir = C:\\Users\\hp\\AppData\\Local\\Android\\Sdk

this is on windows it is needed to find the android sdk location on disc might change
4 run on cmd react-native run-android

this will install and load app on anroid phone

5 to reload make change in App.js text

run cmd "adb shell input keyevent 82"
then a menu will pop up on phone tap reload

done