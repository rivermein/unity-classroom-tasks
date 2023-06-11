uhh i have no clue how to use unity

this helped https://docs.unity3d.com/ScriptReference/GameObject.FindWithTag.html

So. Uh. The task.

<b>Describe some best practices for organising your Unity project</b>

A good practice when organising your UInity project is to keep things in different directories; your sprites in a 'sprites' directory and your scripts in a 'scripts' directory. This makes finding your bits and pieces easier, as they have a designated place where they should be.

<b>Explain the concept of GameObjects & Components, & how they are related.</b>

A GameObject is essentially a container which holds components representing the things within your project. Components are things such as the Rigidbody, which controls how the GameObjects behave. One GameObject can have many Components.

<b>Explain the concept of Prefabs. What are they, & how do they contribute to the efficiency & reusability?</b>

A Prefab is a GameObject that has already been created with all its Components, and can be saved for future use. You can also utilise them in other projects. This is good for efficiency because it means that you don't have to create new GameObjects and refactor them every single time you want to use them. You can also give them to your students, for example. 

<b>Explain the concept of game object hierarchy. How can you organise & structure game objects using parent-child relationships? Provide an example of a situation where using hierarchy can be beneficial.</b>

Game object hierarchy is used to group game objects together so that you can use the same settings (such as tags and position) on every game object, meaning you only have to change the settings in the parent and it will change it for every child.
This is time-saving if you have a large amount of game objects that you want to function similarly, so you don't have to move them all individually, as they will all inherit the position of the parent. For example, in a monster-fighting RPG game, you could have a shield game object that you want to move with the player, so you'd make the shield a child of the player.

<b>In the game Pong, how would you implement the collision detection between the ball & the paddles using colliders?</b>

If you put a collider around the ball and the paddles, you can make them react when colliding with each other. You can make the ball, upon collision with the paddle, change direction and go back towards the other side. It's probably a lot easier to create Pong in Unity than in Windows Forms.

Uh, that's it, I think. I'd like to say a formal apology for making you read this.
