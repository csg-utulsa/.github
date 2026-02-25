# Programmer - Gameplay 
Gameplay programmers implement player-facing mechanics and interactive features that directly shape moment-to-moment play. This includes character controls, combat, abilities, interactions, and gameplay feedback loops. Their work is focused on feel, responsiveness, clarity, and player experience, rather than building broad engine-level frameworks or large-scale architecture.

> \[!IMPORTANT\]
> 
> ### What Your Portfolio Should Contain
> -   **Player-Facing Mechanics** (combat, abilities, interactions, puzzles, pickups)
> -   **Character Control & Camera Systems** (movement feel, jumping, aiming, camera behavior)
> -   **Gameplay State Logic** (win/lose states, checkpoints, objectives, gameplay rules)
> -   **Interactive World Elements** (doors, triggers, hazards, physics-based interactions)
> -   **Gameplay-Focused Code Samples** (clean, readable scripts with comments and structure)
> -   **Gameplay Videos Showing Your Systems in Action** (proof it works in a real build)
> -   **Clean, SOLID, Documented Code** (production-ready, properly commented, readable, and maintainable)
>

# Portfolio Deliverables Checklist
Each portfolio piece should show your ability to implement **gameplay features that are playable, responsive, and reliable**.
-   **Required Deliverables:** Must be included for every gameplay programming piece.    
-   **Add-On Deliverables:** Include only if you personally created them (AI logic, animation graphs, UI systems, etc.).
-   If you collaborated, clearly indicate which parts were your responsibility.

# 

## Required Deliverables 

### A) Presentation
- [ ]  🌟 **Real-Time Gameplay Footage:** A short clip showing the mechanic working in-game context.
- [ ]  🌟 **Feature Preview:** Short looping video or GIF showing the feature in isolation (i.e., a small sandbox (test) scene used to validate the mechanic).
- [ ]  🌟 **In-Engine Screenshot:** Show the component in the Inspector (sliders, tooltips, headers, clean variable names).
- [ ]  **Feature Breakdown with Commentary:** Narrated video demonstrating the mechanic in-game while highlighting the key code sections that power it (core logic, states, checks, and variables).
    

### B) Required Written Info
- [ ] **Feature Name + 1–2 Sentence Summary:** What it is and why it exists.
- [ ] **Player Experience Goal:** What the mechanic should feel like (snappy, heavy, tactical, etc.).
- [ ] **Controls / Inputs:** Keyboard + controller mapping (or clearly state what is supported).
- [ ] **Game / Scene Context:** Where the mechanic is used and what gameplay loop it supports.
- [ ] **Software & Language:** Unity/C#, Unreal/C++, Godot/GDScript, etc.
- [ ] **Your Contribution (Collaboration Note):** What you built vs. what was provided.
- [ ] **Cite External Assets & Libraries:** List any external code, plugins, assets, tutorials, or samples used and note the license/source for each.
- [ ] **Case Study / Breakdown:** Step-by-step explanation of problem-solving, iteration, and refinement processes. Highlight challenges and solutions. (Minimum - one portfolio piece)
    

### C) Code & Implementation
- [ ] 🌟 **GitHub Repository Link:** Link to the project repo (or the specific folder containing the feature).
- [ ] **Core Script(s) Included:** The key scripts that implement the mechanic (cleaned and readable).
- [ ] **Code Snippet Gallery:** 2–5 screenshots showing the “meat” of the logic (state transitions, math, detection logic, etc.).
- [ ] **State Logic Proof:** Evidence of gameplay states (Idle → Jump → Falling, Attack → Recovery, etc.).
- [ ] **Tuning Variables Exposed:** Show adjustable values (speed, damage, cooldown, range, gravity, etc.).
- [ ] **Feedback Hooks:** short clip demonstrating triggered feedback in action (animation, VFX, SFX, UI, camera behavior, hit pause, etc.).
- [ ] **Optimization Note (1–2 Sentences):** How you kept it efficient (pooling, reduced allocations, cached lookups, fewer Update calls, etc.).
- [ ] **README File:** Clear setup instructions for running the demo (controls, how to play, how to test the mechanic).

> \[!NOTE\]  
> All code should follow **professional coding standards**: clear naming conventions, DRY, consistent formatting/style rules, clean organization, robust error handling (null checks, try/catch), and documentation comments (XML or inline where applicable).
>

---

## Add-On Deliverables

### D) Technical Specifics, Testing, & Debugging
- [ ] **Problem → Solution Write-Up:** One bug you encountered and the technical steps you used to fix it.
- [ ] **Modern Input Handling Proof:** Evidence of a proper input system setup (Unity New Input System, Enhanced Input, etc.).
- [ ] **Edge Case Handling Proof:** Demonstrate at least 2 handled edge cases (spam input, interrupted actions, slopes, curved surfaces, overlapping triggers, etc.).

### E) Tools & Extensions
- [ ] **In-Engine Debugging:** screenshot of gizmos and debugging visuals (e.g., hitboxes, rays, detection volumes, state display, etc.)
- [ ] **Custom Editor Tools:** screenshots and code snippets of in-editor tools for designers (randomizers, dialogue graphs, tuning tools).

### F) Collaboration & Integration
- [ ] **Git History Proof:** Evidence of frequent, meaningful commits with clear messages.
- [ ] **Team Role Description:** Documentation of your responsibilities vs. teammates’.
- [ ] **Integration Proof:** Example of system working with another team’s work (UI, audio, gameplay, level scripting, etc.), including a short clip/screenshot + 1–2 sentences explaining the integration.
