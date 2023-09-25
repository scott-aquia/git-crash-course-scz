# Aquia Lunch and Learn: Git Crash Course

Welcome to the Git and GitHub Lunch and Learn Exercise Repository! This repository serves as a hands-on learning platform for attendees of our Git and GitHub session. Here, you'll practice essential Git operations like forking, cloning, branching, committing, and creating pull requests. The primary goal is to familiarize you with the Git workflow in a collaborative setting. As part of the exercise, you'll be adding your name to this README file under the "Completed By:" section, along with a sentence about what you found most valuable in this exercise. Happy learning, and feel free to reach out if you have any questions!

## 🏆 Certificate of Completion Recipients:

- Eric Rippetoe (Learning about forks and branches was new and useful to me)



---




## Live Coding Exercise Instructions

In this live exercise, you'll practice a basic Git flow by forking a repository, cloning it, creating a new branch, making a change, committing that change, pushing the commit, and finally making a Pull Request (PR) into the main repo.

---

### Step 1: Fork the Repository

#### Why
Forking creates a copy of the repository in your GitHub account, allowing you to make changes without affecting the original project.

#### Steps
1. Navigate to the main repository on GitHub.
2. Click the "Fork" button at the top-right corner.

---

### Step 2: Clone the Forked Repository

#### Why
Cloning downloads the repository to your local machine, enabling you to work on the project.

#### Steps
1. Open GitHub Desktop.
2. Click "File" -> "Clone repository."
3. Choose the forked repository and select a local path.
4. Click "Clone."

---

### Step 3: Create a New Branch

#### Why
Branches allow you to work on features or fixes without affecting the main codebase.

#### Steps
1. In GitHub Desktop, click "Current Branch" at the top.
2. Click "New Branch" and give it a meaningful name.
3. Click "Create Branch."

---

### Step 4: Make a Change

#### Why
You'll be adding your name to a README file to practice making changes to a file.

#### Steps
1. Navigate to the local repository folder.
2. Open the README file.
3. Under the title "Completed By:", add a bullet point with your name and a sentence on what you found most valuable in this exercise.
4. Save the file.

---

### Step 5: Stage and Review Changes

#### Why
Staging allows you to prepare and review changes before committing them.

#### Steps
1. Return to GitHub Desktop.
2. You'll see the changes in the "Changes" tab.
3. Check the box next to the README file to stage the changes.
4. Review the changes to ensure they are correct.

**Note**: Staging changes prepares them for commit but doesn't save them. Committing will save these changes.

---

### Step 6: Commit the Changes

#### Why
Committing saves your changes locally with a record of what was changed and why.

#### Steps
1. In GitHub Desktop, write a meaningful commit message describing your changes.
2. Click "Commit to [your-branch-name]."

---

### Step 7: Push the Commit

#### Why
Pushing uploads your local commits to the remote repository on GitHub.

#### Steps
1. In GitHub Desktop, click "Push origin" to push your commits to the remote repository.

---

### Step 8: Create a Pull Request

#### Why
A Pull Request proposes your changes to the original repository for review.

#### Steps
1. Navigate to the original repository on GitHub.
2. Click "Pull Requests" -> "New Pull Request."
3. Choose your fork and branch as the source.
4. Write a sensible title and description for your PR.
5. Click "Create Pull Request."

**Note**: Make sure you're making the PR into the repo you forked from, not your own fork.

<details>
  <summary>ℹ️ <strong>Show Hint</strong>: Detailed Instructions: Making the PR into the Repo You Forked From, Not Your Own Fork</summary>

  ### Why
  When you create a Pull Request (PR), the default behavior might be to propose changes to your own forked repository. However, the goal here is to propose changes to the original repository from which you forked. This is crucial for your changes to be reviewed and potentially merged into the main codebase.

  ### Steps

  #### 1. Navigate to the "Pull Requests" Tab
  - After pushing your changes, go to GitHub and navigate to your own fork of the repository.
  - Click on the "Pull Requests" tab located near the top of the page.

  #### 2. Start a New Pull Request
  - Click the green "New Pull Request" button. This will take you to a new page to configure the PR.

  #### 3. Change the "Base Repository"
  - You'll see two dropdown menus at the top that specify the "base repository" and the "head repository."
    - "Base repository" is where you want your changes to go.
    - "Head repository" is where your changes are coming from.

  - By default, both the "base" and "head" repositories might be set to your own fork. You'll need to change the "base repository" to the original repository you forked from.

  #### 4. Select the Repositories and Branches
  - Click on the "base repository" dropdown and select the original repository (not your fork).
  - Ensure the "base" branch is set to `main` or the branch you want to merge your changes into.
  - The "head repository" should be your own fork, and the "compare" branch should be the branch where you made your changes.

  #### 5. Review and Create
  - After setting the repositories and branches correctly, review the changes one more time to make sure everything looks good.
  - Write a sensible title and a detailed description explaining what changes you've made and why.
  - Click "Create Pull Request."

  **Note**: Always double-check to ensure you're making the PR into the original repository you forked from, and not back into your own fork. This is crucial for your changes to be reviewed and considered for merging into the main project.

  By following these steps, you'll ensure that your Pull Request is directed at the original repository, making it possible for your changes to be reviewed and potentially merged by the project maintainers.

</details>

---

### Step 9: Merge the Pull Request

#### Why
Merging incorporates your changes into the main repository.

#### Steps
1. Wait for your PR to be approved.
2. Once your PR is approved, click "Merge Pull Request" on GitHub.
3. Confirm the merge.

---


Congratulations, you've successfully completed the exercise! Your name should now appear in the README file of the main repository, signifying your completion of this hands-on Git exercise.
