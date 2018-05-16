# Udacity Carnival Starter Project READ ME

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

The end goal of this project is to customize the Udacity Carnival project, which will be something cool that you can show off to your friends and family! The Udacity Carnival consists of 3 Mini-Games: Plinko, Wheel of Fortune, and Coin Toss. With each game, you earn points. When you earn 2000 points, you will receive a virtual classic Carnival prize!

<img src="https://lh3.googleusercontent.com/CEatiFeFgBW3UqlH6SyISQc-j397RspEoS3oGGdf3vn5TidzGS9Op9f1vAoaR1m-1YtoXrURDiEvWa07Loc=s0" width="50%"/>

## Versions
- [Unity Patch 2017.2.0f3](https://unity3d.com/unity/qa/patch-releases?version=2017.2)
- [GVR Unity SDK v1.70.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/1.70.0)
- TextMesh Pro v1.0.55.2017.1.0b12 (*provided*)

## Setup
There's an issue with the Google Android SDK version XX, where it will report an error around "Unable to list target platforms." or "Unrecognized command 'android'".

To workaround this issue, you can manually download the tools to a previous version of the SDK. This will remove the **tools** folder, and replace it with a version that works.
```
cd %Android_SDK_path%
rm -rf tools
wget http://dl-ssl.google.com/android/repository/tools_r25.2.5-ma‌​cosx.zip; unzip tools_r25.2.5-macosx.zip
```
