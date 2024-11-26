1 Version control is a system that records changes to files over time so that you can recall specific versions later. It enables developers to:

Track changes in their codebase.
Collaborate with others without overwriting changes.
Revert to earlier versions when necessary.

2 Log in to your GitHub account.
Click on New Repository.
Enter a repository name (e.g., MyProject).
Add an optional description for clarity.
Choose the repository visibility: Public or Private.
Optionally initialize the repository 

3  A README is the first point of reference for anyone visiting your repository.

4 	  Public Repository	                 Private Repository
Access	Open to everyone; anyone can view it.	 Only accessible to invited collaborators.
Collaboration	Ideal for open-source projects.	 Suitable for proprietary or sensitive work.
Advantages	Wider audience, more contributors.	 Maintains confidentiality.
Disadvantages	Risk of misuse or copying.	     Limited collaboration opportunities

5 git init
 git add .
 git commit -m "Initial commit"
git remote add origin <repository URL>
git push -u origin main

6 git branch feature-branch
git checkout feature-branch
git checkout main
git merge feature-branch


7 Steps to Create & Merge a PR:

Push the branch to GitHub:
bash
Copy code
git push origin feature-branch
Navigate to the repository on GitHub and click New Pull Request.
Add a description of the changes and submit the PR.
Collaborators review, request changes, or approve.
Merge the PR into the main branch.


8 Forking:

Creates a copy of a repository in your GitHub account.
Typically used to contribute to someone else’s repository without affecting the original.
Cloning:

Downloads a repository to your local machine.
Used to work on repositories you own or contribute to.

9  Issues:

Used to track bugs, feature requests, or tasks.
Includes a title, description, and tags for organization.
Example: "Fix login bug: Login button doesn't respond on mobile devices."
Project Boards:

Visualize tasks using boards (e.g., Kanban style).
Columns like To Do, In Progress, Done help organize work.

10. Challenges & Best Practices
Common Challenges:

Merge conflicts during collaboration.
Accidental overwrites or loss of data.
Confusion about Git/GitHub workflows for beginners.
Best Practices:

Commit frequently with descriptive messages.
Use branches to isolate changes.
Conduct regular code reviews via pull requests.
Document workflows and set up a good README.
Use .gitignore to exclude unnecessary files.