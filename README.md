# COMP313_Assignment1

Name: Daniel Pullon

Course: COMP313

Assignment: 1

Title: Rollaball

LINK TO VIDEO:
https://drive.google.com/file/d/1-O1g03o5YhHNTqOJIOlyZQfyt0WqDKLE/view?usp=sharing


Game Description

- Main Action:
  The main game action is to roll the player controlled ball around the map and collect all of the pickups. 
  The pickups are the floating gold cubes. In the case of level 2 you must navigate through the maze and survive without dying. There are very minimal UI elements that encourage the player towards these goals. Even though there is no clear tutorial, I like the progression between level 1 and 2, level 1 is very much a show don't tell tutorial, there is no way to lose and it becomes quickly clear that all pickups need to be collected. The hearts also do this as immediately when damaged you notice the camera shake and a loss of a heart.
  
- Hardest part:
  The hardest part for me was trying to get the arrows to correctly spawn and shoot from the arrow shooter. It took awhile to figure out how to correctly spawn one object from another, eventually I found a tutorial that explained to use a Source Object and that worked well. The next challenge was that I only wanted the arrows to fire when the player was crossing the path, so that the arrows didn't just constantly fire. I then had to implement a trigger point in front of the arrow and specifically check that when the player was near. 

- Most interesting:
  The most interesting for me is the subtle camera interactions that I implemented. When the player moves the ball, in order to give the feeling of momentum I implemented a camera that wasn't tied to the ball and instead is attached by a spring arm, this allows fun and immersive interactions, such as the camera having a slight lag behind the ball to give the feeling of acceleration. The other interesting camera interaction was shaking the screen when the ball is hit, alongside the sound effects that I downloaded, I feel this gives the player a very strong reaction when the ball is damaged further immersing the player.
