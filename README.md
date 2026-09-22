# Adaptive Vision Controller (Assistive Technology)

## Overview
An assistive computer vision application designed for users with limited mobility or motor disabilities. It translates micro-movements of the hand into precise computer commands, enabling full desktop navigation and 3D gameplay without traditional physical input devices.

## Tech Stack
* **Language:** Python
* **Computer Vision:** OpenCV, MediaPipe (Hand Tracking)
* **System Control:** PyAutoGUI (desktop), PyDirectInput (DirectX/gaming)

## Key Features
* **Adaptive Desktop Navigation:** Translates small gestures into full cursor control, including left-click and right-click actions for standard OS interactions (opening folders, navigating UI).
* **DirectX Gaming Integration:** Features a dedicated mode for Minecraft, allowing users to control the camera, mine, and interact with the inventory/crafting system using gesture-mapped inputs.
* **Calibration & Training Module:** Includes a built-in interactive mini-game (balloon popping) to help users practice gesture control and to calibrate tracking sensitivity.
