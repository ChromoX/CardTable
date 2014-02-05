# _Card Table (Not Final Name)_

_Description: Card Table seeks to be a generic simulator for any type of card games. Card Table will be able to connect in an ad-hoc fashion to other players to facilitate multiplayer gaming. At first Card Table will seek to implement the generic features required to play Dominion and Android: Netrunner_

## Project Setup

_Currently in a very basic form. Dependencies are included as well as some test data for Netrunner, and Dominion.
Below are some depencies I intend on using._

1. _[SVG.js](http://www.svgjs.com/)_
2. _[PeerJS](http://peerjs.com/)_
3. _[jQuery](http://jquery.com/)_
4. _More to come..._

## Testing

_Unit tests will be implemented as parts of the project become defined._

## Architecture

Basic Tenants:

Turn -> Phase -> Events

Cards are Active, Passive or Both

Active cards change game state

Passive cards modify game events

Cards can be "used". When a card is used an action has happened which creates an event.

Events are processed in a pipeline architecture. Example in img directory.

## Current Todo

1. _Basic Event System(Starting with Dominion)_
2. _Build Engine APIs (Card, State, Hand, Deck, Board, Event)_

## Future Features

1. _AI Player API_
2. _Voice Control_


## Business Ideas

1. _Provide servers for online play_
2. _Allow companies to license the game engine_
3. _Build/Host offical(Partnership with company) versions of card games using our engine_

### License

We should talk about this...