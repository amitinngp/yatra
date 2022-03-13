# Yatra - Design Handbook

## Description

This is intended to help business with in-built UI components that can be seamlessly integrated as a package and utilized.

### Dependency

- node version > 12.x
- Expo cli

#### Installation

This project uses React Native components with typescript support . Transpiled via Babel.js .
For package manager either npm or yarn can be used. We prefer yarn over npm in setup.

### Local Environment Setup

- check the node version 12 and higher
  `node -v`
- install expo cli
  `sudo npm i -g expo cli` for mac.
  `npm i -g expo cli` for windows.
- install Docker 
  `docker-compose build` #  build docker image
  `docker-compose up`    #  start docker container
  `docker-compose down`  #  stop docker container 
  `docker ps`            #  list active container
#### Run app

```
    "expo start" for deafult , it will ask you later about which port and which environment you want to run your code
    "expo start --android" for running on android emulator
    "expo start --ios" for running on ios simulator
    "expo start --web" for running on local browser.
```
# Using Docker in local env 
  "docker-compose up"
  
To run in actual device

```
    Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

    Press a │ open Android
    Press i │ open iOS simulator
    Press w │ open web

    Press r │ reload app
    Press m │ toggle menu
    Press d │ show developer tools
    shift+d │ toggle auto opening developer tools on startup (disabled)

    Press ? │ show all commands
```

##### Authors

- [@amananurag](https://github.com/amitinngp)
- [@amit](https://github.com/amananurag)
- [@nikeshgadekar](https://github.com/nikeshgadekar007)

###### version history

- 0.1 initial release

##### Licence

MIT Licence

##### Acknowledgement
