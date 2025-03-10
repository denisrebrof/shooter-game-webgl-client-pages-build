
## Quick Start Guide 🚀

### If you want to try this game on local machine, follow this steps:

Steps to run server locally:

1. [Download Jar Release File Here](https://github.com/denisrebrof/shooter-game-server/releases/latest/shooter-game-server.jar)
2. Open command line in directory with downloaded .jar file
3. Ensure that you have Java installed
4. Run downloaded .jar file with command: `java -jar shooter-game-server.jar --spring.profiles.active=dev`
5. Check if server started without errors
6. [Open Game Client Here](https://denisrebrof.github.io/shooter-game-webgl-client-pages-build)
7. If you want to test **_with multiple players_**, open another client instance in **Incognito Mode**
8. Play and Enjoy! 🎮 ♥

### Description
I wrote this project about a year ago for fun and to improve my skills in **Kotlin**, **Spring Boot** and **client-server** interaction

Based on this codebase, I released several projects on [Yandex Games](https://yandex.ru/games/) and [Crazy Games](https://www.crazygames.com/), using **DigitalOcean** for hosting the server

Some time ago, I stopped supporting these projects on **WebGL** game platforms, but you still can test them locally

### Features
* _Custom Web Socket server + client_
* _Dev mode for quick testing_


* Realtime Matchmaking ⌛
* Bots with simple AI support 🤖
* Game store 🏪
* Player Leveling Up 📈
* Progression Rewards 🎁
* UnLockable & Purchasable Weapons 🔫
* Multiple game maps 🗺

### Stack & Sources
|         |                                  Server                                   |                                     Client                                      |
|:--------|:-------------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| Stack   |                    Kotlin, RxJava, Spring Boot ,MySQL                     |                              C#, Unity, UniRX, JS                               |
| Sources | [Server Sources Repo](https://github.com/denisrebrof/shooter-game-server) | [Client Sources Repo](https://github.com/denisrebrof/shooter-game-webgl-client) |
