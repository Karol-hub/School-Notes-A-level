Computer Science 
Advanced GCE H447 
Unit F453

Name: Karol Jeziorczak
Candidate Number: 4162
Centre Name: Rugby High School
Centre Number: 31255

<div style="page-break-after: always;"></div>

# **Sources** 
Name: 
URL: 
Date Accessed: 

# **Image sources** 
Name: Risk of Rain 2
URL: [https://store.steampowered.com/app/632360/Risk_of_Rain_2/](https://store.steampowered.com/app/632360/Risk_of_Rain_2/)  
Date Accessed: 25/09/23

Name: Rain World
URL: [https://store.steampowered.com/app/312520/Rain_World/](https://store.steampowered.com/app/312520/Rain_World/)
Date Accessed: 25/09/23

Name: Celeste
URL: [https://store.steampowered.com/app/504230/Celeste/](https://store.steampowered.com/app/504230/Celeste/)
Date Accessed: 25/09/23

<div style="page-break-after: always;"></div>

# **Project Introduction** 
For my project I intend to create a 2D rouge like game which is focuses on melee combat. This game would be like Rain World with Celeste movement

This is because there are few games which focus on melee combat and this would help it stand out, the rouge like aspect would allow every run to be unique and distinct. Allowing people to replay the game multiple times without getting bored. 

The melee combat will be close range and it will allow people to play in distinctive styles, for example people will be able to change their weapon and ability to suit the playstyle that they are looking for, making any play style viable. 

There will be progress through floors. When the player completes one floor they can move on and enter the next floor. At the end of each floor there will be a boss that the player must defeat to progress. 

The loot and map generation will be random meaning that the player cannot memorize the layout and do the same thing every time but need to adjust to the environment, making the game more challenging. 

I plan for there to be different enemies that have different attack patterns that will not be entirely random meaning that the player can learn how to effectively defeat the enemy. The enemy difficulty will increase as the player progresses through the floors. 

# **Computational Methods** 
Computational methods are computer-based methods which are used to solve problems. They are suitable for my project since I want to make a game which is fun and the following concepts allow me to accomplish this 

**Decomposition** – Splitting a large problem into smaller problems which are more manageable. This would help with my project as I am not going to be working in every aspect of the game at once, decomposition allows me to work on one part of the game at a time since debugging one small piece of code with a couple of errors is a lot easier than debugging all the game code with many, many errors 

**Divide and conquer** – Dividing a problem into smaller problems until they are small enough to be solved directly. This would allow me to develop one aspect of the game at a time and make steady progress on the game. Since each aspect is finished and polished by the time I move on to the next aspect. 

**Abstraction** – is removing the additional detail allowing me to focus on the main points rather than wasting time trying to work on pointless detail that will not be noticed. This will allow me to use my time efficiently as the main points will get the most amount of time making the basics of the game reliable. 

**Modular design** – Subdividing the problem into smaller modules in my case these would be: telescreen, physics engine, movement, abilities, characters etc. These allow me to priorities the modules which need more attention and keep organized as each module can have its own separate folder for all the things needed for that module.  

**Algorithms –** Algorithms allow me to implement features that do not need anything but computer processing to be solved. For example, enemies will use an algorithm to detect and attack the player, the scenery might be made by an algorithm etc. These allow the computer to do specialized processing for the problem that needs to be solved 

**Selection** – Allows for choices to be made in the code. For example, if statement is a type of selection since a condition needs to be met for the code to be executed. This is useful in many scenarios, just to list a couple: if the player is in the air, they should not have the ability to jump. If the players health drops to zero they should be sent to the game over screen and many more. 

**Iteration (looping)** - Allows a certain piece of code to be ran multiple times for example while or for loops which will continue to cycle the code until it is told to stop. These are useful since in a 3D game the players input needs to be recorded every frame to minimize latency, the code needs to sort through those inputs every to make the necessary adjustment to the character and environment all in the same frame. These tasks are repetitive therefore the code will be the same every loop and iteration is perfect for that. 

**Visualization** – The player will not be able to process the raw data outputted by the computer therefore it needs to be put in a format which is comprehensible for humans. There will be a lot of data processing while the game is running such as player position constantly moving, enemies moving and attacking the player. If that were outputted as a string of numbers to the player, they would have no idea what is going on therefore visualization is used to allow the user to interact with the program  

**Pattern recognition** – It would be useful for the computer to recognize patterns as a certain pattern could be used as a condition for selection this could be useful as when the player attacks the computer could recognize this and react accordingly to make the fight interesting. Or it can be used in fighting games to make a move since in some games like mortal combat you can chain inputs to do a special attack. 

# **Suitable Stakeholder** 
My game would be suited for people who have more experience with games it will be suitable for any age over the age of twelve (might be a too violent for children under the age of twelve). 

 Therefore, Ethan Armstrong would be a suitable stakeholder. He is 16 years of age therefore he fits the target demographic. He will give feedback through playtesting and according to the feedback I will be able to adjust the difficulty and balance the aspects of the game to fit the genre and style I am going for. The feedback given to me by him will allow me to adjust the game to make it more enjoyable. 

Daniel Cabrel would also be a stakeholder as they are new to gaming therefore, I will be able to make the game more beginner friendly to expand my target audience and make it more appealing to more people. He will also give feedback through playtesting and interviews allowing me to make the game easy to pick up regardless of skill. 

I have chosen these people since they are part of my target demographic and they will help me to make the game easy to pick up yet challenging. 

# **Researching the Problem** 
## **Risk of Rain 2** 
![[ROR 2 ss.jpg]]
Risk of Rain 2 is a roguelike, third person shooter. A roguelike game means that when you die in the game you must restart the entire game, which means that it does not take long to complete and it can be replayed multiple times, since it has a large variety of items which can be combined to make many unique runs. It has a unique concept since as the time goes up so does the difficulty, meaning that the more time you spend looting the more powerful enemies become creating a unique stressful and fast paced shooter. 
### **Controls:** 
WSAD - to move 
Space - Jump 
E – To interact with the environment (open crates etc.) 
Q – Activate equipment (item that can be used by every character) 
Ctrl – Toggle sprint (to move faster) 
M1 – Primary Skill (unique to character, usually damaging) 
M2 – Secondary Skill (unique to character, usually damaging) 
Shift – Utility Skill (unique to character, usually movement) 
R – Special Skill (Unique to character, usually heavy damage, and long cooldown) 
Tab – Info Screen (shows the stats of the current run) 
M3 – Ping (allows players to communicate in game) 

### **Characters** 
Commando and Huntress – Both are beginner friendly characters which have a basic set of skills and utility to ease the player into the game. They are the first characters you unlock and they are both good characters even after the player has learn to play the game. 

Every character apart from these two needs some sort of challenge to be completed before the player gains access to them. This allows the player to progress at their own pace. 

Acrid, Artificer, Bandit, Captain, Engineer, MUL-T and REX – Once these characters are unlocked, they expand the possible play styles possible to the play allowing the player to play the game in any way they want to for example, Engineer has turrets and a shield if the player wants to bunker down, while Bandit has an invisibility cloak and shotgun allowing for the player to get close and personal. 

Loader and Mercenary – Both have the highest skill ceiling (lots of things to master) and both have lots of unique tech (advanced strategies to use utility to achieve a certain result) for example Loader can launch out her pylon and grapple to it immediately after launching the player a great distance 

Railgunner and Void fiend – Both DLC characters which is a good example of the developers expanding the play style since none of the other characters had long range and these characters fit that style perfectly since Railgunner has a rail-gun which is like a sniper allowing the player to keep their distance and pick of enemies one by one. 

Heretic – A secret character which is unique since they cannot be unlocked, and the character is bound by the run as they are unlocked by picking up a combination of items on that run. 

### **Aim of the game** 
The aim of the game is to get loot and activate the teleporter, after this a boss will spawn, which you must kill to progress. You get teleported to a different stage and the process repeats until stage 5 and after that you get teleported to the moon to kill final boss (Mythrix) or obliterate yourself which has a more secret ending which needs the player to enter a portal on stage 8 after they loop (return back to stage 1 and keep all their items), sometimes a large purple portal can appear which teleports the player to a different realm (with some pretty interesting lore) and they have to defeat Voidling which gives the player an alternate ending. 
### **Target demographic** 
Teens and older since the game contain blood, drug references and fantasy violence. It is aimed at people with all skill types as the game has different difficulty rating which allows the player to play at the level that they are comfortable with.  
### **Good Qualities** 
- The game is very beginner friendly and is enjoyable both alone and with friends.  
- The variety of items allows the player to replay the game with many different combinations and the game does not feel repetitive. The different ending makes the player want to experience them all.  
- The variety in character makes any play style suitable. 
- The game is never “too easy” since there are eclipse challenges which get progressively harder 
### **Bad Qualities** 
- Once you loop a lot the game gets very chaotic and resource intensive because there are so many enemies with different attributes that can create lots of projectiles which slow down the game a lot.  
- Some things can kill you in one hit making death unavoidable in some cases. 
- Sometimes you get runs where you get no good items, and the game becomes a lot more difficult because of bad luck. 
### **What I would include** 
- The variety in characters and the play styles that they allow 
- The different difficulties allowing the player to play at a level that their comfortable with 
## **Celeste**
![[Celeste ss.jpg]]
Celeste is a challenging 2D platformer where the aim is to give precise inputs that will clear the level and allow you to progress into the next room. It takes a long time to complete as the game is very difficult and constantly introduces new features that are harder than the last.
### **Controls** 
WSAD – Movement 
J - Jump
K - Dash
L - Grab
### **Characters** 
Madeline is the protagonist of the game and as the game progresses, as the game progresses they get more and more abilities and the level design reflects this as the game presents rooms that can only be solved with the new skill that the player was shown. The game never gives the character any new skills are just shown to the player and never granted or unlocked meaning that the player can revisit earlier levels and complete them in newer and more efficient ways. The player does get an extra dash in some of the later rooms in the game and this is the only upgrade that the player gets.
### **Aim of the game** 
The aim is to get to the top of the celeste mountain climbing the mountain one room at a time. Rooms get harder the further you progress in the game, the length of these rooms can vary drastically, the same applies to the difficulty. The game itself doesn't have that much levels however each level is very difficult which makes completing one very rewarding.
### **Target demographic** 
Anyone as the game doesn't have any violent or difficult topics discussed, however it will cater better to a slightly older audience because of it's difficulty. The game also targets people who are more experience in platformers as the difficulty of the levels scales quickly.
### **Good Qualities** 
- Beating a room feels rewarding
- Caters who anyone who is willing to try it.
- The movement feels fun
- The movement feels consistent
### **Bad Qualities** 
- Getting stuck on one room can be very frustrating
- To progress far into the game you need to dedicate a lot of time and have a lot of skill
### **What I would include** 
- A similar art style 
- Similar movement system, but something that isn't as complicated so it doesn't overwhelm the player
## **Rain World**
![[Rain world ss.jpg]]
Rain world is an open world game meaning that the player can go explore anywhere to their heart's content. It's also very difficult, and focuses on treating the player as part of the ecosystem rather than a separate entity, for this reason enemies treat the player as any other rival creature and focuses on their own survival rather than killing the player, which is common in most other games.
### **Controls** 
WSAD – Movement 
Space - Jump
E - Grab
Q - Throw
Escape - Pause
Z - Map
### **Characters** 
The player plays as a slugcat which is a small creature with the ability to wield rocks and spears. They can also befriend other wild creatures. They can also interact with scavengers if the player's reputation is good with the scavengers, however this isn't the case for all slugcats as scavengers will become hostile if the player's reputation is low. 

Monk - The easy mode of rain world, where enemies are less common and less aggressive. This character is good for people playing the game for the first time as it allows them to experience the game in a less harsh environment than usual.

Survivor - Regular difficulty of the game

Hunter - Hard mode of rain world where some special tougher enemies spawn that don't usually spawn, enemies are also more common and aggressive. There is also a time limit as the hunter has a limited amount of cycles (days) unlike any of the other characters, hunter also has the ability to consume dead animals.

Rain world also has a DLC called downpour which adds 5 new characters, where each character has unique abilities and objectives, the different characters are unique to the base game characters as they have their own abilities which also come with their downsides. Each character is also set at a different time in the timeline meaning that the layout of the game will be similar however each room will be different for each character and the enemies in that area will also be different. These new characters each require a different approach for the game due to their different downsides, for example gourmand gets tiered after throwing a spear, forcing the player to plan their combat as they will get tiered if they spend too long in combat. Whereas the saint isn't able to use spears because it's a pacifist, but they have a grapple which it can use to traverse the land faster, forcing the player to avoid combat at all costs. 
### **Aim of the game** 
The aim for each character in the game varies, however they all need to progress through the environment to reach their goal, often resulting in combat with the wildlife. The player must also gain enough food to be able to sleep in a shelter and avoid the rain that comes at the end of each cycle (game equivalent of a day). Dying results in the player respawning in the shelter they previously slept in and losing a karma point, however for each successful cycle that the player completes they will gain a karma point. Karma is important as it allows the player to traverse between regions, since regions are separated by karma gates which only let you through if your karma is above a certain level. 
### **Target demographic** 
Anyone as it doesn't contain any graphic scenes or references to difficult topics. However the game caters more to people who are willing to spend time trying to understand it as it's a very challenging game which is very harsh for a new player, lacking any kind of tutorial or explanation. 
### **Good Qualities** 
- Gameplay is fun and keeps the player engaged
- Game has a high skill ceiling meaning there is always a way the player can improve 
- Movement is incredibly fun and feels exceptionally smooth. 
- Lack of permanent upgrades makes the game focus on skill rather than items and unlocks.
- Completing a cycle if very rewarding.
- Player is treated as part of ecosystem rather than separate entity
### **Bad Qualities** 
- Difficult to get into due to no tutorial
- Game is very unforgiving and a small mistake can result in the player getting killed
### **What I would include** 
- A similar combat system 
- Similar movement system
- Treating the player as part of the ecosystem
# **Letter to Client** 

Paragraph 1 - Introduce yourself and coursework 
Paragraph 2 – why you have chosen them and what you need from them (interviews and game testing) 
Paragraph 3 – GDPR (General Data Protection Regulation), data protection explain how you will follow these rules 
Paragraph 4 – Thank them for working with you 

31 Bucannon Road 

CV22 6AZ 

20/11/22 

Dear Ethan Armstrong, 

My name is Karol Jeziorczak. I am studying computer science (OCR specification) at Rugby High School; the coursework requires me to create a game. 
I am asking you to become a game tester for my game so that I can get feedback from you as to how to improve the game. In the future I will ask you to give me feedback on the game to improve the quality and usability of the game, this will be in the form of interviews and game testing. This will hopefully improve the quality of the game and allow me to develop this project further into a fully functional product. 
All the data gathered will be kept secure in order with the GDPR (General Data Protection Regulation). This means that your data will be kept secure and will not be shared with any unauthorized personnel. I will do everything that I can to protect your data. However, if the data will get leaked, you will be the first to get notified.  
Thank you for your time and co-operation (if you choose to). I am looking forward to working with you. 

Sincerely,  

Karol Jeziorczak  

# **Stakeholder Questionnaire** 
Some SS of questionnaire talking about GDPR
## **Analysis** 

```mermaid
pie showData
title Q1: What is your age?

"less than 12":1
"between 12 and 17": 12
"between 18 and 25": 3
"above 25": 2
```
We can see that the target demographic is teens and above meaning that the game can include some violence. It is important to make the game appropriate to the target demographic as they will be the majority of the player base. 

```mermaid
pie showData
title Q2: How much do you play games a week?
"less than 1 hr":1
"between 1 and 3 hours":5
"between 4 and 8 hours":7
"between 9 and 14 hours":3
"above 15 hours":2
```
It is important to balance the progress made and the time invested as if people only play 1-2hrs a day as shown by the questionnaire, it is important to make the player feel like they made progress in that time so that they are willing to continue playing. This could be implemented by each run being 30-40 mins allowing the user to have a couple runs in a session.

```mermaid
pie showData
title Q3: What platform do you play games on? 
"Console":5
"Mobile":2
"PC":11
```
Most people answered replied that they play on pc meaning that it should be ported to pc first. A significant amount of people also play on console so it would be good to port the game to console if possible. 
```mermaid
pie showData
title Q4: what type of games do you play?
"Rougelike/Rougelite":5
"Stratergy":2
"Platformer":4
"Fighter":2
"Survival":3
"Open World":2
```
Most people answered Roguelike/Rougelite and platformer meaning I should focus on these two aspects the most when making my game. Survival will be implemented though planning ahead this might be what routes to take and the risk associated with those routes as well as the risk of combat. As well as management of resources to make sure you survive to the next stage. 
```mermaid
pie showData
title Q5: What mechanics are important to you in a game? 
"Gameplay - combat":7
"Gameplay - movement":5
"User interface":0
"Story":2
"Different playstyles":3
"Permanent progression":1
```
Combat and movement were the most common option so they should be the most polished systems in the game. Though different playstyles was something I should consider. Permanent progression wasn't a popular choice so a roguelike style would be more suitable 
```mermaid
pie showData
title Q6: how many skills should each character have?
"1":6
"2":9
"3":3
```
Most people answered 2 so it would be important to make the skills distinct and unique to allow for different playstyles. One ability could be active that the user can activate when needed e.g. throwing grenade and it will have a cooldown. The other ability could be a utility skill which can be picked regardless of character and is a limited resource and refreshes once a special item is picked up e.g. throwing knife that does damage, refreshes when more are picked up. There could also be a passive ability that the player doesn't need to do anything to activate it, it will be permanently active in the background (e.g. increased movement speed), this can make every character feel unique. 
```mermaid
pie showData
title Q7: Should each character have their own weapon in their class or be able to pick up any weapon?
"Weapon is locked to class":7
"Weapon isn't locked to class":12
```
The majority wanted to have weapons that are picked up and not locked to a class therefore I will give each character a starting weapon and give them the ability to change this weapon if they wish to, allowing the player to experiment with different weapons that may suit their playstyle.
# **Interview with Stakeholder** 

I – Interviewer (Karol Jeziorczak)   
S – Stakeholder (Ethan Armstrong) 

I: Everything you say here will be recorded and used for development of my game; however, it will not be shared with any unauthorized personnel and your data will protected under the GDPA 

S: I understand and agree to these terms. 

I: Question 1. What is the most important feature to you in a game? 

S: Exploration is very important to me; I love finding out hidden mechanics and secrets. 

I: Question 2. How important is difficulty scaling with progress to you? 

S: It is important to make the game challenging as it will make it more fun to overcome. 

I: Question 3. How often should there be boss fights? 

S: A bit after a new mechanic gets introduced so I have time to get used to it however the boss fight will be a test to see if the player can use the gimmicks 

I Question 4. What type of playstyle do you usually go for? 

S: I usually go for a large health build with heavy weaponry 

I: Question 5. Are there any specific features you would like to see? 

S: I would like to see a power slide because it makes the game seem fast paced. 

I: Question 6. What would a good combat system include? 

S: Enemies not having insane amounts of health as it slows down the pace of the game and makes killing them seem like it takes too long. So, with melee weapons there should be more blocking and skill involved rather than just hitting enemies and them dying? 

I: Question 7. What should the final boss look like? 

S: The final boss should be an enemy foreshadowed by the previous environments that has different mechanics from the different bosses that combine them all into one where they need to be interchanged, with a satisfying dying animation for the final boss.  

I: Question 8. How should the inventory management system work? 

S: I think that there should be a very limited amount of inventory room so that management and planning become very important. Also, so that the focus of the game isn’t shifted too much from the combat, as it is the main focus of the game. 

# **System Requirements** 

## **Minimum Hardware Requirements** 
Processor:   
Graphics Card:   
Memory:   
Storage:   
Sound Card: yes 

Input devices: 
- Keyboard – allows you to input characters 
- Mouse – Inputs 2D vector coordinate for mouse position 

Output devices: 
- Display – Outputs image 
- Speakers – Outputs sound 

## **Minimum Software Requirements** 
OS: Windows 10+   
DirectX version: 12   

# **Success Criteria** 

Using the data gathered from my research phase I will aim to implement the following features: 
*ss of excel sheet*
# **Designing the solution** 

**Decomposition of the problem**   
This is one of the computational methods that I am going to use for my game. This is important as it allows me to think of how the game will work at a basic level. 
## **Main Menu** 

The main menu will be there to greet the player once they open the game and allow them to choose what they would like to do 

These will be in the form of buttons that the user can click on.  

## **Variables** 

Variable – stores some sort of data in main memory 

**Data Types** 

Integer – whole number   
Float – real number   
Character – single letter/symbol   
String – series of characters   
Boolean – true or false   
   
CONSTANT_NAME – represented as capitalized with underscores   
variable_name – represented as lowercase with underscores 

Movement 

Abilities 

Generation 

## **Folder Setup** 
*ss of folder setup*
# **Actual Coding** 

**Initial Planning**  
Can be split into two main segments 
- Things that happen every frame  
	- Player Input 
	- Will be under “private void Update()” which is called once every frame 
- Things that happen every physics frame (constant 50Hz) 
	- Anything physics related 
	- Will be under “private void FixedUpdate()” which is called once every 0.02 seconds (can be changed in the unity project settings 

 Using fixed update aims to keep things consistent as frame rate isn’t constant in a game therefore if we were to do physics related actions every frame it would be inconsistent and would feel unreliable as the result would be different based on frame rate. Some things will be exempt from this rule. This will happen when the force is applied once (like a jump) since the force will only be applied in one frame, then the frame rate doesn’t change how it behaves. This will make the game feel more responsive as if we were to do add impulsive forces in the physics frame, we would need to wait for the next physics frame to apply the force, however applying it in the Update void will allow the input to be processed as soon as it is inputted into the computer. 

## **Player Movement** 

### **Success criteria** 

- Walking 
- Can move in all directions relative to the camera 
- Can move up slopes at the same speed as on ground 
- Sprinting 
- Can move in all directions relative to the camera 
- Can move up slopes at the same speed as on ground 
- Moves at a different speed than the walking speed 
- Increased FOV to make it seem like the player is going faster 
- Crouching 
- Can move in all directions relative to the camera 
- Can move up slopes at the same speed as on ground 
- When running and initiating a crouch it becomes a slide 
- When sliding down the slope you accelerate down, and the magnitude is decided by the steepness of the slope. 
- When something is above the player, they can’t un-crouch 
- Player scale changes to make the hitbox smaller 
- Player moves down so that they don’t float when changing scale 
- Jumping 
- Always jumps up 
- Power can be changed 
- When slow enough and  
- Wall running 
- Can go around curves 
- Can't infinitely wall run to climb any wall 
- Can jump off from it 
- Camera 
- Can’t rotate fully up to go upside down 
- Can rotate around depending on mouse movement 
- Gravity 
- Works as intended on slopes 
- Smaller gravity when wall running 
- Acts down when player is in the air. 
### **Testing Scene** 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_aa6f8226a38856f8.png)  

With this I can test features I specified in the criteria and when all of them are met then the movement will be considered as complete. 

**Setup in unity**   
![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_7aeb4531fb2bf749.png)    
The tutorial I took inspiration from said to set up the transforms as seen in the diagram above, and since it is my first-time using unity, I am just following the tutorial. 

Empty – object with no properties apart from rotation location and scale. 

player is just an empty, so it acts as a parent to player_model, orientation, and camera_pos, meaning that if a transform is applied to player, it will be applied to all the children as well, however the children can still act independently without affecting the parent. The only thing that it is useful for is to get its position. 

player_model is just the object that the player appears as, could be used as a hitbox when making a combat system. 

orientation is also an empty, but it can be used to find where the player is looking without up and down rotation, so only rotation across the y axis so when we want to move the player forward, we can use this to determine which direction is forward.  

camera_pos is also an empty and it will be used to know where the camera should be, as parenting a camera to the player directly may cause problems down the line, for example if the camera needs to be moved around in a cutscene then the entire player will be moved with the camera. 

**Camera Position** 

In a script called move_camera   
![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_c95c565b5c9a4aff.png)    
this is the script of cam_holder and cameraPosition refers to camera_pos 

**Camera Rotation** 

In a separate script called cam_rotate 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_fc6a39b66cdf58fa.png)  

sensX will be used to determine how much the movement of the mouse left/right should rotate the camera to the left/right respectively.   
sensY will be used to determine the same thing but the movement of the mouse up/down will rotate the camera up/down. 

Orientation will be used to determine where the player is facing with y rotation. 

xRotation is used to find how much the mouse has moved along the x axis (left or right)   
yRotation is used to find how much the mouse has moved along the y axis (up and down) 

 ![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_52f369d0cd7227a7.png)  

“void Start()” just means that the code is ran once before “void Update()”   
Cursor.lockedState = CursorLockMode.Locked makes it so that the cursor is unable to be moved from the centre of the screen.   
The second line just makes it so that the cursor isn’t visible to the player. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_74a8fc4a853faecd.png)  

“void Update()” means the function is called every frame this is done to make player input processed as soon as possible.   
Everything under “// get mouse” is just finding how much the mouse moved in the last frame and multiplying it by Time.deltaTime will make the mouse movement constant even when frame rate is varying, this is important to keep the game felling smooth and consistent. 

Under “//data processing”  yRotation has mouseX added to it as left and right movements of the mouse will translate to y rotation on the camera. As seen in figure x 

 ![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_34dc3b7e8c39fd91.png)  

_Figure x_ 

“xRotation” has mouseY subtracted to it so that up and down mouse movements in the mouse will be translated to x rotation on the camera as seen in figure y 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_80887ae23857aeff.png)  

_Figure y_ 

“xRotation” is then clamped so that –90 <= xRotation <= 90, doing this completes the “can’t rotate fully up to go upside down” agenda in the success criteria. 

Under “//rotate cam + orientation” camera is rotated along the x and y axis buy the factors xRotation and yRotation respectively and only rotation across the y axis is applied to orientation, just like demonstrated in figure x 

**Gravity** 

I want to make my own custom gravity system as it would cause problems in the future. 

Want the gravity to act in a specific way as seen in the figure below. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_1f605aef0f35be92.png)  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_4578d4f506afbc93.png)  

Want to turn off gravity when the player is sliding to get a glide on the slide. Also, when the player is about to jump as they won’t get pulled down immediately which just makes a tiny hop. 

When the player is wall running, we want a smaller gravity, so they don’t fall immediately 

The only time that we want the gravity to act down is when they are in the air. 

**Basic movement** 

**Player Input (checked every frame)** 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_227ae331e68af35c.png)  Axis this is referring to   
  ![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_a87c5b20ac9c1c61.png)  
When the positive /alt positive button is pressed the axis will return 1,   
When the negative /alt negative button is pressed the axis will return –1   
When neither or both are pressed the axis will return 0   
With this we can know when the player wants to move and can make code to act on this information. 

Orientation is a transform (consists of rotation, position, and scale) that is a child of the player therefore it inherits all the transforms of its parent.  

We can inherit useful things from this like the which way is the player facing, from this we can use “orientation.forward” or “- orientation.forward” to output a normalised vector 3 as to where the player is facing and therefore which direction they should move when pressing W/S (default key binds for forwards and backwards)   
“orientation.right” or “-orientation.right” to output the normalised vector 3 as to which direction should the player move when pressing A/D (default key binds for left and right movement) 

It is useful to know what is around the player, hence we will ray-cast around the player to see what objects are around them. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_6d72b6202eb88956.png) Checked for every frame. With this we can see what is above, below, in front, and to the right and left. What we care about right now is grounded which is a raycast straight down and returns a boolean result weather it hit an object or not and also outputs objHit which will contain data about the object hit by the raycast. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_a1ce14dde3830736.png)  The normal is perpendicular normalized vector of the face that that the ray-cast hit (essentially the direction that the face the raycast hit is facing). So, when the y component of the normal is 1 then the normal is pointing straight up, which means the player is on a flat surface this is important as we want the move direction to be different when the player is on a slope. 

moveDirection calculates the direction in which the force should be applied 

This allows the player to accelerate in any direction they want, depending on which way the player is facing. 

However, this process only works when the player is standing on flat ground. When the player is standing on slanted ground, we want them to uniformly accelerate in all axes that are perpendicular to the normal of the face. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_1d88106b6b1797f7.png) This code finds the direction in front and right of the player rotated by the slant angle and the backwards and left direction can be found by multiplying the values by –1 respectively. 

**Sprinting**   
![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_bfe1b6d2e39128c6.png)    
To spring all that needs to be done is to change moveSpeed to a higher value  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_782172ba0535db01.png)  

We can change this by checking which state the player is in by looking for certain condition. 

This function is referenced under “private void Update()” meaning that it is called every frame, this allows me to always know what state the player is in. Currently some of the states haven’t been explained yet but they will be explained in the rest of this section. 

**Crouching** 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_6eda32ecf59a7316.png)  

Changes the player scale to be half the original size, since they player would be suspended in midair, so a force needs to apply downwards to position the player correctly, the force must be applied in one frame in an impulse that’s what “ForceMode, Impulse” is used. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_13ee81fedca08142.png)  

When the player is sprinting, we want to give them a force forward when they slide which is why we check if the player is grounded and sprinting when they press the crouch key as if both conditions are satisfied then the additional force is applied. 

We also want to check if the player wants to un-crouch. This condition can be met if the player is currently crouching, the crouch key isn’t being pressed down. Also want to check if there is room above the player, this is done with a capsule cast instead of a raycast, elaborated in the figure below.   
![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_5927bb17aa050554.png)   

Beneficial as just a single point in the middle wouldn’t tell me if the player’s head doesn’t have anything over it, whereas a capsule cast does making it more applicable to this scenario. 

Also want to return the player to the original scale and make sure that crouching is set to false for the player state handling. 

**Wall running** 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_8a7098d64cd88e5e.png)  When the player presses space when near a wall we want their velocity to be readjusted based on the normal of the wall so that they are traveling perpendicular to the normal of the wall as seen in the figure above, however there are two possibilities for the perpendicular, so we want to take the one that is more similar to the direction the player is facing. So, we want to take the direction so that it has a positive dot product with the direction the player is facing. 

Since we want to check if the player presses space every frame to make sure that the input gets processes as soon as possible. So, this code is under “private void Update()” 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_e3b7c9644680b7c3.png)  

But the physics needs to be processed every physics frame so it’s in a separate function under “private void FixedUpdate()” which runs at 60Hz 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_ea39ac9f78a6abb1.png)  

Before optimization, lots of conditions are getting tested where I made a Karnaugh table to remove redundant data checks. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_dccb493cad54ea15.png)  

In the following table “normal” refers to “wallrunDirection.normal” 

Check X coordinate 

|   |   |   |   |
|---|---|---|---|
   
||Is normal.x Positive|   |   |
|Is normal.z Positive||1|0|
|1|1|1|
|0|0|0|

From this I can deduce that normal.x doesn’t affect output, so we don’t need to bother checking for it and only check if normal.z is positive 

Check Z Coordinate 

|   |   |   |   |
|---|---|---|---|
   
||Is normal.x Positive|   |   |
|Is normal.z Positive||1|0|
|1|0|1|
|0|0|1|

From this I can deduce that normal.z doesn’t affect the output, so we don’t need to bother checking for it and only check if normal.x is negative 

After optimization 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_35093f2d4464dadd.png)  

Initiate wall run   
![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_50ce2daa54e1a78f.png)   

Only allow player to wall run if the following conditions are met player isn’t touching the floor, player presses the jump key, there is a wall for them to wall run on and the player is pressing the key to move them in the direction of the wall they want to wall run on (e.g. right wall then “d”) this is done in case the player enters a narrow area and there is enough room for them to wall run on either wall so they need to choose, if this wasn’t the case then right wall would take priority as it’s checked for first.   
“wallrunning” is set to true for state management (will be helpful with animations later). 

Wall jump 

If the player wants to exit the wall run, I want them to be able to jump out of it. However, this will only add a force, with a normal jump I reset the y velocity to apply the jump so that the player always gets a jump with the same power, whereas in this case we only want to add the force this makes it so that if the player is rapidly falling and wants to wall jump to negate all the downward velocity they won’t be able to. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_f2e2ae40e14e4c5.png)  

This is done in “void Update()” which is called every frame, even though it’s a physics, this is done since the force applied is an impulse so that it’s only applied once, so even with varying frame rate it will always be constant. In the Figure above θ can be varied and is represented with “wallrunJumpAngle” in the code below. 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_aeeb95ef74865ad.png)  

**Speed Control** 

*Desmos was used for making graph in this section 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_23f55219bae1354c.png)  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_35e34ccd236b4294.png)  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_ae0b4cb60d3b9a3.png) |   
  ![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_b51b31fbb67fd4d5.png)   

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_bf614510ba3940df.png)  

Derivative of first function (www.derivative-calculator.net/) 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_d586d8fd6deb7877.png)  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_a926c551d3126b1c.png)  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_33c21566dfa15757.png)  

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_551b44e5e35c5c5.png)  

Since values of a will be changing and the frames x will be irrelevant 

![](file:///C:/Users/dimki/AppData/Local/Temp/lu1544013jnx.tmp/lu1544013jo0_tmp_b9f68d273eb292b5.png)  

Since ln (2) are both constants we can use the constants rather than calculating it each time 

After trying to implement this into the project I couldn’t get it to work and running so I decided to switch to a new method for the following reasons:  

- New method is less computationally heavy  
    
- New method is more reliable as the maths is simple 
    

The new method is decreasing the magnitude of the player’s velocity by certain percentage, this will maintain their direction so that the game still feels smooth, since if the changes were large, they would be very noticeable, and it would make the game feel worse and movement is important to my stakeholder.  

I decided to decrease the magnitude by a percentage because it would be less noticeable way of decreasing the speed of the player as if there was a constant amount the speed is decreased by it wouldn’t be noticeable when the speed is high however when the speed is low it will decrease by significant increments and decreasing the speed would be very noticeable.