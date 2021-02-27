# bash-swarm-command

Use bash to command the swarm of drones throughout asteroid belt of a distant solar system.


## The Story
Rival companies decided to mine resources of an asteroid belt of a distant solar system.

Seed interstellar ships of each company deployed the initial swarm of drones.
Each drone moves within the asteroid belt, but orbital mechanics prevents them
from stopping near any of the asteroids - it requires too much fuel.
Instead, drones are passing by the asteroids picking or dropping the cargo
and using asteroid gravity assist to slingshot itself to another asteroid.

That means a drone always need to have the next target besides this one.

waypoints: asteroid1 -> asteroid2 -> asteroid 3 -> (back to asteroid1)

### possible missions:
* probe asteroid? (maybe we already know geo survey data from spectrometry)
* establish mining colony
* establish production facility
* establish stockpile facility
* move to
* refuel at
* pick at
* drop at

### asteroid types
* mineral (mine)
* comet   (fuel production)
* hollow  (resource stockpile)

### rules
* only one type of facility can exist on an asteroid
* ships can transport only one unit of cargo
* when rival ships meet in orbit, they self-destruct
* rival drones have to arrive N time to capture the facility (how many exactly? maybe half as much, as already visited by current asteroid holder)

## Game Flow
Use the provided bash script to perform the following commands:

* start a new game
* log - run to see what happend
* status - show current status
* command - set a mission to a drone (as next or as new)
* turn - next player or next turn

