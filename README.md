PROJECT NAME: FLOTSAM

BY: AMINA NUHU 2511921

LINK TO GITHUB REPO: https://github.com/AminaMNuhu/2511921-1805-final-project 
LINK TO GITHUB PAGES: https://aminamnuhu.github.io/2511921-1805-final-project/ 

OVERVIEW OF PROJECT
Flotsam is an aquatic themed sidescroller game which follows a small clownfish through different aquatic entities; the Ocean Floor, the Underworld, the Submarine and the Marshes. It follows a pixel art aesthetic, reminiscent of a 1980s retro game.

THEMES AND DESIGN
The main theme of my game was to combine the aquatic theme with the retro 1980's theme, seeing as the basis of the game was to use tilemaps. To achieve this I decided to combine my original pixel art (the backgrounds, the player, the tile assets) assets made with Pixel Studio and Pixil Art with p5.js logic. Creating the pixel art was a big part of my project as every single visual element of the game from the player to the backgrounds where pixel art. I created specific pixel art for each game level; the backgrounds, platforms and assets which served different purposes in the game.

Using the provided side scroller demo as a guide, I began with the ocean floor idea and one tilemap and a few assets. I then built on this base theme by adding the 
subsequent levels by creating additional functions for each gamestate. I then decide to add cutscenes before each level to act as an introduction and provide directional gameplay advice for the player, as it could develop a linear narrative as the player travels between each level. Using p5.js resources online I decided to use if/else statements to switch game states and the cut scenes. Another coding element I implemented to further emulate the 80s retro game theme was adding a camera object. I attached this to the player's x axis so it follows the fish as it moves, just like super mario bros, or even chrome dino. I decided to make my tilemaps quite wide/long, so without the camera object, most of the gameplay would end up being out of the canvas’ bounds. 

A lot of retro type games and sidescrollers (particularly by Nintendo), are accompanied by instrumental tracks of the jazz and hip-hop genres or similar. To continue this theme I chose some fitting jazz and hip-hop instrumental tracks to back each cutscene and level. To play the music, I decided to try a coding technique not taught in the module (which the project brief encourages); switch/break statement. This appeared to be an equally effective method as if/else statements in switching between audio files. 

CHALLENGES
Some challenges I faced on this project was spontaneously implementing additional levels, as I had to go back and re-establish my original code (editing the variables, function, the if statements in the draw function, etc). Another challenge was trying to add sound effects to my assets which would be triggered by certain collisions. I tried both taught in the module and ones I found outside of the module. Neither worked (I didn't figure out why), so I settled with just bg music 

AESTHETIC DIMENSIONS
I believe that the parity between the technical systems of the game and its aesthetic work quite well. The 2D retro, pixelated, digital appearance of the game pairs well with the tilemap layout, opposed to using smooth, airbrushed 3D assets. Other visual choices such as the use of bright and varied colours and colour schemes within levels and cutscenes also added to this, as they provide thematic identity, technically and aesthetically.

UNREALISED ASPECTS OF PROJECT
If afforded more time I would reattempt the coding of sound effects that would be triggered by collisions. These would include, live down sounds, powering up sounds, coin sounds, etc. I would also layer the background music with multiple sounds to create an ambient atmosphere, imitating what each aquatic entity would sound like in real life. For example, the ‘Marshes’ (level 4) would have sounds of wetland animals, wind, water, etc. With time I would also implement a system where the player’s score is recorded so that they can replay and beat their highscore. I would also add more levels, as well as dialogue boxes. This would add to the narrative of the game, as they player could complete quests to pass a level, like an RPG. 
