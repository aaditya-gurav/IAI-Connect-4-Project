# Connect-4-Project

This project implements the Connect 4 game in Python, featuring an AI opponent powered by the **Minimax algorithm** and a custom heuristic function. It also includes a competition framework to compare different AI agents, including a neural-network–based approach for a 5×5 board variant.

---

## Features

- Interactive Connect 4 gameplay in the terminal.  
- Minimax-based AI with an optimized heuristic evaluation.  
- Baseline AI for comparison.  
- Neural Network agent (supports only 5×5 board size).  
- Competition engine for automated AI-vs-AI matches.

---

## References

1. Heuristic design inspired by the Medium article:  
   *“Artificial Intelligence at Play: Connect Four — Minimax Algorithm Explained”*.  
2. Minimax structure influenced by standard adversarial search implementations.

---

## Installation

Install dependencies using:

```bash
pip3 install -r requirements.txt
````

---

## Run the Game

Play an interactive Connect 4 match:

```bash
python3 play.py
```

This launches a terminal-based game where you can play against the Minimax-powered AI.

---

## Run Experiments

Run AI competitions:

```bash
python3 compete.py
```

You will be prompted to choose from:

* **Tree-Based AI vs Baseline AI**
* **Neural Net vs Baseline AI**

  * Neural network works only for **5×5** board configuration.

---

## Project Structure

```
├── play.py                # Interactive gameplay
├── compete.py             # Competition and experiment runner
├── models/                # Neural network components
│   └── ...               
├── utils/                 # Helper functions and core game logic
│   └── ...
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## Future Enhancements

* Expand neural network support to larger board configurations
* More advanced heuristics for deeper Minimax search
* Add a graphical game interface
