# Mustafa Kum — Gameplay & Performance Engineer

Gameplay Engineer specialized in scalable systems, combat architecture, and performance optimization. With a deep focus on **Unreal Engine 5 (C++)** and **Unity (C#)**, I build data-driven gameplay mechanics, integrate complex AI, and deliver highly polished, shipped products. My background includes full-cycle development for **shipped iOS titles** and extreme performance engineering for **HTML5 playable ads** (sub-1MB bundles).

- 📧 **Email:** kum.mustafa96@gmail.com  
- 💼 **LinkedIn:** https://www.linkedin.com/in/mustafa-kum/  
- 🎮 **itch.io:** https://kumdev.itch.io

---

## 🛠️ Skills & Technologies

**Engines/Languages:** Unity/C#, Unreal Engine 5/C++, HTML5/JavaScript  
**Gameplay & Systems:** State machines, combat, abilities (**GAS/Tags**), BT/EQS AI, UI/HUD, camera systems  
**Animation & VFX:** Animation Blueprints, Montages/Notifies, retargeting, **Niagara**, DOTween, Cinemachine  
**Optimization:** Unreal Insights/`STAT`, async asset/level streaming, object pooling, Addressables, profiling/GC, draw-call/overdraw reduction  
**Release:** iOS (TestFlight/App Store), WebGL, HTML5 playable ads, Git (Perforce familiar)

<p align="left">
  <a href="https://unity.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" width="36" alt="Unity"/></a>
  <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="36" alt="C#"/></a>
  <a href="https://www.unrealengine.com/" target="_blank"><img src="https://raw.githubusercontent.com/EpicKiwi/unreal-engine-editor-icons/refs/heads/master/imgs/NewLevels/NewLevelDefault.png" width="46" alt="Unreal Engine"/></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="36" alt="JavaScript"/></a>
  <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="36" alt="HTML5"/></a>
  <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="36" alt="Git"/></a>
</p>

---

## 🕹️ Unreal Engine 5 & C++ Systems

### 🔥 Advanced Third-Person Combat System (UE5)
Personal project to master AAA-style third-person combat and AI in **UE5/C++** (inspired by *God of War*).
- **Architecture:** C++ cancelable combo state machine; dodge, block, parry; two unique abilities.
- **AI & Systems:** Behavior Trees + Blackboard; EQS positioning; multi-phase boss encounter.
- **Game Feel & VFX:** Root-motion retargeting, Niagara effects, camera shake, hit-stops, time dilation.
- ▶️ **Gameplay Demo:** https://youtu.be/8BcLFCZjd8s  
- 💻 **Repository:** https://github.com/Mustafa-Kum/GodOfWarClone

### 🧠 Scalable Inventory & Equipment System (UE5)
Modular, data-driven Inventory & Equipment System designed for scalability and clean architecture. *(Technical Showcase)*
- Event-driven UI (no Tick, delegate-based updates).
- Fully data-driven via **UDataAssets** and asynchronous asset loading (`StreamableManager`).
- Modular, decoupled architecture following SOLID principles.
- 💻 **Repository:** https://github.com/Mustafa-Kum/Inventory_System_Showcase

### ⚔️ Modular GAS Weapon System (UE5)
Data-Driven, Component-Based Weapon System utilizing Unreal Engine's **Gameplay Ability System (GAS)**. 
- Decouples weapon logic from character classes using Interfaces and Data Assets.
- Features Input Buffering, Asynchronous Asset Loading, and Animation Notify driven state changes.
- 💻 **Repository:** https://github.com/Mustafa-Kum/UE-5.7.3-WeaponSystem-Equip-Unequip

---

## 📱 Unity & Shipped Mobile Games

### 👾 Cubix Path (iOS) — *Shipped*
Sole front-end developer responsible for core gameplay, **UI/UX**, polish, and optimization.
- Built water mechanics and responsive **cube jiggle** feedback.
- Achieved stable **60 FPS** on target devices.
- 🍎 **App Store:** https://apps.apple.com/tr/app/cubix-path-puzzle-match/id6478001225  
- 💻 **Code:** https://github.com/Mustafa-Kum/PuzzleCode

### 🚜 Farm Connect Match (iOS) — *Shipped*
Built the entire front-end for this 3D puzzle game.
- Handled mechanics, UI/UX, polish, custom cameras, and mobile optimization.
- 🍎 **App Store:** https://apps.apple.com/us/app/farm-connect-match-3d-puzzle/id6503044105  
- 💻 **Code:** https://github.com/Mustafa-Kum/FarmPuzzleCode

### 🛠️ Modular Scratch-Card Surface (Unity Optimization)
Highly optimized, open-source scratch-card mechanic for Mobile, WebGL, and Playable Ads. Features batched texture replacement and fail-safe rendering to maintain stable 60FPS.
- 💻 **Code & Setup:** https://github.com/Mustafa-Kum/Moduler-ScratchCard-Unity-Luna

<details>
<summary>📂 <b>View Additional Unity Prototypes & Projects (Click to expand)</b></summary>
<br>

- **Third-Person Shooter:** Third-person controller, combat loop, basic enemy AI. [Play](https://kumdev.itch.io/thirdpersonshooter) | [Code](https://github.com/Mustafa-Kum/ThirdPersonShooter)
- **Merge Valley (WebGL):** Casual merge game. [Play](https://kumdev.itch.io/merge-valley) | [Code](https://github.com/Mustafa-Kum/MergeCode)
- **Cooking Live:** Fast-paced casual prototype. [Play](https://kumdev.itch.io/cook) | [Code](https://github.com/Mustafa-Kum/CookCode)
- **Car Game:** Mobile driving prototype. [Gameplay](https://www.youtube.com/shorts/Uxj482VLfBA) | [Code](https://github.com/Mustafa-Kum/CarGame)
- **Pizza Path:** Casual mobile game. [Gameplay](https://youtube.com/shorts/1HCB7iJKOvM)
- **Passenger Puzzle:** AA mobile puzzle prototype. [Gameplay](https://youtu.be/KGkw-92USvs)
- **CrawRunner (Google Play):** 2D RPG. [Play](https://kumdev.itch.io/crawrunner) | [Code](https://github.com/Mustafa-Kum/CrawRunner)
- **Flowers Needle:** 2D RPG prototype. [Play](https://kumdev.itch.io/flowers-needle) | [Code](https://github.com/Mustafa-Kum/Flowers-Needle-Game-4)
- **CrawShooter:** Top-down shooter. [Play](https://kumdev.itch.io/crawshooter) | [Code](https://github.com/Mustafa-Kum/CrawShooter)
- **Infinity Shooter:** Endless shooter. [Play](https://kumdev.itch.io/infinity-shooter) | [Code](https://github.com/Mustafa-Kum/Infinity-Shooter-Game-1)
- **3D Adventurer:** Camera & movement prototype. [Play](https://kumdev.itch.io/3d-adventurer) | [Code](https://github.com/Mustafa-Kum/Experimental-Game)
- **The Great Fleece:** Stealth mechanics. [Play](https://kumdev.itch.io/the-great-fleece) | [Code](https://github.com/Mustafa-Kum/The-Great-Fleece-Game-3)
- **Dungeon Escape:** 2D puzzle-platformer. [Play](https://kumdev.itch.io/dungeon-escape) | [Code](https://github.com/Mustafa-Kum/Dungeon-Escape-Game-2)
</details>

---

## 🌐 HTML5 & Playable Ads Performance Engineering

> **Achievement:** Built complete mini-games without any game engine (Pure JS/HTML5); maintained bundle sizes **<1 MB**; campaigns achieved **up to +15% CTR** uplift.

### Highlighted HTML5 Projects
- **Co-op Advanced Vampire Survivors Clone (2D):** Engine-less clone focusing on performant projectile management. ▶️ [Play Here](https://sunny-faun-9a54d3.netlify.app/)
- **AppleGrappler Ad:** Built via Unity Luna. ▶️ [Play Here](https://tranquil-bonbon-572e24.netlify.app/) | 💻 [Code](https://github.com/Mustafa-Kum/Apple-Grappler-Unity-Luna)
- **Tail Team Ad:** Pure HTML5/CSS/JS. ▶️ [Play Here](https://kumdev.itch.io/playable-ad-tail-team)

<details>
<summary>📂 <b>View All HTML5 Ads & Engine-less Games (Click to expand)</b></summary>
<br>

**Engine-less Web Games**
- **Vampire Survivors Clone (2D):** [Play](https://kumdev.itch.io/html5) | [Code](https://github.com/Mustafa-Kum/VampireSurvivorCopy)
- **Memory Game:** [Play](https://kumdev.itch.io/hafza-oyunu-html) | [Code](https://github.com/Mustafa-Kum/MemoryGame)
- **BulletStrike (WebGL):** [Play](https://kumdev.itch.io/html-5-2) | [Code](https://github.com/Mustafa-Kum/BulletStrike)
- **Necromancer3D:** [Play](https://kumdev.itch.io/necromancer) | [Code](https://github.com/Mustafa-Kum/Necromancer3D)

**Pure HTML5/CSS/JS Playable Ads**
- **Candy Crush Ad:** [Play](https://kumdev.itch.io/playable-ad-candy-crush)
- **Changable Ad:** [Play](https://kumdev.itch.io/playable-ad-themechangable)
- **Puzzle Ad:** [Play](https://kumdev.itch.io/test)
- **NVIDIA Ad:** [Play](https://kumdev.itch.io/playable-ad--test)
- **Connect-Dots Ad:** [Play](https://kumdev.itch.io/playable-ad-connect-dots)
- **Sand Balls Ad:** [Play](https://kumdev.itch.io/playable-ad-sand-balls)
- **Angry Birds Ad:** [Play](https://kumdev.itch.io/playable-ad-angry-birds)
- **Twisted Tangle 2D Ad:** [Play](https://kumdev.itch.io/playable-ad-twisted-tangle-2d)
- **Fruit Ninja Ad:** [Play](https://kumdev.itch.io/playable-ad-fruit-ninja)
- **Merge Ad:** [Play](https://kumdev.itch.io/playable-ad)
- **Ball Ad:** [Play](https://kumdev.itch.io/playable-ad-baloon)
- **Zeppelin Ad:** [Play](https://kumdev.itch.io/playable-ad-zeplin)
</details>

---
