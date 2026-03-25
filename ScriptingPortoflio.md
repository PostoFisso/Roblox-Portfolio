🧠 **Scripting Portfolio**
Below an overview of my roblox scripting skills and completed projects.
Below my youtube channel, showcasing small (s) of my projects ad commissions: (The final products are more advanced than shown)

**https://www.youtube.com/@sqldevv**

<img width="1900" height="400" alt="scriptingBannerShowcase" src="https://github.com/user-attachments/assets/a5c50907-7c94-4d32-9c22-63a5d07bcba3" />

📌 Inventory System
<img width="1900" height="400" alt="inventorySystem" src="https://github.com/user-attachments/assets/e19de68e-8190-4091-b39f-fe17ed1170c9" />
A modular and scalable inventory system designed for clean integration with other game systems.
Supports item metadata, stack logic, UI binding, and server‑safe replication. Supports cross-platform, and scales each inventory slot dynamically to ensure icons and frames to fit, based on the device in sure; mobile or console regardless. Works in strict connection with data-storage capabilities, to load, or retrieve any data from the player. This also applies to leaving or joining randomly, data is saved within a cache, then released to optimize memory usage.

📌 Data Service Layer (Data Storage)
<img width="1900" height="400" alt="dataStorage" src="https://github.com/user-attachments/assets/fe5efff3-36b8-4a7d-b6e2-59c560b60f5c" />

A robust data pipeline supporting autosaving, periodic saving, binary encoding, and safe fallback logic. Designed for performance, reliability, and minimal data corruption risk. Great for heavy data storage resolution. It combines multiple type of storage data, ranging from basic points, to placement system data and tools/overhead badges. Data is changed from strings content to binary and vice-versa to ensure that the size of each specific asset or abstract object is not expensive-wise. It replaces the need for a open-source library, to keep code source private and safe from indiscreet eyes.

📌 NPC Notoriety System
<img width="1900" height="400" alt="notorietySystem" src="https://github.com/user-attachments/assets/45467275-ef58-4002-8d6f-4ebc929e5b2e" />
A dynamic escalation system inspired by open‑world crime games.

**Features**
Star‑Based Notoriety Levels  
Higher stars = stronger, more numerous AI units (better gear and animations);
Dynamic AI Spawning; (Ai doesn't know where you are, it searches the area for your presence.) Surveillance cameras can pinpoint your location at any time;
NPC types and equipment scale with player threat level. This applies to anyone breaking specific rules (parameters);
Weapon Assignment Logic (Weapons can be a simple tazer or baton, or a heavy-equipment weapon);
NPCs choose weapons based on player notoriety.
Detection & Engagement Rules;
NPCs tag players as [Target] when detected. (Players can lose notoriety);
Line‑of‑Sight Loss → Possible star reduction; 
Breaking laws triggers search mode and de‑escalation;
“Disrespect Mechanic” (Some actions can trigger notoriety);
Non‑criminal actions (bumping, aiming, etc.) can trigger NPC reactions.

DEMO: [![Video](https://img.youtube.com/vi/R8NCFrKhjos/0.jpg)](https://youtu.be/R8NCFrKhjos)


📌 Cinematic Door Teleporter
<img width="1900" height="400" alt="cinematicDoorSystem" src="https://github.com/user-attachments/assets/31f8307c-bd4e-4daf-9c7c-4bdca9f7ce7d" />

A server-side validated cinematic door system, using tween service instead of roblox's constraints, which can cause malfunctions. This prototype allows the user of a plot system to accept or deny any visits, while keeping exploiters out of bounds. It teleports the user to a specific plot, correcting rotation, camera FOV and character humanoid characteristics in real-time. Uses camera transitions, animations, event‑driven triggers, and smooth cinematic sequences.

The door can also use group-level  verification, to deny or approve teleporting any door, or open the door in the first place.

📌 Avatar Editor (Outdated; now using a custom avatar and a better module architecture)
<img width="1900" height="400" alt="avatarEditor" src="https://github.com/user-attachments/assets/0564efd1-2585-42d4-a149-93ef87f5eed0" />

**Features**
Proximity prompt based; (Now using an advanced custom proximity prompt);
Filters player's state and if allowed, teleports the player to a special room to change appearance, and clothing;
The new version allows changing the body colors using a color palette. (Important for some players);
Can be implemented with a data saving system; allowing players to automatically load selected characters, without the requirement to wear the same accessories every time;
Allow players to remove existing hats and accessories, which can disrupt the overall character editing.
Support cross platform implementation and usage, on large scale.

DEMO [![Video](https://img.youtube.com/vi/_zOCNyF0Df0/0.jpg)](https://youtu.be/_zOCNyF0Df0)

📌 Periodic Data Saving
Automatically saves player data at intervals and handles coin accumulation. Leaving the experience triggers an automatic data saving, to avoid crash-related or intentional data loss for players. Can be bound to other mechanics to create a progression-based game or simulator.

DEMO [![Video](https://img.youtube.com/vi/AVknx4BaAqk/0.jpg)](https://youtu.be/AVknx4BaAqk)

📌 Rank & Device Scanning
Detects player device type, input method, and group rank for adaptive gameplay.
Connects automatically to a debounce system, and cross-platform system which changes on-screen information and buttons.

DEMO [![Video](https://img.youtube.com/vi/FgAG7cHb20M/0.jpg)](https://youtu.be/FgAG7cHb20M)

**🧩 Engineer-level Systems**
(These are highly technical systems that nstrate deeper engineering skill.)
Not for sale of distribution.

<img width="1900" height="400" alt="systemsEngineering" src="https://github.com/user-attachments/assets/7539b27c-2320-4fe9-9414-fba87169c871" />

📌 Abstract Syntax Tree (AST) Script Flow Visualizer
A system that parsed Luau code into an AST and visualized script flow as a chart.
Discontinued, but nstrates compiler‑level understanding.

📌 Custom ML Pathfinding System
A fully custom pathfinding system built from scratch in Luau, replacing Roblox’s PathfindingService for full control over AI behavior.
Discontinued for now, for time-management reasons.

Key Features
**Machine Learning Layer**
<img width="1900" height="400" alt="scriptingML" src="https://github.com/user-attachments/assets/70d47828-bc30-49cb-8635-fd08b5b73c6a" />

**Neural‑network‑style prediction** to evaluate obstacles and movement aerodynamics. Works much better than the roblox's built-in pathfinding service, as it combines multiple algorithms to calculate tokens consumption and most optimized paths possible.

**Custom A\ Algorithm***
Optimized heuristic combined with additional mathematical models.

**Dynamic Grid Generation**  
Automatically generates walkable nodes from map geometry.

**Real‑Time Recalculation**  
AI updates paths dynamically based on environment changes.

**Debug Tools**  
Toggleable grid + path visualization for development.

DEMO [![Video](https://img.youtube.com/vi/SQOTcHuuuJE/0.jpg)](https://youtu.be/SQOTcHuuuJE)

😊 **Alternative using roblox's built-in pathfinding: (Runs faster, as it's otpimized using C++)
DEMO [![Video](https://img.youtube.com/vi/UQ8wNuy6Cr0/0.jpg)](https://youtu.be/UQ8wNuy6Cr0)

📌 Binary Placement System
<img width="1900" height="400" alt="placementSystem" src="https://github.com/user-attachments/assets/467fbbf0-42e1-49e8-9896-2d6a5f42d28e" />

A placement system with binary save/load, reversible encoding, and optimized memory footprint.
Data is loaded directly upon joining the game, and supports a user-friendly player slots system to save, overwrite, or delete any slot-data associated with the player's experience. Loads default furniture and plots structures for new players, allowing to change plot aesthethics while offerig a generous plot size, inside and an extra plot outside the plot itself. Can be combined with a textures library to change furniture, but not walls or structural aspects to avoid players breaking plots.
