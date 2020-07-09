---
layout: post
cover: assets/images/video-capture-pro-unity-plugin/how-capture-video-3d.png
title: How to Capture Video in Unity (3D Game)
date: 2020-07-07 12:00:00
categories:
  - VideoCapture
  - Unity
author: evereal
tutorial: true
summary: This tutorial will simply walk you through how to set up Video Capture plugin to record a 3D game in Unity.
permalink: /tutorials/how-to-capture-video-in-unity-3d
video-url-1: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/1
video-url-2: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/2
video-url-3: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/3
video-url-4: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/4
video-url-5: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/5
---

This tutorial will simply walk you through how to set up Video Capture plugin to record 3D game in Unity. The version of Unity used is 2019.4.0f1.

You will need a game, of course, I am using the Unity awesome 3D Game Kit Lite as an example, which you can download <a href="https://assetstore.unity.com/packages/templates/tutorials/3d-game-kit-lite-135162?aid=1100l9ebS" target="_blank">here</a>.

{% include video-url.html url=page.video-url-1 %}

Then, download and import the [Free version](https://evereal.s3-us-west-1.amazonaws.com/video_capture/VideoCaptureTrial_Latest.unitypackage) of Video Capture, or purchase the <a href="https://assetstore.unity.com/packages/slug/155663?aid=1100l9ebS">Pro version</a> on Asset Store.

{% include video-url.html url=page.video-url-2 %}

After importing the Video Capture plugin, place the Video Capture prefab in your game scene, then attach it into the game character Ellen to make sure the capture camera will follow the moving of character. Don't forget to adjust the prefab and camera's position and rotation to make sure you are good with capture angle.

{% include video-url.html url=page.video-url-3 %}

Play the game, start the video record session (click shortcut F1 since the game hide your mouse pointer) and play your video!

{% include video-url.html url=page.video-url-4 %}

Now, let's try to make a 360 video. First, reset the Video Capture prefab and place it in the position you want capture the 360 video. Second, config the Capture Mode to 360, Projection Type to EQUIRECT and Resolution to 4K. At last, let's enable GPU encoding option to boost the performance (Only available in the Pro version).

{% include video-url.html url=page.video-url-5 %}

Play the game, start the video record session (click shortcut F1 since the game hide your mouse pointer) and play your 360 video!

This is just a very basic getting started guide, please visit the <a href="/docs/video-capture-pro-unity-plugin/" target="_blank">document</a> for more details and usages.

Other tutorials you may interested:
* [How to Capture Video in Unity (2D Game)](/tutorials/how-to-capture-video-in-unity-2d)

Download the full project:
* [https://github.com/evereal/video-capture-unity-3d-sample](https://github.com/evereal/video-capture-unity-3d-sample)