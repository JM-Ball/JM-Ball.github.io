## Mermaid Diagram 
### _CHOOSE YOUR OWN ADVENTURE!_


```mermaid
---
config:
  look: handDrawn
  theme: neutral
---
    flowchart TD
    A(You awaken in a tunnel, unaware how you got there.) -->|Go left.| B([You enter a room with two doors.])
    A -->|Go right.| C([You enter a room with a sleeping goblin.])
    B -->|Door #1| D[You are attacked by a venomous spider and die.]
    B -->|Door #2| E([A chest covered in cobwebs sits unopened.])
    C -->|Run?| F([Continue back down the tunnel.])
    C -->|Fight!| H[You are easily overcome and die.]
    E -->|Open?| G[You find a map leading to the exit.]
    F -->|You see a faint light at the end.| I[You find an opening in the wall, leading to freedom.]
    E -->|Leave| J([You find a mysterious potion and sandwich.])
    J -->|Consume the potion|K[You die from poison.]
    J -->|Eat the sandwich| L[You begin choking, waking up a sleeping goblin that attacks you. Killing you.]
    J -->|Continue to search| M[You come across a hidden cellar door leading to the outside.]
```

##### *Description:*
Above we have a simple Mermaid flowchart that highlights the ease of using text and simple brackets to create a quick easy to follow  
chart. Starting from the top you *"Wake up in a dark tunnel without any idea how you arrived, but only two options are in front of you..."*.  
So now you decide your fate by choosing one of the two options to progress through and **_hopefully_** make it out alive.  
> [Using MermaidChart](https://www.mermaidchart.com/app/projects/d14bca98-3880-43db-a82e-28e39b33562c/diagrams/e28d4867-a617-47de-b5f2-c7a918c74750/version/v0.1/edit) allows you 
to write code and make changes while seeing a live display of your chart. With visual diagram options available  you can configure one to best suit your needs. 
