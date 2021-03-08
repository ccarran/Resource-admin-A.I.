#Resource administrator Artificial Intelligence¶
With the rise of Artificial Intelligence thanks to a lot of advancements being made through the last two decades, we've been finding ways to implement it to a lot of aspects of our lifes: From our video recomendations, to our research on fields like astronomy and medicine; from funny robots that can learn to kind of speak like a real human, to advanced AIs that can make a three dimensional space out of a two dimensional picture. And amidst all of these different applications, what I personally find the most interesting is the prospect of giving AIs the ability to tackle on those problems that, while obviously complicated in a real-life environment with hundreds of factors, at their core are actually mostly mechanical, and could potentially be solved using algorithms made by computers.

This is the scenario where I came up with the present project. From the natural resources of a country, to the economy of a small family, to the human resources of a business; the role of managing some form of resource is almost inescapable to humans, so I asked the question of to what extend an AI could be trained to learn how to manage some resources in the confined environment of a game, designed and coded by myself. This project doesn't intend to make an AI that could actually be used in a real life situation, but to explore the ability of an AI made using the currently available resources to tackle on this issue.

##Overview of the game
In the present game, the player is tasked with the mission to manage the resources of a spaceship to try and survive for as long as possible without running out of power, gas or crewmembers.

Each playthrugh is divided in turns, and in every turn four things happen: The resource being used as fuel is lowered, the crewmembers' hunger and thirst levels are lowered, a random event happens, and, depending on the turn, the player might have to make a decision on which resource is used as fuel or if the crew should eat.

###Main Resources
There are four main resources that the player needs to manage: Food, Water, Gas and Power. Food and Water are used to feed the crewmembers during the Meal events, and Gas and Power are used as fuel for the ship every turn, according to the player's decision on the Propulsion Method Choice event. The player starts with 100 units of each of these resources, and can resupply them in some of the Random events that happen every turn.

###Crewmembers
The crewmembers are the fifth, unofficial, resource that the player has to manage. Initially the player gets 6 crewmembers, but depending on the decisions made during the game, more might be added or some might be losed.

Each crewmember has a personal thirst and hunger gauge, which initially starts with 20 units and gets defiled by 1 each turn. If either one of these gauges reaches zero for one of the crewmembers, that specific crewmember will leave the spaceship. To prevent this from happening, the player can feed the crew during the Meal events, if there is enough food and water available.

###Random events
Every turn, the player gets to make a decision based on an event selected at random out of 6 possibilities. These are:

Space Station Event: In this event, the ship encounters a Space Station which offers to replenish one of the four main resources. The player has to select between two of said resources, selected at random.
Pirate Attack Event: Here, a fleet of space pirates wanders near the ship. The player has to make a decision on whether to spend some gas to safely scape, or not use any fuel and run the risk of getting caught by the pirates, in which case a random resource level is lowered.
Trade Event: In this one, another spaceship appears and offers to trade one resource for another. The decision, obviously is enough, lies in either accepting the trade or not.
Supply Beacon Event: The spaceship stumbles upon a supply beacon, which contain one of the main resources, and the player gets to option to either open it or leave it. There are no possible harmful outcomes of opening the beacon.
SOS Call Event: A sudden SOS message is received by the crewmembers from a nearby stranded ship. If the player decides to help the stranded ship's crew, they will join the spaceship.
Planet Exploration Event: Finally, for this event the spaceship gets in range of a planet, and some crewmates offer to go look for resources. If the player sends the expedition, two outcomes might happen: The crewmembers might return with one resource, or they could get lost in the planet.
Periodic events
Besides the random events that happen every turn, there are 2 events that happen at fixated intervals and involve a different kind of choice from the player. These are the Propulsion Method Choice, and the Meal Event:

Propulsion Method Choice: Every 5 turns, the player is asked to select one of the 3 different propulsion methods: Standard, Electrical and Gas. If the standard method is selected, until the next time this event is triggered, the spaceship will use 2 units of power and 2 of gas as fuel. If the Electrical or Gas methods are selected, 4 units of power or gas, respectively, will be used.
Meal Event: Every 6 turns, the player can decide if the crewmembers should go eat. If the player decides to make them eat, 6 units of water and food will be lowered and fed to each of the crewmembers, within the capabilities of the tripulation. This means that, if the player runs out of water of food midway through this event, the rest of the crewmembers that didn't get to eat will keep their current thirst and hunger levels.
Score system
The performance of the player gets determined by the score they get during their playthrough. Each turn, the player gets 100 points for each of the crewmembers that are still in the ship, however if the player loses one of their crewmembers (either by failling to keep them fed or losing them in the Exploration event) 500 points will be substracted from their score.

###Game over
Finally, the game ends when one of three conditions are met: The ship runs out of power, runs out of gas, or loses all the members of its crew. Running out of food or water won't result in a game over, but will obviously mean that the player is at risk of losing their crew to hunger and thirst.
