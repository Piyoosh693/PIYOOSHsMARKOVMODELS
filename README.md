# Hidden Markov Model and Viterbi Algorithm Assignment

## Overview

This project implements a Hidden Markov Model (HMM) and the Viterbi Algorithm for analyzing biological nucleotide sequences. The notebook demonstrates how probabilistic sequence modeling can be applied to identify hidden state transitions within DNA sequences.

The assignment focuses on:

* Defining hidden states and emission probabilities
* Constructing transition probability matrices
* Computing log probabilities for different hidden state paths
* Designing and implementing the Viterbi dynamic programming algorithm
* Performing traceback to recover the most probable hidden state sequence

The implementation is written in Python using mathematical probability computations and NumPy-based matrix operations.

## Objectives

The main objectives of this assignment are:

1. To understand the structure and working of Hidden Markov Models.
2. To calculate probabilities of different hidden state paths.
3. To implement the Viterbi Algorithm for finding the most probable sequence of hidden states.
4. To analyze nucleotide sequences using probabilistic sequence modeling.
5. To practice dynamic programming techniques in computational biology problems.

## Technologies Used

* Python
* NumPy
* Mathematical Log Probability Calculations
* Jupyter Notebook

## Project Structure

The notebook contains the following major sections:

### 1. Hidden State and Transition Matrix Initialization

* Definition of hidden states
* Mapping between state labels and indices
* Construction of the transition probability matrix
* Initialization of emission probabilities

### 2. Log Probability Computation

* Implementation of probability calculations using logarithms
* Evaluation of multiple possible hidden state paths
* Comparison of exon and intron transition paths

### 3. Viterbi Matrix Design

* Explanation of the Viterbi Value Matrix
* Explanation of the Viterbi Trace Matrix
* Representation of state transitions across nucleotide observations

### 4. Viterbi Algorithm Implementation

* Dynamic programming implementation of the Viterbi Algorithm
* Calculation of optimal probabilities for each node
* Storage of traceback information

### 5. Traceback Procedure

* Recovery of the optimal hidden state sequence
* Identification of the most probable biological state path

## Key Concepts Covered

This assignment demonstrates the following concepts:

* Hidden Markov Models (HMM)
* State Transition Probabilities
* Emission Probabilities
* Dynamic Programming
* Log Probability Calculations
* Sequence Analysis
* Viterbi Decoding
* Traceback Mechanism

## How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required dependencies:

```bash
pip install numpy
```

3. Open the notebook file:

```bash
jupyter notebook
```

4. Run all cells sequentially to execute the complete implementation.

## Expected Output

The notebook produces:

* Log probabilities for different hidden state paths
* Viterbi value matrices
* Traceback matrices
* The most probable hidden state sequence for the observed nucleotide sequence

## Learning Outcome

By completing this assignment, the following skills are developed:

* Understanding probabilistic graphical models
* Applying dynamic programming in sequence analysis
* Implementing the Viterbi Algorithm from scratch
* Working with biological sequence data
* Performing probability-based optimization

## Conclusion

This assignment provides a complete implementation of a Hidden Markov Model and the Viterbi Algorithm for biological sequence analysis. It demonstrates how probabilistic methods and dynamic programming techniques can be combined to solve sequence decoding problems efficiently.
