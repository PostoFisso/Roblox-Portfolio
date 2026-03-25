🧠 Scripting Portfolio
<img width="1900" height="400" alt="scriptingBannerShowcase" src="https://github.com/user-attachments/assets/a5c50907-7c94-4d32-9c22-63a5d07bcba3" />

📌 Inventory System
<img width="1900" height="400" alt="inventorySystem" src="https://github.com/user-attachments/assets/e19de68e-8190-4091-b39f-fe17ed1170c9" />
A modular and scalable inventory system designed for clean integration with other game systems.
Supports item metadata, stack logic, UI binding, and server‑safe replication.

📌 Data Service Layer (Data Storage)
<img width="1900" height="400" alt="dataStorage" src="https://github.com/user-attachments/assets/fe5efff3-36b8-4a7d-b6e2-59c560b60f5c" />

A robust data pipeline supporting autosaving, periodic saving, binary encoding, and safe fallback logic.
Designed for performance, reliability, and minimal data corruption risk. Great for heavy data storage resolution.

📌 NPC Notoriety System
<img width="1900" height="400" alt="notorietySystem" src="https://github.com/user-attachments/assets/45467275-ef58-4002-8d6f-4ebc929e5b2e" />
A dynamic escalation system inspired by open‑world crime games.

Features
Star‑Based Notoriety Levels  
Higher stars = stronger, more numerous AI units.

Dynamic AI Spawning  
NPC types and equipment scale with player threat level.

Weapon Assignment Logic  
NPCs choose weapons based on player notoriety.

Detection & Engagement Rules  
NPCs tag players as [Target] when detected.

Line‑of‑Sight Loss → Star Reduction  
Breaking LOS triggers search mode and de‑escalation.

“Disrespect Mechanic”  
Non‑criminal actions (bumping, aiming, etc.) can trigger NPC reactions.

Video
https://youtu.be/R8NCFrKhjos

📌 Periodic Data Saving
<img width="1900" height="400" alt="cinematicDoorSystem" src="https://github.com/user-attachments/assets/cd5e734b-429d-4a62-ab9a-4f17223ba4ef" />
A server-side validated cinematic door system, using tween service instead of roblox's constraints, which can cause malfunctions. This prototype allows the user of a plot system to accept or deny any visits, while keeping exploiters out of bounds. It teleports the user to a specific plot, correcting rotation, camera FOV and character humanoid characteristics in real-time.

📌 Periodic Data Saving
Automatically saves player data at intervals and handles coin accumulation.

Video: https://youtu.be/AVknx4BaAqk

📌 Rank & Device Scanning
Detects player device type, input method, and group rank for adaptive gameplay.

Video: https://youtu.be/FgAG7cHb20M


**🧩 Engineer-level Systems**
(These are highly technical systems that demonstrate deeper engineering skill.)
<img width="1900" height="400" alt="systemsEngineering" src="https://github.com/user-attachments/assets/7539b27c-2320-4fe9-9414-fba87169c871" />

📌 Abstract Syntax Tree (AST) Script Flow Visualizer
A system that parsed Luau code into an AST and visualized script flow as a chart.
Discontinued, but demonstrates compiler‑level understanding.

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

Demo Video
https://youtu.be/R8NCFrKhjos

📌 Binary Placement System
A placement system with binary save/load, reversible encoding, and optimized memory footprint.

📌 Cinematic Door System
Doors with camera transitions, animations, event‑driven triggers, and smooth cinematic sequences.
