# IAT 410 Louis' Personal Blog
<bold>Game Dev Blog<bold>


WEEK1

For this week I did mainly research on a couple of games to
come up with ideas for the game proposal this week. I picked 3 tile based games
which I thought had interesting mechanics and would be simple to implement or
add a twist to. These three games were: Crypt of the Necrodancer, Helltaker, and Hoplite.
Crypt of the Necrodancer is a rhythm based dungeon crawler with some roguelike aspects. Helltaker is a
limited turn tile based puzzle game. And Hoplite is a turn based roguelike for mobile.

I first thought we could take one of the games and put a spin on it, however, I felt like possibly
a combination of the games would create for interesting mechanics. Something along
the lines of a limited turn based puzzle top down dungeon crawler. In the end with some of my inital ideas, 
I helped our team came up with the concept of a top down limited movement dungeon crawler with ocassional puzzle aspects.
I also ended up creating a possible brain visual for our game. I also helped out with the creation of the game design document and
aided in the recognition of some possible design flaws and how we could solve it otherwise.
![Image of Brain](https://user-images.githubusercontent.com/55293393/93465461-afbb5600-f89f-11ea-8f43-a43448b4c148.png)

I didnt find there to be much of a problem with team work at this step since most of it is just ideation anyway.

I also downloaded the Unity game engine this week in combination with visual studio for coding C#
for the Unity game engine. I had spent some time trying to get familiar with the interface and explored 
some online tutorials, espeically those of Brackeys from youtube. I ended up creating a mini 3D sliding game 
prototype using one of his video tutorials. I believe this will be very helpful with starting me off on
my journey to learn this game engine.



WEEK2


For this week it was more based on research for our game and trying to develop our mechanics for the game. I went and watched a couple more game design videos on YouTube made by Game Makers Tool Kit. His one video called Nintendo-Putting Play First made me realize the importance of building a game bottom up by making sure the main mechanics of a game is actually enjoyable to start with and to build off the main mechanic. Using that knowledge and reviewing the comments made during the game design proposal presentation I went to apply that to our game. Once I took a look at our game's primary mechanic of dodging I noticed a flaw within the movement design. We had initially thought that the player would take damage by hitting a wall and would not be able to stop moving until it hits a wall. However we figured that you would inevitably take damage then since you can not steer away from a wall. We Did not end up coming to a conclusion to resolve this issue and decided we would take a week to come up with ideas to resolve this issue. A suggestion I had would be to allow the player to redirect themselves mid movement once. And if the angle in which the hit a wall is shallow enough it will prevent them from taking damage. However, to prevent infinite launching in the game, the redirection will be limited to 1 time per each time they touch a wall, meaning they'd have to touch a wall to reset it.


![Image of Game Example](https://user-images.githubusercontent.com/55293393/94105302-d886a280-fded-11ea-9630-299489c59de6.png)


So to conclude this journal entry, we need to figure out the main mechanic before trying to implement new ideas since trying to build off of a shaky foundation will lead to disaster. Some of the movement mechanics might need to be tested via prototype before we for sure implement them since we want the movement to be fluid. This is because the game is going to be fast paced for the most part.


WEEK3

For this week I again was doing a tad more research along side with figuring out the components of our game design. For this week our team met up and discussed our game's flowboard, gameplay, cast, and narrative. I mainly analyzed the gameplay aspect of our game during our meeting and this week in general. I did the gameplay aspect of the discussion. What I ended up writing was that the main perspective in the game is going to be top down with an interaction model being avatar based. The core gameplay loop will consist of going into a room and analyzing it, dodging all the enemies and the environment, once enemies are dead then proceed to the next room. The winning play for each room is to have one enemy left and to dodge their attacks until they kill themselves. The smart depth in the game loop will be the varying environments and possible use of powerups in each room which will affect how you have to move around the room and can lead to different strategies. These different strategies will allow the player to get to winning play (having one enemy left) in different ways. A lot of the gameplay ideas relates to a game called Binding of Issac.

![Game movement idea](https://user-images.githubusercontent.com/55293393/94776721-11d38b00-0377-11eb-89d6-3c3a1eec46b9.png)

I also then resuggested the change in movement mechanics same as before but instead of just ridirection, it will also freeze time for a second to help let the player make a decision. I got this idea mainly from one of the more interesting mechanics called "bash" from a game called Ori and the Blind forest.
For next week I think our team should start working on completing the prototype and do some proper tests on the mechanics to make sure the game will be enjoyable.

WEEK4

For this week I was mostly doing research on unity and working on the prototype for this weeks lab. Our team met up to discuss the future of our game after some minorly harsh critisim recieved from the previous lab. We wanted to re-evaluate what made our game special. It seems we ended up deciding that what made the game unique was the movement and dodging component of the game. After some brainstorming and deliberating we ended up on deciding on a movement scheme where you can only launch yourself when you are near a wall. You get to freeze for a minor second to choose your direction but if you dont choose your direction in that timeframe you will then unfreeze and keep going in the same direction as before. My role this week was programming all the core mechanics into the prototype of our game. I did some reasearch for this by looking at Brackeys unity tutorials on unity and reading the unity documentation.

![Game Prototype](https://user-images.githubusercontent.com/55293393/95422990-2a065580-08f5-11eb-8ee8-89b8fe89e8bb.PNG)

I believe what our team needs to work on now is the main look of the game with animations and such along with refining the smaller details like, how much health should we have, how much health shoud he enemies have, etc. We also need to work on level design as that is also a large part of our game. We should also test out the prototype robustly as it is going to be the basis on which we will be amking our game.

WEEK5

For this week I mainly worked on coding and looking up resources for unity. Our team dicussed the future of our game, mechanics, and concepts we wanted to implement. We reviewed the GDD and came up with some revisions. I did most of the coding for the first playable this week. It was a good learning experience and I feel way more comfortable with the unity game engine now after spending a lot of time on it. I also learnt how to connect different unity scenes together and to make prefabs. Both of which are and were very useful in the production of the playable. I used both of those in conjunction with the level design one of my team mates had created to have the player transfer between each level and return to the beginning upon death. The prefabs were used to recreate enemies between each level and edit their values durring playmode. I also helped add some of the new visual assets to the game aswell. During the creation of the playable I also had to look up some unity doccumentation, mainly on the scene manager and how it interacts with the build order.

![Level Design Unity](https://user-images.githubusercontent.com/55293393/96086044-84b02c00-0e76-11eb-9351-bc6260722813.PNG)

Some things that I think that our team should add to the game for next week are:
A visual indicator of intended trajectory (between player and current mouse position).
A meter showing current speed and when your speed is low enough to propel yourself in any direction.
Some audio, for example: music, sound fx, etc.
A cooldown after wall-kicking to avoid spam clicks.
Animations for wall kicking, enemy death, and collisions.
Menu screen and menus in general.

My main goal will be how to implement the animations into unity using code or other means. And the other is to do the same with audio, along with completing other visual cues.

WEEK 6

For this week our team discussed what we wanted to accomplish within the time to the next milestone/alpha code. What we wanted to change is: 
Integrate momentum into gameplay
Basic enemies should probably not kill themselves on their own
Maybe add a toggle for full view vs tight view
Skateboarding guys dont take damage unless you’re near them
Make sure level wall sprites 
Speedometer
Soft blocks will appear when all enemies are dead
Part of level design as well (moving or stationing)
Sound cues
Arrow showing trajectory
Glitchiness
Level Counter for now
Tutorial/story but that’s later
Journey from house to brain tower
Add cooldown for clicks
When room starts add a timer before the room begins (mario cart style plz) can make graphics for it later
Make HP pickup bigger
Fix general scale

Ive started planning out the coding aspect of things and am now thinking of implementing a fixed state machine for the AI. Was thinking of using the fixed state machine for the basic enemies to speed up when they sense the player is nearby. Along with that, I was thinking of adding so that the more advanced enemies patrol the area looking for you, and then change states when they see you. The state they will change to is one where they charge towards you at high speeds. For implementing momentum into game play I believe we should have the enemies increase speed as you increase your speed, they will then take more damage against walls but in turn apply more damage to you when they do hit you. I have also been looking up guides on how to implement sounds and small animations into unity. I believe it will be pretty simple to add. 

WEEK 7

Our team worked on more design and implementation of our game this week, preping for the alpha code for next week. We decided on a bunch of features we wanted to complete and are going to combine them together over the coming weekend. A list of the materials in which I have been tasked to do are:

NO TELEPORTING, doors to go back and forth between rooms
Clicking cooldown
Sweetspot thing 
Enemies slowing with powerup
Shield with powerup
Visual health bar filling back up after each level
Visual Cue for brain 

So far I have implemented the door feature by creating doors once the maps/level's enemies have died. The spawn in the walls and once collided with, it will take you to the next level. It will spawn you according to where you entered through (so if you enter through the top, it will spawn you on the bottom side of the map).

![Level Transfer](https://user-images.githubusercontent.com/55293393/97658296-33cd3580-1a29-11eb-9edb-bf0a06aeceed.PNG)
Enter through top end up on bottom.
![Level Transfer 2](https://user-images.githubusercontent.com/55293393/97658361-5b240280-1a29-11eb-962b-cfd3bccb8760.PNG)

I have also implemented the cooldown timer on the wall kicks (the click cooldown from the list of things to complete). I did this by having a timer count down after clicking to jump so you cannot jump from the wall until the timer is up. This will prevent the spam clicking bug that was in the game previously, it will also add a bit more challenge to the game. The health bar replenishing after each level has also been completed.

Things that our team should work on this week are combining our parts of the project together (code, level design, and art) before next week and the completion of playtesting. We should also slightly revise the GDD as we have made some minor changes to it since the previous feedback from labs/playtests.


WEEK 8

This week I completed the rest of the features which I had originally planned to finish last week via code on unity. Our team met up and a discussed the implementation and presentation for this week as well. I added the shield power up by creating a new object and adding a trigger collider to it. Then made it so if the player collided with it, the player will become invulnerable to collision for a short period of time. Furthermore, while the power up is active, a shield sprite will appear around the player providing visual feedback for the power up. I implemented the freeze power up in a similar fashion the only difference is that I made the acceleration factor of the enemies halve while the power up factor is in play. I had also refactored some of the door/level transition code to make it more readable and easier to implement then the previous version of the implementation.
I after implementing most of the mechanics into the game I then added some of the art that my teammate had made. Did this by changing the sprites and prefabs the previous sample art was using.
Next week I believe I should focus on fixing up the AI and making them more responsive to how the player functions. For example adding momentum to them as the player gains momentum. I also think we should add new puzzle rooms along with adding new types of enemies to add more variety.

Week 10

This week our team met up to discuss plans for the beta code assignment. We decided on a set of goals for each of us to complete this week. For me my set of goals was to create a new batch of enemies. One of these enemies will dash, and cause and explosion upon collision with any object. The explosion will damage everything around it and knock it away. The other type of enemy that will be added is a ranged enemy. This enemy is important as we dont have any ranged type enemy in the game currently. This will add variety to the game and help create more effective difficulty ramps in our game. The ranged enemy will stand still and shoot at you. To kill it, you have to get its bullets to bounce back at itself. Im currently programming its line of sight feature in unity using raycasting. Creating this enemy also helps with my coding ability in that regard. I beleive the next step for our team here is to combine our indivdual goals and see what is working and what still needs to be worked on before submission next week.

Week 11

This week our team met up to discuss the final plans for the beta upload. We decided to finish up our portions of the project and combine them before submission. I completed the all the different enemy types I had originally set out to create. These include the exploding enemy which dashes and explodes when it hits something. The range enemy shoots bullets but doesnt move. The bullets bounce around and you are able to kill them by having it bounce back at the enemy. I also created a boss enemy which is similar to the range enemy but instead of shooting bullets, it shoots other enemies. I also created a momentum system where if you kick off of a wall at the right distance away from it (basically have to time the jump) it gives you more momentum then it would if it were too close to the wall. This allows timing to be a mechanic and adds a bit of skill too. Our team needs to work on a menu system now and maybe add some sounds for the final game.
