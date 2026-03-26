# ⚙️ Technical Brief 

# **1. Engine and Tools**

## **Project Specification**

-   **Game Engine:**
-   **Version:**
-   **Primary Language:**
-   **Additional Tools:**

---

## **2. Technical Setup**

> [!NOTE]
> **Course Standard (Required)**
> -   Platform must align with prototype scope
> -   Performance targets must be realistic
> -   Input must be clearly defined and testable
> -   

#

### **2.1 Platform and Performance Targets**

Define the intended deployment environment.

-   **Target Platform:** (PC, WebGL, Mobile, etc.)
-   **Target Resolution:**
-   **Target Frame Rate:**

#### **Performance Constraints**

## List any limitations or optimization goals:

#

### **2.2 Input and Interaction**

Define how the player interacts with the game.

-   **Supported Input Devices:**
    -   ☐ Keyboard & Mouse
    -   ☐ Controller
    -   ☐ Touch
-   **Control Overview:**
    -   Movement:
    -   Primary Action:
    -   Secondary Action:

#

### **2.3 Dependencies**

List required packages, SDKs, or systems.

-   **Unity Packages:**
-   **External Libraries:**
-   **Tested Platforms (OS):**#

---

# **3. Project Structure Standard (REQUIRED)**

All projects must follow a **system-based structure**, not an asset-based structure.

> [!NOTE]
> **Structure Constraints (ENFORCED)**
> -   Do NOT organize by asset type (Scripts/, Prefabs/, etc.)
> -   Do NOT mix multiple systems in one folder
> -   Do NOT place gameplay logic in `_Core`
> -   Do NOT place Editor scripts outside `Editor/`
> -   Do NOT use `UnityEditor` in Runtime code

#

## **3.1 Folder Structure**

```
Assets/  
  ├── \_Core/  
  ├── \_Shared/  
  └── Features/
```
- **_Core**: contains reusable systems and patterns.
    -   No gameplay-specific logic
    -   Used by multiple systems
    -   Stable and reusable

- **_Shared**: handles interaction between systems.
    -   No standalone gameplay features
    -   Prevents tight coupling
- **Features**: contains all game systems.
    -   Each system must be self-contained
    -   Organized by feature, not asset type
    -   Each feature must follow:

```
FeatureName/  
  ├── Runtime/  
  └── Editor/
```

     -  **Runtime**
        -   Included in final build
        -   Contains gameplay logic and UI

     -  **Editor**
        -   Development tools only
 
### Folder Naming Convention Standards
| Rule                       | Description                                                                                               | ✅ Good Examples                 | ❌ Bad Examples              |
| -------------------------- | --------------------------------------------------------------------------------------------------------- | -------------------------------- | --------------------------------------- |
| **No Spaces**              | File and folder names should never contain spaces to avoid issues with version control and build systems. | `InventorySystem`                | ❌ `my inventory system`                   |
| **PascalCase**             | Use PascalCase (UpperCamelCase) for all folders, scripts, and major assets.                               | `InventoryUI`                    | ❌ `inventory_ui`                          |
| **Descriptive Names**      | Names should clearly describe the purpose of the asset or system. Avoid vague or overly short names.      | `InventoryManager`, `PlayerData` | ❌ `Manager`, `Data`                       |
| **Consistent Terminology** | Use the same word consistently across the project for the same concept.                                   | `Item` (used everywhere)         | ❌ `Item`, `Object`, `Thing` (mixed usage) |

# 
### Special Folder Conventions
| Convention                   | Purpose                                                                                    | Example                               |                     
| ---------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------- |
| **Leading Underscore (`_`)** | Forces foundational folders to the top of the project window for visibility and priority.  | `_Core`, `_Shared`                    |
| **Feature Naming**           | Feature folders should represent complete systems, not asset types.                        | `InventorySystem`, `PlayerController` |
| **Avoid Redundancy**         | Do not repeat unnecessary words if the context is already clear from the folder structure. | `InventorySystem/InventoryScripts`    |

# 

## **4.3 Feature Structure (MANDATORY)**

   Not included in builds










