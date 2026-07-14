# 🎮 C# Mini-Game Challenge — Microsoft & freeCodeCamp C# Certification
> **Challenge Project** · Microsoft Learn × freeCodeCamp · C# Certification Path

This project is part of a **challenge module** in the Foundational C# certification offered by Microsoft in partnership with freeCodeCamp. The course provides a starter file with a working game skeleton, along with a specification for each challenge — no step-by-step walkthrough. The task is to independently design and implement the missing functionality to meet each spec.

All gameplay logic described below — termination handling, food consumption detection, player state changes, and movement speed modification — was implemented by me as part of these challenges, building on top of the provided starter code.

---

## 🕹️ About the Game

A small but complete mini-game where a player character moves across the console screen, consumes food objects, and reacts to what they eat. The game runs in a loop, tracks player state, and responds to keyboard input in real time.

---

## ⚙️ Features

- Player movement controlled by keyboard input
- Food consumption detection and player state updates
- Movement speed modification based on food consumed
- Food regeneration in a new random position after consumption
- Game termination on unsupported key press
- Game termination if the terminal window is resized

---

## 🧠 Concepts Applied

- C# methods with return values, required and optional parameters
- `switch` statements and `if-else` logic
- `for` loops and array manipulation
- `Random` class for dynamic food placement
- Console I/O for real-time interaction
- Code organization through method decomposition

---

## 🚀 How to Run

Make sure you have the [.NET SDK](https://dotnet.microsoft.com/download) installed.

```bash
git clone https://github.com/hi-myn/csharp-minigame-challenge.git
cd csharp-minigame-challenge
dotnet run
```

---

## 📋 Prerequisites

- .NET 10+ SDK
- Visual Studio Code (with C# extension) or Visual Studio
- Basic familiarity with C# console applications

---

## 🏅 Course Context

This project is part of the **Foundational C# with Microsoft** certification, offered on Microsoft Learn in partnership with freeCodeCamp. The challenge modules test the ability to independently design and implement features from a functional specification, starting from a provided base project — no walkthroughs included.

🔗 [Microsoft Learn — Foundational C# Certification](https://learn.microsoft.com/en-us/collections/yz26f8y64n7k07)

---

## 📄 License

This project is for educational purposes as part of a Microsoft Learn & freeCodeCamp challenge.
