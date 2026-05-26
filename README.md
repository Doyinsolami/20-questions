# 20 Questions — Country Guessing Game

A terminal-based AI guessing game that identifies countries 
by asking up to 20 yes/no questions.

## Overview
Think of a country and the game will try to guess it by asking 
smart, data-driven questions. It uses a scoring-based approach 
that handles fuzzy answers (0 to 1 scale) and learns from 
mistakes by adding new countries to its dataset.

## Features
- Asks up to 20 questions to identify any country
- Accepts fuzzy answers (e.g. 0.7 for "mostly yes")
- Selects the most informative question at each step using 
  variance and balance scoring
- Uses logical inference to eliminate impossible candidates
- Learns new countries when it guesses wrong and saves them 
  to the dataset for future games
- Supports play again without restarting

## How to Run
```bash
pip install pandas openpyxl
python 20qgame.py
```

## Tech Stack
Python, Pandas, Excel (openpyxl)

## About
Developed by Doyinsola Oduwole for COSC 581 Artificial Intelligence.
