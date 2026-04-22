# Week 10 (March 30 to April 5)
During this week I finally decided to do some more concrete work after getting nowhere by just thinking about things. I now had an event that told me when the npcs heard gunshots or grenade explosions, so I made them have a state system like so:

enum STATE { STATE_IDLE, STATE_TASK, STATE_FLEEING, STATE_PURSUIT }

currently, only STATE_TASK and STATE_FLEEING are being used. I also separated the units into the types of:

enum UNIT_TYPE { UNIT_CIVILIAN, UNIT_GUARD, UNIT_HITMAN, UNIT_TARGET }

though, in this I only currently used UNIT_CIVILIAN. I did begint to do the basic logic for the UNIT_GUARD and UNIT_HITMAN, in that I made it so if they heard a gunshot or grenade explosion and they could see the player (linecast), then they'd become hostile. So when I implemented the gun logic, they'd start shooting at the player.
