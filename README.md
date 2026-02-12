# GDIM32 In Class Activities

# W6
## Activity 1: Tool Demos

- Don't use GetComponent in Update(). Use in Start()?

- Make player a member variable?

- Use GetComponent if the object hasn't been introduced yet.

- Mesh colliders are pretty inefficiant. Use simple ones like circle collider.

- Using too many Rigidbodies will make your game run slow. If all you need to do is detect a collision, put a Rigidbody on the player and not the other object.

- Singleton example: W6 Demo3 _Breakpoints --> checking that there's only one at a time. Awake() is called before start! Set singleton up in Awake. Set ResetGame(); in Start().


## Activity 2: Final Project Group Meeting

- Role call: everyone was here!



# W5
## Activity 1

1.) what do you think of the design of these interfaces and abstract classes? Would you keep it the same, or change it, if you were building a project with items like these?

- I would keep it the same because the item class doesn't need to become a componant.

## Activity 2

2.) in the second demo, what classes represent the Model, View, and Controller aspects of the MVC pattern used in the scene?

- The scriptable objects represent the model, the view is represented by the enemy dialogue and player ui, the the player and enemy represent the logic.

## Activity 3

- Player script includes: abstract class. As well as scriptable objects (Ex: for different character movements as well as different character health stats?) 
- Attacks would use: inheritance (Ex: for the character to have unique attacks --> punch : Attack, as well as different players having different attacks)
- State machines for what state the player or

## Activity 4

Attendance: Bilal, Laura, me
[Final project proposal](https://docs.google.com/document/d/11w2xkRcvvsdrWrjTOsVOLnSm630WmjlCOwrMvn1rDKk/edit?tab=t.0)    

# W4
## Activity 1
Partner: Kai


1.) When you run the game with multiple locator objects in the scene, the duplicate locator objects delete themselves, leaving only one locator object. The code: 

if (Instance != null && Instance != this)
        {
            Destroy(this);
            return;
        } 
Makes sure that only one Locator exist at a time while the game is running. 

## Activity 2 Mini game 4 Breakdown
![IMG_8699](https://github.com/user-attachments/assets/11cc3b0d-7e63-477b-9777-52e8246fada4) 


# W3
## Activity 0-2
My partner for the activity: Alejandra

## Activity 3
![Uploading IMG_8583.jpg…]() 


# W2
## Activity 1
![Uploading IMG_8541.jpg…]()

## Activity 2
[link to commit](https://github.com/UCI-GDIM32-W25/mg2-sloan05/commit/a9a9bb949befcb4d9b34b04b1aaad61d0039c794)
In class, I worked on getting the penguin to jump, I set up the coin prefabs, the ground, and the penguin sprite. I also started setting up the code that is supposed to "destroy" the coins once the penguin collects/collides with them. Everything's set up in the hierarchy correctly, and I attached colliders and rigibody to the coins, ground, and player character. Lastly, in order to make the coins spawn on the right, and then despawn on the left, I set up a square GameObject on the right and attached its own script to it, and set up a similar square GameObject to the left with its script attached to it. The square on the left has a collider component. My plan was to have the square GameObject on the right spawn the coins, and the square GameObject on the left "destroy" or despawn the coins once the coins collide with it.

# Week 1
## In Class Activity 3
Link: 

https://docs.google.com/document/d/1HH-a70vlsNRXiXXa4zF664u3KKXgsxgVxMmo6fgR_Y0/edit?usp=sharing 

## In Class Activity 2
1.) x = 10

2.) x = 2

3.) This line prints a line of dialogue in the console: "Hello World" every frame.

4.) replace ??? with MonoBehaviour

5.) At the start of the game, it prints x = 10. 

6.) The name of "10" is an argument. It represents the starting amount or number at the beginning of the game. ("x=" + x) is a parameter which represents what we're passing in for x. It will show in the debug log console: x = 10

7.) The _playerTransform variable is instantiated but never used.

8.) Transform.Translate is written incorrectly. It should be replaced with _playerTransform.Translate
## In Class Activity 1

- Make notes
- Don’t procrastinate!
- Read the pre-learning slides
- Use out of class tools (YouTube / Unity documents)
- Take advantage of support when in need of assistance: peers, LAs, Office hours and discord
- Ask questions
- *Learn how to use the inspector
- Create map concepts 
- make sure your itch links work for the love of god




- Create bullet points by writing dashes.
- Here's another bullet point entry.


Remove all placeholder text in order to get full credit for README file formatting.
