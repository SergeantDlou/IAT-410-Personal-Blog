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

For this week I mainly worked on coding and looking up resources for unity. Our team dicussed the future of our game, mechanics, and concepts we wanted to implement. We reviewed the GDD and came up with some revisions. I did most of the coding for the first playable this week. It was a good learning experience and I feel way more comfortable with the unity game engine now after spending a lot of time on it. I also learnt how to connect different unity scenes together and to make prefabs. Both of which are and were very useful in the production of the playable. I used both of those in conjunction with the level design one of my team mates had created to have the player transfer between each level and return to the begging upon death. The prefabs were used to recreate enemies between each level and edit their values durring playmode.

Some things that I think that our team should add to the game for next week are:
A visual indicator of intended trajectory (between player and current mouse position).
A meter showing current speed and when your speed is low enough to propel yourself in any direction.
Some audio, for example: music, sound fx, etc.
A cooldown after wall-kicking to avoid spam clicks.
Animations for wall kicking, enemy death, and collisions.
Menu screen and menus in general.
