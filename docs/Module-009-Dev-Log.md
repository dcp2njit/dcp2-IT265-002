<!-- Markdown Docs: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
## Name: Denise Payumo
### Module: 009

<!-- Repeat the below as needed-->
### Date: [04/21/2025]

#### Goals for this Module
- [x] Goal 1: Plan and begin digital prototype
- [x] Goal 2: Do more playtesting
- [x] Goal 3: Continue tweaking game rules and cards
#### Progress
- **What I accomplished**:
I've been adding to the looseleaf document for the digital prototype, and the lectures this week were very useful to help me plan. I have a rough idea of how I want to approach the movement logic and card logic. Not realizing how little time there is left to finish the project, I think I'm going to switch from Godot to Unity, since I'm more familiar with Unity. I did more playtesting with my friends and had some more friends playtest it together too, and I made a lot more changes to the cards as well as some tweaks to the rules. 



   <!--Your entry here or N/A if not applicable for this entry-->
- **Challenges faced**:
     <!--Your entry here or N/A if not applicable for this entry-->
N/A
- **Solutions**:
     <!--Your entry here or N/A if not applicable for this entry-->
N/A
#### Learnings
- Key insights, techniques, or concepts explored.
Entity Based systems
  - Entities - ID-tagged objects like players, items, or triggers
    - Behavior: comes from attached components and systems, can react to player actions or update autonomously
    - Interactions: physical and event-drien mechanics including collisions, triggers, cooperation and parent-child interactions
    - States: can be toggled via interactios or internal logic, often saved/restored between sessions, visual changes may reflect state 
  - Components - Data-only traists (i.e., health, position, inventory)
    - Modular traits without logic
    - Used to define position, stats, inventory, animations, etc.
    - Reusable accross many entities that follow a standard formt
  - Systems - Code that processs entities with specific components
    - apply logic to all entities with relevant components
    - Improve efficiency by fitering only needed entities
    - Modular and reusable across different game contexts   
- Entities are individual objects defined by components with a unique ID for tracking
- ECS = ENtity-Component-System architecture
N/A

#### Free Thinking
- Brainstorm or reflect on design ideas, architecture patterns, or potential improvements.
    <!--Your entry here or N/A if not applicable for this entry-->
  - Considering that my grid also has walls between coordinates, I'm not too sure how I should approach it.
  - Maybe I should use nodes / linked lists, or expand the size of the 2d array to account for each "wall"

#### Next Steps
- Tasks or experiments to focus on during the next session.
   <!--Your entry here or N/A if not applicable for this entry-->
  - Begin scripting the game logic
