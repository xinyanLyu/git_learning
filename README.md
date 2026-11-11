# git_learning
## 1.Introduction
### 1.1 Definition
#### 1.1.1 What is GitHub? - cloud-based hosting service
 [00:24 - 00:59]: GitHub is a cloud-based hosting service used to upload, store, and track code-based work—a process known as version control. It provides on-demand internet storage so users don't have to keep large files locally. While similar services exist like GitLab and BitBucket, GitHub remains the most popular.

#### 1.1.2 Primary Uses
[00:59 - 01:22]: GitHub is mainly used for storing projects, tracking file changes, collaborating with others, and connecting with a community of users. It also hosts numerous public open-source projects for learning, practice, and contribution.

##### 1.1.3 GitHub vs. Git 
[01:22 - 01:46]: Git is a standalone version control software that can operate completely independently. GitHub is a platform built on top of Git that enhances project management and collaboration. GitHub is entirely dependent on Git; you cannot use GitHub without it.

##### 1.1.4 Collaboration and Repositories 
[01:46 - 03:10]: GitHub simplifies the version control workflow in the cloud, making it accessible to anyone for teamwork as well as solo projects by maintaining a complete history of every stage. A repository (repo) combines project files with Git's history tracking. Because a GitHub repo is stored in the cloud on the internet, it is referred to as a remote repo, whereas one saved on a computer is a local repo.

### 1.2 Set up repo
#### 1.2.1 What is a Repo?
 - A repository (or repo) is where your project files are stored along with Git's version history tracking.

 - Local Repo: A repository stored directly on your personal computer.

 - Remote Repo: A repository hosted on the internet in the cloud (such as on GitHub), making it accessible for teamwork and backups.

#### 1.2.2 What to Set When Creating a Repo
When setting up a new repository from scratch, you configure a few key settings:

- Repository Name: A unique name for your project (e.g., soccer_analysis).

- Description: A short optional summary explaining what the project is about, which is especially helpful for collaborators.

- Visibility (Public vs. Private): Choosing Public makes the project visible to anyone on the internet (while still letting you control who can make changes).

- Initialization Files:

  - README file: A guide that describes the project and explains how to use it. It is standard practice to include one.

  - .gitignore file: Acts like a block list for files you don't want committed or saved to your repo (such as confidential data or system files). You can choose templates based on your programming language (e.g., Python).

  - License: Defines copyright and usage permissions (e.g., selecting None applies default copyright laws).


#### 1.2.3 Key Features of a Repository
Once your repository is created, you can navigate its main sections:

 - Code: The core section where all your project folders and files live, along with the project's About section.

- Issues: A space to track tasks, bugs, or problems, and communicate with other contributors.

- Pull Requests (PRs): Think of this as a suggestion box. It displays suggested changes, compares them against the current version of the project, and allows you to review and merge them.

- Settings: Where you can manage repository options later, such as changing the repository name or managing access permissions and collaborators.
- 
### 1.3 README
#### 1.3.1 Introduction to the README [00:00 - 00:09]: 
A README serves as the instruction manual for your repository, acting as the first file visitors see to understand your project and how to use it.

#### 1.3.2 Editing the README [00:09 - 00:36]: 
The README is always displayed at the bottom of the Code section of your repository. It uses a Markdown format (.md extension). You can open it for editing by clicking the pencil icon located in the top-right corner of the README rendering.

#### 1.3.3 Markdown Syntax Fundamentals [00:36 - 02:06]:

 - Edit vs. Preview: You can toggle between the Edit and Preview tabs to check how your formatting renders.

 - Headings: Use one to six hashtags (#) to create headings ranging from the largest title down to the smallest(up to 6#s). Certain headers also add a dividing line to the file.

 - Text Formatting: Wrap text in single asterisks for italics or double asterisks for bold. 2 *: **bold** ; 1 * :*italic*

 - Hyperlinks: Use square brackets for the clickable link text followed by parentheses containing the URL.[]()

 - Images: Formatted similarly to hyperlinks but preceded by an exclamation mark (!), with alternative text inside the square brackets for accessibility and screen readers. You can also drag and drop images directly.![]()

#### 1.3.4 What to Include in a README [02:06 - 03:17]: A comprehensive README should act as a clear project manual, including:

- The project title and motivation/background.

- Fundamenta:
   -  title
   -  Description of technology and why?
   -  Description of process and why?
   -   table of contents
  

- Extra:
   - How project came about
   - motivation
   - limitation
   - challenges
   - problem it solves
   - intended use cases
   -  proper credits for external sources.
