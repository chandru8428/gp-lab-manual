# EXP-06: Implement the AI random movement.
## Date: 24/4/25

## Aim:
Implement the AI random movement.

## Algorithm:
- **Step:01** Create a Character Blueprint.
- **Step:02** Create a Blackboard.
- **Step:03** Open the Behavior Tree editor.
- **Step:04** Create Behavior Tree nodes for the following:

    **"Selector" node:** Controls the execution of child nodes.  
    **"Service" node:** Monitors and updates values in the Blackboard.  
    **"Sequence" node:** Executes child nodes in sequential order.  
    **"Random" decorator:** Randomly selects a child node to execute.  
    **"Move To" task:** Moves the AI character to a specified location.

- **Step:05** Set up the Blackboard with vector key and bool keys and save it.
- **Step:06** Set up the AI character Blueprint with the help of AI controller component.
- **Step:07** Set the AI controller and behavior treeiIn the Possess node, select the AICharacter Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”
- **Step:08** Set up the NavMesh and boundaries, we can adjust the size and position to cover the desired play area.

## Output:

![image](https://github.com/user-attachments/assets/94fad862-2974-47f9-90d3-d15b6e02ec77)

![image](https://github.com/user-attachments/assets/a1f507a2-2141-4a9a-b7ac-b9a7d7734ede)

![image](https://github.com/user-attachments/assets/542235b0-adab-4e4e-bcc9-7f80b14e8f10)

![image](https://github.com/user-attachments/assets/0abcbac9-2225-4563-a76d-b85bab1ccc71)

## Result:
Thus, the AI concept to the actor for a random movement is imple
