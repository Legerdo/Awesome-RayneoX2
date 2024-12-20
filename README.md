# Awesome-SmartGlassesAppDev
단독 구동되는 안드로이드 OS 기반 스마트 안경 (Rayneo X2, Inmo Air, Vuzix Blade 등등 ) 관련 프로젝트에서 사용할만한 유용한 라이브러리 목록( 유니티 엔진 위주 )</br>
해당 기기의 카메라 모드가 3DOF, 6DOF 여부에 따라 호환이 안될 수 있으므로 직접 수정해야함.

# 목차
 
- [Compatible](#Compatible)
    - [AR](#AR)
    - [ML/OCR](#ML_OCR)
    - [AI](#AI)
    - [STT](#STT)
    - [Video](#Video)
    - [GPS](#GPS)
    - [Webview](#Webview)
    - [Keyboard](#Keyboard)
    - [Storage](#Storage)

- [Uncompatible](#Uncompatible)
    - [RayneoX2](#RayneoX2)

- [Information](#Information)

# Compatible

## WebRTC

Unity Webrtc - https://github.com/Unity-Technologies/com.unity.webrtc

WebRTC Video Chat - https://assetstore.unity.com/packages/tools/network/webrtc-video-chat-68030

## AR

Vuforia - https://developer.vuforia.com/home

Maxst - https://maxst.com/AR_Platform/

EasyAR - https://www.easyar.com</br>
EasyAR Extension Example(RayneoX2) - https://leiniao-ibg.feishu.cn/file/UhQob7gDGoFISxxaymCciEQ8nko

ARFoundation - https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@6.1/manual/index.html

Arunityx - https://github.com/artoolkitx/arunityx

Lightship - https://lightship.dev/docs/ardk/setup/

Snapdragon Spaces - https://spaces.qualcomm.com/developer/ar-sdk/

## ML_OCR

Mediapipe - https://github.com/homuler/MediaPipeUnityPlugin

TensorFlow Lite - https://github.com/asus4/tf-lite-unity-sample

OpenCV - https://assetstore.unity.com/packages/tools/integration/opencv-for-unity-21088

Android/ML Kit - https://developers.google.com/ml-kit

Sentis - https://docs.unity3d.com/Packages/com.unity.sentis@2.1/manual/index.html / https://huggingface.co/unity

Tesseract - https://github.com/Neelarghya/tesseract-unity

vision - https://cloud.google.com/vision

ai-vision - https://azure.microsoft.com/ko-kr/products/ai-services/ai-vision

AI Vision - https://www.oracle.com/artificial-intelligence/vision/

CLOVA OCR - https://www.ncloud.com/product/aiService/ocr

GO AI OCR - https://www.gridone.co.kr/ko/solution/ai

nhncloud OCR - https://www.nhncloud.com/kr/service/ai-service/ocr

## AI

OpenAI Official - https://platform.openai.com/docs/overview

OpenAI - https://github.com/RageAgainstThePixel/com.openai.unity

OpenAI-Unity - https://github.com/srcnalt/OpenAI-Unity

Claudia Official - https://docs.anthropic.com/en/docs/welcome

Claudia - https://github.com/Cysharp/Claudia

together.ai - https://www.together.ai/

Anthropic.SDK - https://github.com/tghamm/Anthropic.SDK

huggingface - https://github.com/huggingface/unity-api

Perplexity API - https://docs.perplexity.ai/home

Gemini Official - https://ai.google.dev/

UGemini - https://github.com/Uralstech/UGemini

## STT

whisper.unity - https://github.com/Macoron/whisper.unity

Google AI - https://cloud.google.com/speech-to-text

SpeechRecognizer - https://developer.android.com/reference/android/speech/SpeechRecognizer

UnitySpeechToText - https://github.com/yasirkula/UnitySpeechToText

voice-sdk - https://developers.meta.com/horizon/documentation/unity/voice-sdk-overview / https://assetstore.unity.com/packages/tools/integration/meta-voice-sdk-immersive-voice-commands-264555

voice-activity-detection-unity - https://github.com/mochi-neko/voice-activity-detection-unity

CLOVA - https://www.ncloud.com/product/aiService/csr

리턴제로 - https://www.rtzr.ai/

## Video

UnityYoutubePlayer - https://github.com/iBicha/UnityYoutubePlayer

videokit - https://github.com/videokit-ai/videokit

## GPS

Mapbox - https://docs.mapbox.com/unity/maps/guides/

GoogleMaps - https://mapsplatform.google.com/

ArcGIS - https://developers.arcgis.com/unity/

Cesium - https://cesium.com/platform/cesium-for-unity/

Online Maps v3 - https://assetstore.unity.com/packages/tools/integration/online-maps-v3-138509

here-sdk - https://www.here.com/platform/here-sdk

## Webview

TLabWebView - https://github.com/TLabAltoh/TLabWebView

gree/Webview - https://github.com/gree/unity-webview/tree/experimental/unity-over-native-ui

3d-webview - https://assetstore.unity.com/packages/tools/gui/3d-webview-for-android-web-browser-137030

UniWebView 5 - https://docs.uniwebview.com/guide/render-as-texture.html

## Keyboard

Custom UI/VR keyboard - https://assetstore.unity.com/packages/tools/input-management/custom-ui-vr-keyboard-205464

TLabVKeyborad - https://github.com/TLabAltoh/TLabVKeyborad

## Storage

dropbox-sdk-dotnet - https://github.com/dropbox/dropbox-sdk-dotnet

unity-google-drive - https://github.com/elringus/unity-google-drive/tree/main

# Uncompatible

## RayneoX2

호환되지 않거나 일부 기능이 제한됨(하드웨어 자체의 문제라기보다 RayneoOS/AppContainer 등 OS, 앱 문제로 인해 안되는걸로 추정되기 때문에 별도의 방법이 필요할 수 있음)

Sceneview/AR Core, Snapdragon Spaces, Lightship, AR Foundation</br>
Google Play Services - FusedLocationProviderClient 같은 GPS 서비스도 사용이 불가능</br>
Bluetooth - 링 및 휴대폰을 제외한 다른 기기와의 연결이 원활하지 않음 </br>
Notifications / Background Task / Multitasking</br>
Native App - SoftKeyboard, Camera, Storage Etc.. - UI 일부가 짤리거나 충돌이 발생

# Information

Android XR - https://developer.android.com/develop/xr
</br>https://www.youtube.com/watch?v=UhDx9NMqT7o&t=1s

RayneoX2 Official Document</br>
https://open.rayneo.com/#/docs/x2</br>
https://leiniao-ibg.feishu.cn/wiki/IwTRwecN0ikZcjkHAhicN5lWn0g

I-XRAY - https://www.youtube.com/watch?v=gHrSXe1cElI

Mobile Bluetooth Controller</br>
https://play.google.com/store/apps/details?id=io.appground.blek / https://play.google.com/store/apps/details?id=io.appground.blekpremium</br>
https://play.google.com/store/apps/details?id=com.jb.bluetoothbuttons</br>
https://play.google.com/store/apps/details?id=com.samsung.android.oneconnect</br>
https://play.google.com/store/apps/details?id=io.port6.watchbridge

AI Face Detection(Tutorial) - https://www.youtube.com/watch?v=yIImVW9m2lY
