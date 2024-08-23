# Git Assignment - Grace-talent
a. What is an issue?
An issue is a way to track tasks, enhancements, bugs, or any other work that needs to be addressed within a project. Issues provide a forum for discussion among team members and can include descriptions, labels, milestones, and assignments to specific team members. 

b. What is a pull request?
A pull request (PR) is a method used for contributing code to a project. When a developer has made changes to a codebase in a separate branch, they can submit a pull request to propose merging those changes into another branch, typically the main branch. 

c. Describe the steps to open a pull request?
1. Go to your repository on GitHub.
2. Click on the "Compare & pull request" button that appears when you push your branch.
3. Add a title and description to explain what changes you’ve made.
4. Review the changes, and ensure that the correct base and compare branches are selected.
5. Click "Create pull request."
6. Reviewers may leave comments or request changes. Make any necessary updates and push them to your branch.
7. GitHub will automatically update the pull request with the new commits.
8. Once approved, you or the repository owner can merge the pull request into the main branch.

d. Describe the steps to add a collaborator to a repository (share write permissions)
1. Go to Your Repository on GitHub:

Navigate to the repository where you want to add a collaborator.
2. Access the Repository Settings:

Click on the "Settings" tab in your repository.
3. Go to Manage Access:

In the sidebar, select "Manage access" (under the "Collaborators" section).
4. Invite a Collaborator:

Click the "Invite a collaborator" button.
Enter the GitHub username or email address of the person you want to add as a collaborator.
5. Choose Permission Level:

Once the person accepts the invitation, you can choose their permission level:
Read: Can view the repository.
Triage: Can manage issues and pull requests without write access to the code.
Write: Can push to branches and merge pull requests.
Maintain: Can manage repository settings, including the ability to remove collaborators.
Admin: Full access, including managing teams, settings, and deleting the repository.
6. Send the Invitation:

Click "Add collaborator" to send the invitation.
7. Collaborator Accepts the Invitation:

The invited collaborator will receive an email or notification on GitHub to accept the invitation. Once accepted, they will have the permissions you assigned.

e. What is the difference between git and GitHub?
Git:

Definition: Git is a distributed version control system (VCS) that allows developers to track changes in source code during software development. It helps in managing project files, coordinating work among multiple people, and keeping a history of changes.

Functionality: Git operates on your local machine, enabling you to create repositories, track changes, commit updates, and branch out versions of your code without needing internet access. Git commands like git add, git commit, git branch, and git merge are used to manage your code locally.

Use Case: Git is used for version control, ensuring that changes can be tracked, reviewed, and reverted if necessary.

GitHub:

Definition: GitHub is a web-based platform that hosts Git repositories online. It provides a user-friendly interface for collaborating on projects, sharing code, and integrating with other tools and services.

Functionality: GitHub extends the functionality of Git by offering cloud storage for repositories, collaboration features like pull requests, issue tracking, and integrated CI/CD pipelines. It also allows developers to fork repositories, contribute to open-source projects, and manage permissions.

Use Case: GitHub is used for collaboration, sharing code with others, managing project workflows, and utilizing Git's version control capabilities in a cloud environment.

f. What does git diff do?
The git diff command is used to show the differences between changes in your Git repository. It compares the changes between various points in your project's history. 

g. What is the main branch?

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?