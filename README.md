# PokemonEmeraldRL
A RL project leveraging Monte Carlo and PPO algorithms to enable an agent to successfully play Pokemon Emerald with the end goal of defeating the first gym leader.
[Fill out more description about what this project is, what pokemon is a little, how the battles work, etc)

## Instructions for Running Model/Agent
The first step to run this program is to setup a local Pokemon Showdown server. To do so, follow below:

1.) Install the latest version of [Node.js](https://nodejs.org/en/)
2.) Clone the pokemon-showdown repository and follow the setup instructions below:
```
git clone https://github.com/smogon/pokemon-showdown.git
cd pokemon-showdown
npm install
cp config/config-example.js config/config.js
node pokemon-showdown start --no-security
```
