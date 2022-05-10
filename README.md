# PlatformerGame

### ABSTRACT

The game consists of two stages and is a scrolling platformer shooter that is set in a radioactive wasteland. The player, our protagonist, faces off against enemy soldiers with and must deftly navigate the wasteland with his movement skills and precision shooting abilities.

The goal of the game is to get to the conclusion of each level while fighting enemy soldiers and avoiding obstacles, as well as collecting bullet packs, health packs and grenade drops placed at strategic locations throughout the levels to aid the player.

![image](https://user-images.githubusercontent.com/60477228/167600251-930ac4b4-3eab-4668-bded-869cb8b30569.png)

### GAMEPLAY

The player is given two types of ammunition, a limited amount of bullets and grenades. The two types of ammunition each have their pros and cons, and must be used efficiently by the player to traverse the level.

The grenades enable the player to kill off enemies from a safe distance, thus not bringing themselves into harm's way, however, the grenades have a cooldown on explosion, thus needing the player to expertly throw their grenade at the exact right time. Two grenades are needed to kill an enemy.

If the player’s grenades run out, or if the player is surprised by an enemy soldier, the player can also use his bullets to kill the enemy, however, it will bring the player in harm’s way and he will need to use his movement skills to deftly avoid the enemies bullets.

There are random drops of both health, grenade and bullet packs, and based on the amount of each resource they have, players must change up their play strategy to fit these random drops.

The player has the access to the following controls:
- W - Jump 
- D - Move Forward
- A - Move Back
- SPACEBAR - Fire Bullets
- Q - Throw Grenades
- ESC KEY - Quit Game

### OBJECTS IN GAME

#### Player Character

The player character is a sprite of a green character. They have the flexibility to shift both forward and backward. Leaping is also an ability for the player character to dodge gaps and obstacles. To dispose of attackers throughout the levels, the player character utilises a rifle and grenades.

#### Player Monitors

Player Monitors are graphical representations of the player subject's different characteristics.
The health bar shows the player's character's durability.
The ammunition level displays how many bullets the player has left.
The grenade level indicates how many grenades remain with the player.

#### Toxic Water

The toxic, polluted water is a game-breaking obstacle. If the player character falls into the water, the game will reset and the player will have to start the level over from their beginning position.

#### Enemy Character

The enemy soldiers are red sprites who will start firing at the player character if they are in their line of sight. The red colour is chosen so as to contrast with the colour of the player character and thus differentiate them. They can scan the platform they are placed on in both directions, and traverse the platform forward and backward. They are unable to follow the player character across platforms, and are thus relegated to the platform they are placed on.

#### Health, Ammunition and Grenade Drops

The player will come across either health, ammunition and grenade drops dispersed about the levels. These can be collected to recharge the player's indicator for each resource to full.

#### Bullets

Bullets are one of the player’s main ways to damage enemy characters. These bullets can only be held by the player character in a finite number. Every bullet shot deducts one from the total number of bullets and they travel in a straight line. While the player character has at least one bullet, he or she will be able to fire it. Enemy characters in the game will take moderate damage from the bullet.

#### Grenades

Grenades are another of the player’s main ways to damage enemy characters. The player character can only carry a certain number of these grenades at a time. Every grenade launched deducts one from the total grenade count. The grenades have a parabolic trajectory. When the player character has at least one grenade, he or she will be able to throw it. The player and opponent characters in the game will take a lot of damage from the grenade, much more than from a bullet.

### OUTPUT SCREENSHOTS

#### Game Screen

![image](https://user-images.githubusercontent.com/60477228/167600251-930ac4b4-3eab-4668-bded-869cb8b30569.png)

#### Start Screen

![image](https://user-images.githubusercontent.com/60477228/167600386-83b03b08-dc5b-4d70-a0ed-6fb58170c85a.png)

Restart Screen

![image](https://user-images.githubusercontent.com/60477228/167600456-2f44305e-0555-4409-b44a-8bf311835676.png)

Player Character

![image](https://user-images.githubusercontent.com/60477228/167600559-3c245e84-6942-48a3-b725-839754a63887.png)

Enemy Character

![image](https://user-images.githubusercontent.com/60477228/167600601-f6abc19c-68ad-4564-b457-4a1b82a39cfe.png)

Health, Ammunition and Grenade Count Bar

![image](https://user-images.githubusercontent.com/60477228/167600723-c1125f01-07ee-4e4d-ad47-9fad31fb1099.png)

Toxic Water

![image](https://user-images.githubusercontent.com/60477228/167600788-e334145c-6c9d-41ca-b5c8-1b9db93150cc.png)

Health Drop

![image](https://user-images.githubusercontent.com/60477228/167600866-f987ff3c-ef30-4ccd-984e-74fddad26070.png)

Ammunition Drop

![image](https://user-images.githubusercontent.com/60477228/167601001-c0f638f0-8e33-4af1-bb10-fbef57b7ef73.png)

Grenade Drop

![image](https://user-images.githubusercontent.com/60477228/167601045-0a123a3a-50fc-422f-8787-86ccd2f765b6.png)

Bullets

![image](https://user-images.githubusercontent.com/60477228/167601076-28f5015b-92d1-437f-8fc4-075876d5019c.png)

Grenades

![image](https://user-images.githubusercontent.com/60477228/167601125-6f5c70d0-02f1-4d81-a260-6d8fe8c5d2e8.png)

### TECHNOLOGIES USED 

Pygame is a collection of Python modules for making video games. On top of the excellent SDL library, Pygame adds capabilities. In the python language, this enables the creation of fully featured games and multimedia products.

We have used pygame module in our project because it gives us the following benefits:
- For key functions, it uses optimized C and Assembly code: C code is generally 10-20 times faster than Python code, and assembly code can easily be 100x or more.
- Pygame is modular, which means it may be used in different ways. Many of the main modules can be independently initialized and used.
- It doesn't have hundreds of thousands of lines of code for features that aren't used. The core is kept simple, while further features such as GUI libraries and effects are developed outside of pygame.

### FUTURE SCOPE

This project has quite some scope for improvement, and thus, in the future we plan to implement the following:
- An interactive GUI that is user-friendly and improves the redundancy that occurs in the UI of the program.
- Implementation of file handling, so as to store the data that has been inputted by the user in a more permanent manner.
- A better seating map, that is more interactive than the current one.
- Inclusion of start and end dates for movies. Movies automatically are deleted from the system once it’s expired past its end date.
- Returning Clients to be able to create accounts, so as to not create a new client each time and to store information of previous movies watched. 
- Inclusion of password protection.

