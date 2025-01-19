# Task 04 - Git and GitHub

Add your answers below the questions in this file. For example: 

```
- Question 0: What command is used to create an empty file in the terminal?
- Answer: `touch filename.txt`
```

If you are unsure of an answer, write about what you know about the topic or what you tried to solve it.

## Questions

- Question 1: What does the command `git add .` do? Include an explanation of what "." refers to.
- Answer 1: It means one is **adding the changes** to the file, and the "." refers to **all changes.**

- Question 2: What is the difference between `git pull` and `git clone`?
- Answer 2: **'git pull'** is to update an already existing repo, whereas **'git clone'** creats a local copy of an entire remote repo.

- Question 3: What command can you use to see the currently active branch?
- Answer 3: git branch

- Question 4: When attempting to run `git log` you receive an error: `fatal: not a git repository` - what does this mean?
- Answer 4: It means that the directory where you’re running the git log command is **not currently a Git repository.** Git is unable to find the .git directory, which is required for Git commands to function.

- Question 5: What makes a folder a Git repository?
- Answer 5: git init

- Question 6: Explain the command `git checkout -b new-branch`.
- Answer 6: This commands brings you to a **new branch** that it's being **created simultaneously.**

- Question 7: What is the difference between a fork and a clone?
- Answer 7: The difference between a fork and a clone lies in **how they are used** in Git-based workflows and their relationship to the original repository. Here's an explanation of each:
    1. **Fork:**

        >**Definition:** A fork creates a copy of a repository on a server, typically on a platform like GitHub, GitLab, or Bitbucket. This copy is entirely independent of the original repository and belongs to your account.
        - **Purpose:**
            - To create a personal version of someone else’s repository.
            - To make changes, experiment, or contribute to the original repository without directly affecting it.
        >**Where It Exists:** The forked repository exists on the remote platform (e.g., GitHub) under your account.
        - **Relationship to Original:**
            - The fork remains linked to the original repository (upstream), so you can fetch updates from the upstream repository and merge them into your fork if needed.
            - Contributions can be made to the original repository by submitting pull requests from your fork.
        - **Use Cases:**
            - Open-source contributions.
            - Working on a copy of a repository without permission to modify the original.
        - **Example:**
            - Forking the https://github.com/someuser/repository repository to your GitHub account creates https://github.com/yourusername/repository.

    2. **Clone:**

        >**Definition:** A clone creates a local copy of a repository on your computer. This copy includes the repository's files, branches, commit history, and metadata.
        - **Purpose:**
           - To work on the repository locally.
           - To make changes and push them back to the remote repository.
        >**Where It Exists:** The clone exists locally on your computer.
        - **Relationship to Original:**
            - A clone is directly connected to the original remote repository, referred to as the origin.
            - Changes can be pushed back to the original repository (if you have the appropriate permissions).
        - **Use Cases:**
            - Downloading and working on a repository locally.
            - Collaborating on a shared repository with a team.
        - **Example:**
            - Cloning the https://github.com/someuser/repository repository to your local machine with:

        >git clone https://github.com/someuser/repository.git


- Question 8: What is the purpose of a Pull Request?
- Answer 8: A **Pull Request (PR)** is a key feature of version control platforms like GitHub, GitLab, or Bitbucket, used in **collaborative development workflows.** It allows developers to propose changes to a codebase and collaborate on those changes before integrating them into the main branch.
Purpose of a Pull Request:

    - **Propose Changes:**
        - A PR lets a developer notify others of changes they want to merge into the main branch (or another branch).
        - These changes are typically made in a feature or bug-fix branch.

    - **Facilitate Code Review:**
        - Team members or project maintainers can review the proposed changes, provide feedback, and request modifications before accepting them.
        - Helps ensure high-quality, error-free code.

    - **Enable Collaboration:**
        - Pull requests foster collaboration by allowing multiple people to discuss, suggest, and improve the proposed changes.
        - Commenting features allow inline discussions on specific parts of the code.

    - **Track Changes:**
        - A pull request provides a clear record of what changes were made, why they were made, and who made them.
        - Links to related commits, issues, and discussions are often included.

    - **Integrate Changes Safely:**
        - Pull requests ensure that changes are tested and reviewed before merging, reducing the risk of introducing bugs or breaking the codebase.

    - **Automate Quality Assurance:**
        - Many systems run automated checks (e.g., unit tests, linting, security scans) on the proposed changes as part of the pull request process.

- Question 9: Explain the .gitignore file.
- Answer 9: A .gitignore **file** is a configuration file used in Git to specify which files or directories should be **ignored** by Git. This means that the files listed in .gitignore will not be tracked, staged, or included in commits, even if they are present in the repository.
Purpose of .gitignore:

    - **Avoid Unnecessary File Tracking:**
        - Prevent temporary files, logs, compiled binaries, or other irrelevant files from being included in version control.

    - **Protect Sensitive Information:**
        - Exclude files containing sensitive data (e.g., API keys, passwords, or private credentials).

    - **Maintain Clean Repositories:**
        - Ensure that only essential files are tracked, keeping the repository clean and efficient.

    - **Prevent Merge Conflicts:**
        - Ignoring files that are environment- or system-specific (e.g., IDE settings, OS-specific files) avoids unnecessary conflicts when collaborating.

- Question 10: What is the license of the https://github.com/github/gitignore repository?
- Answer 10: The [github/gitignore](https://github.com/github/gitignore) repository is licensed under the **Creative Commons Zero v1.0 Universal (CC0-1.0)** license.

>This license allows you to freely use, modify, and distribute the .gitignore templates without any restrictions. The CC0-1.0 license effectively places the work in the public domain, waiving all copyright and related rights.

For more details, you can view the [LICENSE](https://github.com/github/gitignore/blob/main/LICENSE) file in the repository. 

- Question 11: In the repository https://github.com/github/gitignore what is the commit message of commit `3af7bb0`?
- Answer 11: "Create Ballerina.gitignore"

- Question 12: In the repository https://github.com/github/gitignore what is the commit id (hash) of the oldest commit?
- Answer 12: b8a7b9e

- Question 13: In the repository https://github.com/github/gitignore how many commits has the file Grails.gitignore had?
- Answer 13: 7 commmits

- Question 14: To this repository add a .gitignore file that ignores the .vscode folder. If it is already added to the repository, delete it.
- Answer 14: 