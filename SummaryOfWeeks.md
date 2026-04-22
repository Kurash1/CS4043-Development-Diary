# Week 2 (Febuary 2 to 8)

After finding the team I'd be working with, and the language and engine we'd be using. I spent the rest of week 2 re-familiarizing myself with them. I already had plenty of experience in the Godot engine, but I hadn't used GDScript as much. So I began reading through the plenty of GDScript documentation. This was less of learning the language, and more of just reminding myself of how the language worked again. After I felt comfortable enough with the concepts in my head, I made a small program that allowed me to send external program signals through a UDP Peer into GDScript.

# Week 3 (Febuary 9 to 15)

This is the first week I managed to make it to the labs, as I had ended up having a panic attack right before the labs on Week 2. During the labs we discussed the division of labour, and according to the division of labour I'll begin working on Saturday. So I can't say I've done much as of the writing of this. My role will be to make the enemy, target, and investigator Ai, while also making the primary map of the game. So what I've already done this week is look through some shopping mall blueprints (as that is the setting of our game), and then I worked on my own separate game project where I'm also working with ai, specifically I was re-familiarizing myself with all the parts of it that I used.

# Week 4 (Febuary 16 to 22)

I created a basic test_npc node that would just try to find a path towards the player and move along that path. I decided to just use the Godot pathfinding solutions instead of inventing my own. Which is a NavigationRegion node which contains nodes for each npc that have a child NavigationAgent node.

# Week 5 (Febuary 23 to March 1)
I was sick for the first half of Week 5 so I couldn't do as much work. But in the later half I managed to create a basic testing scene that would serve as a basic idea of the final game area. I also made the task_npc node, which would serve as the basis of all future developments. I made an npc_manager that would create a certain number of task_npc nodes in the scene, and assign them to go to specific stores in the map after which they should leave the store.

# Week 6 (March 2 to 8)
I spent the entirety of week 6 working on trying to solve the problem of the task_npc nodes getting stuck to each other. I did not solve this during week 6.

# Week 7 (March 9 to 15)
In week 7 I figured out a way to setup so each task_npc node counted as an obstacle for the others to avoid. So that somewhat made it, so they somewhat worked now. I still had a lot of testing to do, but as long as the amount of npcs remained low enough, and the scenes weren't too small, it should work.

# Week 8 (March 16 to 22)

# Week 9 (March 23 to 29)

# Week 10 (March 30 to April 5)

# Week 11 (April 6 to 12)

# Week 12 (April 13 to 19)
NPC_TYPES commit

# Week 13 (April 20 - 22)
