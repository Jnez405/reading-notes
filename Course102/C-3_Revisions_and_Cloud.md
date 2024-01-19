# C-3_Revisions_and_Cloud
## Version Control
**Version Control** is like a time-travel system for files. It helps you go back to previous versions, see changes, and fix mistakes easily. It's a tool that lets you keep track of how files evolve over time and collaborate with others more efficiently.

`Local Version Control`

- In local version control, changes are tracked on an individual's local machine.
- A database on the local machine keeps a record of file changes and versions.
- It's useful for personal projects or when working alone.
- Popular systems include RCS (Revision Control System) and tools like Git for local repositories.

`Centralized Version Control`

- In centralized version control, a central server stores the master copy of the project's files.
- Developers work on their local copies, and changes are committed to the central server.
- It facilitates collaboration among team members but relies on a central server.
- Examples include CVS (Concurrent Versions System) and SVN (Subversion).

`Distributed Version Control`

- In distributed version control, every developer has their own complete repository with the project's entire history.
- Changes can be made locally, and collaboration can occur without a central server.
- Git is a widely used distributed version control system that allows for efficient collaboration and flexibility.

`Cloning`

cloning is the process of copying a repository, often from a remote source, to a local machine, enabling collaboration, development, and version control.

- Clone an existing remote repository to your local machine using the `git clone` command followed by a repository’s URL.

- Example : `git clone https://github.com test`

`Tracking and Staging`

**Tracking** helps you understand the status of files in your Git repository, while **Staging** allows you to choose and prepare specific changes for the next commit, contributing to a controlled and organized version control workflow.

- **Tracking** in Git involves monitoring changes to files and understanding their status.

    - Use `git status` to see the current status of tracked and untracked files in the repository.

- **Staging** refers to preparing specific changes or files for the next commit.

    - Use `git add <filename>` to stage a specific file or git add . to stage all changes in the repository.

`Snapshot`

Snapshots, or commits, provide a detailed history of the project's progression, allowing for version control, collaboration, and the ability to revert to previous states if needed.

- The `git commit -m` command is used to finalize and document these snapshots, accompanied by a descriptive commit message.

`Pushing`

Pushing in Git refers to the action of uploading your local repository's commits and changes to a remote repository.

- `git push` uploads your local commits to a remote repository on GitHub.


***


<!-- Blog Article (2-3 paragraphs with code sample)
Dictionary / Flash Cards
Notes in outline form
Fill-in-the-blank worksheet of key concepts


What is Version Control?
What is cloning in Git?
What is the command to track and stage files?
What is the command to take a snapshot of your changed files?
What is the command to send your changed files to Github? -->
