[***Game Design Concept***](https://drive.google.com/file/d/1-yiF2Pq-OgJaTXsMAQbIckoDzGINz26O/view)

_The skeleton for a game design concept._ 


## High Level Concept

***Working title :*** Abyssal Nexus

***Concept statement :*** A high level of management of tasks. Risking bots for the greater good or playing it safe.

***Target audience :*** People who love working the terminal and managing multiple tasks.

***Unique Selling points :*** It has a distinct graphic style, highly customizable, multiple play styles.

## Product Design

### Player Experience and Game POV
***Who is the player :*** The player is a operator in a control center.

***What is the setting :*** _Deep-Sea Exploration_. The game takes place underwater, where the player manages a team of underwater robots tasked with searching for anomalies in the deep sea. The robots must contend with strong currents, underwater creatures, and other challenges as they navigate the ocean floor.

***What is the fantasy the game grants the player :*** _The fantasy of discovery_. The game could offer the player the opportunity to discover new and unexpected anomalies in the deep sea, unraveling mysteries and uncovering secrets that have been hidden for centuries. The player could experience a sense of curiosity and wonder as they encounter strange and unusual phenomena and try to figure out what they mean.

***What emotions do you want the player to feel :*** _Fear_, _Excitement_. You can fear the unknown or get excited when you discover something cool.

***What keeps the player engaged for the duration of their play :*** To find out what still lurks out there.

### Visual and Audio Style

***What is the “look and feel” of the game :*** Cold and creepy. While you are just the operator you should feel there is something out there. Everything is top-down in the terminal, you can hear a bit of what the robots can hear. You can hear the surrounding ambience.

***How does this support the desired player’s experience :*** Managing in complex situation while you need to stay cool fits great with.

***What concept art or reference art can you show to give the feel of the game :*** Mix on old based terminal games. Some visuals based on _Duskers_, and atmosphere based on _surviving the abyss_. References at the bottom of this file.

### Game World Fiction
You are stuck in a control center deep underwater. You can hear weird things, so you send some robots to figure it out.  

### Monetization
***How will the game make money :*** Currently open-source so no plans to make money.

### Platform(s), Technology, and Scope 
Only desktops, since it will run in a terminal. Hoping tho on multiple operating systems so, windows, linux maybe even macOS.

## Detailed & Game System Design

### Core loops
***How do game objects and the player’s actions form loops :*** Solving problems, finding clues & equipment, going deeper.

***Why is this engaging :*** I believe solving a problem is one of the most engaging and exciting thing you can do, so with this you solve smaller problems so eventually solve the biggest problem.

***How does this support player goals :*** Gather more stuff get more chances to discover.

***What emergent results do you expect/hope to see :*** People feeling proud to achieve a task, getting curious to find out what is behind the next problem.

### Objectives and Progression
***How does the player move through the game, literally and figuratively, from tutorial to end :*** 
* The progression will be linear getting harder, but the player is getting stronger and smarter.
* The player only controls the bots through commands or routines.
* The only tutorial will be the interface and some basic commands.

***What are their short-term and long-term goals :*** Solving a problem to continue the core loop, long-term discover new thing find out what lurks.

***How do these support the player-fantasy :*** Feeling of discovery, will only happen if you progress. You can only overcome fear if you continue. 


### Game Systems
***What systems are needed to make this game :***
* Graphics Engine
* Terminal Engine (to get commands working)
* World generation
* Creature generation
* Anomaly generation
* History simulation

***Which ones are internal (simulation, etc.) and which does the player interact with :***
* _Graphics Engine_. This how the player is able to see the world.
* _Terminal Engine_. This is how the player interacts with the world.
* _World generation_. This is internal it is how the world looks. (_Internal_)
* _Creature generator_. What are creatures/things the player can find in the world. (_Internal_)
* _Anomaly generator_. What wierd thing is happening in the world. (_Internal_)
* _History simulation_. How did the anomalies and creature change the world. (_Internal_)


### Interactivity
***What is the player doing moment-by-moment :*** Managing the bots, thinking how to get around an obstacle. Making routines. Planning on where to go next.

***How does the player move through the world :*** By typing in commands, or having the bots following routines.

***How does physics work :*** Top-down so only collisions.

***How does combat work :*** Very open there can be some equipment that can fight back (stat check type of fight), but also you can lure the enemies into traps. 

***How does discovery and research work :***
- _Scanning_: The player could use their bots to scan the environment and search for anomalies. The player could receive data from the scan and use it to determine the location of the anomalies.

- _Observation_: The player could observe the environment and search for clues to uncover anomalies. This could involve looking for patterns, unusual behavior, or any other signs that indicate an anomaly.
 
- _Collecting Samples_: The player could collect samples of the environment or anomalies and bring them back to the control center for analysis. This could involve deploying specific bots or tools to collect the samples.

- _Analysis_: The player could analyze the data collected from scans, observations, and samples to gain insights into the anomalies. This could involve using specialized equipment in the control center, such as microscopes or chemical analysis tools.

- _Research_: The player could conduct research on the anomalies and their potential significance. This could involve studying historical records, collaborating with other experts, or conducting experiments to better understand the anomalies.




## References
GDC template : https://drive.google.com/file/d/1-yiF2Pq-OgJaTXsMAQbIckoDzGINz26O/view

### Visuals

[Terminal based ui](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstackoverflow.com%2Fquestions%2F2754576%2Fcan-anyone-suggest-a-java-or-scala-dos-terminal-based-ui-framework&psig=AOvVaw2IAIVwEF6D3jElJ0ffLbwt&ust=1677723627103000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCPjZnNjVuf0CFQAAAAAdAAAAABAE)

[Duskers normal view](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.wired.com%2F2016%2F05%2Fduskers-review%2F&psig=AOvVaw3pProJf7gXtAWwagOSkNix&ust=1677719984300000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCOC5rI_Iuf0CFQAAAAAdAAAAABAE)

[Duskers map view](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.wired.com%2F2016%2F05%2Fduskers-review%2F&psig=AOvVaw3pProJf7gXtAWwagOSkNix&ust=1677719984300000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCOC5rI_Iuf0CFQAAAAAdAAAAABAI)

[Surving the abyss](https://www.google.com/url?sa=i&url=https%3A%2F%2Ffingerguns.net%2Fgames%2F2023%2F01%2F17%2Fsurviving-the-abyss-early-access-review-pc-down-where-its-wetter%2F&psig=AOvVaw0-dCuKFgPaaEzWW-WyEk6U&ust=1677720067677000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCKidibfIuf0CFQAAAAAdAAAAABAU)