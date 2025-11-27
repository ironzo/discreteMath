# Discrete Mathematics Learning Repository

Welcome to my discrete mathematics learning journey! This repository contains my implementations and solutions to various problems from my discrete mathematics course.

## 📚 Course Information

I'm following the [**Introduction to Discrete Mathematics for Computer Science**](https://www.coursera.org/specializations/discrete-mathematics) specialization by UC San Diego on Coursera.

This comprehensive specialization covers:
- Mathematical Thinking in Computer Science
- Combinatorics and Probability
- Graph Theory
- Number Theory and Cryptography
- The Traveling Salesman Problem (Delivery Problem)

## 🧮 What is Discrete Mathematics?

Discrete Mathematics is the language of Computer Science. It's essential for:
- Data Science
- Machine Learning
- Software Engineering
- Algorithm Design
- Cryptography

## 📂 Projects

### 1. Diagonal Puzzle (`diagonales.ipynb`)
**Problem**: Draw 16 non-intersecting diagonals on a 5×5 grid.

**Concepts Covered**:
- Backtracking algorithms
- Constraint satisfaction problems
- Combinatorial optimization
- Recursive problem solving

**Solution Approach**: Uses a backtracking algorithm to explore all possible diagonal placements while ensuring no two diagonals share a common vertex on the 6×6 grid of intersection points.

---

### 2. Frobenius Coin Problem (`recursion.ipynb`)
**Problem**: Given only 5- and 7-coins, what is the maximum amount that cannot be paid?

**Concepts Covered**:
- Recursion and memoization
- Dynamic programming
- Number theory (Frobenius number)
- Greatest common divisor (GCD)
- Chicken McNugget Theorem

**Solution Approach**: 
- **Mathematical formula**: For coprime integers a and b, the Frobenius number is `g(a,b) = ab - a - b`
- **Computational verification**: Uses dynamic programming to verify which amounts can/cannot be paid
- **Result**: For 5 and 7 coins, the answer is **23** (the largest unpayable amount)

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd discreteMath

# Install Jupyter if you haven't already
pip install jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## 📖 Learning Philosophy

This repository follows a hands-on, problem-solving approach:
1. **Try First**: Attempt to solve puzzles independently
2. **Implement**: Code solutions in Python
3. **Analyze**: Study the underlying mathematical concepts
4. **Optimize**: Improve algorithms and understand complexity

## 🎯 Goals

- Master discrete mathematics fundamentals
- Develop strong problem-solving skills
- Build a portfolio of well-documented solutions
- Prepare for technical interviews and advanced CS topics

## 📝 Notes

All code is written as learning exercises. Solutions include:
- Detailed comments explaining the logic
- Time complexity analysis
- Multiple approaches when applicable
- Clean, readable code following best practices

## 🤝 Contributing

This is a personal learning repository, but suggestions and improvements are welcome! Feel free to:
- Open issues for bugs or suggestions
- Suggest optimizations or alternative approaches
- Share related resources

## 📜 License

This project is open source and available for educational purposes.

## 🔗 Resources

- [Coursera Specialization](https://www.coursera.org/specializations/discrete-mathematics)
- [UC San Diego CSE Department](https://cse.ucsd.edu/)

---

*Last Updated: November 26, 2025*

Happy Learning! 🎓

