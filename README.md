# 🐾 Zoo World – Unity MVP Test Project

### Description
This is a test task for a top-down animal simulation using MVP architecture in Unity. It features predators and prey, random spawning, simple food-chain logic, and UI counters.

---

## ✅ Features

- MVP Pattern: Clear separation between Model, View, Presenter
- Predators eat prey and show "Tasty!" effect
- Prey jumps, predators move linearly
- UI counter shows number of dead animals
- Clean, extensible code (ready to scale to 1000+ animal types)
- Dependency injection–ready

---

## 📁 Folder Structure
Assets/ZooWorld/
├── Scripts/
├── Prefabs/
├── Resources/
├── UI/
└── README.md

---

## 🧠 Architecture Highlights

- `AnimalModel`: holds data/state
- `AnimalView`: handles movement/FX
- `AnimalPresenter`: manages logic between model & view
- `AnimalManager`: updates and handles collision system
- `UICounterPresenter`: tracks deaths, updates counters

---

## 🎮 How to Use

1. Open `MainScene.unity`
2. Press Play
3. Animals spawn randomly and interact
4. UI (top-right) updates when animals die

---

## 🔧 Requirements

- Unity 2021.3+ (LTS recommended)
- TextMeshPro (enabled by default in Unity UI projects)
