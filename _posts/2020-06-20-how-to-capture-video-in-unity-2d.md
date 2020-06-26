---
layout: post
cover: assets/images/video-capture-pro-unity-plugin/how-capture-video-2d.png
title: How to Capture Video in Unity (2D Game)
date: 2020-06-20 12:00:00
categories:
  - VideoCaptureTutorials
  - Unity
author: evereal
tutorial: true
summary: This tutorial will simply walk you through how to set up Video Capture plugin to record a 2D game in Unity.
video-url-1: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_2d/1
video-url-2: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_2d/2
video-url-3: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_2d/3
video-url-4: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_2d/4
---

This tutorial will simply walk you through how to set up Video Capture plugin to record a 2D game in Unity. The version of Unity used is 2019.4.0f1.

You will need a game, of course, I am using the Unity awesome 2D Game Kit as an example, which you can download <a href="https://assetstore.unity.com/packages/essentials/tutorial-projects/2d-game-kit-107098?aid=1100l9ebS" target="_blank">here</a>.

{% include video-url.html url=page.video-url-1 %}

Then, download and import the [Free version](https://evereal.s3-us-west-1.amazonaws.com/video_capture/VideoCaptureTrial_Latest.unitypackage?v=2.3.5) of Video Capture, or purchase the <a href="https://assetstore.unity.com/packages/slug/155663?aid=1100l9ebS">Pro version</a> on Asset Store.

{% include video-url.html url=page.video-url-2 %}

Third, place Video Capture prefab in your scene. Set capture from the screen is the easiest way to capture a 2D game, and don't forget to attach `DontDestroy.cs` script if the capture session includes loading a new scene.

{% include video-url.html url=page.video-url-3 %}

Play the game and start the video record session.

{% include video-url.html url=page.video-url-4 %}

Finally, play your video!

This is just a very basic getting started guide, please visit the <a href="/docs/video-capture-pro-unity-plugin/" target="_blank">document</a> for more details and usages.

Download the full project: [https://github.com/evereal/video-capture-unity-2d-sample](https://github.com/evereal/video-capture-unity-2d-sample)