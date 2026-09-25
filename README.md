# 🎯 Bingo Pro Max Enterprise System

A modern, web-based Bingo Gaming System built with a Single Page Application (SPA) architecture, audio integration, and role-based management.

## 🚀 Features

- **Game Operator View:** 1-75 random number calling with real-time UI updates and local audio playback (`yared/` audio pack).
- **Role-Based Access:** 
  - **Admin:** User management (Create, Block, Delete).
  - **National Lottery Inspector:** Financial auditing, revenue tracking, and 15% tax calculations.
  - **Operator:** Live bingo card verification and game board controls.
- **State Persistence:** Automatically saves and restores game state from the backend.

## 📁 Repository Structure

```text
├── index.html            # Core Frontend Application (HTML/CSS/JS)
└── yared/                # Audio files for number calls (b1.m4a - o75.m4a)
