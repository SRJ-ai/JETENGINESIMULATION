
# 🚀 Jet Engine Simulation with Unity and AR

## 📄 Overview

The **Jet Engine Simulation** project is a Unity-based simulation that demonstrates the working principles of a jet engine. It includes an Augmented Reality (AR) model that can be visualized using Unity's AR capabilities. The project simulates the operation of a jet engine, allowing users to interact with the engine and learn about its components.

## 📁 Project Structure

```
JetEngineSimulation/
├── Assets/                      # Unity assets including models, textures, and materials
├── Scenes/                      # Unity scenes
│   └── MainScene.unity          # Main simulation scene
├── Scripts/                     # C# scripts for Unity logic
│   ├── EngineController.cs      # Controls engine behavior
│   └── ARController.cs          # Manages AR interactions
├── ARModels/                    # AR models for Jet Engine visualization
│   ├── Engine3DModel.obj        # 3D model of the jet engine
│   └── EngineTextures/          # Textures for the 3D model
├── Readme.md                    # This file
└── requirements.txt             # Dependencies for the Unity project
```

## 💻 Setup Instructions

### Prerequisites

1. **Unity**: Ensure that you have Unity installed. You can download it from the [official website](https://unity.com/).
2. **AR Foundation**: This project utilizes Unity's AR Foundation, so make sure to install the necessary AR packages in Unity.

### Steps to Run the Simulation

1. Clone the repository:
   ```bash
   git clone https://github.com/SRJ-ai/JetEngineSimulation.git
   ```

2. Open the project in Unity.

3. Ensure that you have the AR Foundation package installed:
   - Open **Window > Package Manager**.
   - Install **AR Foundation** and any related dependencies like **ARKit** or **ARCore**, depending on your platform.

4. Open the **MainScene.unity** file located in the **Scenes/** folder.

5. Build and run the scene using Unity's build settings for your target platform (e.g., Android, iOS).

6. If you want to view the simulation in AR, you'll need to test it on a device that supports AR features.
