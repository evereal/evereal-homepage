---
layout: product
cover:  assets/images/video-capture-pro-unity-plugin/cover.png
title: Video Capture Pro Unity Plugin
# tags: ['Video Capture', 'GPU Encoder', 'Unity Plugin']
summary: Video Capture is a plugin that enables the developers to capture video and audio from your Unity application.
asset-store-url: https://assetstore.unity.com/packages/tools/video/video-capture-pro-155663?aid=1100l9ebS
asset-store-widget: https://assetstore.unity.com/linkmaker/embed/package/155663/widget?aid=1100l9ebS
# gumroad-store-url: https://gum.co/aqwVBW
price: 49.99
order: 1
youtube-id: agd0Q3xvB2U
---

<h4><a href="/docs/video-capture-pro-unity-plugin/">Document</a> <span style="font-size: 18px;">&nbsp;|&nbsp;</span> <a href="https://evereal.s3-us-west-1.amazonaws.com/video_capture/VideoCaptureTrial_Latest.unitypackage?v=2.3.5">Free Trail</a></h4>

<b>Video Capture</b> is a plugin that enables you, the Unity developer, to capture video and audio from your Unity application. It’s great for recording video trailers, demos and in-app footage for your Unity-based game or app. It’s fast, flexible and easy to use. When the video is recorded you decide how it’s handled. Give your users complete freedom to share it, restrict it to playback from within your app, or anything in between.

<b>Price:</b> ${{page.price}}

<b>Features:</b>
* Extremely easy to use
* Capture video from any camera
* Capture video from screen with cursor
* Capture video from render texture
* Capture audio inside scene
* Capture audio from microphone
* Multiple codec support (H.264, H.265, FFV1, VP8, VP9)
* Multiple cameras capture simultaneously
* Live streaming to remote streaming services (Youtube, Facebook, etc.)
* Up to 8K video capture
* Up to 16K screenshot or sequence images capture
* Stereo video capture (Left Right, Up Bottom)
* 360 video capture (Equirectangular, Cubemap)
* 360 stereo video capture (Left Right, Up Bottom)
* Real-time and Offline capture supported
* Linear and Gamma color spaces supported

<b>Supported Platforms:</b>
* Windows (32-bit or 64-bit)
* macOS (64-bit)

<b>Showcases:</b>
{% include youtube.html id='3obJ5ejvpAg' %}
{% include youtube.html id='hBEMjfLrm50' %}
{% include youtube.html id='FseT9nuhXks' %}
{% include youtube.html id='qSsK5MAuHUc' %}

<b>Screenshots:</b>
![Video Capture Pro Screenshot 1](/assets/images/video-capture-pro-unity-plugin/screenshot-1.png)
![Video Capture Pro Screenshot 2](/assets/images/video-capture-pro-unity-plugin/screenshot-2.png)
![Video Capture Pro Screenshot 3](/assets/images/video-capture-pro-unity-plugin/screenshot-3.png)

<b>FAQ:</b>
<ul style="list-style-type: none;">
<li>
<b>Q: What's the Unity version required for Video Capture plugin?</b>
</li>
<li>
<b>A:</b> We recommend using Unity 5.6 or newer.
</li>

<li>
<br>
</li>

<li>
<b>Q: Can I use multiple cameras for capturing simultaneously?</b>
</li>
<li>
<b>A:</b> Yes, but the more cameras you use, the more resources you cost on your device. In addition, the 360 video record does not support multi-camera record for now.
</li>

<li>
<br>
</li>

<li>
<b>Q: What are offline render settings?</b>
</li>
<li>
<b>A:</b> If you enable offline render settings, the capture session will only move to the next frame until the current frame record succeeds. It's useful for you to create a smooth video when you capture 8K video or intensive video capture.
</li>

<li>
<br>
</li>

<li>
<b>Q: Does my device support the high performance GPU encoding?</b>
</li>
<li>
<b>A:</b> GPU encoding is for Windows only and requires a dedicated graphics card.
</li>

<ul>
<li>
NVIDIA Quadro, Tesla, GRID or GeForce products with Kepler, Maxwell and Pascal generation GPUs. NVidia Windows display driver: 375.95 or newer.
</li>

<li>
AMD GPUs supporting the following driver: AMD Radeon Software Crimson 17.1.1 or later.
</li>

<li>
Windows 7 SP1 or newer.
</li>
</ul>

<li>
<br>
</li>

<li>
<b>Q: What is the resolution limit for recorded video?</b>
</li>
<li>
<b>A:</b> Support video resolution is different based on encoding type:
</li>

<ul>
<li>
AMD GPU encoding: Up to 4K (4096 x 2048)
</li>

<li>
NVidia GPU encoding: Up to 4K (4096 x 4096)
</li>

<li>
Software encoding: Up to 8K (7680 x 4320)
</li>
</ul>

<li>
<br>
</li>

<li>
<b>Q: Why can't I generate a video on macOS?</b>
</li>
<li>
<b>A:</b> If you cannot generate a video on macOS, this may be due to the program having no permission to run FFmpeg. To fix this, please click Grant macOS Build permission item in the VideoCapture editor menu.
</li>

<li>
<br>
</li>

<li>
<b>Q: I am using macOS and Unity 2017, why can't I import the assets?</b>
</li>
<li>
<b>A:</b> The Video Capture Pro asset includes a sample wav audio file. macOS version Unity 2017 has a bug import wav file, exclude the wav audio file then you will import assets successfully.
</li>

<li>
<br>
</li>

<li>
<b>Q: How can I record game UI with Video Capture?</b>
</li>
<li>
<b>A:</b> Please change Capture Source to SCREEN, and you can try the demo “Demo_02_FromScreen” which will record game UI.
</li>

<li>
<br>
</li>

<li>
<b>Q: I am using Windows, why does the program exit after enable the GPU encoding?</b>
</li>
<li>
<b>A:</b> There might be exceptions during capturing with GPU, please make sure you are using Direct3D11 for Windows Graphic API.
</li>

</ul>