<div align="center">
  <a href="https://github.com/Greazi-Times/ScoreboardNumberRemover">
    <img src="pack.png" alt="Logo" width="128" height="128">
  </a>

<h3 align="center">Scoreboard Number Remover</h3>

  <p align="center">
    A resourcepack that allows you to remove the numbers on your scoreboard
    <br />
    <br />
    <a href="https://github.com/Greazi-Times/TechsDiscordBot-V2">View Documentation</a>
    ·
    <a href="https://github.com/Greazi-Times/TechsDiscordBot-V2/issues">Report a Bug</a>
  </p>
</div>

<p align="center">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Greazi-Times/IOT_MQTT" >
  <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/Greazi-Times/IOT_MQTT">
</p>

<br/>

---

## Introduction
This system resourcepack is created to remove the scoreboard numbers of your scoreboard.
You can either use a already compiled pack on the releases or compile it your self.

Usage on your own resourcpack is allowed and can be done no support will be given what so ever on how to import this to your own resourcepack.

<br/>

## How to install it on your server
To get your resourcepack on your server you will need to do some extra steps. You will first need to host your resourcepack some where like Dropbox.
<br/>
For this guide we are using Dropbox.

<br>

First you will need to upload your resourcepack to Dropbox and copy the share URL
<br>
2. Now you need to change the last number `0` to a `1` shown below
```
https://www.dropbox.com/s/jysxaohomoedjqe/%C2%A7aScoreboard%20Number%20Remover%20%C2%A7r.zip?dl=1
```
In the `server.properties` file you will need to copy that link to the following setting:
```properties
...
server-ip=
resource-pack-prompt= https://www.dropbox.com/s/jysxaohomoedjqe/%C2%A7aScoreboard%20Number%20Remover%20%C2%A7r.zip?dl=1
allow-nether=true
...
```
When you restart your server it will be now be loaded on the player when he or she joins the server
