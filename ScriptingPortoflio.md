🧠 Scripting Portfolio

Below is an overview of my Roblox scripting skills and completed projects.
I also link my YouTube channel, which showcases small prototypes of my projects and commissions.
**(Final products are more advanced and bug‑fixed compared to the demos.)**


I am currently developing several complex open‑source scripts that will be available on my main profile.
I primarily publish anti‑exploit systems, reverse‑engineering tools, and administration modules, as they align with my computer science objectives.


[![WhoAmI](https://github.com/user-attachments/assets/f5cc21db-dce7-403c-8300-95ed8ab62905)](https://www.youtube.com/@sqldevv)

Examples of my work:


<img width="1900" height="400" alt="scriptingBannerShowcase" src="https://github.com/user-attachments/assets/a5c50907-7c94-4d32-9c22-63a5d07bcba3" />

📌 Inventory System
<img width="1900" height="400" alt="inventorySystem" src="https://github.com/user-attachments/assets/e19de68e-8190-4091-b39f-fe17ed1170c9" />

A modular and scalable inventory system designed for clean integration with other game systems.
It supports item metadata, stack logic, UI binding, and server‑safe replication.
The system is fully cross‑platform and dynamically scales each inventory slot to ensure icons and frames fit correctly on any device, including mobile and console.

It works in strict connection with the data‑storage layer to load or retrieve player data.
Data is cached when players leave or join unexpectedly, then released to optimize memory usage.

**The new version supports cross‑platform interaction and uses a custom grip system that changes how players interact with tools.**


[![Demo](https://github.com/user-attachments/assets/<img width="1280" height="720" alt="toolsRarityClickDemo" src="https://github.com/user-attachments/assets/0998ee26-4a4b-4c1d-9f6e-3c8d6436e6dd" />)](https://youtu.be/InRCrSKMKw8?si=J1M-3scHaZta9bab)



📌 Data Service Layer (Data Storage)
<img width="1900" height="400" alt="dataStorage" src="https://github.com/user-attachments/assets/fe5efff3-36b8-4a7d-b6e2-59c560b60f5c" />

A robust data pipeline supporting autosaving, periodic saving, binary encoding, and safe fallback logic.
Designed for performance, reliability, and minimal corruption risk.

It combines multiple data types, ranging from basic stats to placement‑system data and tools/badges.
String data is converted to binary and back to reduce storage cost.
This system replaces the need for open‑source libraries, keeping the code private and secure.

📌 NPC Notoriety System
<img width="1900" height="400" alt="notorietySystem" src="https://github.com/user-attachments/assets/45467275-ef58-4002-8d6f-4ebc929e5b2e" />
A dynamic escalation system inspired by open‑world crime games.

**Features**
Star‑based notoriety levels  
Higher stars = stronger, more numerous AI units with better gear and animations.

Dynamic AI spawning  
AI does not know your exact location; it searches the area.
Surveillance cameras can pinpoint you at any time.

Threat‑scaled NPC types and equipment  
Applies to any player breaking defined rules.

Weapon assignment logic  
NPCs choose weapons based on notoriety level.

Detection & engagement rules  
NPCs tag players as Targets when detected.
Line‑of‑sight loss may reduce stars.
Breaking laws triggers search mode and de‑escalation.

“Disrespect Mechanic”  
Certain non‑criminal actions (bumping, aiming, etc.) can trigger reactions.

[![Demo](https://github.com/user-attachments/assets/<img width="1280" height="720" alt="thumbnailClickPathfinding" src="https://github.com/user-attachments/assets/c39f3a9a-dfb6-4006-bbe1-e3047354638e" />
)](https://youtu.be/R8NCFrKhjos?si=5wwJf8dq52DugAlj)


📌 Cinematic Door Teleporter
<img width="1900" height="400" alt="cinematicDoorSystem" src="https://github.com/user-attachments/assets/31f8307c-bd4e-4daf-9c7c-4bdca9f7ce7d" />

A server-side validated cinematic door system, using tween service instead of roblox's constraints, which can cause malfunctions. This prototype allows the user of a plot system to accept or deny any visits, while keeping exploiters out of bounds. It teleports the user to a specific plot, correcting rotation, camera FOV and character humanoid characteristics in real-time. Uses camera transitions, animations, event‑driven triggers, and smooth cinematic sequences.

The door can also use group-level  verification, to deny or approve teleporting any door, or open the door in the first place.**

📌 Avatar Editor (Outdated — replaced with a custom avatar system and improved module architecture)
<img width="1900" height="400" alt="avatarEditor" src="https://github.com/user-attachments/assets/0564efd1-2585-42d4-a149-93ef87f5eed0" />

**Features**
Proximity‑prompt based (now replaced with a custom advanced prompt)

Teleports players to a dedicated room to change appearance

Supports body‑color editing via a color palette

Can integrate with data saving to automatically load saved outfits

Allows removal of hats and accessories that interfere with editing

Fully cross‑platform

[![Demo](https://github.com/user-attachments/assets/<img width="1280" height="720" alt="avatarEditorClickDemo" src="https://github.com/user-attachments/assets/0186499c-6ca0-48b7-8952-5e8060baf63d" />)](https://youtu.be/_zOCNyF0Df0?si=SPd45ojNOAG5iEDc)
📌 Periodic Data Saving

Automatically saves player data at intervals and handles coin accumulation.
Leaving the experience triggers an automatic save to prevent crash‑related or intentional data loss.
Can be connected to progression systems for simulators or RPGs.

[![Demo](https://github.com/user-attachments/assets/)<img width="1280" height="720" alt="New ProjecperiodicDataSavingClickDemot" src="https://github.com/user-attachments/assets/b9ef773d-8991-4fbc-aea4-502eb17c3383" />](https://youtu.be/AVknx4BaAqk?si=r-YpLYbqVzktvo63)

📌 Rank & Device Scanning

**Detects player device type, input method, and group rank for adaptive gameplay.
Connects automatically to a debounce system, and cross-platform system which changes on-screen information and buttons.**

[![Demo](https://github.com/user-attachments/assets/)<img width="1280" height="720" alt="rankAndDeviceScanningClickDemo" src="https://github.com/user-attachments/assets/09043f22-f28c-440b-9025-121e01fab87d" />](https://youtu.be/FgAG7cHb20M?si=FLrX-YHurnOJMM_q)

**🧩 Engineer-level Systems**
(These are highly technical systems that nstrate deeper engineering skill.)
Not for sale of distribution.

<img width="1900" height="400" alt="systemsEngineering" src="https://github.com/user-attachments/assets/7539b27c-2320-4fe9-9414-fba87169c871" />

📌 Abstract Syntax Tree (AST) Script Flow Visualizer
Parsed Luau code into an AST and visualized script flow as a chart.
Discontinued, but demonstrates compiler‑level understanding.

📌 Custom ML Pathfinding System
A fully custom pathfinding system built from scratch in Luau, replacing Roblox’s PathfindingService for full control over AI behavior.
Currently discontinued for time‑management reasons.

Key Features
**Machine Learning Layer**
<img width="1900" height="400" alt="scriptingML" src="https://github.com/user-attachments/assets/70d47828-bc30-49cb-8635-fd08b5b73c6a" />

**Key Features**
Machine‑learning‑style prediction  
Evaluates obstacles and movement aerodynamics.
Outperforms Roblox’s built‑in pathfinding by combining multiple algorithms to compute token consumption and optimal paths.

Custom A\ Algorithm*
Optimized heuristic with additional mathematical models.

Dynamic grid generation  
Automatically generates walkable nodes from map geometry.

Real‑time recalculation  
AI updates paths dynamically as the environment changes.

Debug tools  
Toggleable grid and path visualization.

[![Demo](https://github.com/user-attachments/assets/)<img width="1280" height="720" alt="mlPathfindingClickDemo" src="https://github.com/user-attachments/assets/cae4265e-d32f-4ad5-a760-4edbe2655814" />](https://youtu.be/SQOTcHuuuJE?si=eLg7LrIfDqSY0EtE)


😊 **Alternative using Roblox’s built‑in pathfinding** : (Runs faster due to C++ optimization.)

[![Demo](https://github.com/user-attachments/assets/)<img width="1280" height="720" alt="pathfindingServiceClickDemo" src="https://github.com/user-attachments/assets/31011a5a-1dcc-413d-b0e8-c0ea3a2e385f" />](https://youtu.be/UQ8wNuy6Cr0?si=5twpESlUYmfEA6tg)


📌 Binary Placement System
<img width="1900" height="400" alt="placementSystem" src="https://github.com/user-attachments/assets/467fbbf0-42e1-49e8-9896-2d6a5f42d28e" />

A placement system with binary save/load, reversible encoding, and an optimized memory footprint.

Data loads immediately when players join and supports a user‑friendly slot system to save, overwrite, or delete slot data.
New players receive default furniture and plot structures.
Players can customize plot aesthetics while maintaining structural integrity to prevent breaking the plot.
Can integrate with a texture library for furniture customization.
