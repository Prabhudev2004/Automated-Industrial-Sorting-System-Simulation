#  Automated Industrial Sorting System Simulation (Pygame)

This project is a **Pygame-based simulation** of an **industrial conveyor sorting system**, developed at **Acubiq Pvt Ltd**.    
It demonstrates how packages can be **detected, classified, and sorted** automatically using simulated **weight, color, and size sensors**, along with an actuator arm mechanism.

---

##  Features
- **Conveyor Belt Simulation** with animated stripes for realism.  
- **Three Sensor Modes**:  
  - ⚖ **Weight Sensor** → Sorts based on weight ranges.  
  - 🎨 **Color Sensor** → Sorts by package color.  
  - 📏 **Size Sensor** → Sorts by package size.  
- **Interactive Mode Switching** via button panel (clickable in the GUI).  
- **Actuator Arm Animation** to move packages onto the correct output belt.  
- **Multiple Output Belts (4)** with live counters:
  - Current packages
  - Assigned count
  - Processed count
- **Real-time HUD** showing:
  - Mode in use  
  - Total spawned, assigned, processed, and unsorted packages  
- **Logging** (`system.log`) for sensor readings, actuator actions, and mode changes.

---

## Demo Video
    
![Demo ](https://github.com/ACUBIQ/Pygame/blob/74533cd86d054685d0b3e4a285902a2ea5580dd3/Conveyor%20Sorting%20Simulation.gif)

---

## Installation, Usage & Documentation 

```bash
# 1️⃣ Clone the Repository
git clone https://github.com/Prabhudev2004/Pygame.git
cd Pygame

# 2️⃣ Install Dependencies
pip install pygame

# 3️⃣ Run the Simulation
python sensor_module.py
```
---

##  Controls  
🖱️ **User Interactions**  
- Click top-panel buttons → **⚖ Weight**, **🎨 Color**, **📏 Size** to switch active sensor mode  
- Active sensor **glows** when selected  
- ❌ Close window → Exit the simulation  

This ensures a **hands-on experience**, where the user can dynamically change the sorting mechanism in real-time. 

---

## 🛠️ Tech Stack  
🔧 Our simulation was powered by:  
- **Language:** Python 🐍  
- **Library:** Pygame 🎮 for graphics, animation & interactivity  
- **Logging:** Python logging module 📝 for event tracking  

Together, these tools allowed us to **blend logic, visualization, and data monitoring** seamlessly.  

---

## 🧠 Flow Diagram

The working of the simulation follows a **clear pipeline**:
![FLOW](https://github.com/ACUBIQ/Pygame/blob/b32de88fca7a4e48a59d9b8305bf84e488ab93a9/Flow%20Diagram.png)

---

## 👥 Team & Roles  
This project was a **collaborative success**, with each member contributing their expertise:  

👨‍💻 **Main Control Logic Lead – Prabhudev**  
- Designed **decision logic** for Weight/Color/Size sensors  
- Built **state machine control** for actuator arm  
- Integrated **HUD counters** & interactive mode switching  

🎨 **GUI Developer – Veda**  
- Crafted the **conveyor visuals, gradients, and buttons**  
- Designed package rendering: outer color, inner box, shadows  
- Added **sensor glow effects** for active highlighting  

🧪 **Sensor Module Developer – Vittal**  
- Developed **functions for weight, color, size sensors**  
- Ensured accurate **attribute-to-belt mapping**  
- Logged sensor readings for debugging & validation  

🤖 **Actuator & Animation Developer – Amogh**  
- Programmed **arm extension/retraction logic**  
- Created **smooth package dropping animations**  
- Synchronized actuator timing with conveyor speed  

⚙️ **Configuration & Logging Engineer – Soujanya**  
- Set up **logging system** for all events (`system.log`)  
- Designed **spawn settings & attribute distributions**  
- Verified counters: spawned, assigned, processed, unsorted 

---

## 📸 Output  

The simulation produced **realistic and interactive results**:  

1️⃣ **Conveyor Belt Visualization**  
- Continuously moving belt with packages of random attributes.  

2️⃣ **Sensor Detection & Mode Switching**  
- Active sensor line glows ✨  
- User can switch between Weight / Color / Size instantly.  

3️⃣ **Package Classification & Sorting**  
- Packages automatically sorted into correct output belts.  
- Actuator arm animation ensures **smooth & realistic motion**.  

4️⃣ **Output Belts with Live Counters**  
- Each belt displays **current, assigned, processed** package counts.  

5️⃣ **Statistics & Logging**  
- On-screen HUD shows total **spawned, assigned, processed, unsorted**.  
- Every event stored in `system.log` 📑 for debugging & traceability. 


📷 **Screenshots:** 

Based on WEIGHT:

![Base on Weight](https://github.com/ACUBIQ/Pygame/blob/3dd30fed8b7cce92fc5b77755e6043a5f879542a/output%20based%20on%20weight.png)

Based on COLOR:

![Base on Color](https://github.com/ACUBIQ/Pygame/blob/3dd30fed8b7cce92fc5b77755e6043a5f879542a/output%20based%20on%20color.png)

Based on SIZE:

![Base on Size](https://github.com/ACUBIQ/Pygame/blob/3dd30fed8b7cce92fc5b77755e6043a5f879542a/output%20based%20on%20size.png)

---

## 📊 Results  

Our simulation achieved **100% accuracy** in sorting packages within the virtual environment.  

✔ **Conveyor Belt** → Smooth & continuous flow  
✔ **Sensors** → Correctly detected Weight / Color / Size attributes  
✔ **Interactive Switching** → Real-time mode change without interruption  
✔ **Sorting Mechanism** → Packages dropped accurately into 4 output belts  
✔ **HUD** → Updated live with accurate statistics  
✔ **Logging** → Captured all major events for debugging  
✔ **Overall Performance** → Robust, interactive, visually appealing  

**Simulation video output:![simulation](https://github.com/ACUBIQ/Pygame/blob/bf4b5242372a150ea0e5a717871c878964e47d97/Conveyor%20Sorting%20Simulation.mp4)
*

---

## 🎯 Conclusion  

This project successfully **simulated an Automated Industrial Sorting System** entirely in software using **Python & Pygame**.  

Through this, we:  
- Applied **modular programming** & **state machine logic**  
- Built a **user-friendly GUI** with animations & interactivity  
- Implemented **logging & debugging practices** for reliability  
- Strengthened **team collaboration** by dividing into functional modules  

👉 This project not only deepened our knowledge of **industrial automation software design**, but also laid the foundation for future integration with **real hardware, IoT devices, and AI-driven vision systems**.

---

## **🙌 Acknowledgements**

We extend our gratitude to **Acubiq Pvt Ltd** for:  
- Continuous mentorship 👨‍🏫  
- Technical guidance 💡  
- Providing us an opportunity to **apply theory into practice**  

This experience gave us a **professional insight into industrial automation systems** and enhanced both our **technical & collaborative skills**.
---
