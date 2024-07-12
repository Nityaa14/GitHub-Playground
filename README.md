### README for Student Practice Repository

---

# Welcome to the CodeDay Practice Repository!

## 📝 Overview
This repository is designed for you to practice using GitHub. You will learn how to create repositories, create branches, upload files, commit changes, and raise pull requests (PRs).

## 🌟 Getting Started

### Step 1: Fork this Repository
1. Click the "Fork" button at the top right corner of this page to create a copy of this repository in your GitHub account.

### Step 2: Clone Your Fork

#### Using GitHub Desktop
1. Open GitHub Desktop and log in to your account.
2. Click on "File" > "Clone Repository".
3. Select the forked repository from your list.
4. Click "Clone".

#### Using the Terminal
1. Clone the forked repository to your local machine using the command:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   ```
2. Navigate into the cloned repository:
   ```bash
   cd repo-name
   ```

### Step 3: Create a Branch

#### Using GitHub Desktop
1. In GitHub Desktop, go to "Branch" > "New Branch".
2. Name your branch after yourself and click "Create Branch".

#### Using the Terminal
1. Create a new branch named after yourself:
   ```bash
   git checkout -b your-name
   ```

### Step 4: Create Your Team Folder

#### Using File Explorer/Finder
1. In your local repository folder, create a new folder named after your team.

#### Using the Terminal
1. Inside the repository, create a new folder named after your team:
   ```bash
   mkdir team-name
   cd team-name
   ```

### Step 5: Add a File

#### Using File Explorer/Finder
1. Add a file in your team folder. This could be a text file, image, or any other type of file.
2. For example, create a text file named `hello.txt` with the content "Hello, CodeDay!".

#### Using the Terminal
1. Add a file in your team folder:
   ```bash
   echo "Hello, CodeDay!" > hello.txt
   ```

### Step 6: Commit Your Changes

#### Using GitHub Desktop
1. In GitHub Desktop, you will see the changes you made.
2. Write a summary of your changes in the "Summary" box (e.g., "Added hello.txt to team-name folder").
3. Click "Commit to your-name".

#### Using the Terminal
1. Add your changes to the staging area:
   ```bash
   git add .
   ```
2. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Added hello.txt to team-name folder"
   ```

### Step 7: Push Your Branch

#### Using GitHub Desktop
1. Click on "Push origin" to push your branch to your forked repository.

#### Using the Terminal
1. Push your branch to your forked repository:
   ```bash
   git push origin your-name
   ```

### Step 8: Raise a Pull Request (PR)

#### Using GitHub Website
1. Go to the original repository on GitHub.
2. Click on "Compare & pull request" next to your branch name.
3. Add a title and description for your PR.
4. Click "Create pull request".

## 🎯 Tasks to Complete
- [ ] Fork the repository
- [ ] Clone the repository
- [ ] Create a branch named after yourself
- [ ] Create a folder named after your team
- [ ] Add a file to your team folder
- [ ] Commit your changes
- [ ] Push your branch to GitHub
- [ ] Raise a pull request

## 🏆 Goals
By completing these tasks, you will:
- Understand how to navigate and use GitHub.
- Learn the basics of version control with Git.
- Practice collaborative coding techniques.

## 💬 Need Help?
If you have any questions or need assistance, feel free to reach out to your CodeDay mentors or post in the discussion section of this repository.

Happy Coding! 🚀

---
