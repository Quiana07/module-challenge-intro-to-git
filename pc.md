## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
 Git is a free open-source version control system, storing code in a cloud, used to track changes in source code, which enables other developers to view these changes.

2. What is the difference between Git and GitHub?
Git is a version control system that allows you to keep track of source code history. Git hub is a safe cloud that allows you to manage your Git repositories.

3. Why do we create a branch?
Branching allows us to separate from a master branch, in order to make necesarry changes to code or fix bugging issues..etc. These changes do not affect the main branch until it is actually merged over at a later time.

4. What is the purpose of a Pull Request?
The purpose of a Pull Request is to inform other developers of changes made to a repository, so that these changes can be discussed among other team members prior to changes being merged into base branch.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
The Git checkout -b command is used to switch brances.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The 'git fectch' command grabs all changes from the remote repository and stores it in a separate branch on your local repository. The 'git merge' command integrates all changes from a local branch into a main branch. The "git pull' grabs and downloads all content from a remote repository so that it can be transferred onto a local repository.

7. What is a merge conflict?
A merge conflict occurs with Git is unable to resolve code differences between two commits.

8. How do you resolve a merge conflict?
#1 would be to open the conflicted file and make necessary changes
#2 After editing, use the git add command  to stage the new merged content
#3 Create a new commit with the git commit command
