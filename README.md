## RunUO - Ultima Online Server Emulator
[![GitHub Label](https://img.shields.io/badge/RunUO-2.3-blue)](https://img.shields.io/badge/RunUO-2.3-blue)
[![GitHub license](https://img.shields.io/github/license/bohica89/RunUO-2.3?color=blue)](https://github.com/bohica89/RunUO-2.3/blob/main/License)
[![GitHub stars](https://img.shields.io/github/stars/bohica89/RunUO-2.3?logo=github&style=flat)](https://github.com/bohica89/RunUO-2.3/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/bohica89/RunUO-2.3?logo=github)](https://github.com/bohica89/RunUO-2.3/issues)

## Introduction

This version of RunUO 2.3 is running on the .NET 2.0 framework, which is very old.
Security updates are obviously no longer being sent from Microsoft for .NET 2.0.
This means, running this version of RunUO comes with security risks. 
If you wish to use at a large scale, performace might also be lacking for public network traffic.

## Use Case

Updates to this version will be focused on providing some support for the needs of smaller groups of people.
Meaning, if you just want to start a server for family or friends, this is going to do the trick.

This version of RunUO also works very well for people with older, less powerful machines looking to host a server.

## Quick Start Guide

1. Open the folder scripts/misc/DataPath.cs.
2. To open .CS (C#) files, you can use Notepad++.
3. Edit line 16 and input the directory path where your UO client files are located.
4. Close the editor.
5. Click and run RunUO.exe.
6. Create an account and password. (If you mess up and it skips to password, press Ctrl+C)
7. Leave the terminal running. (This is the running server/shard service terminal)
8. You can connect to your shard using the following information: IP: localhost, Port: 2593.

You can use the ClassicUO client to connect to your shard. (https://www.classicuo.eu/)

## Multiplayer Setup

1. You'll want to port forward port 2593.
2. You'll want to also unrestrict this port in your local firewall settings.
3. Give your external IP address to your friends and the port for them to connect.
4. If you want to hide your external IP address, you can use a service like No-IP. (https://www.noip.com/)
5. No-IP offers 3 free addresses that directly link to your external address but hide it behind a URL address for public use.
6. Connect to the running server the same way as above.
