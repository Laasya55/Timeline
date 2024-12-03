# **Unity Timeline: Creating a Cemetery Cutscene with Death**  

This project demonstrates how to use Unity's **Timeline** feature to create a cinematic cutscene. In this example, we bring a cemetery to life with an eerie scene featuring "Death" walking around. This lab exercise provides a hands-on introduction to using Timeline for storytelling in Unity.  

---

## 🎯 **Project Overview**  

Unity’s **Timeline** is a powerful tool for creating cinematic sequences and cutscenes. This project walks through the process of setting up a Timeline asset to animate a "Death" character, camera movements, and environmental effects in a haunting cemetery setting.  

---

## ✨ **Features**  

1. **Timeline Asset**: Manages animations, cameras, and effects in a cutscene.  
2. **Animated Character**: Death walks around the cemetery with a chilling demeanor.  
3. **Camera Cinematics**: Smooth camera pans, transitions, and close-ups to enhance the eerie atmosphere.  
4. **Ambient Effects**: Use of lighting, fog, and sound effects to create a haunting environment.  
5. **Seamless Cutscene**: Combines animations, audio, and effects for a cinematic experience.  

---

## 🚀 **Getting Started**  

### **Prerequisites**  
- **Unity**: Version 2020.3 or higher.  
- Basic understanding of Unity’s interface and components.  
- Unity package for Timeline (included in the Unity Editor by default).  

---

## 📜 **Lab Instructions**  

### 1. **Setting Up the Scene**  
- Create a **Cemetery Environment**:  
  - Import cemetery assets or use Unity’s built-in assets.  
  - Add gravestones, trees, and fog to set the eerie tone.  

- Place the **Death Character**:  
  - Download or create a character model for Death.  
  - Place the character in the scene, positioned at the cemetery entrance.  

---

### 2. **Creating a Timeline Asset**  
1. In the **Hierarchy**, create an empty GameObject and name it `CemeteryCutsceneManager`.  
2. Add a **Playable Director** component to this GameObject.  
3. In the **Project** window, right-click and select **Create > Timeline**.  
4. Name the Timeline asset `CemeteryCutscene`.  
5. Drag the Timeline asset into the Playable Director’s **Timeline Asset** field.  

---

### 3. **Animating Death**  
1. Open the Timeline window (**Window > Sequencing > Timeline**).  
2. Add Death to the Timeline:  
   - Drag the Death GameObject into the Timeline to create an **Animation Track**.  
3. Add Walk Animation:  
   - Assign a walking animation to the track (e.g., "DeathWalk" from Mixamo or your animation library).  
4. Adjust the animation length to match the walking path in the cemetery.  

---

### 4. **Camera Cinematics**  
1. Create a **Cinemachine Virtual Camera** for dynamic shots.  
   - Install the **Cinemachine** package if needed.  
2. Add a Cinemachine Track to the Timeline.  
3. Set up multiple camera shots:  
   - **Wide Shot**: Show the entire cemetery as Death enters.  
   - **Close-Up**: Focus on Death’s face or scythe.  
   - **Tracking Shot**: Follow Death as they walk among the gravestones.  

---

### 5. **Adding Environmental Effects**  
1. **Fog and Lighting**:  
   - Use **Volumetric Fog** and low lighting to enhance the atmosphere.  
   - Add a faint blue light to suggest moonlight.  
2. **Sound Effects**:  
   - Add a **Soundtrack Track** to the Timeline.  
   - Include ambient sounds like wind, creaking trees, and footsteps.  

---

### 6. **Finalizing the Cutscene**  
- Align all tracks in the Timeline for a seamless sequence.  
- Test the cutscene by pressing **Play** and ensure the timing and transitions are smooth.  

---

## 🎮 **How to Play the Cutscene**  
1. Press **Play** in the Unity Editor.  
2. Watch as Death walks through the cemetery in a chilling cinematic sequence.  
3. Adjust and refine the cutscene using the Timeline as needed.  

---

## 🔮 **Key Learnings**  
- **Timeline Basics**: How to create and manage Timeline assets.  
- **Character Animation**: Importing and animating characters.  
- **Camera Control**: Creating cinematic camera movements using Cinemachine.  
- **Environmental Design**: Using lighting and effects to set the tone.  
- **Cutscene Creation**: Combining assets to tell a story visually.  

---

## 📜 **License**  
This project is for educational purposes and can be freely modified and shared.  

---
