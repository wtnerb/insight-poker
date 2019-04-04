# insight-poker

This repo exists to contain a list of the different repos that make up Insight Poker. No files beyond the license and readme should exist here.

Some repos have not yet been pushed to github but do exist. Most likely still a work in progress.

Target release for alpha of full app is mid May. This may change if the developer does something silly like get a full time job.

## Repos
repo name/link | description
----------|--------
[poker evaluate](https://github.com/wtnerb/poker-evaluate)| A Go microservice that will determine the winning player(s) given a poker scenario.
[poker models](https://github.com/wtnerb/poker-models)|Data transfer objects, card object definitions, etc.
hand init |A Go microservice that will set up a game of poker, shuffle a deck of cards, deal, pick first player, etc
poker app |A Reactjs frontend that allows for easy user interactivity.
game host |A Go service that mostly acts as a router, calling to other services as necessary.
