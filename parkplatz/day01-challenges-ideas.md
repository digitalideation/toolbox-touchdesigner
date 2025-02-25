### **🎨 Basic Effects**

✅ **Blur an Image** → Find an operator that softens edges (**Blur TOP**)  
✅ **Sharpen an Image** → Enhance details (**Convolve TOP**)  
✅ **Invert Colors** → Flip brightness and colors (**Invert TOP**)  
✅ **Apply a Grayscale Filter** → Remove color (**Monochrome TOP**)  
✅ **Adjust Brightness & Contrast** → Modify intensity (**Level TOP**)

---

### **🌊 Distortion & Warping**

✅ **Pixelate an Image** → Create a low-res effect (**Resolution TOP**)  
✅ **Warp an Image** → Create a wavy distortion (**Displace TOP**)  
✅ **Glitch Effect** → Introduce artifacts (**Reorder TOP or Feedback TOP**)  
✅ **Kaleidoscope Effect** → Repeat patterns in a symmetrical way (**Kaleidoscope TOP**)  
✅ **Water Ripple Effect** → Simulate water ripples (**Displace with Noise TOP**)

---

### **💡 Lighting & Color Effects**

✅ **Create a Glow Effect** → Add a soft light effect (**Glow TOP**)  
✅ **Add a Fake 3D Lighting Effect** → Simulate depth (**Phong MAT with a SOP shape**)  
✅ **Color Cycling Animation** → Continuously shift colors (**Lookup TOP with a CHOP ramp**)  
✅ **Create a Duotone Effect** → Map an image to two colors (**Lookup TOP**)

---

### **🔄 Animation & Motion**

✅ **Animate an Image Left to Right** → Move it automatically (**Transform TOP + LFO CHOP**)  
✅ **Fade In & Out** → Animate opacity (**Math CHOP controlling a Level TOP**)  
✅ **Shake Effect** → Random jitter motion (**Noise CHOP driving Transform TOP**)  
✅ **Spin an Image in a Loop** → Rotate dynamically (**Transform TOP + Timer CHOP**)  
✅ **Zoom In and Out** → Create a pulsating effect (**Transform TOP + Sin wave CHOP**)

---

### **🔀 Composition & Layering**

✅ **Overlay Two Images** → Blend them together (**Composite TOP**)  
✅ **Create a Double Exposure Effect** → Use transparency for layering (**Composite TOP with Add mode**)  
✅ **Add a Soft Vignette** → Darken edges smoothly (**Ramp TOP + Multiply Composite**)  
✅ **Cut Out a Shape from an Image** → Use a mask (**Threshold TOP + Composite TOP**)

---

### **🔥 Advanced / Interactive**

✅ **Real-Time Webcam Distortion** → Apply effects to live camera feed (**Video Device In TOP + Displace TOP**)  
✅ **Audio-Reactive Visuals** → Use music to control effects (**Audio CHOPs + TOPs**)  
✅ **Mouse-Triggered Effects** → Use cursor movement to distort an image (**Mouse In CHOP controlling Displace TOP**)  
✅ **Text Glitch Effect** → Animate broken text visuals (**Text TOP + Noise TOP as mask**)
