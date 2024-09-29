# Workshop Instructions

Welcome to the workshop! Please follow the steps below to complete your task of adding your name to the leaderboard.

## Step-by-Step Guide

### 1. Fork the Repository
- Start by forking the provided repository into your GitHub account.

### 2. Clone the Forked Repository
- Clone your forked repository to your local machine using the following command:
  ```bash
  git clone <your-forked-repo-url>
  ```

### 3. Create a New Branch
- Create a new branch where you will add your name. It's suggested to name the branch as follows:
  ```bash
  git checkout -b add-your-name
  ```

### 4. Add Your Name to the Leaderboard
- Open the `leaderboard.md` file and add your name to the list.

### 5. Commit the Changes
- Stage and commit your changes with a meaningful commit message:
  ```bash
  git add leaderboard.md
  git commit -m "Add <Your Name> to the leaderboard"
  ```

### 6. Fetch the Main Branch
- Fetch the latest changes from the main branch:
  ```bash
  git fetch origin main
  ```

### 7. Merge Changes with the Main Branch
- Merge your branch with the main branch locally:
  ```bash
  git merge origin/main
  ```

### 8. Resolve Any Merge Conflicts
- If you encounter merge conflicts, follow these steps:
  1. **Identify the Conflict:** Git will notify you of conflicts after the merge command.
  2. **Open the Conflicted Files:** Look for sections marked with `<<<<<<<`, `=======`, and `>>>>>>>`.
  3. **Resolve the Conflicts:** Edit the file to keep the desired changes and remove the conflict markers.
  4. **Stage the Resolved Files:** 
     ```bash
     git add <filename>
     ```
  5. **Commit the Resolutions:** 
     ```bash
     git commit -m "Resolved merge conflicts in <filename>"
     ```

### 9. Push the Changes to Your GitHub Repository
- Push your changes to your GitHub fork:
  ```bash
  git push origin add-your-name
  ```

### 10. Create a Pull Request
- Go to your forked repository on GitHub and submit a pull request to the main repository.

### 11. Approval and Merge
- We will review and accept your pull requests, completing the process.

Thank you for participating! If you have any questions, feel free to ask. Happy coding!
