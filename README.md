# Java Random Number Statistical Analysis

A Java-based tool to evaluate the distribution and statistical accuracy of various built-in random number generators.

## Project Structure
- **Generator.java**: The primary class containing logic for data generation, statistical calculation (Mean, StdDev, Min, Max), and console formatting.

## Features
- Compares `java.util.Random`, `Math.random()`, and `ThreadLocalRandom`.
- Analyzes sample sizes of 10, 1,000, and 1,000,000.
- Custom implementation of sample standard deviation logic.

## How to Run
1. Ensure you have JDK 8 or higher installed.
2. Compile the file: `javac Generator.java`
3. Run the class: `java Generator`
