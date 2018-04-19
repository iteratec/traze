# Traze
Traze is a simple tron-like multi client online game serving as a playground for exploring new technologies.

## Hosted by iteratec
You can join a hosted instance at [traze.iteratec.de](https://traze.iteratec.de).

## Host yourself
TODO: add docker-compose.yml

# Components
The traze project consists of multiple components:

[traze-gamserver](https://github.com/iteratec/traze-gameserver) implements the gamelogic in haskell and publishes the game state to the broker.

[traze-web-grid](https://github.com/iteratec/traze-web-grid) renders the game state as a grid with players on a canvas

[traze-client-python](https://github.com/iteratec/traze-client-python) a client based on Python 3.6. 

[traze-client-java](https://github.com/iteratec/traze-client-java) a client based on Java. 
