# Reinforcement Learning - Q-Learning 

## Outline
1. Introduction
2. Terminology
3. Implementation - Tic-Tac-Toe


## Tic Tac Toe - Q-Learning Agent

This repository contains a simple Python implementation of a Q-Learning agent for playing the game of tic-tac-toe. The agent learns a policy for playing the game by interacting with the environment and updating its Q-table.

## Overview

The code is divided into three main components:

1. `TicTacToe` class: Represents the game environment, including the game state, available actions, state updates, and rewards.

2. `QLearningAgent` class: Represents the reinforcement learning agent that uses the Q-Learning algorithm to learn a policy for playing tic-tac-toe. The agent balances exploration and exploitation using an epsilon-greedy strategy.

3. Training loop: A loop that iterates through a specified number of episodes, playing tic-tac-toe games and allowing the agent to learn from the game outcomes.

Once the agent has been trained, it can play games of tic-tac-toe using the learned policy. A simple text-based interface is provided for playing against the agent.

