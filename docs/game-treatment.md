# IT265 Design Treatment Checkpoint

---

## Title

- Mech-U Rescue
- Protocall
- IDK

<!-- 
Enter the name of your game concept. 
Make it concise yet engaging, reflecting the game's essence. 
-->

---

## Concept Statement

In this roguelike survival game set in a futuristic post-apocalyptic city during the peak of a recent zombie outbreak, the player controls a mech pilot responding to distress calls, managing scarce resources, and navigating the hazardous streets to rescue survivors while facing life-threatening obstacles in a race against time.

<!-- 
Provide a one-sentence summary that captures the core idea of your game. 
This should convey what makes your game unique in a compelling way. 
-->

---

## Genre and Style


### Genre
Roguelike Strategy Survival Board Game


- resource management
- tactical turn-based movement/actions
- elements of chance/randomness 


<!-- 
Specify the game's genre (e.g., action, adventure, strategy, puzzle). 
Mention any sub-genres if applicable. 
-->

### Style

Dark, muted color palette for the environment to match the tone of the setting, and high-contrast/saturated colors to add to the futuristic feel(maybe), with - a post-apocalyptic city with urban decay and overgrowth, crumbling infrastructure, and desperate survivors seeking rescue


Isometric / pixelated (for digital) 
Physical - 3D modeled or printed with illustrations



<!-- 
Describe the tone, visual approach, and gameplay feel. 
Examples: "A dark, gothic horror with hand-drawn 2D animation" or 
"A lighthearted, comedic party game with vibrant colors and exaggerated physics." 
-->

---

## Target Audience

### Demographics
<!-- 
Identify the target age group, interests, and gamer profile. 
Mention if your game appeals to casual or hardcore players. 
-->

Age Group: 12+
Interests: 
- Survival/Apocalypse Games
- Roguelikes
- Turn-based Strategy Games
- Resource Management
- Decision Making
Gamer Profile: Fans of tactical games, roguelikes, survival challenges, and games that force you to manage scarce resources

The game can appeal to both casual and hardcore players, as difficulty can be adjusted to suit player preferences.

### Accessibility
<!-- 
Describe how the game will accommodate different skill levels. 
Will there be difficulty modes, tutorials, assistive options, etc.? 
-->
- There will be clear icons/symbols and high contrast for the important/interactable assets of the game to make it easy for all players to identify and distinguish in both digital and physical formats.
- The game will include multiple difficulties to appeal to newbies, casuals, and hardcore players.
There will be a gradual learning curve, as the initial survivor will always be the easiest to help introduce and familiarize the player with the resource management, dice, and card mechanics before it becomes increasingly difficult.
- The game rules will be written out to be referred to at any time and the game will not be super rigid, meaning players can alter the game rules as they like to play it how they want, or adjust it to be both easier or challenging.

### Inclusivity Strategies
<!-- 
Explain how the game promotes inclusivity. 
Consider gender representation, cultural diversity, and accessibility features for disabled players. 
-->
- The game will not have a fixed protagonist and there are no cultural or gender restrictions in theming. 
- The game will be set in a fictional post-apocalyptic, utilizing universal symbols and high contrast visuals for easy comprehension and identifiability across different languages.


---

## Core Gameplay Mechanics

### Primary Mechanics

- **Turn-based Movement and Actions**
  - Player has a limited number of Action Points (AP) per turn for movement and other actions.
- **Dice Rolling for **Randomization****
  - Randomized coordiantes for distress calls
  - Hazardous encounters - Dice roll (or coin flip) for deciding the outcomes of risky actions (engaging with zombies and other hostiles, navigating/looting dangerous terrain, etc.)
- **Resource Management System**
  -  Action Points - spendable points that replenish (+2/3) each turn, can be stacked if points arent all used at end of turn.
      - Used for movement - consumes mech fuel and AP
      - Used for actions -  consumes energy and AP
  -  Health - player's physical condition;
      -  -health for bad encounters with zombies/hazards
      -  +health for consuming medkits
  -  Energy - player's physical stamina and capacity to perform risky/physically demanding actions
      - -energy when rescuing survivors, engaging in combat, or looting hazardous areas
      - +energy for consuming food, resting in safe areas, etc
  -  Fuel - primary resource for movement, reaching 0 before answering all distress calls = loss
  -  Supplies - consumable items
      -  Medkit: +health -AP
      -  Food: +energy -AP
      -  Fuel: +fuel -AP
  -  Inventory - The mech has 6 inventory slots, which can be occupied by food, medkits, fuel, and survivors.
      - As you rescue survivors, your available slots will decrease
      - If your inventory is full but you have an option to loot, you may discard an item to replace it with your new loot  

 
- **Card Decks**
    -  Event Cards
      - Draw 1 every turn
        - random cards that vary between helpful/harmful events that can sometimes present players with a choice or subject them to encounter/experience something they have no choice over. 
    - Rescue Cards
      - Upon reaching distress call location, draw 1 rescue card to determine the profile the of survivor, the scenario, and any potential benefits or detriments they may add (addition/consumption of resources, etc.)
    - Hazard Cards
      - can be drawn upon
        - landing on a coordinate with a yellow caution symbol at the end of a turn
        - choosing to take the subway system
        - being prompted to draw a hazard card by another card
<!-- 
List and describe the core gameplay mechanics players will engage with. 
Explain how they contribute to the game's challenge and fun. 
-->

- Movement System
  - The board is an isometric 6x6 city grid with X and Y coordinates
  - Distress Call locations are determined by **TWO** d6 dice rolls;
    - 1 roll for X-coordinate
    - 1 roll for y-coordinate
  - Player moves are turn-based
    - Moving on the grid costs **Action Points** and **Fuel**
      - Moving straight in any direction costs 1 AP and 1 fuel
      - Moving diagonally costs 2 AP and 1 fuel
  - Mech can be upgraded if a survivor posesses the skill to do so.
    - consumption of action points, energy, and an extra turn, but is an investment that can mean less fuel/AP consumption for larger moves in future turns


### Goals and Challenges
<!-- 
Detail what players aim to achieve and the obstacles they must overcome. 
Explain how these challenges drive player engagement. 

-->
Goals:
- Primary Goal: Successfully answer 3 distress calls by rescuing survivors and returning them back to HQ before mech fuel or player health runs out.
- Secondary Goals:
  - Optimize routes between distress calls to preserve fuel and/or energy 
  - Manage resources as efficiently as possible
  - When prompted by random events/encounters, think critically and choose the most optimal decisions

Challenges:
- Limited turns - Limited turns simulates the time constraint and sense of urgency of the player's situation, prompting them to make strategic moves and decisions. 
- Scare resource management - managing limited Action Points(AP), fuel, health, and supplies forces strategic choices
- Dynamic Hazards - Unpredictable events and encounters with zombies, hostile survivors, stractural hazards create dangerous obstacles for players to navigate and adapt to.
- Risk vs. Reward Decisions -You can rescue and drop off survivors in bulk, or one by one, or a mix of both. Choosing which, when, and how to rescue and drop off survivors is difficult considering the significant impact it has on resource consumption and exposure to hazards.

### Progression
<!-- 
Describe how the gameplay evolves over time. 
Are there new abilities, unlockable levels, skill trees, or difficulty scaling? 
-->
- Difficulty scaling -
  - As more survivors are saved, the player has less inventory slots making supplies even scarcer and difficult to manage
  - With each survivor saved, the deduction values hazard cards and negative events increase by 1.
    - Ex: If an encounter gives -2 health with 0 survivors rescued. then having:
      - 1 survivor = -3 health
      - 2 survivors =  -4 health
      - 3 survivors = -5 health
- Mech upgrades - consumption of action points, energy, and an extra turn, but in turn can mean less fuel/AP consumption for larger moves in future turns
- 


### Game Rules
<!-- 
Outline the core rules governing the gameplay experience. 
Ensure they are clear, structured, and intuitive. 
-->
Board Setup
- Choose your starting position (either at HQ or through 2 dice rolls) and place your Player Piece on the board
- Deterimine distress call locations with 2 dice rolls and place the Survivor Piece on the board
  - Repeat 2 times for the remaining survivors.
- The board is static with fixed positions for important locations

1. Players start with **!0 Health, 10 Energy, 12 Fuel,**
2.  
3. 



---

## Story and Setting



### Setting
<!-- 
Describe the game world, its rules, and any unique environmental elements. 
Provide enough detail to establish immersion. 
-->
- A futuristic post-apocalyptic city that had been in the midst of rebuilding
- The game takes place during the peak of another zombie outbreak, making the city extremely dangerous and difficult to navigate safely.
- Infected people and mutated creatures, hostile survivors, and environmental hazards such as contaminated areas and collapsing structures pose a threat to anyone traversing the city.


### Plot
<!-- 
Outline the central narrative arc. 
What is the player’s role in the story, and what major events drive the gameplay forward? 
-->


### Characters
<!-- 
List key characters, their roles, and how they impact the story. 
Describe their motivations, personality traits, and influence on the player’s journey. 
-->

Protagonist - A selfless and highly-skilled strategist and mech pilot appointed as a first responder in a life-threatening mission to respond to distress calls amidst the sudden zombie outbreak. With limited time, fuel, health, energy, and supplies, the protagonist is forced into a do-or-die situation. They are further characterized and defined by player choices.

Survivors - A diverse range of individuals that the protagonist can encounter when answering a distress call. Their profiles (determined by Rescue Cards) range from skilled technicians to injured civilians. Survivors may contribute positively by providing bonus resources, skills, or upgrades, while others may hinder progress by using up resources and add to risk.


---

## Unique Selling Points (USP)
<!-- 
Identify what makes your game stand out from others in its genre. 
Highlight key features that differentiate it in the market. 
-->

---

## Inspiration

### Sources
<!-- 
List books, movies, historical events, or games that influenced this project. 
-->
Into the Breach
The Last of Us


### Why It Matters
<!-- 
Explain how these inspirations shape the game’s mechanics, visuals, or themes. 
-->
- Into the Breach - inspired pixelated isometric / grid style with fixed position for structures, inspired the idea for a turn-based tactical/strategy board game
- The Last of Us - inspired the post-apocalyptic setting, tone, and aesthetic
-


---

## Player Experience Goals
<!-- 
Describe the intended player emotions and reactions. 
Examples: excitement, curiosity, tension, relaxation, humor. 
-->
- **Tension / Sense of urgency** - limited turns and scarce resources should apply pressure on the player to make meaningful choices and strategies.
-** Excitement/Curiousity **- Randomized events, starting positions, and distress call destinations along w/ the flexibility of rules/difficulty ensure unique playthroughs + replayability, enticing players to retry with different strategies to see whether they can play more efficiently in the next run.
- **Satisfaction **- Successfully rescuing all survivors and overcoming hazards and obstacles should feel rewarding to the player, especially if they are able to find efficient paths and resource management strategies
- **Sense of improvement/mastery** - The startegic aspect of the game and emphasis on making smart moves should give players a growing sense of improvement and mastery of the game's mechanics.

---

## Technical Requirements

### Platform
<!-- 
Specify where the game will be played (e.g., PC, console, mobile, VR). 
Mention any cross-platform support if applicable. 
-->
Physical - Boardgame
Digital - PC game - web-based through itch.io

### Tools
<!-- 
List key engines, programming languages, or frameworks required for development. 
-->
**For Digital**
Unity Engine
- C# Scripting
- 
---

## Art and Sound Direction

### Visual Style
<!-- 
Describe the art direction, including color schemes, animation style, and UI elements. 
-->

### Sound Design
<!-- 
Explain the role of music, sound effects, and audio feedback in enhancing immersion. 
-->

---

## Monetization Strategy
<!-- 
Describe how the game will generate revenue. 
Examples: one-time purchase, freemium model, ads, DLC, cosmetics, subscriptions. 
-->

---

## Treatment Details

### Gameplay Example
<!-- 
Write a step-by-step walkthrough of a core gameplay scenario. 
Explain what the player does, the challenges faced, and how the game responds. 
-->

---

### Challenges and Considerations

#### Potential Risks
<!-- 
Identify elements that could fail or require refinement. 
Examples: balancing issues, unclear mechanics, technological constraints. 
-->

#### Feasibility
<!-- 
Describe any technological, financial, or development constraints. 
How will you mitigate these risks? 
-->

---

## Visualizing the Game Concept

### Concept Sketches or Storyboards
- Provide at least **two sketches**  
- Ensure sketches accurately represent the game’s concept and theme  
- Maintain coherence with the game’s style and theme  

<!-- 
Upload sketches here, or describe the key visual elements in detail if unavailable. 
-->

---

## Pitch Preparation

### Pitch Summary
<!-- 
Provide a concise and engaging summary of the game concept and theme. 
Make it persuasive and easy to understand. 
-->

### Target Audience Appeal
<!-- 
Explain how the game connects with its intended audience. 
What elements make it particularly appealing to them? 
-->

### Market Differentiation
<!-- 
Describe what makes this game unique in the current gaming market. 
Compare it to similar games and highlight key advantages. 
-->

---

## External Feedback
<!-- Duplicate Feedback group as necessary if beyond 3 -->

### Feedback 1
- **Reviewer**:  
  <!-- Enter name and relation to you -->
- **Summary**:  
  <!-- Summarize feedback focusing on concept, mechanics, and style -->
- **Refinement**:  
  <!-- Explain how this feedback will improve the design -->

### Feedback 2
- **Reviewer**:  
  <!-- Enter name and relation to you -->
- **Summary**:  
  <!-- Summarize feedback focusing on concept, mechanics, and style -->
- **Refinement**:  
  <!-- Explain how this feedback will improve the design -->

### Feedback 3
- **Reviewer**:  
  <!-- Enter name and relation to you -->
- **Summary**:  
  <!-- Summarize feedback focusing on concept, mechanics, and style -->
- **Refinement**:  
  <!-- Explain how this feedback will improve the design -->


---

## Appendix
<!-- 
Include any additional sketches, mood boards, or early design mockups if available.  
If digital assets are unavailable, describe any rough concepts you have in mind. 
-->

---
