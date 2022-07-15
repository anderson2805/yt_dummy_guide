---
tags: 
 - youtube-api
 - google
title: Getting Started
author:
  name: Ng Wei Jie
  email: ngweijie@outlook.com
---

## How to access Youtube+?
Youtube+ can be access via streamlit on: 
- [Link 1](https://share.streamlit.io/ytexplorer/youtubeplus){:target="_blank"}
- [Link 2](https://share.streamlit.io/anderson2805/youtubeplus){:target="_blank"}

## How to obtain Youtube API?
Source: [Youtube API Documentation](https://developers.google.com/youtube/v3/docs/?apix=true){:target="_blank"}

1. Access [developers console](https://console.developers.google.com/){:target="_blank"}
2. Create New Project (if you do not have any)
![image](../assets/img/yt_api_create_project.png)
![image](../assets/img/yt_api_create_project2.png)
3. Enable [Youtube Data API v3](https://console.cloud.google.com/apis/library/youtube.googleapis.com){:target="_blank"}
![image](../assets/img/yt_api_enable_yt_api.png)
4. Go to Credentials> Create Credentials > API key
![image](../assets/img/yt_api_create_api.png)
5. Configure the API key to improve security
![image](../assets/img/yt_api_config_api.png)
6. (Optional) For each use of API key on Youtube+, we recommend regenerate key. Due to key are encrypted with HTTPS only.
![image](../assets/img/yt_api_regen_api.png)