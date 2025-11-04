🧠 Simple Reflex Agent — Vacuum Cleaner Simulation

This project demonstrates a Simple Reflex Agent in Artificial Intelligence using Python & Matplotlib.
The agent operates in a 2x2 grid environment (4 rooms) and follows basic reflex-based logic to clean dirty rooms.

✅ Project Overview

A Simple Reflex Agent acts purely based on the current percept (current state) without memory or learning.
It checks whether the room it's currently in is dirty:

If Dirty → Clean

If Clean → Move to next room

This simulation visualizes the cleaning process in real-time using plots.

🎯 Objectives

Understand how reflex agents work in AI

Implement perception–action logic

Simulate agent movement and decision-making

Visualize environment updates using Matplotlib

🏗️ How the Agent Works
Step	Action
1️⃣ Observe current room state	Clean/Dirty
2️⃣ Apply rule	If Dirty → Clean else Move
3️⃣ Update environment	Change room status
4️⃣ Render grid	Color rooms & show agent
5️⃣ Repeat	Move to next room cyclically
📌 Features

2×2 grid environment (Room1–Room4)

Real-time animation with Matplotlib

Reflex decision making (no memory)

Dynamic room color updates

🟥 Red = Dirty

🟩 Green = Clean

Agent shown as 🔵 blue circle

🧠 Concepts Used

Artificial Intelligence basics

Reflex agents

Rule-based action selection

Python functional and procedural logic

Data visualization with Matplotlib

💻 Technologies
Component	Tool
Language	Python
Visualization	Matplotlib
Shapes	patches.Rectangle, patches.Circle
▶️ How to Run
pip install matplotlib
python main.py


Make sure Matplotlib is installed before running the program.

📸 Output Preview

Rooms animate as the agent moves

Red rooms turn green after cleaning

Agent moves room-by-room in sequence

🌟 Future Enhancements

Model-based agent with memory

Learning-based vacuum agent

User-interactive grid size

Random dirt generation

🙌 Acknowledgment

This project is a hands-on demonstration of reflex agents — a fundamental concept in AI — before moving into advanced learning systems.
