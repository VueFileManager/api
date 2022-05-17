# API Documentation for VueFileManager Pro & Light
We wrote the documentation for the VueFileManager in Insomnia HTTP client which is free and open source client available for Windows, Linux and macOS. API Documentation in Insomnia client will bring you flexible and interactive experience while you are working on your own application with VueFileManager API.

![Insomnia HTTP Client](https://i.ibb.co/9ppFv6Q/Screenshot-2022-05-17-at-09-15-23.png)

## Contents

- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Interface Explanation](#interface-explanation)

## Installation
1. Download and install [Insomnia HTTP client](https://insomnia.rest/download).
2. Open Insomnia client and create new project via Git Clone button. 
3. Paste url address `https://github.com/VueFileManager/api.git` into URL input and confirm the popup.
4. Open newly created document and switch at center of the top navigation into **Debug** tab.
5. That's all.

## Environment Setup
To properly run all documented endpoints you have to set environment variables.

In the top left corner you will see **Config** dropdown menu, click on it and select **Manage Environments**. In Config environment you will see two variables which you have to edit on your own.

1. `base_url` - The base url of your running server with VueFileManager
2. `token` - The authentication token generated in the VueFileManager app or obtained via `/api/login` login route.

We are providing you 4 demo backends which you can set and play via Insomnia HTTP clients:

#### Demo for metered billing (SaaS version):
```
https://demo-metered.vuefilemanager.com
```

#### Demo for fixed billing (SaaS version):
```
https://demo-fixed.vuefilemanager.com
```

#### Demo without billing system:
```
https://demo-regular.vuefilemanager.com
```

#### Demo for Light version of VueFileManager:
```
https://demo-light.vuefilemanager.com
```

## Interface Explanation:
Interface is divided into three parts:

#### Left Sidebar
All VueFileManager API endpoints sorted into multiple categories

#### Middle part
Contains URL address bar with 5 Tabs:
1. Body of the request
2. Request authorization with bearer token for all secured endpoints
3. Queries for your request
4. Header setup for sending requests
5. Docs where you find explanations for current endpoint

#### Right Sidebar
The original response of the request which was sent





