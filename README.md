# Mustafa Kum — Gameplay & Performance Engineer

Versatile **Gameplay & Performance Engineer** with professional experience in **Unity (C#)** and a deep focus on **Unreal Engine 5 (C++)**. I build responsive, polished gameplay systems and ship to **iOS** and **WebGL**. I've also created high-performance **HTML5/JavaScript playable ads** (bundles **<1 MB**, **up to +15% CTR** uplift).

- 📧 **Email:** kum.mustafa96@gmail.com
- 💼 **LinkedIn:** https://www.linkedin.com/in/mustafa-kum/
- 🎮 **itch.io:** https://kumdev.itch.io

---

## 🗺️ Navigate

[🚀 Unreal Engine 5](#-unreal-engine-5-projects) · [🧩 Modular RPG Series](#-modular-rpg-series-ue5) · [🎮 Unity Shipped](#-unity--shipped-games) · [🎮 Unity Team Projects](#-unity--team-projects) · [🎮 Unity Personal](#-unity--personal-projects) · [✨ Playable Ads](#-playable-ads-html5javascript) · [🕹️ HTML5 Games](#️-html5--javascript-games)

---

## 🛠️ Skills & Technologies

| Category | Skills & Technologies |
| :--- | :--- |
| 🛠️ **Engines & Languages** | Unity (C#), Unreal Engine 5 (C++), HTML5/JavaScript |
| ⚔️ **Gameplay & Systems** | State machines, Combat, Modular Ability Systems (**GAS/Tags**), Skill Books, Cast Bars, BT/EQS AI, UI/HUD, Camera |
| ✨ **Animation & VFX** | Animation Blueprints, Montages/Notifies, Retargeting, **Niagara**, DOTween, Cinemachine |
| ⚙️ **Optimization** | Unreal Insights/`STAT`, Async asset streaming, Object pooling, Addressables, Profiling/GC |
| 🚀 **Release & Tools** | iOS (TestFlight/App Store), WebGL, Playable Ads, Git (Perforce familiar) |

<br>

<p align="left">
  <a href="https://unity.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" width="36" alt="Unity"/></a>
  <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="36" alt="C#"/></a>
  <a href="https://www.unrealengine.com/" target="_blank"><img src="https://raw.githubusercontent.com/EpicKiwi/unreal-engine-editor-icons/refs/heads/master/imgs/NewLevels/NewLevelDefault.png" width="46" alt="Unreal Engine"/></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="36" alt="JavaScript"/></a>
  <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="36" alt="HTML5"/></a>
  <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="36" alt="Git"/></a>
</p>

---

## 🚀 Unreal Engine 5 Projects

### 🔥 Third-Person Action Game (UE5)
*Personal project — Sole Developer*

![](https://img.shields.io/badge/Unreal_Engine-5-blue?logo=unrealengine) ![](https://img.shields.io/badge/Language-C++-00599C?logo=cplusplus&logoColor=white) ![](https://img.shields.io/badge/Performance-High-lightgray) ![](https://img.shields.io/badge/AI-Behavior_Trees-brightgreen) ![](https://img.shields.io/badge/System-GAS-yellowgreen)

Personal project third-person combat and AI in **UE5/C++** (inspired by *God of War*).

- **Architecture:** C++ cancelable combo state machine; dodge, block, parry; two unique abilities
- **Enemy AI:** Behavior Trees + Blackboard; EQS positioning; multi-phase boss encounter
- **Animation:** Animation Blueprints, Montages/Notifies, root-motion, retargeting
- **VFX & Feel:** Niagara effects; camera shake; hit-stops; time dilation; procedural feel
- **UI/Loop:** Main menu, in-game HUD, settings; Arena Mode with wave spawner
- **Data & Perf:** Curve Tables for tuning; SFX integration; continuous optimization
- 🎬 **Gameplay Demo:** https://youtu.be/8BcLFCZjd8s
- 💻 **Repository:** https://github.com/Mustafa-Kum/GodOfWarClone

---

### ⚔️ Modular GAS Weapon System (UE5)
*Personal project — Sole Developer | Technical Showcase*

![](https://img.shields.io/badge/Unreal_Engine-5-blue?logo=unrealengine) ![](https://img.shields.io/badge/System-GAS-yellowgreen) ![](https://img.shields.io/badge/Design-Data_Driven-orange) ![](https://img.shields.io/badge/Pattern-Component_Based-lightgray)

Data-Driven, Component-Based Weapon System utilizing Unreal Engine's **Gameplay Ability System (GAS)**. Decouples weapon logic from character classes using Interfaces and Data Assets. Features **Input Buffering**, **Asynchronous Asset Loading**, and **Animation Notify** driven state changes for a smooth, AAA-feel combat experience.

- 💻 **Repository:** https://github.com/Mustafa-Kum/UE-5.7.3-WeaponSystem-Equip-Unequip

---

## 🧩 Modular RPG Series (UE5)

> A step-by-step AAA-style RPG architecture built in **Unreal Engine 5 (C++)**.  
> Each part is a self-contained, production-quality module focused on clean architecture, GAS integration, and scalable design.

![](https://img.shields.io/badge/Unreal_Engine-5-blue?logo=unrealengine) ![](https://img.shields.io/badge/Language-C++-00599C?logo=cplusplus&logoColor=white) ![](https://img.shields.io/badge/System-GAS-yellowgreen) ![](https://img.shields.io/badge/Architecture-Modular-lime) ![](https://img.shields.io/badge/Design-Data_Driven-orange)

| # | System | Highlights | Repository |
|:--|:-------|:-----------|:-----------|
| **1** | **Inventory & Equipment System** | Event-driven UI · GAS buff/debuff via `FActiveGameplayEffectHandle` · CDO parsing for tooltips · Async loading via `StreamableManager` · Modular armor with `SetLeaderPoseComponent` | [🔗 Repo](https://github.com/Mustafa-Kum/Inventory_System_Showcase) |
| **2** | **HP & Mana Vitals System** | Reactive UI via GAS delegates · WoW/FFXIV-style trailing bars · Proportional stat scaling · `UCharacterDataAsset`-driven initialization | [🔗 Repo](https://github.com/Mustafa-Kum/UE5-Gas-Vitals-System) |
| **3** | **Melee Combat System** | Combo chaining · Input buffering · Animation-driven combat windows · Reliable melee hit detection · Crit feedback · Hit stop · Pooled combat text | [🔗 Repo](https://github.com/Mustafa-Kum/ue5-rpg-melee-combat-system) |
| **4** | **Ability System** | GAS-based active/passive skills · Skill book + action bar · Cast bar · Cooldowns/costs · Dynamic tooltips · Haste-scaled cast timing · Animation-driven commit/cancel windows · AOE + airborne impact | [🔗 Repo](https://github.com/Mustafa-Kum/ue5-rpg-ability-system) |
| **5** | **Enemy AI** *(Upcoming)* | Behavior Trees + GAS integration | — |
| **6** | **Advanced Stat System** *(Upcoming)* | Buffs, debuffs, stacking | — |

The Ability System module expands the RPG foundation with GAS-driven active/passive skills, animation-authored cast timing, stat-scaled damage, skill book/action bar UI, cooldown and resource handling, dynamic tooltips, and area-impact abilities such as Warcry and Shockwave.

---

## 🎮 Unity — Shipped Games

### 👾 Cubix Path (iOS) — *Shipped*
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX, optimization, release)*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Platform-iOS-000000?logo=apple&logoColor=white) ![](https://img.shields.io/badge/Status-Shipped-success) ![](https://img.shields.io/badge/Performance-60_FPS-brightgreen)

Puzzle game shipped to the App Store. Responsible for every technical layer of the product — core gameplay architecture, backend logic, UI/UX, and App Store release pipeline.

- Water mechanic, responsive **cube jiggle** feedback
- Full UI/HUD/menus and responsive layouts
- Stable **60 FPS** on target devices
- 🍎 **App Store:** https://apps.apple.com/tr/app/cubix-path-puzzle-match/id6478001225
- 🎬 **Gameplay:** https://www.youtube.com/watch?v=0eXOciigD3o
- 💻 **Code:** https://github.com/Mustafa-Kum/PuzzleCode

---

### 🚜 Farm Connect Match (iOS) — *Shipped*
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX, camera, optimization, release)*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Platform-iOS-000000?logo=apple&logoColor=white) ![](https://img.shields.io/badge/Status-Shipped-success) ![](https://img.shields.io/badge/Genre-3D_Puzzle-blue)

3D puzzle game shipped to the App Store. Owned the entire technical stack — mechanics, UI/UX, camera systems, mobile performance, and release pipeline.

- Optimized 3D physics and memory management to maintain a stable **60 FPS** on target iOS devices
- 🍎 **App Store:** https://apps.apple.com/us/app/farm-connect-match-3d-puzzle/id6503044105
- 🎬 **Gameplay:** https://www.youtube.com/watch?v=t4rGmqsmI0I
- 💻 **Code:** https://github.com/Mustafa-Kum/FarmPuzzleCode

---

## 🎮 Unity — Team Projects

### 🍳 Cooking Live (Unity)
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX)*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Mechanics-Responsive_Input-blue) ![](https://img.shields.io/badge/UX-Juicy_UI-orange)

Fast-paced casual prototype focused on responsive input, juicy UI, and clear feedback loops.

- ▶️ **Play:** https://kumdev.itch.io/cook
- 🎬 **Gameplay:** https://www.youtube.com/watch?v=1nN6eWOxZDQ
- 💻 **Code:** https://github.com/Mustafa-Kum/CookCode

---

### ⚔️ Merge Valley (Unity / WebGL)
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX)*

![](https://img.shields.io/badge/Unity-WebGL-990000?logo=webgl&logoColor=white) ![](https://img.shields.io/badge/Optimization-Web_Target-success) ![](https://img.shields.io/badge/Genre-Merge-blue)

Casual merge game deployed to WebGL; built core loop, UI/UX, and WebGL-specific optimization.

- ▶️ **Play:** https://kumdev.itch.io/merge-valley
- 🎬 **Gameplay:** https://www.youtube.com/watch?v=zLaT6ParDjk
- 💻 **Code:** https://github.com/Mustafa-Kum/MergeCode

---

### 🚗 Car Game (Unity)
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX)*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Systems-Physics-yellowgreen) ![](https://img.shields.io/badge/Platform-Mobile-lightgray)

Mobile driving prototype — vehicle controls & physics, VFX/SFX, polished UI.

- 🎬 **Gameplay:** https://www.youtube.com/shorts/Uxj482VLfBA
- 💻 **Code:** https://github.com/Mustafa-Kum/CarGame

---

### 🧩 Passenger Puzzle (Unity)
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX)*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Genre-Puzzle-blue) ![](https://img.shields.io/badge/Scope-AA_Mobile-orange)

AA mobile puzzle prototype — core mechanics, UI/UX, and full feedback systems. Owned all technical layers within the team.

- 🎬 **Gameplay:** https://youtu.be/KGkw-92USvs

---

### 🍕 Pizza Path (Unity)
*3-person team — Full-Stack Game Developer (gameplay, backend, UI/UX)*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Systems-UI_Polish-orange)

Casual mobile game — full gameplay logic, UI systems, and polish.

- 🎬 **Gameplay:** https://youtube.com/shorts/1HCB7iJKOvM

---

## 🎮 Unity — Personal Projects

### 🛠️ Modular Scratch-Card Surface (Unity — Open Source)
*Personal project — Sole Developer*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/Rendering-Optimized-success) ![](https://img.shields.io/badge/Performance-60_FPS-brightgreen) ![](https://img.shields.io/badge/Open_Source-MIT-blue)

Highly optimized, open-source scratch-card mechanic for Mobile, WebGL, and Playable Ads. Features batched texture replacement and fail-safe rendering to maintain stable 60 FPS.

- 💻 **Code & Setup:** https://github.com/Mustafa-Kum/Moduler-ScratchCard-Unity-Luna

---

### 🔫 Third-Person Shooter (Unity)
*Personal project — Sole Developer*

![](https://img.shields.io/badge/Unity-C%23-black?logo=unity&logoColor=white) ![](https://img.shields.io/badge/AI-Basic_Enemy-yellowgreen) ![](https://img.shields.io/badge/Mechanics-Combat_Loop-red)

Third-person controller, full combat loop, basic enemy AI.

- ▶️ **Play:** https://kumdev.itch.io/thirdpersonshooter
- 🎬 **Gameplay:** https://www.youtube.com/watch?v=HaTiYeD7i1I
- 💻 **Code:** https://github.com/Mustafa-Kum/ThirdPersonShooter

---

<details>
<summary>📂 <b>Unity Prototypes & Experiments (Click to expand)</b></summary>
<br>

- **CrawRunner** — 2D RPG; previously on Google Play (AdMob & Google Play SDK) | [Play](https://kumdev.itch.io/crawrunner) | [Gameplay](https://www.youtube.com/watch?v=jNo36mdWnEo) | [Code](https://github.com/Mustafa-Kum/CrawRunner)
- **Flowers Needle** — 2D RPG prototype with narrative/quests | [Play](https://kumdev.itch.io/flowers-needle) | [Gameplay](https://www.youtube.com/watch?v=OOyf2Ugnms4) | [Code](https://github.com/Mustafa-Kum/Flowers-Needle-Game-4)
- **CrawShooter** — Top-down shooter prototype | [Play](https://kumdev.itch.io/crawshooter) | [Code](https://github.com/Mustafa-Kum/CrawShooter)
- **Infinity Shooter** — Endless shooter prototype | [Play](https://kumdev.itch.io/infinity-shooter) | [Code](https://github.com/Mustafa-Kum/Infinity-Shooter-Game-1)
- **3D Adventurer** — Movement, camera, environmental interaction | [Play](https://kumdev.itch.io/3d-adventurer) | [Code](https://github.com/Mustafa-Kum/Experimental-Game)
- **The Great Fleece** — Stealth mechanics and guard AI | [Play](https://kumdev.itch.io/the-great-fleece) | [Code](https://github.com/Mustafa-Kum/The-Great-Fleece-Game-3)
- **Dungeon Escape** — 2D puzzle-platformer with tile-based design | [Play](https://kumdev.itch.io/dungeon-escape) | [Code](https://github.com/Mustafa-Kum/Dungeon-Escape-Game-2)

</details>

---

## ✨ Playable Ads (HTML5/JavaScript)

![](https://img.shields.io/badge/HTML5-Pure-E34F26?logo=html5&logoColor=white) ![](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black) ![](https://img.shields.io/badge/Architecture-Engine--less-darkgray) ![](https://img.shields.io/badge/Optimization-<1_MB-success) ![](https://img.shields.io/badge/Metric-+15%25_CTR-blue)

> Built without any game engine; bundle sizes **<1 MB**; campaigns achieved **up to +15% CTR** uplift.

### 💄 Beauty Brand — HTML5 Interactive End Cards / Playable Ads
*Commercial freelance project — Engine-less HTML5/JavaScript*

![](https://img.shields.io/badge/HTML5-Pure-E34F26?logo=html5&logoColor=white) ![](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black) ![](https://img.shields.io/badge/Format-Interactive_End_Cards-blue) ![](https://img.shields.io/badge/Platform-Mobile-lightgray) ![](https://img.shields.io/badge/Workflow-Fast_Iteration-orange)

A set of browser-based **interactive end cards / playable ad flows** created for a beauty e-commerce campaign. Built as lightweight HTML5 experiences and iterated directly against briefing feedback, design revisions, and CTA / UX adjustments.

**Implemented interaction types:**
- **Spin-to-win** reward wheel
- **Design selection** / “pick your style” flow
- **Swipe / slider reveal**
- **Scratch-card reveal**
- **Hold-to-apply / progress CTA**
- Multiple branded CTA/result states and messaging revisions

**Focus areas:**
- Mobile-friendly interaction flow
- Lightweight browser-ready implementation
- Fast iteration with creative / project teams
- UX clarity, reward pacing, and CTA behavior
- Flexible visual integration from design exports / SVG assets

- Link : https://streamable.com/zo2me5

> Public portfolio version intentionally anonymized. Brand name can be shared privately if needed.

---

- **NVIDIA Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad--test)
- **Tail Team Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-tail-team)
- **Candy Crush Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-candy-crush)
- **Changeable Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-themechangable)

<details>
<summary>📂 <b>View More Playable Ad Campaigns (10+ Projects)</b></summary>
<br>

- **Puzzle Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/test)
- **AppleGrappler Ad** — Unity Luna [Code](https://github.com/Mustafa-Kum/Apple-Grappler-Unity-Luna)
- **Connect-Dots Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-connect-dots)
- **Sand Balls Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-sand-balls)
- **Angry Birds Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-angry-birds)
- **Twisted Tangle 2D Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-twisted-tangle-2d)
- **Fruit Ninja Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-fruit-ninja)
- **Merge Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad)
- **Ball Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-baloon)
- **Zeppelin Ad** — Pure HTML5/CSS/JS | [Play](https://kumdev.itch.io/playable-ad-zeplin)

</details>

---

## 🕹️ HTML5 / JavaScript Games

![](https://img.shields.io/badge/HTML5-Pure-E34F26?logo=html5&logoColor=white) ![](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black) ![](https://img.shields.io/badge/Performance-Engine--less-success)

- **Co-op Advanced Vampire Survivors Clone (2D)** — Engine-less, performant projectile management | [Play](https://sunny-faun-9a54d3.netlify.app/) | [Code](https://github.com/Mustafa-Kum/Vampire-Survivors-Clone)
- **Vampire Survivors Clone (2D)** — Engine-less clone | [Play](https://kumdev.itch.io/html5)
- **Memory Game** — Embeddable, responsive component | [Play](https://kumdev.itch.io/hafza-oyunu-html)
- **BulletStrike (WebGL)** — Top-down shooter in pure JS | [Play](https://kumdev.itch.io/html-5-2)
- **Necromancer3D** — 3D Vampire Survivors-style demo without Three.js | [Play](https://kumdev.itch.io/necromancer)
