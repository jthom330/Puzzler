## Puzzler Project Overview

### Intro
The objective of this project was to design a basic VR puzzle game using the Unity3D game engine for my first assignment in the Udacity VR nano-degree program.  The focus here was simply to familiarize myself with designing and implementing some basic interactions and movement within a VR experience.  I have worked with the Unity engine fairly extensively prior to this course, so to challenge myself I attempted to add a bit more polish to the provided template. 

In order to guide my goals, I decided to build my app around the use case of a casual mobile VR users.  Because of this decision, I felt that the application needed to be a bit more visually striking in order to be memorable to users who would likely try it and then uninstall.  With this in mind, I wanted to focus on the atmospheric aspects of the game environment.  I believe that the use of lighting and shadows turned out very well in the final result.  

The majority of my time with this project was spent with level design and experimenting with lighting options, as I expected it would be.  While I did modify the scripts slightly to allow for some animations and different highlighting options for the orbs, I would have liked to have done more of the scripting for this project.  However, this gave me an opportunity to focus on the design areas that I normally pay less mind to.     


### Outcomes
I found that my original concept did not vary much while I went through the process of building it out.  I feel that adding the extra touches of polish added quite a bit to the experience and atmosphere.  During testing, I received feedback stating that the additions of some of the extra animations, sound effects, and higher quality assets made the experience a bit more immersive.  The only area I would have liked to iterate more on was the terrain/backdrop, as it was not as detailed as the rest of the scene.  

#### Demo Video
[![Puzzler Demo](https://github.com/jthom330/Puzzler/blob/master/Puzzler/Screenshots/Main_Puzzle.png)](https://youtu.be/uju2j0xXLVo)

## Development

### Concept
I liked the original idea presented in the course of using a dungeon style setting.  Using that as a starting point, I wanted to add some implied story or purpose behind the players actions.  To accomplish this, I decided to add a path to imply the direction the player is traveling and a mountain range to block the path so that entering the dungeon was the only way forward.  

Original Level Design Sketch: 

![Sketch](https://github.com/jthom330/Puzzler/blob/master/Puzzler/Screenshots/sketch.png "Level Sketch")

### Audience
I decided to cater more to users who have had some casual VR experience in the past.  I chose this audience because I believe that is the largest target audience that would be trying out mobile VR experiences such as these.  Below is a persona I had in mind when designing the original concept.  

#### Persona
**Age:** 24

**Occupation:** IT Service Desk Technician

**Name:** Jane Smith

**Quote:** “I want to make the most of my leisure time.”

**Summary:** Jane works in IT and enjoys her job, but she makes it a point to make the most of her time away from work. This can vary from playing with a variety of apps and other software or tinkering on personal projects.
VR Experience: Casual User

### User Testing 
For this project I did two rounds of testing.  The first round was right after getting the basic scene functional, in order to get ideas about perspective and the environment.  The second round was when the app was in a near finished state for the purpose of adding a last bit of polish.  

#### First Round Results 
##### User observations
* Camera seems too low to the ground
* Terrain textures are too stretched out
* Dungeon needs more visual interest

##### Changes Made
* Adjusted camera height and the scale of objects
* Used higher resolution textures on the terrain near the player
* Recreated dungeon using higher quality assets, added animations to the doors, changed the colors and highlighting affect of the orbs, added several props to populate the scene

#### Second Round Results 
##### User observations
* Player is too close to the orbs
* Each orb's sound should be different 
* Sound effect volumes need to be adjusted

##### Changes Made
* Moved the puzzle solving way-point back so that all the orbs could more easily be seen at once
* Changed the pitch of each orb to be slightly different
* Reduced volume of the failure sound, the torch sound effects, and the door squeaking sounds

## Conclusion

Finished Game Screenshots:

![Screenshot](https://github.com/jthom330/Puzzler/blob/master/Puzzler/Screenshots/Start_UI.png "Screenshot")
![Screenshot](https://github.com/jthom330/Puzzler/blob/master/Puzzler/Screenshots/Halo_Effect.png "Screenshot")

The final product turned out to be as forboding and atmospheric as I could have hoped given the small scope of the project.  I used the terrain and a dark sky box surrounding the center of the scene to attempt to imply a story that the player could fill in on their own.  The use of lights to cast emphasized shadows on the scene, animated doors, and the addition of some environmental props helped make the scene come across as mysterious and slightly haunting.  I am definitely happy with the general look of the game.

Another aspect that I also put some focus on were the orbs and the players interactions with them.  I decided early that I wanted to embed the orbs in the walls around the exit to both indicate their purpose and make them fit more seamlessly into the environment I was trying to create.  I also wanted to vary the colors of the orbs to both add some visual interest as well as make the memorization step a bit easier.  The last alteration to the orbs, which would not have happened without user testing, was changing the pitch of each orb's sound to make the audio a bit less repetitive and to further aid with memorization.  I spent a bit more time on the orbs than I thought I would, but I like the results much better than the default orbs provided.     

Given my past experience with Unity, I did not learn much new material in terms of Unity's capability or how to implement functionality using it.  However, I took this project as an opportunity to focus on areas that I have less experience with.  In this case that would be level design and creating atmosphere.  In the past I have usually contributed primarily to game-play mechanics, so this exposure to atmosphere and level creation was an interesting new experience.  

Now that this application is completed I will be moving on the the next assignment.  However, I do plan on adding this project to my personal portfolio.  I may try to add a little more polish, especially to the environment, or adding more rounds to the sequence matching, but I am happy with the state that it is in.

You can check out some of my other projects at https://www.wileythompson.me/


