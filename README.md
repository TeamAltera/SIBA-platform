# SIBA (Social IoT Based on AI chatbot)
SIBA platform is available to both developers and users.<br/>
Developers do not need to develop IoT applications for users, and users can use IoT devices with KakaoTalk.<br/>
Platform for developing and operating IoT devices that can operate through Kakao Channel using scenario graph definition<br/>

Click [here](https://www.youtube.com/watch?v=EZWuRYBgoIA&t=287s) if you want to see the project demo video.

## Related repositories
- For SIBA end-user
    - [open builder skill server](https://github.com/DCU-ICSLab/siba-BE-usr)
    - [end-user web app](https://github.com/DCU-ICSLab/siba-FE-usr)
    - [end-user IoT-hub](https://github.com/DCU-ICSLab/siba-mid)
- For SIBA developer
    - [developer server](https://github.com/DCU-ICSLab/siba-BE-dev)
    - [developer web tool](https://github.com/DCU-ICSLab/siba-FE-dev)
    - [developer IoT-hub](https://github.com/DCU-ICSLab/SIBA-hub-developer)
    - [SIBA arduino library](https://github.com/DCU-ICSLab/SIBA)

## System architecture

## how to make SIBA IoT device
Describes how to develop a device from the developer's perspective.
1. Defining hub frames in developer tools
1. git clone & set siba-hub-config.yml file
1. launch (Docker and Docker-compose must be installed before)
1. Create Device's Scenario graph repo
1. Defining the state values used in scenario graphs and devices
1. Code Frame Extraction for SIBA IoT Devices
1. Write the logic code you want in the code frame
1. device's code build & upload 
1. Testing that the device works in the developer tools
1. Click the Deploy button to deploy to the skill server

## how to use SIBA IoT device
Describes how to use the device created on the user side.
1. add kakao channel & Connect your hub to your router by wire.
1. Click the Join button to access your web app and sign in with your Kakao ID.
1. Connect your smartphone wirelessly to the router to which your hub is connected.
1. In your web app, click the Scan button to identify if the user hub exists, and add the hub if it exists.
1. click the Scan Device button to scan and add a device.
1. From then on, users can operate the device by clicking the SIBA button on the Kakao channel.

## Team QuadCore members
- Gyojun Ahn (Project Leader)
- Sangwon Lee
- Jinhyeok Kim
- Sohyeon Jeon