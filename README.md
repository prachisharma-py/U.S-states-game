# 🗺️ U.S. States Game

A fun and educational game built with Python and Turtle Graphics to help you learn the 50 U.S. states.  
As you guess correctly, the state name appears on the map in its correct location.  
A perfect blend of learning and fun!

---

## 🎬 Demo

![U.S. States Game Demo](demo.gif)

---

## 📌 Features

- 🎨 Interactive graphical interface using the Turtle module
- 🧠 Type in state names, and they will appear on the map if correct
- 📈 Track your progress out of 50 states
- 📄 Automatically generates a `states_to_learn.csv` file listing missed states when you exit early
- 🔤 Case-insensitive input handling
- 🔁 Encourages repeated learning and memorization through self-testing

---

## 🎮 How to Play

1. Run the script.
2. A blank U.S. map appears.
3. A prompt will ask: **"What's another state's name?"**
4. Type a valid U.S. state name.
5. If correct, it appears on the map.
6. To exit the game early, type **"Exit"**.
7. Upon exiting, a CSV file called `states_to_learn.csv` is created with the states you missed.

---

## 💾 Saving Your Progress

When you exit early by typing **"Exit"**, the game will create a file named `states_to_learn.csv` in the project folder.  
This file contains the list of states you missed during your session, allowing you to review and learn them later.

---

## 🧠 Learning Mechanism

- The game reads data from a CSV file `50_states.csv` which includes:
  - State names
  - X and Y coordinates for label placement on the map
- All correct guesses are tracked in a list.
- When the user exits, a list comprehension identifies and saves unguessed states into `states_to_learn.csv`.


📓 Educational Use

This project is ideal for:

🧒 Elementary and high school students learning U.S. geography

👩‍🏫 Teachers who want an interactive classroom tool

👨‍💻 Python learners exploring basic graphics and data handling

---

## 🛠️ Requirements

- Python 3.x
- [`pandas`](https://pandas.pydata.org/)
- `turtle` (comes pre-installed with Python)
