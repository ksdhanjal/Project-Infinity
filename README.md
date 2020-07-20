# Project Infinity
Project Infinity is a mind controlled rover which is made using arduino and is controlled by  Neurosky Mindwave Headset with the help of an app

## Working

- The app first connects to Arduino and then to Neurosky mindwave headset.
- After the app is connected to headset, it  starts to recieve raw data
-  NeuroSky's Android SDK converts the raw data to decode Attention, Meditation, and Eye Blink Detection waves
- When the user blinks twice with the intensity exceeding the set threshold then the app cycles through the directions and when the user again blinks, the app sends the command to the rover via Bluetooth

## Preview

-![Project Infinity](https://github.com/ksdhanjal/Project-Infinity/blob/master/screenshot/Screenshot_20200503-025414_Project%20Infinity.jpg)

## Acknowledgements 
- Arduino's code by [@d4rk-lucif3r](https://github.com/d4rk-lucif3r/Project-Infinity)
- [NeuroSky's Android SDK](https://store.neurosky.com/products/android-developer-tools-4)

## Side note
You can also use implementation provided by [@pwittchen](https://github.com/pwittchen/neurosky-android-sdk)
