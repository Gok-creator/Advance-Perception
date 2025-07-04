# 🎯 Perception Bone Target (Unreal Engine 5 C++ Component)

A lightweight Unreal Engine component that attaches a perception target directly to a skeletal bone (e.g. `"head"`), allowing AI to "see" actors from more accurate positions like the head or spine.

Perfect for stealth, sniping, or cinematic AI behavior.

---

## ✨ Features

- 🔒 Attach directly to a bone/socket (default: `"head"`)
- 🚫 No Tick required (uses `AttachToComponent`)
- ⚙️ Easily usable from both C++ and Blueprints
- 🎮 Ideal for accurate AI Sight & line-of-sight behavior

---

## 📦 Installation

1. Add the `PerceptionBoneTarget` folder to your project's `Source/YourGame/` directory.
2. Include the module in your `.uproject` or `.uplugin` file.
3. Build the project.


---

## 🛠️ Usage

1. Add `UPerceptionBoneTarget` as a component to your actor (either in C++ or Blueprint).
![Screenshot_36](https://github.com/user-attachments/assets/36b8abe5-888c-42bb-bcd3-085231f99aa4)
2. Set the `BoneName` property (e.g., `"head"`, `"spine_01"`).
 ![Screenshot_37](https://github.com/user-attachments/assets/e71edf3c-7394-4cc1-b9a7-6d101092926b)
3. It will auto-attach to the specified bone on `BeginPlay`.
