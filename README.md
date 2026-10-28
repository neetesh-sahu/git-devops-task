# DevOps Internship Task 4: Version-Controlled DevOps Project with Git

## 📌 Project Overview

This project demonstrates Git and GitHub version control practices as part of a DevOps internship task. It covers repository management, branching strategies, meaningful commits, Pull Requests, merging, version tagging, and project documentation.

## 🎯 Objectives

- Initialize and manage a Git repository.
- Create and manage multiple branches.
- Follow meaningful commit message conventions.
- Implement a feature branch workflow using Pull Requests.
- Maintain project documentation using Markdown.
- Use `.gitignore` to exclude unnecessary files.
- Create Git tags for version management.

## 🛠️ Tools and Technologies

- **Git** – Version control system
- **GitHub** – Repository hosting and collaboration
- **Linux (Pop!_OS)** – Development environment
- **Bash** – Shell scripting
- **Visual Studio Code** – Code editor
- **Markdown** – Project documentation

## 📁 Project Structure

```text
git-devops-task/
├── README.md
├── .gitignore
├── docs/
│   └── git-workflow.md
└── scripts/
    └── hello.sh
```

## 🌿 Git Branching Strategy

The project uses the following branches:

| Branch | Purpose |
|---|---|
| `main` | Main project baseline |
| `dev` | Development and integration branch |
| `feature/add-hello-script` | Feature development |

## ⚙️ Implementation Steps

### 1. Repository Initialization

Initialized the local Git repository and configured the `main` branch.

### 2. Branch Management

Created the `dev` branch and the feature branch `feature/add-hello-script`.

### 3. Feature Development

Added a Bash script that displays a success message and demonstrates the project's Git workflow.

### 4. Commit and Push

Committed the changes with meaningful commit messages and pushed the branches to GitHub.

### 5. Pull Request and Merge

Created a Pull Request from `feature/add-hello-script` into `dev`, reviewed the changes, and merged the Pull Request.

### 6. Version Tagging

Created the Git tag `v1.0.0` to identify the initial project release after integrating the feature.

## 🚀 How to Run the Project

Clone the repository:

```bash
git clone https://github.com/neetesh-sahu/git-devops-task.git
cd git-devops-task
```

Make the script executable:

```bash
chmod +x scripts/hello.sh
```

Run the script:

```bash
./scripts/hello.sh
```

### Expected Output

```text
======================================
Hello from DevOps Internship Task 4!
======================================
Git version control is working successfully.
Project Status: Success
Feature branch working successfully!
```

## 🔖 Useful Git Commands

```bash
git branch -a
git log --oneline --graph --all
git status
git tag
```

## 📚 Learning Outcomes

- Understanding Git fundamentals and repository management.
- Creating branches and managing feature development.
- Using Pull Requests for code review and integration.
- Creating and managing Git tags.
- Writing clear Markdown documentation.
- Following a structured version-control workflow.

## ✅ Project Status

**Completed**

The project demonstrates repository initialization, branching, commits, Pull Request merging, version tagging, and documentation.

## 👨‍💻 Author

**Neetesh Sahu**

DevOps Internship Trainee

GitHub: [neetesh-sahu](https://github.com/neetesh-sahu)

## 📄 License

This project was created for educational and internship purposes.
