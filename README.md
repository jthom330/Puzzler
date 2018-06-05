## Puzzler Project Overview
The objective of this project was to design a basic VR puzzle game using the Unity3D game engine for my first assignment in the Udacity VR nano-degree program.  The focus here was simply to familiarize myself with designing and implementing some basic interactions and movement within a VR experience.  I have worked with the Unity engine fairly extensively prior to this course, so to challenge myself I attempted to add a bit more polish to the provided template. 


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
* Camera seems to low to the ground
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

Given my past experience with Unity, I did not learn much new material in terms of Unity's capability or how to implement functionality using it.  However, I took this project as an opportunity to focus on areas that I have less experience with.  In this case that would be level design and creating atmosphere.  In the past I have usually contributed primarily to game play mechanics, so this exposure to atmosphere and level creation was an interesting new experience.  

Now that this application is completed I will be moving on the the next assignment.  However, I do plan on adding this project to my personal portfolio.  I may try to add a little more polish, especially to the environment, or adding more rounds to the sequence matching, but I am happy with the state that it is in.

You can check out some of my other projects at https://www.wileythompson.me/


