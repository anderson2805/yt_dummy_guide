---
title: About
permalink: /about/
---

<!-- This is a [starter template](https://vsoch.github.com/tw-jekyll/) for a Tailwind jekyll theme, based
on [these docs](https://github.com/superfly/docs) that are based on [Tailwind css](https://tailwindcss.com/docs/installation),
however everything has been modified to work on GitHub pages (using Jekyll). If you don't need
native deployment on GitHub pages, then please consider checking out Tailwind. 
The original [Apache License](https://github.com/vsoch/tw-jekyll/tree/main/LICENSE) is included.

See the [respository]({{ site.repo }}) for more details. -->

This site provides the functions of knowledge management for capabilities on Youtube+.

Youtube+ collect Youtube data via official [Youtube API](https://developers.google.com/youtube/v3) with captions ingested using [youtube_transcript_api](https://pypi.org/project/youtube-transcript-api/)

The goal is collection, data processing and visualization for analysis, all in one seamless interface. 

Youtube+ is hosted with Streamlit Cloud and can be access via: 
- [Link](https://share.streamlit.io/ytexplorer/youtubeplus){:target="_blank"}
- [Alternative](https://share.streamlit.io/anderson2805/youtubeplus){:target="_blank"}

For local installation, follow this guide.

## About Streamlit Cloud
Streamlit Cloud is a workspace for your team to deploy, manage, and collaborate on your Streamlit apps. You connect your Streamlit Cloud account directly to your GitHub repository (public or private) and then Streamlit Cloud launches the apps directly from the code you've stored on GitHub. Most apps will launch in only a few minutes, and any time you update the code on GitHub, your app will automatically update for you. This creates a fast iteration cycle for your deployed apps, so that developers and viewers of apps can rapidly prototype, explore, and update apps.

Under the hood Streamlit Cloud handles all of the containerization, authentication, scaling, security and everything else so that all you need to worry about is creating the app. Maintaining Streamlit apps is easy. Containers get the latest security patches, are actively monitored for container health. We are also building the capability to observe and monitor apps.
### Network and Application Security
#### Data Hosting
Our physical infrastructure is hosted and managed within Google Cloud Platform (GCP) using their secure data centers. Streamlit leverages many of the platform's built-in security, privacy, and redundancy features. GCP continually monitors its data centers for risk and undergoes assessments to ensure compliance with industry standards. GCP's data centers have numerous accreditations, including ISO-27001, SOC 1 and SOC 2.

#### Virtual Private Cloud
All of our servers are within a virtual private cloud (VPC) with firewalls and network access control lists (ACLs) to allow external access to a select few API endpoints; all other internal services are only accessible within the VPC.

#### Encryption
All Streamlit apps are served entirely over HTTPS. All data sent to or from Streamlit over the public internet is encrypted in transit using 256-bit encryption. Our API and application endpoints are TLS only (v1.2). We use only strong cipher suites and HTTP Secure Transport Security (HSTS) to ensure browsers interact with Streamlit apps over HTTPS. We also encrypt data at rest using AES-256.


## Support

If you need help, please don't hesitate to [open an issue](https://www.github.com/{{ site.github_user }}/{{ site.github_repo }}).

