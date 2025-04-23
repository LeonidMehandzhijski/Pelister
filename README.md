# Pelister

A 2D game prototype built in Unreal Engine using both Blueprints and C++.

## Overview

Pelister is a small-scale 2D game project demonstrating core gameplay mechanics, asset setup, and basic C++ integration in Unreal Engine.

## Prerequisites

- **Unreal Engine 5.3** or later  
- **Visual Studio 2022** (Windows) with “Game Development with C++” workload, or **Xcode 14+** (macOS)  
- **Git** command-line tools

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/LeonidMehandzhijski/Pelister.git
   cd Pelister
2. **Generate project files**
   Windows: run GenerateProjectFiles.bat
   macOS: run GenerateProjectFiles.command

4. **Open in Unreal Editor**
  Double-click Game_2DPart2.uproject

## Building
- Windows (Visual Studio)
  Select Development Editor & Win64
  Build the UE5 solution
- macOS (Xcode)
  Select the UE5 scheme
  Build ShaderCompileWorker and UE5Editor

## Project Structure
  Config/           – Engine and project .ini files  
  Content/          – Blueprints, Maps, Sprites, Textures  
  Source/           – C++ source modules  
  Intermediate/     – Auto-generated build files  
  Saved/            – Logs, autosaves, backups  
  Game_2DPart2.uproject  
  .gitignore  

## Running the Game
- In Unreal Editor, press Play
- To package a standalone build: File → Package Project → [Platform]

## Contributing
- Fork the repo
- Create a branch: git checkout -b feature/my-feature
- Commit changes and open a Pull Request
