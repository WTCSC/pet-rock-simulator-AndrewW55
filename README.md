[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/3zOHVIfr)
# Pet "The Rock" Simulator #
## Requirements ##
- python 3.x

## How to use ##
1. Clone/Download
2. Run in Python

## Features: ##
- **Stats:**  
  - `hunger`: Starts at 100  
  - `health`: Starts at 100  
  - `age`: Starts at 0  

- **Loop Behavior:**  
  - The program keeps running in a `while True` loop.  
  - You will repeatedly be prompted to enter an action.  
  - The stats will update based on your choices.

## Decision Tree ##
Start
 └─ main()
      ├─ Check age >= 100
      │     └─ If True: End ("bruh died" / "RIP fr")
      ├─ Else check health <= 50
      │     ├─ If True:
      │     │     ├─ Print status
      │     │     ├─ Print "Cuh is NOT aight"
      │     │     └─ Call Action(input)
      ├─ Else check hunger <= 50
      │     ├─ If True:
      │     │     ├─ Print status
      │     │     ├─ Print "Luh jit kina hungry?"
      │     │     ├─ health = health - 10
      │     │     └─ Call Action(input)
      ├─ Else (normal case)
      │     ├─ Print status
      │     ├─ Print "bruh luh key chillin"
      │     └─ Call Action(input)
 └─ Action(act)
      ├─ If act == "FEED"
      ├─ Else if act == "REELS"
      ├─ Else if act == "CLASH"
      └─ Else if act == "LOOK"