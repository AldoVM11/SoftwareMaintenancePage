# Restaurant Sales Predictions

Software Maintenance - 8B BIS

-Team-

- Meléndez Burgos José Roberto

- Hernández Correa Omar Francisco

- Zamora Martínez Aldo Oscar

- Vera Vela Jesús Gabriel

- Venancio Rivas Concepción

# Introduction 

## Why GitHub?
As we have learned over the course of the class, at its core, GitHub uses Git, a distributed version control system. Git allows multiple developers to work on a project simultaneously, keeping track of changes made to the codebase over time. With Git, developers can create branches to work on different features or bug fixes independently and later merge those changes back into the main codebase.
GitHub extends the functionality of Git by providing a user-friendly interface and a range of collaboration tools.

Here are some key features of GitHub:

- Issue Tracking: GitHub includes an issue tracking system where you can create, assign, and track issues or bugs in your project. It helps you keep track of tasks, prioritize work, and facilitate communication among team members.

- Pull Requests: Pull requests allow developers to propose changes to a repository. They provide a way to submit code changes, request feedback, and discuss improvements. Pull requests are commonly used for code review before merging changes into the main project.

- Collaboration and Social Features: GitHub enables developers to collaborate on projects with features like commenting, mentioning other users, and emoji reactions. You can have discussions, share ideas, and provide feedback directly on specific lines of code.

- Code Review: GitHub provides tools for code review, making it easy for developers to review each other's code, suggest changes, and discuss improvements. Code review helps improve code quality, catch errors, and ensure adherence to best practices.

- Integrations and Automation: GitHub offers integrations with various development tools and services, such as continuous integration and deployment (CI/CD) systems, code analysis tools, testing frameworks, and project management platforms. These integrations allow you to automate parts of your development workflow and streamline processes.


## Why ClickUp?
ClickUp is a versatile project management and collaboration platform designed to streamline workflows, enhance productivity, and facilitate effective communication within teams. It provides a wide range of features and tools to help individuals and organizations manage tasks, projects, and processes efficiently.
- Structure and organization: ClickUp offers a variety of features to organize and structure your software projects. You can create task lists, set priorities, create Kanban boards, set up custom workflows, and use different views to visualize your project in different ways. This helps you maintain order and clarity in your software development activities.

- Time and Productivity Tracking: ClickUp allows you to track time spent on tasks and projects, which can be useful for estimating and monitoring resources used. In addition, it provides reports and productivity metrics that allow you to assess team performance and make adjustments as needed.

- Integrations and Automations: ClickUp offers numerous integrations with other popular tools and services, such as Slack, Google Drive, GitHub, and more. This allows you to sync and centralize information in one place, making it easy to communicate and share files with your team.

# Methodology
## Method for creating a management environment for the tool you will be using


## Step-by-step process of uploading your project to Github
### Creation of the SSHKeys
1.- First we need to create our SSH Key to access to out account in github inside git, so the first thing that we are going to do is to, open the GitBash in the place where our files are, then type "ssh-keygen -t rsa -b 4096 -C "YOUR_EMAIL"" and then, press enter twice, and a new file will be created in the route "C:\Users\\"USERNAME"\\.ssh"
!(![e4e4fda9-9af6-4d73-b05d-12c4eb1457b3](https://github.com/AldoVM11/SoftwareMaintenancePage/assets/105750734/eef69ab7-c4b8-4c9f-989c-cea8d8fe7d7f)
)

2.- Once is done that, we need to copy the SSH public key into our clipboard, this to save it for the next steps, the command that we are going to use is "clip < ~/.ssh/id_ed25519.pub", then, in our account of github, we need to create the SSH Keys, in order to do this, we need to go, settings/access/SSH and GPG Keys, then in new SSH Key, we fill all the things that ask us, and in the key field, we will paste the content of the file that was previously copied in our clipboard, then add, and with that is the connection with git and github.

### Upload of the files
1.- Create a GitHub Repository: Sign in to GitHub and navigate to the main page. Click on the "New" button to create a new repository. Provide a repository name, description, and choose appropriate settings (public or private).

2.- Add remote origin: To add a new remote repository, use the 'git remote add origin' command in the terminal, inside the directory where your repository is stored. 'git remote add origin https://github.com/OWNER/REPOSITORY.git' The address after the word origin is according to the repository previously created.

3.- Add Project Files: Place all the relevant project files within the repository directory on your local machine. Use the 'git add ' command to stage the files for commit.

4.- Commit Changes: Commit the changes using the git commit -m "Commit message" command. It is good practice to provide a descriptive commit message that summarizes the changes made.

5.- Push to GitHub: Push the committed changes to the GitHub repository using the git push command. This will upload the project files to the remote repository on GitHub.

# Conclusion
## Meléndez Burgos José Roberto


## Hernández Correa Omar Francisco
GitHub has always been a platform of choice for these types of projects, and just for software engineering in general. It's quite the powerful tool since it excels in managing code repositories, facilitating collaboration among developers, and providing features like version control, code review, issue tracking, and documentation. Our primary deal with it, of course, is the fact that we can work in a team from a much easier way. That is why this tool is so handy, and now, combining it with ClickUp, which hold just as many features, but even broader than ever, we can end up creating something special.

## Zamora Martínez Aldo Oscar
The way of how github have open us the way of saving our documentation with the possibility of returning in case that the job done is not as we like, is one of the most common things that happens in our life, as this, knowing how to use it and the ease of manipulation of our files, have become more efficient in the way of working, simply correcting the mistakes that we made with just one line of code or with 2 clicks of our mouse, can help us a lot in the daily life of a programmer or in the company, so it's really important to know to how to use this tools, in case that we need to modify some of our files and try to save them in case that in a future is needed.

## Vera Vela Jesús Gabriel


## Venancio Rivas Concepción
GitHub has become a fundamental platform for software development, promoting collaboration, version control, and project management efficiently. Its ability to host both public and private repositories has enabled developers and teams worldwide to work together effectively, driving innovation and speeding up the development process. 

# References

Generating a new SSH key and adding it to the ssh-agent - GitHub Docs. (n.d.). GitHub Docs. https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Adding a file to a repository - GitHub Docs. (n.d.). GitHub Docs. https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

Manuel, B. (2023, May 18). What Is ClickUp? [Features, FAQ & How to Get Started]. Cloudwards. https://www.cloudwards.net/what-is-clickup/

Gaba, I. (2023). What is GitHub And How To Use It? Simplilearn.com. https://www.simplilearn.com/tutorials/git-tutorial/what-is-github
