

# 🤖✨ **Project Journal Entry — CHECK POINT 1**

---

##  **Current Progress — Mechanical + Structural**
I now have the **full internal backbone structure assembled**, with all motors mounted and aligned. This is a major milestone because it means the robot’s mechanical foundation is stable enough for motion testing and code integration.

### **Completed Mechanical Work**
- Backbone/frame printed and assembled  
- Motors mounted at correct pivot points  
- Linkages tested for range of motion  
- Initial movement tests (rough but functional)  
- Wiring routed through the internal structure  

### **Mechanical Notes for Future Reference**
- Motor torque is sufficient, but slow movements require smoothing  
- Linkage tolerances are tight — may need lubrication or slight redesign  
- Frame rigidity is good; minimal flex under load  
- Need to document print settings (layer height, infill, supports)  
- Finish building structure (ears)

---

## 🧶 **Soft Robotics Component — Crochet/Plush Body**
The next major step is creating the robot’s **crochet/plush outer shell**. This isn’t just decoration — it’s part of the sensory design. For students with ADHD, tactile comfort can be grounding and emotionally regulating.

### **Design Considerations**
- **Texture:** soft, low-friction yarn that feels calming  
- **Stretch:** enough elasticity to allow movement without restricting motors  
- **Padding:** polyfill placement that preserves motion while adding softness  
- **Openings:** access points for charging, wiring, and maintenance  
- **Sound transparency:** a mesh or thinner area where audio can pass through  

### **Technical Notes to Document**
- Yarn type + hook size  
- Stitch pattern (tight vs. loose)  
- How the shell attaches to the frame (Velcro, snaps, sewn anchors)  
- How fabric thickness affects motor torque  

---

## 🧠💻 **Software Progress — Adapting USC Blossom Code**
I’ve begun exploring and adapting movement code from the USC Blossom database. Their motion library is extremely helpful, but my robot’s geometry and motor layout are different, so I need to remap everything.

### **Software Tasks Completed**
- Identified relevant Blossom movement functions  
- Began mapping motor IDs to my hardware  
- Tested basic PWM control  
- Started experimenting with timing curves  

### **Next Software Tasks**
- Smooth motion using easing functions  
- Implement breathing or blooming as the first polished movement  
- Add safety limits to prevent over-rotation  
- Document calibration values for each motor  
- Integrate sound timing with motion  

---

## 🔊 **New Feature: Sound Mechanism**
I decided to add a **sound mechanism** to enhance interaction and grounding. Sound can help students with ADHD refocus, feel acknowledged, or calm down depending on tone and timing.

### **Why Sound Matters**
- Provides non-visual cues  
- Reinforces interaction loops  
- Supports emotional expression  
- Helps regulate attention  

### **Sound Hardware Options I’m Considering**
1. **DFPlayer Mini** — plays MP3 files (breathing sounds, chimes)  
2. **Piezo Buzzer** — simple tones for feedback  
3. **I2S Speaker (ESP32)** — high-quality audio for expressive sound  

### **Integration Considerations**
- Sound opening in the crochet body  
- Avoiding muffling from polyfill  
- Syncing sound with movement (e.g., breathing + soft hum)  
- Managing electrical noise from motors  

---

## 🎯 **Goals Before the USC Visit (May 13)**

### **What I will have ready to share**
- **One fully functional movement** (breathing is the priority)  
- **A partially or fully completed plush shell**  
- **A working sound demo** (even simple tones)  
- **A short video** showing the robot moving  
- **Technical documentation**, including:
  - print settings  
  - wiring diagrams  
  - code snippets  
  - crochet pattern notes  
  - motion calibration  

### **Questions I want to ask USC faculty**
- How to smooth servo jitter for slow, organic motion  
- Best linkage designs for soft robotics  
- How to design soft bodies that don’t restrict movement  
- How to integrate sound without overstimulation  
- How to document iterative prototyping for research-level work  

---

## 🔄 **Reflection**
This project is becoming more complex, but also more meaningful. The combination of movement, softness, and sound is starting to form a cohesive character — something that feels alive and supportive. I need to improve my documentation habits so future-me (and USC faculty) can clearly see my engineering decisions, failures, and iterations. The next two weeks will be focused on polishing one movement, building the plush shell, and integrating sound so I have a strong prototype to share on May 13.

<img width="5712" height="4284" alt="IMG_6047" src="https://github.com/user-attachments/assets/093a72e2-7dbf-41d0-943c-d7c24dc418b2" />
<img width="4284" height="5712" alt="IMG_6046" src="https://github.com/user-attachments/assets/53b0d288-276f-4491-b3cd-a1efb591024b" />
<img width="4284" height="5712" alt="IMG_5990" src="https://github.com/user-attachments/assets/9d50c596-f8d4-4cad-8805-5bf52a9a2f58" />
<img width="974" height="612" alt="Screenshot 2026-05-04 at 16 56 38" src="https://github.com/user-attachments/assets/74526fad-5d32-40f6-8e2f-9bf05a5f9eb0" />
