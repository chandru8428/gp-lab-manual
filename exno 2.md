# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date:12.03.2025
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure :
1. First, open a blank project in Unreal Engine with the Third Person 
or First Person template for basic character movement.
2. In the Content Drawer, import or download character and 
collectible assets from the Unreal Marketplace or use prebuilt 
assets.
3. Create a new Blueprint Class of type Character, and name it 
BP_PlayerCharacter.
4. Open BP_PlayerCharacter, and in the Event Graph, set up input 
bindings (like MoveForward, MoveRight, and Jump) to control the 
character's movement using the Input Axis and Input Actions.
5. Add a Collision Box to the character or create a Collectible 
Blueprint (e.g., BP_Coin) with collision enabled
6. In the Collectible Blueprint, use the OnComponentBeginOverlap
node to detect when the player overlaps with the collectible. On 
overlap, increase the score variable and destroy the collectible 
actor.
7. In the Player Blueprint, create two variables: Health (integer) and 
Score (integer).
8. Use Print String or a UI Widget Blueprint to display the current 
score and health on the screen.
9. You can reduce health based on events like hitting an obstacle or 
enemy, using collision or trigger boxes.
10. Add logic to reset the game or display “Game Over” if health 
reaches zero
## Output:
![image](https://github.com/user-attachments/assets/d26d7f34-cb0d-4417-a5e6-5e5ea0ec5411)
![image](https://github.com/user-attachments/assets/4233c819-92f2-4e0a-8e0f-c0938b6d1e6c)
![image](https://github.com/user-attachments/assets/007fdb2b-ca76-4cc9-9435-88f0ce03451a)
![image](https://github.com/user-attachments/assets/3debc02f-d725-4376-8d30-d6db7d4d6d77)
//paste your output screenshot here



## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
