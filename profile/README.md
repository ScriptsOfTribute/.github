## Tales of Tribute AI Competition


### About

The deckbuilding card game *Tales of Tribute* is a special activity recently added to the massively popular multiplayer online role-playing video game [The Elder Scrolls Online](https://www.elderscrollsonline.com). Although the game remains small by CCG standards (about 120 cards and only a few keywords), it is interesting and challenging for humans, with a significant potential for being a good AI testbed.

The players start with the same base cards and build their decks during the game by buying cards from a shared resource pool called the Tavern (a concept similar to Dominion). Tales of Tributes encourages long-term strategic planning - to ensure the deck we build contains enough strong cards and is not clustered with weak ones. In the meantime, because of a huge randomness factor influencing e.g., which cards occur in the Tavern, it is usually hard to stick with a pre-made plan - so it also requires considerable adaptiveness. 

Tales of Tribute AI Competition aims to fill the void after the [Hearthstone AI Competition](https://hearthstoneai.github.io) while being significantly more challenging than a toy problem covered by [Legends of Code and Magic](https://legendsofcodeandmagic.com/) and the [Strategy Card Game AI Competition](https://github.com/acatai/Strategy-Card-Game-AI-Competition).

The competition will be run using *ScriptsOfTribute*, an open reimplementation of the original game in .Net framework designed especially for this event. It features the game manager that allows running AI agents implemented as C# classes against each other and a graphical user interface that support human vs. AI games. 

The competition's winners will be decided upon the global winrate in all vs. all tournament, conducted on a large number of mirror matches using the same seeds.


### Competition

We plan to launch a competition co-located with [IEEE Conference on Games 2023](https://2023.ieee-cog.org/), and currently are in the middle of migrating the game engine and adding some features.

More details soon...

### Thesis

The initial version of the ScriptsOfTribute has been described in the [engineer's thesis](https://jakubkowalski.tech/Supervising/Budzki2023ImplementingTalesOfTribute.pdf).

```
@mastersthesis{Budzki2023ImplementingTalesOfTribute,
  title={{Implementing Tales of Tribute as a Programming Game}},
  author={Budzki, Dominik and Kowalik, Damian and Polak, Katarzyna},
  type={Engineer's Thesis},
  year={2023},
  school={University of Wroc{\l}aw}
}
```













