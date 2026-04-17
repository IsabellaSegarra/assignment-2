# Assignment 2 — EDS 232

**Classification with KNN and Logistic Regression**

This repository contains the starter notebooks and files for Assignment 2. You will work across two tasks that focus on classification and potenital problems in linear regression

---

## Repository Structure

```
assignment-2/
├── task2/
│   ├── hw2-task2.ipynb
│   └── tests/            # Autograder tests for Task 2
│       ├── q1.py
│       ├── q2.py
│       └── ...
├── .gitignore
└── README.md
```

---

## Tasks Overview

### Task 1 — Potential problems in linear regression


With the help of AI, you will explore common problems that may arise when fitting a linear regression model and create examples that illustrate these issues.



---

### Task 2 — Classification 

`hw2-task2.ipynb`

Using the EJI dataset from the Centers for Disease Control and Prevention and Agency for Toxic Substances Disease Registry, you will build a KNN and Logistic Regression classifier, calculating and comparing metrics for both.

---



## Getting Started

### 1. Fork this repository

Click **Fork** at the top right of this page to create your own copy under your GitHub account.

### 2. Clone your fork

Open a terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/assignment-2.git
cd assignment-2
```

### 3. Open the notebooks

Launch JupyterLab or your preferred environment from inside the `assignment-2` directory. Do not move notebook files out of the repository folder.

### 4. Work through the tasks

Open each file and follow the instructions. For the `.ipynb` notebooks, always **run the first cell first** to initialize the Otter autograder before attempting any exercises.

### 5. Commit and push regularly

```bash
git add .
git commit -m "describe what you completed"
git push
```

---

## Autograder (Otter Grader)

Tasks 1 and 2 use `otter-grader` for automatic feedback.

- Run the **first cell** of each notebook to initialize the grader before anything else.
- After each exercise, run the `grader.check("qN")` cell to check your answer immediately.
- Before submitting, run the final `grader.check_all()` cell and leave its output visible — Gradescope uses this output as part of your grade.
- Do **not** modify or delete any locked `grader.check()` cells.

---

## Submitting to Gradescope

1. Make a final commit and push to ensure all your work is on GitHub.
2. Go to Gradescope and open the Assignment 1 portal.
3. Select **GitHub** as your submission method.
4. Choose your forked repository and the `main` branch.

Gradescope pulls directly from your repository at the time of submission. Make sure all notebooks have been run top-to-bottom and all outputs are visible before your final push.

---
