# feature-exercise
Job Fair GitHub Clinic Exercises 
Practice Repository
This repository is designed as a beginner-friendly workspace to practice creating and managing GitHub repositories. It provides a quick introduction to GitHub’s fundamental features—such as cloning, branching, committing, pushing, and handling pull requests—so you can become comfortable with version control workflows.

Creating a GitHub Repository
Cloning the Repository
Working with Branches
Making Changes and Committing
Pushing Changes to GitHub
Creating a Pull Request
Merging a Pull Request
Issues and Project Management
Contributing
Resources

Purpose
The main goal of this repository is to help you get hands-on practice with:

Creating repositories
Using Git commands (clone, branch, commit, push, etc.)
Utilizing GitHub workflows (pull requests, reviews, merging)
Managing and tracking issues or tasks
If you’re new to Git and GitHub, this README will guide you through the most essential operations.

Prerequisites
Git Installed: Make sure you have Git installed on your computer.
On Windows or macOS, visit Git Downloads.
On Linux, you can use your package manager (e.g., sudo apt install git on Ubuntu).
GitHub Account: Sign up for a free account at github.com.
Creating a GitHub Repository
Go to GitHub.com and log in.
In the top-right corner, click the + icon, then select New repository.
Fill in:
Repository name (e.g., practice-repo)
An optional description
Choose between Public or Private visibility
(Optional) Initialize with a README.
Click Create repository.
You now have a repository created on GitHub!

Cloning the Repository
Navigate to your newly created GitHub repository in the browser.
Click the green Code button and copy the URL (HTTPS or SSH).
Open a terminal (or Git Bash) on your computer, then run:
bash
git clone <your-repo-URL>
A local copy of the repository is now on your machine.
Working with Branches
Using branches helps you isolate your work without affecting the main (default) branch.

Create a new branch:
bash
git checkout -b feature/my-new-branch
Now you can work on this feature branch independently.
Making Changes and Committing
Add or edit files in your local repository.
Check which files have changed:
bash

git status
Stage your changes:
bash

git add <file-name>
or to add all changes:
bash

git add .
Commit your changes with a message:
bash

git commit -m "Add a new feature or fix something"
Pushing Changes to GitHub
If you’re on a new branch, push it to GitHub for the first time:
bash

git push -u origin feature/my-new-branch
For subsequent commits on this same branch, you can push simply using:
bash

git push
Creating a Pull Request
A Pull Request (PR) lets others know you have changes you’d like to merge into the main branch.

On GitHub, navigate to your repository, find the Pull requests tab, and click New pull request.
Choose the branch you want to merge into (often main or master) and the branch that contains your changes (e.g., feature/my-new-branch).
Add a descriptive title and a comment about your changes.
Click Create pull request.
Merging a Pull Request
Your team members (or you) review the changes.
If there are no conflicts and everything looks good, click Merge pull request.
Confirm the merge, and the changes from your feature branch will be added to the main branch.
(Optional) Delete the feature branch if it’s no longer needed.
Issues and Project Management
Issues: Use the Issues tab to track bugs, enhancements, or tasks. Click New issue and provide details.
Labels and Milestones: Categorize issues with labels (like bug, enhancement) and group them into milestones (like v1.0).
Projects: Use GitHub Projects or GitHub Projects (beta) to create a Kanban-style board for task management and to track progress visually.
Contributing
Feel free to practice:

Creating additional branches
Submitting pull requests
Opening issues
This repository is for educational and practice purposes. The more you experiment with Git and GitHub, the more comfortable you’ll become in real projects.

License
This project is licensed under the MIT License. You’re free to use this repository as a starting point for your own projects.

Resources
GitHub Guides
Git Documentation
Pro Git Book

