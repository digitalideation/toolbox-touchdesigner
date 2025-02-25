
## Morning

### **🟢 Part 1: Introduction to the TouchDesigner Interface (30 min)**

- **101 – Navigating the Environment**
- The User Interface
- Using the OP Create Dialog
- Reading Network Anatomy
- Reading Operator Anatomy
- Operator Wires, References & Links
- ...

---

### **🟡 Part 2: Understanding Operators & Network Anatomy (30 min)**

- **101 – Navigating the Environment**
- ...
- Working with TOPs
- Working with CHOPs
- Working with DATs
- Working with SOPs
- Working with COMPs

---

### **🟠 Part 3: Creating & Connecting Operators (45 min)**

- Adding **new operators** to the network. (101)
- [**Cooking process**: How TouchDesigner updates nodes dynamically. ](https://docs.derivative.ca/Cook)

  1.  **Introduction to Cooking in TouchDesigner**

      - Definition: Cooking as the computation of operators.
      - Importance: Essential for generating outputs efficiently.

  2.  **Conditions for Cooking**

      - Nodes cook when viewers are visible.
      - Nodes contributing to displayed panels or data output.
      - Nodes sending video/audio out via specific operators.

  3.  **Cooking Mechanism**

      - **What Causes Cooking**:
        - Cook requests from downstream nodes or viewers.
        - Changes in inputs, parameters, or expressions.
      - **Order of Cooking**:
        - TouchDesigner uses a "pull system" where nodes cook when data is requested.
        - Cooking starts from the output and moves upstream.

  4.  **Event-Driven Cooking**

      - Execute DATs and other operators respond to events.
      - Events can trigger parameter changes and node cooking.

  5.  **Forced Cooking**

      - Certain nodes cook every frame regardless of changes.
      - Examples: Movie File Out TOP, Touch Out OPs.

  6.  **Optimizing Performance**

      - Minimize the number of nodes that cook.
      - Use the Performance Monitor to track cooking.
      - Utilize the Probe component to watch live cooking.

  7.  **Practical Applications**

      - Understanding cooking helps in optimizing complex networks.
      - Essential for real-time applications like live performances or installations.

  8.  **Conclusion**
      - Recap the importance of cooking in TouchDesigner.
      - Encourage further exploration of optimization techniques.

---
## Afternoon

### **🟢 Part 1: Importing & Manipulating Images (45 min)**

- **102 – TOPs: Working with Images**
- Working with Image Files
- Working with Video Files
- Adjusting Images
- Shapes & Colors
- ...

---

### **🟡 Part 2: Basic Compositing, Mattes & Masks (1 hour)**

- **102 – TOPs: Working with Images**
- Basic Compositing
- Mattes & Masks
- ...
- 🔹 Using **Ramp TOP, Noise TOP, and Threshold** to define masks. (Not in curriculum)

  - **Ramp TOP**: Generates gradient textures that can serve as masks
    - _Explanation_: The Ramp TOP creates gradients (linear, circular, etc.) which can be used to mask or blend image
    - _Reference_: [Ramp TOP Documentation](https://docs.derivative.ca/Ramp_TOP)
  - **Noise TOP**: Produces various noise patterns useful for creating organic mask
    - _Explanation_: The Noise TOP generates patterns like Perlin or Simplex noise, which can add randomness to mask
    - _Reference_: [Noise TOP Documentation](https://docs.derivative.ca/Noise_TOP)
  - **Threshold TOP**: Converts images to high-contrast black and white, effectively creating matte

    - _Explanation_: The Threshold TOP sets pixel values below a certain threshold to 0 and above it to 1, creating a binary mas
    - _Reference_: [Threshold TOP Documentation](https://docs.derivative.ca/Threshold_TOP)

    **Practical Application** Combine these TOPs to create dynamic masks For instance, apply a Threshold TOP to a Noise TOP to produce a high-contrast, random pattern mask This mask can then be used in a Composite TOP to blend two images based on the mask's luminance values

---

### **🟠 Part 3: Building Patterns & Applying Effects (45 min)**

🔹 Using procedural **Noise & Ramp** textures. 

- **Procedural Textures** Utilize Noise and Ramp TOPs to create dynamic backgrounds or overlay
	- _Explanation_ Procedural textures are generated algorithmically, allowing for infinite variations without external image
	- _Reference_: [Working with the Noise TOP](https://learn.derivative.ca/courses/200-intermediate/lessons/202-tops-intermediate/topic/working-with-the-noise-top/)

🔹 Creating **animated visuals** with feedback loops.

- **Feedback TOP** Enables the creation of recursive visual effects by feeding the output of a network back into itsel - _Explanation_ The Feedback TOP stores the previous frame's image, allowing for effects like motion trails or iterative transformation - _Reference_: [The Secret of Feedback Loops in TouchDesigner](https://derivative.ca/community-post/tutorial/secret-feedback-loops-touchdesigner-tutorial/66168)

🔹 Applying effects like **Blur, Edge Detect, and Glow**.

- **Blur TOP** Softens images by averaging pixel values with their neighbor
  - _Explanation_ The Blur TOP reduces image sharpness, useful for creating depth or focus effect
  - _Reference_: [Blur TOP Documentation](https://docs.derivative.ca/Blur_TOP)
- **Edge TOP** Detects edges within an image, highlighting areas of significant contras
  - _Explanation_ The Edge TOP outputs lines where there are sharp color changes, useful for stylized visuals or outline
  - _Reference_: [Edge TOP Documentation](https://docs.derivative.ca/Edge_TOP)
- **Glow Effect** Achieved by combining Blur and Add TOPs to create a blooming effect around bright area
  - _Explanation_ By blurring bright parts of an image and adding them back onto the original, a glow effect is produce
  - _Reference_: [Blur Glow Effect in TouchDesigner](https://derivative.ca/community-post/blur-glow-effect-touchdesigner/66473) \_ \*\*Practical Application Create an animated background using a Noise TOP, apply a Feedback TOP to introduce motion trails, and enhance the visual with a Glow effect by combining Blur and Add TOP.

---

### **🔵 Part 4: Saving & Exporting (30 min)**

🔹 Capturing visuals as **images or videos**.  
🔹 Adjusting settings for performance optimization.  
🔹 Best practices for **real-time rendering**.

---

### **📌 Summary of Day 1**

✅ Navigating TouchDesigner & understanding the interface.  
✅ Learning the **5 operator families**.  
✅ Working with **images, masks, and effects**.  
✅ Hands-on **mini-projects** for real-time visuals.
