# 🌐 Free RDP Access via Google Cloud

This repository provides a quick and easy guide to set up a Remote Desktop Protocol (RDP) using Docker on Google Cloud. With just a few steps, you can deploy an Ubuntu desktop with a graphical interface and VNC support.

## 🚀 Quick Start Guide

### 1. Open Google Cloud Console

Click the link below to access Google Cloud's shell:

[Open Google Cloud Console](https://console.cloud.google.com/welcome?project=glassy-proton-394217&cloudshell=true&pli=1)

### 2. Run Docker Command

Once you're in the cloud shell, simply run the following Docker command to start your RDP server:

```bash
docker run -p 6070:80 dorowu/ubuntu-desktop-lxde-vnc
```
### 3. Change Port

Go to Web Preview and Go to Change Port and set port to 6070:
