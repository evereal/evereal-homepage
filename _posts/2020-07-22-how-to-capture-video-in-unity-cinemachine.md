---
layout: post
cover: assets/images/video-capture-pro-unity-plugin/how-to-capture-video-in-unity-cinemachine.png
title: How to Capture Video in Unity Cinemachine
date: 2020-07-22 12:00:00
categories:
  - VideoCapture
  - Unity
author: evereal
tutorial: true
summary: This tutorial will simply walk you through how to set up Video Capture plugin to record a video in Unity Cinemachine.
permalink: /tutorials/how-to-capture-video-in-unity-cinemachine
youtube-id-1: jmYvx02eQ8Q
video-url-1: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/1
video-url-2: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/2
video-url-3: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/3
video-url-4: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/4
video-url-5: https://evereal.s3-us-west-1.amazonaws.com/video_capture/how_capture_video_3d/5
---

This tutorial will simply walk you through how to set up Video Capture plugin to record a video in Unity Cinemachine. The version of Unity used is 2019.4.0f1.

I am using the Unity awesome Film Sample Project as an example in this tutorial, which you can download <a href="https://assetstore.unity.com/packages/templates/film-sample-project-130415?aid=1100l9ebS" target="_blank">here</a>.

Then, download and import the [Free version](https://evereal.s3-us-west-1.amazonaws.com/video_capture/VideoCaptureTrial_Latest.unitypackage) of Video Capture, or purchase the <a href="https://assetstore.unity.com/packages/slug/155663?aid=1100l9ebS">Pro version</a> on Asset Store.

{% include youtube.html id=page.youtube-id-1 %}

* After importing the Video Capture plugin, place the Video Capture prefab in your game scene.
* Then drag and drop game main camera into the Video Capture's Regular Camera field to make sure the video ouput will take effect of the camera post processing and CinemachineBrain.
* You can enable the offline render option and set higher resolution to capture quality video.
* Play the game, start the video record session and play your video!

This is just a very basic getting started guide, please visit the <a href="/docs/video-capture-pro-unity-plugin/" target="_blank">document</a> for more details and usages.

Other tutorials you may interested:
* [How to Capture Video in Unity 2D Game](/tutorials/how-to-capture-video-in-unity-2d)
* [How to Capture Video in Unity 3D Game](/tutorials/how-to-capture-video-in-unity-3d)

<!-- Youtube Support -->
{% include lazyload-youtube.html %}