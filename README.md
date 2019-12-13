# KataGo
So this project is derived from KataGo with the idea of exploring a better way of using a strong engine to model players. Previously most attempts at lowering the level of play for an engine involve training only on lower level games or introducing mistakes or limiting the engine in some way. I strongly disagree with this approach. A master human player is not made into a better teacher by disgarding all higher level knowledge.

Ideally I want to build and engine that combines a super-human level network with fixed weights with a seperate network that is able to using that superior knowledge and a player embedding that represents the knowledge and skills of a particular player to predict and model that players decisions. This would allow the creation of a bot the perfectly exploits a given players biggest knowledge gaps. You could use the embedding to create human like players of various levels with various knowledge gaps.

I hope that long term this could create a bot that plays ideally in order to instruct a player. Essentially a bot that plays good teaching games.
## License
This was the License note included in the original KataGo. Any modifications I make are similiarly BSD style released for free use.

Except for several external libraries that have been included together in this repo under `cpp/external/` as well as the single file `cpp/core/sha2.cpp`, which all have their own individual licenses, all code and other content in this repo is released for free use, modification, or other purposes under a BSD-style license. See [LICENSE](LICENSE) file for details.
