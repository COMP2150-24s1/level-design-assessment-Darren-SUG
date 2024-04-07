# COMP2150  - Level Design Document
### Name: Darren Sugihartono
### Student number: 47870966 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?
In the starter room there is a staff pickup and a breakable column which encourages the player to use the newly obtained staff to break the part of the wall that looks different, this teaches them that different looking walls are breakable. The player will also learn how to time their jumps to be able to make it across many acid pools and each of these acid encounters are usually close by to a checkpoint to prevent the player from going back too far and making the game boring. Players will find that by exploring different areas they will be rewarded with health pickups to help them recover any health lost but these rewards are mostly guarded by enemies so the player will have to be able to kill them beforehand or dodge all enemies which might prove difficult. Some areas in the game aren’t accessible until the player has either moved a box to the right position or pressed a switch so that will help them explore the map further.
### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 
I think my intensity curve is more linear when moving through the different sections of the level. The most difficult parts of the game are the parkour sections since the enemies reaction time is really slow which makes them easy to kill if you have the pistol but even without the pistol the player should be able to kill them easily so by combining enemies and parkour is where it gets tougher in section 2 and 3. There is a very tense encounter when the player has to get the final key, they must get through many enemies and at the end there are moving platforms over acid and the player will have to start that section over if they fall in so there's some relief when they reach the key and get a health pickup. I think section 3 has the most tense moments since I added a lot more acid to increase the risk.
### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?
The main challenge is finding the keys, parkour and killing the enemies. For the first section of the level, I separated the enemies and parkour to introduce them slowly first so then it would be easy at first. In section 2, I tried to put some spikes near enemies so that the player would have to worry about not touching the spikes and killing the enemies and I also added a little cave area where there's a switch but there are enemy spawners inside so it's a little risky to go through but if the player is able to kill or dodge the enemies then they will be rewarded for it by being able to get through to the next section of the level. Section 3 is where I added a lot more spikes, acid and enemies since it had to be the hardest section and since there was a lot of acid, I decided to balance it out by adding a second checkpoint to the section and another health pickup near the key to relieve the player of the health lost.
### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?
I use doors and roadblocks to make the player explore the level until they find what they need to move on, like a switch or a box. I created multiple pathways so that the player can choose to go where they want to go but if they skipped an important part then they would have to track back to find what they needed. I made the aesthetic kind of cave-like for most of the level but I don't think there were any distinct places other than section 3 using a different tile type although section 2 has a different background to some parts to match the section 3 above it so that may be an interesting look when a player goes through it.
## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Weapon Pickup (Staff)
![Staff Storyboard](DocImages/StaffEncounter.jpg)
Since it was the beginning of the level, I thought that the player would need a weapon early on so I gave them a staff which they can test out on the breakable column.
### 2.2. Moving Platforms
![Moving Platforms Storyboard](DocImages/SpitterMovingPlatformEncounter.jpg)
The parkour in my level is going to get harder so I wanted to introduce the mechanic earlier so that the player can expect harder sections with moving platforms.
### 2.3. Spitters
![Spitter Storyboard](DocImages/SpitterMovingPlatformEncounter.jpg)
The spitter here was to help by letting the player dodge its spit or kill the spitter so they would know how spitters worked and how they could potentially disrupt parkour sections.
### 2.4. Checkpoints
![Checkpoint Storyboard](DocImages/AcidCheckpointEncounter.jpg)
I added the check point here because I wanted to introduce acid right after so if the player falls into the acid then they would realise that they can respawn at these checkpoints.
### 2.5. Acid
![Acid Storyboard](DocImages/AcidCheckpointEncounter.jpg)
The acid is placed right next to the checkpoint because I did not want the players to have to go all the way to the beginning if they fell in the acid.
### 2.6. Weapon Pickup (Gun)
![Gun Storyboard](DocImages/GunHealthSpikeEncounter.jpg)
I wanted to encourage exploration so I kind of hid the gun so that players needed to explore if they wanted to find the gun which would help kill enemies a lot easier.
### 2.7. Health Pickups
![Health Pickup Storyboard](DocImages/GunHealthSpikeEncounter.jpg)
Since the player might or might not have taken damage up until this point then I gave them some health to relieve them of the stress of low health.
### 2.8. Spikes
![Spike Storyboard](DocImages/GunHealthSpikeEncounter.jpg)
The spikes were added here so that if the player still had max health and accidentally touched the spike then they would be able to use the health pickup.
### 2.9. Chompers
![Chompers Storyboard](DocImages/ChomperEncounter.jpg)
I wanted to let the player use the gun that they recently received if they had found it so that they could test it out.
### 2.10. Passthrough Platforms
![Passthrough Platform Storyboard](DocImages/PassablePlatformEncounter.jpg)
The passthrough platform was added here to add a little puzzle solving since the player can see a room underground and they would be rewarded with a switch to enable a platform that leads to the key.
### 2.11. Keys
![Key Storyboard](DocImages/KeyEncounter.jpg)
The key was added here so that the player would need to explore more sections and tell the player that getting to the end does not mean that they are finished with the section.
## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram
![Molecule Diagram](DocImages/MoleculeDiagram.png)
### 3.2. Level Map – Section 1
![Section 1 Level Map](DocImages/Section1.jpeg)
### 3.3.	Level Map – Section 2
![Section 2 Level Map](DocImages/Section2.jpeg)
### 3.4.	Level Map – Section 3
![Section 3 Level Map](DocImages/Section3.jpeg)
## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


