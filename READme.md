# ai-reinforcement-learning

## Introduction

This project focuses on implementing various reinforcement learning algorithms to solve gridworld and Pacman problems. You will be working on both value-based and Q-learning approaches, experimenting with different grid layouts, and fine-tuning agents' parameters to improve their performance.

## Getting Started

To get started with the project, follow the instructions below:

1. Clone this project repository to your local machine.

```bash
git clone https://github.com/your-username/reinforcement-learning-project.git
```

2. Navigate to the project directory.

```bash
cd reinforcement-learning-project
```

3. Ensure you have Python 3 installed on your machine.

4. Install the required Python packages using pip.

```bash
pip install -r requirements.txt
```

## Running the Autograder

You can use the autograder to test your implementations and evaluate your agents' performance. Here are some sample commands to run the autograder for different questions:

### Question 1: Value Iteration

```bash
python autograder.py -q q1
```

### Question 2: Bridge Crossing Analysis

```bash
python autograder.py -q q2
```

### Question 3: Policies

```bash
python autograder.py -q q3
```

### Question 4: Asynchronous Value Iteration

```bash
python autograder.py -q q4
```

### Question 5: Prioritized Sweeping Value Iteration

```bash
python autograder.py -q q5
```

### Question 6: Q-Learning

```bash
python autograder.py -q q6
```

### Question 7: Epsilon Greedy

```bash
python autograder.py -q q7
```

### Question 8: Bridge Crossing Revisited

```bash
python autograder.py -q q8
```

### Question 9: Q-Learning and Pacman

```bash
python autograder.py -q q9
```

### Question 10: Approximate Q-Learning

```bash
python autograder.py -q q10
```

## Project Structure

The project repository contains several files and directories:

- `valueIterationAgents.py`: Implementations of a value iteration agent.
- `qlearningAgents.py`: Implementations of Q-learning agents for Gridworld, Crawler, and Pacman.
- `analysis.py`: File to put your answers to questions given in the project.
- `mdp.py`: Defines methods on general MDPs.
- `learningAgents.py`: Defines the base classes ValueEstimationAgent and QLearningAgent, which your agents will extend.
- `util.py`: Utilities, including util.Counter, which is particularly useful for Q-learners.
- `gridworld.py`: The Gridworld implementation.
- `featureExtractors.py`: Classes for extracting features on (state, action) pairs. Used for the approximate Q-learning agent.
- `environment.py`: Abstract class for general reinforcement learning environments.
- `crawler.py`: The crawler code and test harness (you will run this but not edit it).
- `graphicsCrawlerDisplay.py`: GUI for the crawler robot.
- `autograder.py`: Project autograder.
- `testParser.py`: Parses autograder test and solution files.
- `testClasses.py`: General autograding test classes.
- `test_cases/`: Directory containing the test cases for each question.
