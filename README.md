# vvvv - Intel RealSense Plugin
vvvv Intel Realsense SDK 2016.r2 

Rebuilded Aoi repo: https://github.com/aoi/vvvv_RealSensePlugin

Node list

|node|content|
|---|---|
|RGB|RGB camera image |
|Depth|Depth image / depth information. |
|Hand|Hands detection. Skeleton, mask.|
|Face|Face detection. Facial expression / expression information. Heart rate.|
|SpeechRecognition|Speech recognition|
|3DScan|3D scan with .obj export|
|Segmentation|Background removed. (not working)|
|TouchlessController|UI manipulation by gesture.|

### Requirements

|Item |version|
|---|---|
|RealSense Camera|SR300/R200|
|RealSense SDK|2016 R2|
|RealSense Runtime|2016 R2|
|vvvv|45beta35.8 64bit|

## Installation:
### Intel RealSense SDK
Install RealSense SDK 2016.r2
https://software.intel.com/en-us/intel-realsense-sdk/download

### Install vvvv

Download / install vvvv 64bit Version from the following site. 
https://vvvv.org/downloads

Download / install DX11 Nodes from the following site. 
https://vvvv.org/contribution/directx11-nodes

### Install RealSense Plugin

Copy packs folder to the vvvv root folder

## specification

Corresponding resolution by function 
https://software.intel.com/sites/landingpage/realsense/camera-sdk/v1.1/documentation/html/index.html?doc_advanced_working_with_multiple_modaliti.html

