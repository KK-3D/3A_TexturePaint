
# 3A_Texture Paint v1.0 — User Manual

<img width="615" height="623" alt="Captura de ecrã 2026-11-03 205824" src="https://github.com/user-attachments/assets/19c7bb05-0e56-4c62-8622-32272c8d9404" />

Welcome to the official user manual for **3A_Texture Paint v1.0**, a native viewport texture painting plugin designed for LightWave 3D. This guide covers all functionalities, tabs, and settings available in the Numeric interface panel.

<img width="512" height="342" alt="Captura de ecrã 2026-11-03 205153" src="https://github.com/user-attachments/assets/60a4312f-c3fb-4760-b4ad-e61649f9ab03" />

## 1. Brush Tab Overview

The **Brush** tab contains all settings related to painting tools, color selection, symmetry, alpha presets, stamp projections, and viewport display options.

| Feature Thumbnail | Feature Name & Description |
| --- | --- |
|  | **Prepare / Update UV Mesh & Color/Mode Controls**<br>

<br>• **Prepare / Update UV Mesh:** Initializes or updates the UV environment and mesh topology for painting.<br>

<br>• **Colour & Swatch:** Sets the active painting color using RGB values or color picker.<br>

<br>• **Mode:** Switches between painting modes (e.g., Paint, Erase).<br>

<br>• **Radius & Strength:** Controls brush size in pixels and stroke opacity/intensity. |
|  | **Symmetry & Mirror Options**<br>

<br>• **Symmetry X/Y/Z:** Enables mirror painting across selected axes.<br>

<br>• **Mirror X- / X+:** Defines the directional offset or polarity for symmetrical strokes. |
|  | **Brush Alphas & Presets**<br>

<br>• **Preset Thumbnail Grid:** Visual selector for alpha brush shapes and textures.<br>

<br>• **Alpha Content Dir:** Directory path pointing to custom alpha files.<br>

<br>• **Import / Remove / Invert Alpha:** Manage custom alpha maps to texture brush strokes dynamically. |
|  | **Stamp Image Settings**<br>

<br>• **Image Editor Images:** Selects loaded images from LightWave’s Image Editor as stamps.<br>

<br>• **Stamp Controls:** Adjust Display Opacity, Center X/Y coordinates, Scale, and Rotation degrees for image stamping. |
|  | **Undo, Wireframe & Preview Options**<br>

<br>• **Undo Levels:** Configures the number of undo steps matching Modeler.<br>

<br>• **Viewport Texture Preview / Show Wireframe:** Toggles real-time texture and wireframe overlays.<br>

<br>• **Fast Preview:** Optimizes viewport performance for high-resolution maps. |

---

## 2. Texture Tab Overview

The **Texture** tab handles image creation, resolution settings, destination directories, file saving, and project management.

| Feature Thumbnail | Feature Name & Description |
| --- | --- |
|  | **Image Setup & Resolution**<br>

<br>• **Destination PNG:** Defines the output file path for exported textures.<br>

<br>• **New Image with Alpha:** Creates texture maps with transparency support.<br>

<br>• **New Image Resolution:** Dropdown to select resolutions (1024x1024, 2048x2048, 4096x4096, 8292x8292).<br>

<br>• **Create Texture Image / Current Texture:** Initializes the working canvas. |
|  | **Saving & Project Management**<br>

<br>• **Auto-save Texture Image & Save Timing:** Automatically saves progress (e.g., Every stroke).<br>

<br>• **Save Texture Now / Export PNG:** Manual triggers to save or export texture files.<br>

<br>• **Project / Autosave & Open Selected Project:** Saves and reloads entire painting sessions. |

---

## 3. Layers Tab Overview

The **Layers** tab provides multi-layer painting capabilities, allowing non-destructive workflows with blend modes, opacity control, and layer organization.

| Feature Thumbnail | Feature Name & Description |
| --- | --- |
|  | **Layer Controls & Importing**<br>

<br>• **Active Layer & Layer Name:** Selects and renames working layers (e.g., 01 - Base).<br>

<br>• **Visible & Opacity:** Toggles layer visibility and adjusts transparency percentage.<br>

<br>• **Move Layer Up / Down / Clear Layer:** Reorders layer stack or clears layer contents.<br>

<br>• **Import into Active Layer:** Loads external images directly into the selected layer slot. |

---
