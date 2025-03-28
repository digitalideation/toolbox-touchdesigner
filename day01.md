## Day 1: Introduction & Core Concepts

### 🕘 Morning Session (3 hours) – Understanding the Interface & Navigation

**Objective:** Get familiar with the **TouchDesigner interface, node-based workflow, and operator families**.

#### 1️⃣ Introduction to the TouchDesigner Interface (30 min)

🔹 What is TouchDesigner? Overview of real-time visual programming.  
🔹 Exploring the **Network Editor, Parameters, and Timeline**.  
🔹 **Navigating** the interface (zooming, panning, and selecting).

📌 **Exercise:** Open TouchDesigner and explore the **default project**. Modify an existing node, tweak parameters, and preview changes.

#### 2️⃣ Understanding Operators & Network Anatomy (30 min)

🔹 The **5 Operator Families**:

- **TOPs (Texture Operators)** – image/video processing
- **CHOPs (Channel Operators)** – signal processing & animation
- **SOPs (Surface Operators)** – 3D modeling & geometry
- **DATs (Data Operators)** – working with text & tables
- **COMPs (Component Operators)** – UI elements & containers

🔹 **Reading Networks**: Understanding node connections, flow, and dependencies.  
🔹 How to **connect, rearrange, and rewire operators** effectively.

📌 **Exercise:**

- Create a **simple network** with different operator families.
- Observe how data flows from one node to another.

#### 3️⃣ Creating & Connecting Operators (45 min)

🔹 Adding **new operators** to the network.  
🔹 **Cooking process**: How TouchDesigner updates nodes dynamically.  
🔹 Bypass, Delete, and Replacing Operators efficiently.  
🔹 Using the **Viewer Active Mode** to preview results.

📌 **Exercise:**

- Create a **TOP network** that loads an image and applies a basic effect.
- Experiment with **connections** and **node order**.

#### 4️⃣ Operator Families Deep Dive (45 min)

Each group will create **mini-projects** using different operator families:  
  
☞ **TOPs:** Load an image, apply color adjustments, and transform it.  
☞ **CHOPs:** Generate a sine wave and manipulate it in real-time.  
☞ **SOPs:** Create basic 3D shapes and modify them.  
☞ **DATs:** Display text dynamically.  
☞ **COMPs:** Build a simple UI with a button and slider.

📌 **Challenge:** Combine multiple operators and **animate** a simple effect.

---

### 🕒 Afternoon Session (3 hours) – Working with Images (TOPs)

**Objective:** Learn how to import, manipulate, and process images/videos.

#### 1️⃣ Importing & Manipulating Images (45 min)

🔹 **Loading images** into TouchDesigner (Movie File In, Webcam Feed, etc.).  
🔹 Adjusting **Resolution, Format, and Color Space**.  
🔹 Using **Transform TOP** for scaling, rotation, and positioning.

📌 **Exercise:** Import an image and modify it using **Transform & Level TOPs**.

#### 2️⃣ Basic Compositing, Mattes & Masks (1 hour)

🔹 **Compositing techniques**: Overlays, blending modes, transparency.  
🔹 Creating **masks** for selective image effects.  
🔹 Using **Ramp TOP, Noise TOP, and Threshold** to define masks.

📌 **Exercise:**

- Blend two images together with **different blend modes**.
- Create a **mask** using a custom shape.

#### 3️⃣ Building Patterns & Applying Effects (45 min)

🔹 Using procedural **Noise & Ramp** textures.  
🔹 Creating **animated visuals** with feedback loops.  
🔹 Applying effects like **Blur, Edge Detect, and Glow**.

📌 **Exercise:**

- Build a **dynamic background pattern** using Noise TOP.
- Add **feedback effects** for motion trails.

#### 4️⃣ Saving & Exporting (30 min)

🔹 Capturing visuals as **images or videos**.  
🔹 Adjusting settings for performance optimization.  
🔹 Best practices for **real-time rendering**.

📌 **Final Challenge:**

- Apply everything learned today in a **mini-project**:  
   🔹 Load an image, add effects, and export the result.  
   🔹 Present the **before & after** versions.

---

#### 📌 Summary of Day 1

✅ Navigating TouchDesigner & understanding the interface.  
✅ Learning the **5 operator families**.  
✅ Working with **images, masks, and effects**.  
✅ **mini-projects** for real-time visuals.

### Ideas / References

- [Day01 challenges ideas](./parkplatz/day01-challenges-ideas.md)
- [Day01 exercise ideas](./parkplatz/day01-exercises-ideas.md)
- [Filters idea](https://www.moshpro.app/#top)
- [Keyboard Shortcuts cheat-sheet](https://matthewragan.com/teaching-resources/touchdesigner/touchdesigner-keyboard-shortcuts/)
