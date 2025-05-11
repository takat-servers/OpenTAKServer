# OpenTAKServer

![PyPI - Downloads](https://img.shields.io/pypi/dm/opentakserver)
![PyPI - Version](https://img.shields.io/pypi/v/opentakserver)
![Discord](https://img.shields.io/discord/1183578214459777164?logo=discord&label=Discord&link=https%3A%2F%2Fdiscord.gg%2F6uaVHjtfXN)
![GitHub Release Date](https://img.shields.io/github/release-date/brian7704/OpenTAKServer)


OpenTAKServer (OTS) is yet another open source TAK Server for ATAK, iTAK, and WinTAK. OTS's goal is to be easy to install and use, and to run on both servers and SBCs (ie Raspberry Pi).

This version is specific for TAKAT needs. Some functionality has been adapted for talking to our own management API and video management. We suggest to use the original version of OTS.

## Current Features
- Connect via TCP from ATAK, WinTAK, and iTAK
- SSL
- Authentication
- [WebUI with a live map](https://github.com/brian7704/OpenTAKServer-UI)
- Client certificate enrollment
- Send and receive messages
- Send and receive points
- Send and receive routes
- Send and receive images
- Share location with other users
- Save CoT messages to a database
- Data Packages
- Alerts
- CasEvac
- Optional Mumble server authentication
  - Use your OpenTAKServer username and password to log into your Mumble server
- Video Streaming
- Mission API
  - Data Sync plugin
  - Fire Area Survey plugin

## Planned Features
- Federation
- Groups/Channels

## Requirements
- RabbitMQ
- MediaMTX (Only required for video streaming)
- openssl
- nginx

## Documentation

https://docs.opentakserver.io

## Supporting the project

If you would like to support the project you can do so [here](https://buymeacoffee.com/opentakserver)
