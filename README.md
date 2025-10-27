# Git & GitHub Exercise – Data Scientist Interview

Please follow the instructions below to complete the Git & GitHub exercise.  

---

## Level 1 — Core Git & GitHub Workflow

### Objective
Demonstrate basic fluency with Git branching, commits, .gitignore, and opening a Pull Request.

### Tasks
1. Fork this repository to your GitHub account and clone your fork locally.  
2. Create a branch named `feature/cleaning`.  
3. Add a notebook file: `notebooks/data_cleaning.ipynb` (it can be empty or include a single dummy cell).  
4. Update `.gitignore` to exclude CSV files (if not already present).  
5. Commit your changes with a clear, descriptive message.  
6. Switch back to `main` and merge your branch (locally or via Pull Request).  
7. Push your changes and open a Pull Request if you merged locally, or share your PR link if you merged via PR.

## Level 2 — Merge Conflict Resolution

### Objective
Show that you can handle a merge conflict when two people change the same file.

### Tasks

1. Make sure you are on your feature branch:  
   ```bash
   git checkout feature/cleaning

