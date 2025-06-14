# KMP Algorithm Simulation Website

This project is a web-based simulation of the **Knuth-Morris-Pratt (KMP)** string matching algorithm, built using **HTML** and **CSS**. It allows users to understand the core logic of the algorithm and experiment with it interactively to see how it works step by step.

## About the KMP Algorithm

The KMP (Knuth-Morris-Pratt) algorithm efficiently finds occurrences of a pattern within a text by avoiding unnecessary comparisons. It uses a preprocessed array (called the LPS array – Longest Prefix which is also Suffix) to skip characters in the text without rechecking them.

### How it Works:

1. **Preprocessing**: An LPS (Longest Prefix Suffix) array is created based on the pattern.
2. **Matching**: The pattern is then compared against the main text. When a mismatch occurs, the algorithm uses the LPS array to skip ahead rather than starting from scratch.

This avoids re-comparing characters and reduces the time complexity to **O(n + m)**, where `n` is the length of the text and `m` is the length of the pattern.

## Website Features

- **Introduction**: Explains the algorithm and logic behind KMP and has a guide to use the simulation.
- **Interactive Visualization**: Users can enter their own **text** and **pattern**, and visualize how KMP matches patterns step by step.
- **User Cases**: Gives examples of some use cases of the KMP algorithm

## Technologies Used

- HTML5
- CSS3

## Project Structure

```bash
kmp-simulation/
├── index.html
├── style.css
└── README.md
