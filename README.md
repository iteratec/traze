# Traze
Traze is a multi client online tronlike game with MQTT based protocol. It aims to provide a playground for various game clients, AI game bots, and showcase of a resonable secure MQTT application, and it’s fun! You can write your own game client and participate in the game using the specified protocol.

## Hosted by iteratec
You can join a hosted instance at [traze.iteratec.de](https://traze.iteratec.de).

## Protocol
The game protocol facilitates multiple MQTT topics with JSON payload. An extensive documentation of the protocol details is provided on [traze.iteratec.de](https://traze.iteratec.de).

## Components
The traze project consists of multiple components. Each component has their own repository and lifecycle. You can find all traze related code under the [traze topic](https://github.com/topics/traze) on github. Some important examples are:

### Core

These are the core components of the traze game

[traze-docs](https://github.com/iteratec/traze-docs) web documentation of the traze protocol.

[traze-gamserver](https://github.com/iteratec/traze-gameserver) haskell game server implementation for the traze protocol.

[traze-web-grid](https://github.com/iteratec/traze-web-grid) web view that renders the game state as a grid with players on a canvas

### Client Libraries

These are some client libraries that can be used to interact with the traze game server.

[traze-client-python](https://github.com/iteratec/traze-client-python) a client library based on Python 3.6.

[traze-goclient](https://github.com/iteratec/traze-client-go) a client library for golang

### Human Interface Clients

Game clients for human players

[traze-client-java](https://github.com/iteratec/traze-client-java) a client based on Java.

[traze-javascript-vanilla](https://github.com/iteratec/traze-javascript-vanilla) a client based on (vanilla) ES6 JavaScript which is both for steering a player and rendering the grid ([demo](https://iteratec.github.io/traze-javascript-vanilla/))

### Bot Implementations

[traze-golang-bot](https://github.com/iteratec/traze-golang-bot) a traze bot written in go.
